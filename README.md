# elm-base

This project is just a dead simple elm application with 
node tools ready for development. It includes:

- sass
  All `.scss` get compiled into `.css`

- elm
  Compiles `src/elm/Main.elm` and loads it fullscreen.

- es6
  Compiles `src/*.js` using babel.

- webpack
  Creates js/css bundles for optimized asset delivery.

- watch
  Just edit and files get automatically recompiled.

- browsersync
  Reloads connected browsers when new bundle is built.


## prerequisites

- Install elm
- `elm package install`
- `npm install`

## development
`npm run dev`

## resources

- [Elm Architecture](https://github.com/evancz/elm-architecture-tutorial/)
- [Start App](https://github.com/evancz/start-app)
- [Elm Docs](http://elm-lang.org/docs)