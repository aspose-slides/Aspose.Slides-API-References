---
title: Presentation constructor
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
此建構函式從頭建立新的簡報。  
            建立的簡報包含一個空白投影片。


```python
def __init__(self):
    ...
```



## __init__(self, load_options) {#loadoptions}
此建構函式從頭建立新的簡報。  
            建立的簡報包含一個空白投影片。


```python
def __init__(self, load_options):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/zh-hant/aspose.slides/loadoptions) | 其他載入選項。 |


## __init__(self, stream) {#iorawiobase}
此建構函式是讀取現有簡報的主要機制。


```python
def __init__(self, stream):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸入串流。 |


## __init__(self, file) {#str}
此建構函式取得來源檔案路徑，從中讀取簡報內容。


```python
def __init__(self, file):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| file | **str** | 輸入檔案。 |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當輸入檔案長度為零時拋出 |


## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
此建構函式是讀取現有簡報的主要機制。


```python
def __init__(self, stream, load_options):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸入串流。 |
| load_options | [`LoadOptions`](/slides/python-net/zh-hant/aspose.slides/loadoptions) | 其他載入選項。 |


## __init__(self, file, load_options) {#str-loadoptions}
此建構函式取得來源檔案路徑，從中讀取簡報內容。


```python
def __init__(self, file, load_options):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| file | **str** | 輸入檔案。 |
| load_options | [`LoadOptions`](/slides/python-net/zh-hant/aspose.slides/loadoptions) | 其他載入選項。 |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當輸入檔案長度為零時拋出 |



### 另見
* 類別 [`LoadOptions`](/slides/python-net/zh-hant/aspose.slides/loadoptions)
* 類別 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 庫 [`Aspose.Slides`](/slides/python-net)