---
title: save method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/presentation/save/
weight: 100
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
將簡報的所有投影片儲存為具有指定格式的檔案。


```python
def save(self, fname, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** | 要建立的檔案路徑。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
將簡報的所有投影片以指定格式儲存至資料流。


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
將簡報的所有投影片以指定格式並使用其他選項儲存至資料流。


```python
def save(self, stream, format, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸出資料流。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | 其他格式選項。 |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | 如果您嘗試在非 Office 2007-2010 格式中<br/>            儲存加密檔案 |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
將簡報的特定投影片（保留頁碼）儲存為具有指定格式的檔案。


```python
def save(self, fname, slides, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** | 要建立的檔案路徑。 |
| slides | **List[int]** | 投影片位置陣列，從 1 開始計算。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 stream 或 slides 參數為 None 時。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 當 slides 參數包含錯誤的頁碼時。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當使用不支援的 SaveFormat，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP 時。 |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
將簡報的特定投影片（保留頁碼）以指定格式儲存至資料流。


```python
def save(self, stream, slides, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸出資料流。 |
| slides | **List[int]** | 投影片位置陣列，從 1 開始計算。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
將簡報的特定投影片（保留頁碼）儲存為具有指定格式的檔案。


```python
def save(self, fname, slides, format, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** | 要建立的檔案路徑。 |
| slides | **List[int]** | 投影片位置陣列，從 1 開始計算。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | 其他格式選項。 |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
將簡報的特定投影片（保留頁碼）以指定格式並使用其他選項儲存至資料流。


```python
def save(self, stream, slides, format, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸出資料流。 |
| slides | **List[int]** | 投影片位置陣列，從 1 開始計算。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | 其他格式選項。 |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 stream 或 slides 參數為 None 時。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 當 slides 參數包含錯誤的頁碼時。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當使用不支援的 SaveFormat，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP 時。 |



### 另請參閱
* 類別 [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions)
* 類別 [`IXamlOptions`](/slides/python-net/zh-hant/aspose.slides.export.xaml/ixamloptions)
* 類別 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)
* 列舉 [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)