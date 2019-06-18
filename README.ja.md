# MultiBlogExt

これはMovable Typeのプラグインです。
標準機能の再構築トリガーでは、記事やコンテンツデータの削除で再構築トリガーを実行することはできませんが、このプラグインを利用すると実行することができます。

## インストール

1. 次のリンクを開き、アーカイブファイルをダウンロードしてください。 [releases](https://github.com/usualoma/mt-plugin-MultiBlogExt/releases).
1. アーカイブファイルを展開してください。
1. `plugins`ディレクトリをサーバーへアップロードしてください。

    $MT_HOME/
        plugins/
            MultiBlogExt/

## 設定方法

記事やコンテンツデータに対して「公開取り消し」のトリガーを設定してください。削除の操作が行われた場合にもそのトリガーが実行されるようになります。（「公開取り消し」と「削除」を区別してトリガーを作成することはできません。）


## バージョン

* Movable Type 7
* Movable Type 6 ([0.1](https://github.com/usualoma/mt-plugin-MultiBlogExt/releases/0.1)が利用できます)

## LICENSE

Copyright (c) 2019 Taku AMANO

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
