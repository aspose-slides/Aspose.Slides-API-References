---
title: ExternalResourceResolver class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver クラス

コールバック クラスは Html、Svg ドキュメントのインポート中に外部リソースを解決するために使用されます。  
このリゾルバーを使用すると、クライアントが提供した HTML または SVG ファイルがサーバー ソフトウェアにローカルまたはネットワーク上のファイルを取得させる脆弱性が生じる可能性があります。  
注意して使用してください。ExternalResourceResolver を指定しないこと（埋め込みオブジェクトのみが読み取られます）を推奨します。または、指定された uri が有効かどうかをチェックするサブクラスを作成してください。

ExternalResourceResolver 型は次のメンバーを公開します:

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/ja/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | ベース URI と相対 URI から絶対 URI を解決します。 |
| [`get_entity(self, absolute_uri)`](/slides/python-net/ja/aspose.slides.importing/externalresourceresolver/get_entity/#str) | URI を実際のリソースを含むオブジェクトにマップします。 |

### 参照
* モジュール [`aspose.slides.importing`](/slides/python-net/ja/aspose.slides.importing)
* ライブラリ [`Aspose.Slides`](/slides/python-net)