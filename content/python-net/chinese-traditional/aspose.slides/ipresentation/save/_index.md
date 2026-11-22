---
title: save method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ipresentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
將簡報的所有投影片儲存為一組表示 XAML 標記的檔案。


```python
def save(self, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/zh-hant/aspose.slides.export.xaml/ixamloptions) | The XAML format options. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
將簡報的所有投影片儲存為指定格式的檔案。


```python
def save(self, fname, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | Format of the exported data. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
將簡報的所有投影片以指定格式儲存至串流。


```python
def save(self, stream, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | Format of the exported data. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
將簡報的所有投影片儲存為指定格式的檔案，並使用額外的選項。


```python
def save(self, fname, format, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | Additional format options. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
將簡報的所有投影片以指定格式儲存至串流，並使用額外的選項。


```python
def save(self, stream, format, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | Additional format options. |

### Exceptions

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | 如果嘗試以 <br/>非 Office 2007-2010 格式儲存加密檔案 |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
將簡報中指定的投影片儲存為指定格式的檔案。


```python
def save(self, fname, slides, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | Format of the exported data. |

### Exceptions

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 stream 或 slides 參數為 None 時。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 當 slides 參數包含錯誤的頁碼時。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
將簡報中指定的投影片以指定格式儲存至串流。


```python
def save(self, stream, slides, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | Format of the exported data. |

### Exceptions

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 stream 或 slides 參數為 None 時。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 當 slides 參數包含錯誤的頁碼時。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
將簡報中指定的投影片儲存為指定格式的檔案。


```python
def save(self, fname, slides, format, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | Additional format options. |

### Exceptions

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 stream 或 slides 參數為 None 時。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 當 slides 參數包含錯誤的頁碼時。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
將簡報中指定的投影片以指定格式儲存至串流。


```python
def save(self, stream, slides, format, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | Additional format options. |

### Exceptions

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 stream 或 slides 參數為 None 時。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 當 slides 參數包含錯誤的頁碼時。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |



### See Also
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 類別 [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions)
* 類別 [`IXamlOptions`](/slides/python-net/zh-hant/aspose.slides.export.xaml/ixamloptions)
* 列舉 [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)