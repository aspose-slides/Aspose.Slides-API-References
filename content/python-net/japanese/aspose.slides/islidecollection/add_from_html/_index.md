---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/islidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
HTMLテキストからスライドを作成し、コレクションの末尾に追加します。

### 戻り値

追加されたスライド



```python
def add_from_html(self, html_text):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| html_text | **str** | 追加するHTML。 |


## add_from_html(self, html_stream) {#iorawiobase}
HTMLテキストからスライドを作成し、コレクションの末尾に追加します。

### 戻り値

追加されたスライド



```python
def add_from_html(self, html_stream):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | HTMLファイルのソースとして使用されるStreamオブジェクト。 |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
HTMLテキストからスライドを作成し、コレクションの末尾に追加します。

### 戻り値

追加されたスライド。



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| html_text | **str** | 追加するHTML。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメータがNoneの場合、すべての外部オブジェクトは無視されます。 |
| uri | **str** | 指定されたHTMLのURI。相対リンクの解決に使用されます。 |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
HTMLテキストからスライドを作成し、コレクションの末尾に追加します。

### 戻り値

追加されたスライド。



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | HTMLファイルのソースとして使用されるStreamオブジェクト。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメータがNoneの場合、すべての外部オブジェクトは無視されます。 |
| uri | **str** | 指定されたHTMLのURI。相対リンクの解決に使用されます。 |



### 参照
* クラス [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver)
* クラス [`ISlideCollection`](/slides/python-net/ja/aspose.slides/islidecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)