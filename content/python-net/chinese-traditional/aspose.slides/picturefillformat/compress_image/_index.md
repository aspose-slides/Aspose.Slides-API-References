---
title: compress_image method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
根據形狀大小和指定的解析度縮小圖像大小，以壓縮圖像。可選地，它也會刪除裁剪區域。

### 回傳值

**bool** 表示圖像是否成功壓縮。若圖像已調整大小或被裁剪則回傳 **True**，否則回傳 **False**。



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| 參數 | 型別 | 說明 |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | 如果為 true，則此方法會移除圖像的裁剪區域，可能進一步縮小其大小。 |
| resolution | [`PicturesCompression`](/slides/python-net/zh-hant/aspose.slides.export/picturescompression) | 壓縮的目標解析度，以 [`PicturesCompression`](/slides/python-net/zh-hant/aspose.slides.export/picturescompression) 列舉的值指定。 |

### 備註

此方法更改圖像的大小和解析度，類似於 PowerPoint 的「圖片格式 → 壓縮圖片」功能。

### 例外狀況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當解析度不是有效值時拋出此例外。 |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
根據形狀大小和指定的解析度縮小圖像大小，以壓縮圖像。可選地，它也會刪除裁剪區域。

### 回傳值

**bool** 表示圖像是否成功壓縮。若圖像已調整大小或被裁剪則回傳 **True**，否則回傳 **False**。



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| 參數 | 型別 | 說明 |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | 如果為 true，則此方法會移除圖像的裁剪區域，可能進一步縮小其大小。 |
| resolution | **float** | 目標解析度，以 DPI 為單位。此值必須為正數，定義圖像將如何重新調整大小。 |

### 備註

此方法更改圖像的大小和解析度，類似於 PowerPoint 的「圖片格式 → 壓縮圖片」功能。

### 例外狀況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當解析度不是正值時拋出此例外。 |



### 另請參閱
* 類別 [`PictureFillFormat`](/slides/python-net/zh-hant/aspose.slides/picturefillformat)
* 列舉 [`PicturesCompression`](/slides/python-net/zh-hant/aspose.slides.export/picturescompression)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)