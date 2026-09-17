---
title: HtmlExternalResolver class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver クラス

HTML インポートルーチンで画像などの参照オブジェクトを取得するために使用されるコールバックオブジェクトです。  
このリゾルバーを使用すると、クライアントが提供した HTML ファイルがサーバーソフトウェアにローカルまたはネットワーク上のファイルを取得させる脆弱性が生じる可能性があります。使用する際は注意が必要です。HtmlExternalResolver を指定しないこと（埋め込みオブジェクトのみが読み取られます）を推奨するか、指定された URI が有効かどうかをチェックするサブクラスを作成してください。

HtmlExternalResolver 型は以下のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/ja/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | ベース URI と相対 URI から絶対 URI を解決します。 |
| [`get_entity(self, absolute_uri)`](/slides/python-net/ja/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | URI を実際のリソースを含むオブジェクトにマッピングします。 |

### 参照
* モジュール [`aspose.slides.importing`](/slides/python-net/ja/aspose.slides.importing)
* ライブラリ [`Aspose.Slides`](/slides/python-net)