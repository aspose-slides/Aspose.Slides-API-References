---
title: add method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
將 WebVTT 關閉式字幕添加至集合的末端。

### 傳回值

已添加的 [`ICaptions`](/slides/python-net/zh-hant/aspose.slides/icaptions) 實例。



```python
def add(self, label, file_path):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| label | **str** | 關閉式字幕的標籤。 |
| file_path | **str** | WebVTT 檔案的路徑。 |

### 例外情況

| 例外情況 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 若 `file_path` 為 `None` 時拋出。 |
| **RuntimeError(Proxy error(ArgumentException))** | 若 `file_path` 為空字串時拋出。 |


## add(self, label, stream) {#str-iorawiobase}
將 WebVTT 關閉式字幕從串流添加至集合的末端。

### 傳回值

已添加的 [`ICaptions`](/slides/python-net/zh-hant/aspose.slides/icaptions) 實例。



```python
def add(self, label, stream):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| label | **str** | 關閉式字幕的標籤。 |
| stream | **io.RawIOBase** | 包含 WebVTT 格式資料的輸入串流。 |

### 例外情況

| 例外情況 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 若 `stream` 為 `None` 時拋出。 |
| **RuntimeError(Proxy error(ArgumentException))** | 若輸入資料不是 WebVTT 格式時拋出。 |



### 另請參閱
* 類別 [`CaptionsCollection`](/slides/python-net/zh-hant/aspose.slides/captionscollection)
* 類別 [`ICaptions`](/slides/python-net/zh-hant/aspose.slides/icaptions)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)