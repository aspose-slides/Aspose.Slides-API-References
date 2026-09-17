---
title: insert_from_html method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

### 戻り値

追加されたスライド



```python
def insert_from_html(self, index, html_text):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 挿入位置。 |
| html_text | **str** | 追加するHTML。 |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

### 戻り値

追加されたスライド



```python
def insert_from_html(self, index, html_stream):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 挿入位置。 |
| html_stream | **io.RawIOBase** | HTML ファイルのソースとして使用される Stream オブジェクト。 |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

### 戻り値

追加されたスライド



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 挿入位置。 |
| html_text | **str** | 追加するHTML。 |
| use_slide_with_index_as_start | **bool** | このフラグは、挿入を開始する方法を決定します: 新しいスライドから開始するか、指定されたインデックスのスライドから開始するか。<br/><br/>            **true** の場合、データの挿入は指定されたインデックスのスライド上の空白から開始されます。<br/><br/>            **false** の場合、データは作成されたスライドに追加されます。 |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

### 戻り値

追加されたスライド



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 挿入位置。 |
| html_stream | **io.RawIOBase** | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| use_slide_with_index_as_start | **bool** | このフラグは、挿入を開始する方法を決定します: 新しいスライドから開始するか、指定されたインデックスのスライドから開始するか。<br/><br/>            **true** の場合、データの挿入は指定されたインデックスのスライド上の空白から開始されます。<br/><br/>            **false** の場合、データは作成されたスライドに追加されます。 |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

### 戻り値

追加されたスライド。



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 挿入位置。 |
| html_text | **str** | 追加するHTML。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメータが None の場合、すべての外部オブジェクトは無視されます。 |
| uri | **str** | 指定されたHTMLのURI。相対リンクを解決するために使用されます。 |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

### 戻り値

追加されたスライド。



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 挿入位置。 |
| html_stream | **io.RawIOBase** | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメータが None の場合、すべての外部オブジェクトは無視されます。 |
| uri | **str** | 指定されたHTMLのURI。相対リンクを解決するために使用されます。 |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

### 戻り値

追加されたスライド。



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 挿入位置。 |
| html_text | **str** | 追加するHTML。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメータが None の場合、すべての外部オブジェクトは無視されます。 |
| uri | **str** | 指定されたHTMLのURI。相対リンクを解決するために使用されます。 |
| use_slide_with_index_as_start | **bool** | このフラグは、挿入を開始する方法を決定します: 新しいスライドから開始するか、指定されたインデックスのスライドから開始するか。<br/><br/>            **true** の場合、データの挿入は指定されたインデックスのスライド上の空白から開始されます。<br/><br/>            **false** の場合、データは作成されたスライドに追加されます。 |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

### 戻り値

追加されたスライド。



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 挿入位置。 |
| html_stream | **io.RawIOBase** | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver) | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメータが None の場合、すべての外部オブジェクトは無視されます。 |
| uri | **str** | 指定されたHTMLのURI。相対リンクを解決するために使用されます。 |
| use_slide_with_index_as_start | **bool** | このフラグは、挿入を開始する方法を決定します: 新しいスライドから開始するか、指定されたインデックスのスライドから開始するか。<br/><br/>            **true** の場合、データの挿入は指定されたインデックスのスライド上の空白から開始されます。<br/><br/>            **false** の場合、データは作成されたスライドに追加されます。 |



### 参照
* クラス [`IExternalResourceResolver`](/slides/python-net/ja/aspose.slides.importing/iexternalresourceresolver)
* クラス [`SlideCollection`](/slides/python-net/ja/aspose.slides/slidecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)