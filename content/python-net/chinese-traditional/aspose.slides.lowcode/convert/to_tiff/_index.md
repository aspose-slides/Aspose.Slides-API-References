---
title: to_tiff method
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
將輸入的投影片轉換為一組 TIFF 格式的影像。  
            如果將輸出檔名設定為「myPath/myFilename.tiff」，結果將會儲存為一組「myPath/myFilename_N.tiff」檔案，其中 N 為投影片編號。


```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) | 輸入的投影片。 |
| output_file_name | **str** | 輸出檔名。 |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
將輸入的投影片轉換為 TIFF 格式，並使用自訂選項。  
            如果將輸出檔名設定為「myPath/myFilename.tiff」且 `multipage` 為 `false`，結果將會儲存為一組「myPath/myFilename_N.tiff」檔案，其中 N 為投影片編號。  
            否則，若 `multipage` 為 `true`，結果將會是一個多頁的「myPath/myFilename.tiff」文件。


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation) | 輸入的投影片。 |
| output_file_name | **str** | 輸出檔名。 |
| options | [`ITiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions) | TIFF 儲存選項。 |
| multipage | **bool** | 指定生成的 TIFF 文件是否應為多頁。 |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### 另請參閱
* 類別 [`Convert`](/slides/python-net/zh-hant/aspose.slides.lowcode/convert)
* 類別 [`ITiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions)
* 類別 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)
* 模組 [`aspose.slides.lowcode`](/slides/python-net/zh-hant/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)