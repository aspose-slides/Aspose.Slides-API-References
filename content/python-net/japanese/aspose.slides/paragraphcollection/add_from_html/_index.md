---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
指定された HTML 文字列からテキストをコレクションに追加します。


```python
def add_from_html(self, text):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| text | **str** | HTML テキスト。 |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
指定された HTML 文字列からテキストをコレクションに追加します。


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| text | **str** | HTML テキスト。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver) | URI を解決し、参照されたオブジェクトを取得するリゾルバーコールバックオブジェクト。 |
| uri | **str** | HTML ドキュメントを追加するための URI。相対リンクの解決に使用されます。 |

### 備考

リゾルバーを指定すると脆弱性が生じる可能性があります。注意して使用してください。



### 参照
* クラス [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver)
* クラス [`ParagraphCollection`](/slides/python-net/ja/aspose.slides/paragraphcollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)