---
title: to_jpeg method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
將輸入的簡報轉換為一系列 JPEG 格式的圖像。  
如果輸出檔名為 "myPath/myFilename.jpeg"，結果將保存為一系列 "myPath/myFilename_N.jpeg" 檔案，其中 N 為投影片編號。

```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) | 輸入的簡報。 |
| output_file_name | **str** | 輸出的檔案名稱。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
將輸入的簡報轉換為一系列 JPEG 格式的圖像。  
如果輸出檔名為 "myPath/myFilename.jpeg"，結果將保存為一系列 "myPath/myFilename_N.jpeg" 檔案，其中 N 為投影片編號。

```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) | 輸入的簡報 |
| output_file_name | **str** | 輸出的檔案名稱。 |
| image_size | [`Size`](/slides/python-net/zh-hant/aspose.slides/size) | 每張產生圖像的大小。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
將輸入的簡報轉換為一系列 JPEG 格式的圖像。  
如果輸出檔名為 "myPath/myFilename.jpeg"，結果將保存為一系列 "myPath/myFilename_N.jpeg" 檔案，其中 N 為投影片編號。

```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) | 輸入的簡報。 |
| output_file_name | **str** | 輸出的檔案名稱。 |
| scale | **float** | 相對於原始投影片大小，套用於輸出圖像的縮放因子。 |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 渲染選項。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### 參見
* 類別 [`Convert`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert)
* 類別 [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions)
* 類別 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)
* 類別 [`Size`](/slides/python-net/zh-hant/aspose.slides/size)
* 模組 [`aspose.slides.lowcode`](/slides/python-net/zh-hant/aspose.slides.lowcode)
* 函式庫 [`Aspose.Slides`](/slides/python-net)