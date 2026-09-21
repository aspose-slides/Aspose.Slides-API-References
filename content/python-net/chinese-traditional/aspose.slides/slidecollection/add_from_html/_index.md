---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
從 HTML 文字建立投影片並將其新增至集合的末端。

### 返回值

已新增的投影片



```python
def add_from_html(self, html_text):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| html_text | **str** | 要新增的 Html。 |


## add_from_html(self, html_stream) {#iorawiobase}
從 HTML 文字建立投影片並將其新增至集合的末端。

### 返回值

已新增的投影片



```python
def add_from_html(self, html_stream):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | 將用作 HTML 檔案來源的 Stream 物件。 |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
從 HTML 文字建立投影片並將其新增至集合的末端。

### 返回值

已新增的投影片。



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| html_text | **str** | Html to add. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 用於取得外部物件的回呼物件。若此參數為 None，將忽略所有外部物件。 |
| uri | **str** | 指定 HTML 的 URI。用於解析相對連結。 |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
從 HTML 文字建立投影片並將其新增至集合的末端。

### 返回值

已新增的投影片。



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | 將用作 HTML 檔案來源的 Stream 物件。 |
| resolver | [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver) | 用於取得外部物件的回呼物件。若此參數為 None，將忽略所有外部物件。 |
| uri | **str** | 指定 HTML 的 URI。用於解析相對連結。 |



### 另請參閱
* 類別 [`IExternalResourceResolver`](/slides/python-net/zh-hant/aspose.slides.importing/iexternalresourceresolver)
* 類別 [`SlideCollection`](/slides/python-net/zh-hant/aspose.slides/slidecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)