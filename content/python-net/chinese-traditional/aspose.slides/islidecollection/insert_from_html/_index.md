---
title: insert_from_html method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
從 HTML 文字建立投影片，並將它們插入集合中指定的位置。

### 傳回值
已新增投影片



```python
def insert_from_html(self, index, html_text):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_text | **str** | 要新增的 HTML。 |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
從 HTML 文字建立投影片，並將它們插入集合中指定的位置。

### 傳回值
已新增投影片



```python
def insert_from_html(self, index, html_stream):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_stream | **io.RawIOBase** | 用作 HTML 檔案來源的 Stream 物件。 |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
從 HTML 文字建立投影片，並將它們插入集合中指定的位置。

### 傳回值
已新增投影片



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_text | **str** | 要新增的 HTML。 |
| use_slide_with_index_as_start | **bool** | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片。<br/><br/>            如果 **true**，則資料插入將從具有指定索引的投影片上的空白處開始。<br/><br/>            如果 **false**，則資料將新增至已建立的投影片。 |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
從 HTML 文字建立投影片，並將它們插入集合中指定的位置。

### 傳回值
已新增投影片



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_stream | **io.RawIOBase** | 用作 HTML 檔案來源的 Stream 物件。 |
| use_slide_with_index_as_start | **bool** | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片。<br/><br/>            如果 **true**，則資料插入將從具有指定索引的投影片上的空白處開始。<br/><br/>            如果 **false**，則資料將新增至已建立的投影片。 |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
從 HTML 文字建立投影片，並將它們插入集合中指定的位置。

### 傳回值
已新增投影片。



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_text | **str** | 要新增的 HTML。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 用於取得外部物件的回呼物件。如果此參數為 None，則所有外部物件將被忽略。 |
| uri | **str** | 指定 HTML 的 URI。用於解析相對連結。 |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
從 HTML 文字建立投影片，並將它們插入集合中指定的位置。

### 傳回值
已新增投影片。



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_stream | **io.RawIOBase** | 用作 HTML 檔案來源的 Stream 物件。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 用於取得外部物件的回呼物件。如果此參數為 None，則所有外部物件將被忽略。 |
| uri | **str** | 指定 HTML 的 URI。用於解析相對連結。 |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
從 HTML 文字建立投影片，並將它們插入集合中指定的位置。

### 傳回值
已新增投影片。



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_text | **str** | 要新增的 HTML。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 用於取得外部物件的回呼物件。如果此參數為 None，則所有外部物件將被忽略。 |
| uri | **str** | 指定 HTML 的 URI。用於解析相對連結。 |
| use_slide_with_index_as_start | **bool** | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片。<br/><br/>            如果 **true**，則資料插入將從具有指定索引的投影片上的空白處開始。<br/><br/>            如果 **false**，則資料將新增至已建立的投影片。 |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
從 HTML 文字建立投影片，並將它們插入集合中指定的位置。

### 傳回值
已新增投影片。



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入位置。 |
| html_stream | **io.RawIOBase** | 用作 HTML 檔案來源的 Stream 物件。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 用於取得外部物件的回呼物件。如果此參數為 None，則所有外部物件將被忽略。 |
| uri | **str** | 指定 HTML 的 URI。用於解析相對連結。 |
| use_slide_with_index_as_start | **bool** | 此旗標決定插入的起始方式：從新投影片或從具有指定索引的投影片。<br/><br/>            如果 **true**，則資料插入將從具有指定索引的投影片上的空白處開始。<br/><br/>            如果 **false**，則資料將新增至已建立的投影片。 |



### 另請參見
* 類別 [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver)
* 類別 [`ISlideCollection`](/slides/python-net/zh-hant/aspose.slides/islidecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)