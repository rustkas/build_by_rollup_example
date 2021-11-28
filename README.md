# Сборка rollup своими руками!
Этот проект реализовано по [YouTube-видео](https://youtu.be/DXNQTd0mpIg)

[![Сборка rollup своими руками! video](https://img.youtube.com/vi/DXNQTd0mpIg/0.jpg)](https://youtu.be/DXNQTd0mpIg "Сборка rollup своими руками!")

## Создание необходимых папок и файлов одной командой:

`npm init -y && npm install react-dom && mkdir src && mkdir src && mkdir public && touch ./public/index.html && touch ./src/index.jsx && touch ./src/App.jsx && touch rollup.config.js && npm i --save-dev rollup @rollup/plugin-node-resolve @rollup/plugin-commonjs @rollup/plugin-babel babel-cli @babel/core @babel/preset-env @babel/plugin-transform-react-jsx @babel/preset-react @rollup/plugin-replace rollup-plugin-uglify process && touch babel.config.json`

Плагины rollup-plugin-node-resolve, rollup-plugin-commonjs, rollup-plugin-babel, babel считаются устаревшим. Поэтому рекомендуется использовать @rollup/plugin-node-resolve, @rollup/plugin-commonjs, @rollup/plugin-babel, babel-cli.

### Команды удаления пакета (при необходимости/обновлении):

```
npm uninstall --save rollup-plugin-node-resolve
npm uninstall --save rollup-plugin-commonjs
npm uninstall --save rollup-plugin-babel
npm uninstall --save babel
```

Команда сборки проекта:

```
npm run build
npm run build:iife
```
