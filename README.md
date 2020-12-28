# ri1anapolis-banners

## What's it?

This repo will be used by the ri1anapolis.com.br website to show information in its banner area!

## How it works?

The ri1anapolis.com.br website will make a request to the `banners.json` file and it's contents will be parsed and styled to fit the banner design on the website.

## Why?

Sometimes we need to show our users some important information ASAP. Make a whole banner update in the site repo may not be the fastest way to do it, so this method will do it as needed.

## How to use it?

Just update the `banners.json` file as needed, but following these guidelines:

- It's an array of objects;
- Each object may have:
  - `title`: a required string;
  - `subtitle`: a optional string;
  - `body`: a required array of strings. Each string will be converted in a paragraph;
  - `actionLinks`: a optional array of objects. Each object must have a `title` and a `url`, and will be converted in link buttons on the website.
