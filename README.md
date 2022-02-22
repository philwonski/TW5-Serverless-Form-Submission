# TW5-Serverless-Form-Submission

This sample app is a template for a serverless "JAMstack" web form. 

The purpose is to demonstrate form creation, state management, and serverless form submission, as described in [this post](https://mydigitalmark.com/serverless-form-submissions). 

## The Form

You can see the form in the `output/index.html` file. It's just a basic form with a bit of conditional logic. 

You can edit the form by modifying the tiddlers in the `tiddlers` folder directly. Alternatively, launch the wiki locally from the working directory with:

`tiddlywiki --listen`

Once you make edits, you save the static form by running:

`tiddlywiki --build index`

## The Endpoint

Per the article, I set up an endpoint in Pipedream for receiving the form submissions. You'll want to swap that out for your own endpoint. Check the `tiddlers/endpoint` for the URL. 