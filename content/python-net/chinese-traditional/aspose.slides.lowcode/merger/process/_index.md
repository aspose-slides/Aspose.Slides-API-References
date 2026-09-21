---
title: process method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
將多個具有相同格式的 PowerPoint 簡報合併為單一簡報檔案。

```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| input_file_names | **List[str]** | 輸入簡報檔案名稱的陣列。 |
| output_file_name | **str** | 合併後產生的簡報檔案的輸出檔名。 |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當輸入檔案名稱無效或格式不匹配時拋出。 |


## process(input_file_names, output_stream) {#liststr-iorawiobase}
將多個具有相同格式的 PowerPoint 簡報合併為單一簡報檔案。

```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| input_file_names | **List[str]** | 輸入簡報檔案名稱的陣列。 |
| output_stream | **io.RawIOBase** | 輸出串流。 |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當輸入檔案名稱無效或格式不匹配時拋出。 |


## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
將多個具有相同格式的 PowerPoint 簡報合併為單一簡報檔案。

```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| input_file_names | **List[str]** | 輸入簡報檔案名稱的陣列。 |
| output_file_name | **str** | 合併後產生的簡報檔案的輸出檔名。 |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | 定義合併簡報如何儲存的額外選項。 |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當輸入檔案名稱無效或格式不匹配時拋出。 |


## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
將多個具有相同格式的 PowerPoint 簡報合併為單一簡報檔案。

```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| input_file_names | **List[str]** | 輸入簡報檔案名稱的陣列。 |
| output_stream | **io.RawIOBase** | 輸出串流。 |
| options | [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions) | 定義合併簡報如何儲存的額外選項。 |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當輸入檔案名稱無效或格式不匹配時拋出。 |



### 另請參閱
* 類別 [`ISaveOptions`](/slides/python-net/zh-hant/aspose.slides.export/isaveoptions)
* 類別 [`Merger`](/slides/python-net/zh-hant/aspose.slides.lowcode/merger)
* 模組 [`aspose.slides.lowcode`](/slides/python-net/zh-hant/aspose.slides.lowcode)
* 函式庫 [`Aspose.Slides`](/slides/python-net)