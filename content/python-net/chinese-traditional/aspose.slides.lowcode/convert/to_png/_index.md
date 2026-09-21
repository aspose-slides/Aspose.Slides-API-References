---
title: to_png method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
將輸入的簡報轉換為一組 PNG 格式的圖像。  
如果輸出檔案名稱為 "myPath/myFilename.png"，結果將儲存為一組 "myPath/myFilename_N.png" 檔案，其中 N 為投影片編號。

```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) | 輸入的簡報。 |
| output_file_name | **str** | 輸出檔案名稱。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
將輸入的簡報轉換為一組 PNG 格式的圖像。  
如果輸出檔案名稱為 "myPath/myFilename.png"，結果將儲存為一組 "myPath/myFilename_N.png" 檔案，其中 N 為投影片編號。

```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) | 輸入的簡報 |
| output_file_name | **str** | 輸出檔案名稱。 |
| image_size | **aspose.slides.Size** | 每個產生圖像的大小。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
將輸入的簡報轉換為一組 PNG 格式的圖像。  
如果輸出檔案名稱為 "myPath/myFilename.png"，結果將儲存為一組 "myPath/myFilename_N.png" 檔案，其中 N 為投影片編號。

```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) | 輸入的簡報。 |
| output_file_name | **str** | 輸出檔案名稱。 |
| scale | **float** | 相對於原始投影片大小，套用於輸出圖像的縮放比例。 |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 渲染選項。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### 另請參閱
* 類別 [`Convert`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert)
* 類別 [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions)
* 類別 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)
* 模組 [`aspose.slides.lowcode`](/slides/python-net/zh-hant/aspose.slides.lowcode)
* 函式庫 [`Aspose.Slides`](/slides/python-net)