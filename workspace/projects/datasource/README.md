# Datasource
アプリのビジネスロジックを実装するプロジェクトです。
[Angular CLI](https://github.com/angular/angular-cli) で作成されています。

全体的な内容は[ワークスペースのREADME](../../../README.md) を参照してください。





## ファイル構成
パス | 用途
--- | ---
./src/repositories/ | ビジネスロジックの実装
./src/usecases/ | アプリの使い方の実装
./src/public-api.ts | このライブラリで公開するモジュールの定義





## Angular について
### Code scaffolding
Run `ng generate component component-name --project datasource` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module --project datasource`.
> Note: Don't forget to add `--project datasource` or else it will be added to the default project in your `angular.json` file. 

### Build
Run `ng build datasource` to build the project. The build artifacts will be stored in the `dist/` directory.

### Publishing
After building your library with `ng build datasource`, go to the dist folder `cd dist/datasource` and run `npm publish`.

### Running unit tests
Run `ng test datasource` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Further help
To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
