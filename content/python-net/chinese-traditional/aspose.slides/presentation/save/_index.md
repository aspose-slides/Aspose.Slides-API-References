---
title: save method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
將簡報的所有投影片儲存為一組代表 XAML 標記的檔案。


```python
def save(self, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/zh-hant/aspose.slides.export.xaml/ixamloptions) | XAML 格式選項。 |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
將簡報的所有投影片儲存為指定格式的檔案。


```python
def save(self, fname, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** | 已建立檔案的路徑。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
將簡報的所有投影片儲存為指定格式的資料流。


```python
def save(self, stream, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸出資料流。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}



```python
def save(self, fname, format, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
將簡報的所有投影片儲存為指定格式的資料流，並附加其他選項。


```python
def save(self, stream, format, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸出資料流。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | 其他格式選項。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | 如果您嘗試在 <br/>            none Office 2007-2010 格式中儲存已加密的檔案。 |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
將簡報中指定的投影片儲存為保留頁碼的指定格式檔案。


```python
def save(self, fname, slides, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** | 已建立檔案的路徑。 |
| slides | **List[int]** | 投影片位置的陣列，起始值為 1。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 stream 或 slides 參數為 None 時。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 當 slides 參數包含錯誤的頁號時。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
將簡報中指定的投影片儲存為保留頁碼的指定格式資料流。


```python
def save(self, stream, slides, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸出資料流。 |
| slides | **List[int]** | 投影片位置的陣列，起始值為 1。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
將簡報中指定的投影片儲存為保留頁碼的指定格式檔案。


```python
def save(self, fname, slides, format, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** | 已建立檔案的路徑。 |
| slides | **List[int]** | 投影片位置的陣列，起始值為 1。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | 其他格式選項。 |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
將簡報中指定的投影片儲存為保留頁碼的指定格式資料流。


```python
def save(self, stream, slides, format, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸出資料流。 |
| slides | **List[int]** | 投影片位置的陣列，起始值為 1。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | 其他格式選項。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 stream 或 slides 參數為 None 時。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 當 slides 參數包含錯誤的頁號時。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |



### 另請參閱
* 類別 [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions)
* 類別 [`IXamlOptions`](/slides/python-net/zh-hant/aspose.slides.export.xaml/ixamloptions)
* 類別 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)
* 列舉 [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)