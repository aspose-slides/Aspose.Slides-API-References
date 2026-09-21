---
title: save method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
將簡報的所有投影片儲存為一組以 XAML 標記表示的檔案。

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
將簡報的所有投影片儲存至指定格式的串流。

```python
def save(self, stream, format):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸出串流。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |

## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
將簡報的所有投影片儲存為指定格式的檔案，並使用額外的選項。

```python
def save(self, fname, format, options):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** | 已建立檔案的路徑。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | 其他格式選項。 |

## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
將簡報的所有投影片儲存至指定格式的串流，並使用額外的選項。

```python
def save(self, stream, format, options):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸出串流。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | 其他格式選項。 |

### 例外

| Exception | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | 如果您嘗試以 <br/>            none Office 2007-2010 格式儲存加密檔案。 |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
將簡報的指定投影片儲存為指定格式的檔案。

```python
def save(self, fname, slides, format):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** | 已建立檔案的路徑。 |
| slides | **List[int]** | 包含投影片位置的陣列，從 1 開始。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |

### 例外

| Exception | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 stream 或 slides 參數為 None 時。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 當 slides 參數包含錯誤的頁碼時。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
將簡報的指定投影片儲存至指定格式的串流。

```python
def save(self, stream, slides, format):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸出串流。 |
| slides | **List[int]** | 包含投影片位置的陣列，從 1 開始。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |

### 例外

| Exception | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 stream 或 slides 參數為 None 時。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 當 slides 參數包含錯誤的頁碼時。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
將簡報的指定投影片儲存為指定格式的檔案。

```python
def save(self, fname, slides, format, options):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| fname | **str** | 已建立檔案的路徑。 |
| slides | **List[int]** | 包含投影片位置的陣列，從 1 開始。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | 其他格式選項。 |

### 例外

| Exception | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 stream 或 slides 參數為 None 時。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 當 slides 參數包含錯誤的頁碼時。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
將簡報的指定投影片儲存至指定格式的串流。

```python
def save(self, stream, slides, format, options):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸出串流。 |
| slides | **List[int]** | 包含投影片位置的陣列，從 1 開始。 |
| format | [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat) | 匯出資料的格式。 |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | 其他格式選項。 |

### 例外

| Exception | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 stream 或 slides 參數為 None 時。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 當 slides 參數包含錯誤的頁碼時。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 另請參閱
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 類別 [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions)
* 類別 [`IXamlOptions`](/slides/python-net/zh-hant/aspose.slides.export.xaml/ixamloptions)
* 列舉 [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)