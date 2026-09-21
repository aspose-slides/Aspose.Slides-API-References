---
title: add method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
將 WebVTT 隱藏式字幕新增至集合的末端。

### 回傳值

已新增的 [`ICaptions`](/slides/python-net/zh-hant/aspose.slides/icaptions) 實例。

```python
def add(self, label, file_path):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| label | **str** | 隱藏式字幕的標籤。 |
| file_path | **str** | WebVTT 檔案的路徑。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 `file_path` 為 `None`，則拋出此例外。 |
| **RuntimeError(Proxy error(ArgumentException))** | 如果 `file_path` 為空，則拋出此例外。 |

## add(self, label, stream) {#str-iorawiobase}
從串流將 WebVTT 隱藏式字幕新增至集合的末端。

### 回傳值

已新增的 [`ICaptions`](/slides/python-net/zh-hant/aspose.slides/icaptions) 實例。

```python
def add(self, label, stream):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| label | **str** | 隱藏式字幕的標籤。 |
| stream | **io.RawIOBase** | 包含 WebVTT 格式資料的輸入串流。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 `stream` 為 `None`，則拋出此例外。 |
| **RuntimeError(Proxy error(ArgumentException))** | 如果輸入資料不是 WebVTT 格式，則拋出此例外。 |

### 另見
* 類別 [`ICaptions`](/slides/python-net/zh-hant/aspose.slides/icaptions)
* 類別 [`ICaptionsCollection`](/slides/python-net/zh-hant/aspose.slides/icaptionscollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)