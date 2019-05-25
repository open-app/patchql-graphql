# Patchwork GraphQL Schema

[![npm version](https://badge.fury.io/js/ssb-graphql-patchwork.svg)](https://badge.fury.io/js/ssb-graphql-patchwork)

GraphQL schema for Secure Scuttlebot, meant to be used as a plugin with [open-app-graphql-server](https://github.com/open-app/open-app-graphql-server). You can also add it to your existing schema using [schema stitching](https://www.apollographql.com/docs/graphql-tools/schema-stitching.html).

## Usage

Install it with `npm i -S ssb-graphql-patchwork` and use it with your GraphQL server, or use it as a plugin with the [open-app-graphql-server](https://github.com/open-app/open-app-graphql-server).

## API


### Subscription

#### messages

##### `messagesByType ({ type: String })`
Retrieve messages with a given type, ordered by receive-time.
