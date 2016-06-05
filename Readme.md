Example webpack config using Preact and HMR
---

##DO NOT USE. Doesn't work for now. 
Research ongoing .. stay tunded. 

This is an example repo for Preact + Webpack using Hot-Module-Reloading. 

Forked from the [Using Webpack's Hot Module Replacement with
React][blog-link] tutorial/repo.


To run:

- clone the repo
- run `npm install`

For now: please ignore the npm warning regarding the unmet dependecy for redbox. 
redbox-react@1.2.6 requires a peer of react@^0.14.0 || ^15.0.0 but none was installed.
Of course, this also means: in-browser-redbox-error-reporting doesn't work.

The rest seems to work, just as expected.

- run `npm start`
- visit http://localhost:8080
- edit anything in the `render` method of `App.js` and see HMR at work.

Pull requests welcome!
