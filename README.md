# Gun starter app
*[Gun](https://github.com/amark/gun) application boilerplate*

This boilerplate is a good starting point for gun applications, or just for understanding how all the pieces fit together.

> Important: Make sure you update the gun version to latest, as the package.json on this app becomes stale!

## Cloning
```sh
# Download the code
$ git clone https://github.com/gundb/gun-starter-app.git

# Install the dependencies
$ cd gun-starter-app
$ npm install
```

Once the code has been downloaded, you can easily start the server:

```sh
$ npm start
```

> Under the hood, this is just running `node server.js`

## Trying it
In two browser windows, open `localhost:8090/index.html`.

> Make sure your server is running!

There's a global gun reference you can access in the developer console called `data`. Change the value on `message` and it'll update in real-time on the other browser.

```js
// Updates on the other browser window.
data.put({
	message: 'updated value',
})
```



## Questions
Have more questions? Send 'em our way on the [gitter channel](http://gitter.im/amark/gun/).

# private
- https://www.youtube.com/watch?v=ZiELAFqNSLQ with code
- https://github.com/amark/gun/blob/master/examples/basic/private.html or https://gist.github.com/amark/44b8110a3c848917d6c738f9c3a36e24

# default Vite+vue+gun
- https://www.youtube.com/watch?v=HC4MfirOPq0

# gun-util
- https://github.com/diatche/gun-util#GunUser

# gun examples users /groups
- https://gist.github.com/alterx/4be465d63fc23e37f95639b0b8ea1739

# read /write permissions
- https://github.com/Dletta/rwperm/blob/master/main.html
# meething
- https://github.com/meething/meething
