#### How to install

You don't need ruby or node.js interpreter in your local to run this app. You just need a docker, so please download in [here](https://www.docker.com/).

```bash
# build the image
$> docker build .

# show list of your images
$> docker images

# run app with the image
$> docker run -p 3000:3000 {imageID} \
bin/rails s -b 0.0.0.0
```

Done, open `localhost:3000` to the rails app.
