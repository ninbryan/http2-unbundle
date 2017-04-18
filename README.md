# React Hello World in Unbundle

tested in [C9](https://c9.io) workspace

trying to mess with http2 with [http2server](https://gitlab.com/sebdeckers/http2server)

using [unbundle](https://gitlab.com/sebdeckers/unbundle) for my react app

currently in [express](http://expressjs.com/), will look into it...

```sh

# initial setup

nvm install 6

nvm alias default 6

npm i -g now # to serve http2, haven't figured it out yet

now

# http2server & unbundle fails to build in now...

npm i -g surge

surge

# did not work...

# back to now

cd public

touch package.json # with specific requirements

now

# deploy as static in now.sh
# failed

# added flags in start script...

now

now --static --name h2u

# express to root...

now

# was it the engine....

# changed engines node to 7.9.x in public/package.json
# did not take in npm setting to 4.2.x...

# failed...

nvm install 7

nvm alias default 7

npm install # yup...

npm run build

npm run start

# works locally (c9 workspace)...

```