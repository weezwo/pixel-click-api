# PixelClick
### Sketch it out.

This is a fork (of sorts) of [PixelClick](https://github.com/weezwo/pixel-click): a basic drawing app in React.js using the react-sketch package. It has been retooled for deployment on heroku.

## Structure

This fork is comprised of two repositories: [pixel-click-client](https://github.com/weezwo/pixel-click-client) and [pixel-click-api](https://github.com/weezwo/pixel-click-api). The client is written in React and Redux and proxies to the Rails API.

## Installation/Development

Use Ruby 2.3.3 and Rails 4.2.3.
To begin developing/tinkering with PixelClick, fork and clone this repo, then run:

```
$ bundle install
$ rake db:migrate
```

PixelClick in development mode uses Foreman to run the Rails API alongside a React.js front-end. To run your own local development server, run

```
$ rake start
```

You're off to the races!

## Contributions

Contributions are welcome via pull requests and issues.

## License

PixelClick is released under the MIT license.
