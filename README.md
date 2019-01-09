# contactsbook
A Contacts list application built  using angular with FIrestore as the backend . The Contact form  is processed as a Template form 

## TODO
Refactor the code to process the form using Form builder for  a reactive form<br/>
Add authentication services and  use pureCSS

## Get started

### Clone the repo

```shell
git clone https://github.com/bryanforbes/contactsbook
cd contactsbook
```

### Install npm packages

Install the `npm` packages described in the `package.json` and verify that it works:

```shell
npm install
npm start
```

The `npm start` command builds (compiles TypeScript and copies assets) the application into `dist/`, watches for changes to the source files, and runs `lite-server` on port `3000`.

Shut it down manually with `Ctrl-C`.

#### npm scripts

These are the most useful commands defined in `package.json`:

* `npm start` - runs the TypeScript compiler, asset copier, and a server at the same time, all three in "watch mode".
* `npm run build` - runs the TypeScript compiler and asset copier once.
* `npm run build:watch` - runs the TypeScript compiler and asset copier in "watch mode"; when changes occur to source files, they will be recompiled or copied into `dist/`.
* `npm run lint` - runs `tslint` on the project files.
* `npm run serve` - runs `lite-server`.
