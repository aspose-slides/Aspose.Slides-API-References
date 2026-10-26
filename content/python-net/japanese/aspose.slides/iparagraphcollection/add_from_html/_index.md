---
title: add_from_html method
second_title: Aspose.Slides の Python 用 .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
指定された html 文字列からテキストをコレクションに追加します。


```python
def add_from_html(self, text):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | **str** | HTML テキスト。 |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
指定された html 文字列からテキストをコレクションに追加します。


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | **str** | HTML テキスト。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver) | URI を解決し、参照されたオブジェクトを取得するリゾルバー コールバック オブジェクト。 |
| uri | **str** | HTML ドキュメントを追加するための URI。相対リンクの解決に使用されます。 |

### 備考

リゾルバーを指定すると脆弱性が発生する可能性があります。注意して使用してください。


### 参照
* クラス [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver)
* クラス [`IParagraphCollection`](/slides/python-net/ja/aspose.slides/iparagraphcollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)