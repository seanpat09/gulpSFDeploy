An extension of the gulp-jsforce-deploy library (https://github.com/jsforce/gulp-jsforce-deploy).
This includes a compiler for resource-bundles generated by mavensmate

First install gulp-jsforce-deploy
```
npm init
npm install gulp gulp-zip gulp-jsforce-deploy --save-dev
```

Set up your credentials in the credentials.js file. List all of the metadata you want to deploy in the
metadataList.js file (TODO: Support wildcards)