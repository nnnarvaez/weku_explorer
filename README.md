# Blockchain Explorer based on Steem-JS (For private steemd based Blockchains)
Steem explorer is a client-side block explorer for steem-like blockchains. It uses Steem-JS API to query users, posts, and transactions directly to the seed nodes.

![](https://images2.weku.io/DQmPwvwxgBER3zS82B7PtDYTM3tbiT3z5qQbNXB9eQ2kf2Q/image.png)

## Config
Change the configuration file `src/config.js` with the symbols and rpc_node of the blockchain.

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

## TO-DO:

**Fix pagination for new query pages**

* account votes
* account tranfers

Currently first paginates then filters resulting in empty paginated pages.
# weku_explorer
