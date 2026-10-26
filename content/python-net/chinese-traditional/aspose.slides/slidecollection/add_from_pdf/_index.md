---
title: add_from_pdf method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/slidecollection/add_from_pdf/
weight: 40
---
## add_from_pdf(self, path) {#str}
從 PDF 文件建立投影片，並將它們新增至集合的末端。

### 返回
已添加的投影片



```python
def add_from_pdf(self, path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| path | **str** | A path to the PDF document |


## add_from_pdf(self, pdf_stream) {#iorawiobase}
從 PDF 文件建立投影片，並將它們新增至集合的末端。

### 返回
已添加的投影片



```python
def add_from_pdf(self, pdf_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pdf_stream | **io.RawIOBase** | A stream which will be used as a source of the PDF document |


## add_from_pdf(self, path, pdf_import_options) {#str-asposeslidesimportingpdfimportoptions}
根據 PDF 匯入選項，從 PDF 文件建立投影片，並將它們新增至集合的末端。

### 返回
已添加的投影片



```python
def add_from_pdf(self, path, pdf_import_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| path | **str** | A path to the PDF document |
| pdf_import_options | [`PdfImportOptions`](/slides/python-net/zh-hant/aspose.slides.importing/pdfimportoptions) | Options for pdf import |


## add_from_pdf(self, pdf_stream, pdf_import_options) {#iorawiobase-asposeslidesimportingpdfimportoptions}
從 PDF 文件建立投影片，並將它們新增至集合的末端。

### 返回
已添加的投影片



```python
def add_from_pdf(self, pdf_stream, pdf_import_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pdf_stream | **io.RawIOBase** | A stream which will be used as a source of the PDF document |
| pdf_import_options | [`PdfImportOptions`](/slides/python-net/zh-hant/aspose.slides.importing/pdfimportoptions) | Options for pdf import |



### 另見
* 類別 [`PdfImportOptions`](/slides/python-net/zh-hant/aspose.slides.importing/pdfimportoptions)
* 類別 [`SlideCollection`](/slides/python-net/zh-hant/aspose.slides/slidecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)