---
title: insert_from_html method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
從 HTML 文字建立投影片，並將其插入集合中的指定位置。

### 傳回值

已新增的投影片



```python
def insert_from_html(self, index, html_text):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入的位置。 |
| html_text | **str** | 要加入的 HTML。 |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
從 HTML 文字建立投影片，並將其插入集合中的指定位置。

### 傳回值

已新增的投影片



```python
def insert_from_html(self, index, html_stream):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入的位置。 |
| html_stream | **io.RawIOBase** | 作為 HTML 檔案來源的 Stream 物件。 |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
從 HTML 文字建立投影片，並將其插入集合中的指定位置。

### 傳回值

已新增的投影片



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入的位置。 |
| html_text | **str** | 要加入的 HTML。 |
| use_slide_with_index_as_start | **bool** | 此旗標決定插入的起始方式：從新投影片或從具指定索引的投影片。<br/><br/>            若 **true**，則資料插入將從具指定索引的投影片的空白處開始。<br/><br/>            若 **false**，則資料會加入已建立的投影片。 |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
從 HTML 文字建立投影片，並將其插入集合中的指定位置。

### 傳回值

已新增的投影片



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入的位置。 |
| html_stream | **io.RawIOBase** | 作為 HTML 檔案來源的 Stream 物件。 |
| use_slide_with_index_as_start | **bool** | 此旗標決定插入的起始方式：從新投影片或從具指定索引的投影片。<br/><br/>            若 **true**，則資料插入將從具指定索引的投影片的空白處開始。<br/><br/>            若 **false**，則資料會加入已建立的投影片。 |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
從 HTML 文字建立投影片，並將其插入集合中的指定位置。

### 傳回值

已新增的投影片。



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入的位置。 |
| html_text | **str** | 要加入的 HTML。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 用於取得外部物件的回呼物件。若此參數為 None，則會忽略所有外部物件。 |
| uri | **str** | 指定 HTML 的 URI。用於解析相對連結。 |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
從 HTML 文字建立投影片，並將其插入集合中的指定位置。

### 傳回值

已新增的投影片。



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入的位置。 |
| html_stream | **io.RawIOBase** | 作為 HTML 檔案來源的 Stream 物件。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 用於取得外部物件的回呼物件。若此參數為 None，則會忽略所有外部物件。 |
| uri | **str** | 指定 HTML 的 URI。用於解析相對連結。 |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
從 HTML 文字建立投影片，並將其插入集合中的指定位置。

### 傳回值

已新增的投影片。



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入的位置。 |
| html_text | **str** | 要加入的 HTML。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 用於取得外部物件的回呼物件。若此參數為 None，則會忽略所有外部物件。 |
| uri | **str** | 指定 HTML 的 URI。用於解析相對連結。 |
| use_slide_with_index_as_start | **bool** | 此旗標決定插入的起始方式：從新投影片或從具指定索引的投影片。<br/><br/>            若 **true**，則資料插入將從具指定索引的投影片的空白處開始。<br/><br/>            若 **false**，則資料會加入已建立的投影片。 |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
從 HTML 文字建立投影片，並將其插入集合中的指定位置。

### 傳回值

已新增的投影片。



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 插入的位置。 |
| html_stream | **io.RawIOBase** | 作為 HTML 檔案來源的 Stream 物件。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 用於取得外部物件的回呼物件。若此參數為 None，則會忽略所有外部物件。 |
| uri | **str** | 指定 HTML 的 URI。用於解析相對連結。 |
| use_slide_with_index_as_start | **bool** | 此旗標決定插入的起始方式：從新投影片或從具指定索引的投影片。<br/><br/>            若 **true**，則資料插入將從具指定索引的投影片的空白處開始。<br/><br/>            若 **false**，則資料會加入已建立的投影片。 |



### 另見
* 類別 [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver)
* 類別 [`SlideCollection`](/slides/python-net/zh-hant/aspose.slides/slidecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)