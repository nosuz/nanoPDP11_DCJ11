# nanoPDP11_DCJ11

## About this project

## Cloning this project

This project contains a submodule for parts symbols and footprints. Use the next command to clone this project.

このプロジェクトは、KiCad のシンボルとフットプリント用サブモジュールを含んでいます。そのため、次のコマンドでクローンしてください。

```
git clone --recursive https://github.com/nosuz/nanoPDP11_DCJ11.git

# or
git clone https://github.com/nosuz/nanoPDP11_DCJ11.git
git submodule update --init --recursive
```

And you might need to update the submodule because that is not updated with the project. In this case, follow the next command.

また、サブモジュールは、本体のレポジトリと同期しないため、手動でサブモジュールのアップデートが必要になる場合があります。その場合には、次のコマンドでアップデートしてください。

```
git submodule update --recursive
```
