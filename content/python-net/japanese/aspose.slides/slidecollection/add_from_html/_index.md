---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
HTML テキストからスライドを作成し、コレクションの末尾に追加します。

### Returns

Added slides



```python
def add_from_html(self, html_text):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_text | **str** | 追加する Html。 |


## add_from_html(self, html_stream) {#iorawiobase}
HTML テキストからスライドを作成し、コレクションの末尾に追加します。

### Returns

Added slides



```python
def add_from_html(self, html_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | HTML ファイルのソースとして使用される Stream オブジェクト。 |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
HTML テキストからスライドを作成し、コレクションの末尾に追加します。

### Returns

Added slides.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_text | **str** | 追加する Html。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメーターが None の場合、すべての外部オブジェクトは無視されます。 |
| uri | **str** | 指定された HTML の URI。相対リンクの解決に使用されます。 |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
HTML テキストからスライドを作成し、コレクションの末尾に追加します。

### Returns

Added slides.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメーターが None の場合、すべての外部オブジェクトは無視されます。 |
| uri | **str** | 指定された HTML の URI。相対リンクの解決に使用されます。 |



### See Also
* クラス [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver)
* クラス [`SlideCollection`](/slides/python-net/ja/aspose.slides/slidecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)