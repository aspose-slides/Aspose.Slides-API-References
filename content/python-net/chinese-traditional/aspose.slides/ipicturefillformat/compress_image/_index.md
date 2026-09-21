---
title: compress_image method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
透過根據形狀大小與指定的解析度縮減圖像尺寸來壓縮圖像。可選地，它也會刪除被裁剪的區域。

### 回傳

一個 **bool**，指示圖像是否成功壓縮。如果圖像已重新調整大小或被裁剪，則回傳 **True**，否則回傳 **False**。

```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | 如果為 true，方法將移除圖像的裁剪區域，可能進一步減少其大小。 |
| resolution | [`PicturesCompression`](/slides/python-net/zh-hant/aspose.slides.export/picturescompression) | 壓縮的目標解析度，以 [`PicturesCompression`](/slides/python-net/zh-hant/aspose.slides.export/picturescompression) 列舉的值指定。 |

### 備註

此方法會變更圖像的尺寸與解析度，類似於 PowerPoint 的「圖片格式 → 壓縮圖片」功能。

### 例外狀況

| 例外狀況 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當解析度不是有效值時拋出此例外。 |

## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
透過根據形狀大小與指定的解析度縮減圖像尺寸來壓縮圖像。可選地，它也會刪除被裁剪的區域。

### 回傳

一個 **bool**，指示圖像是否成功壓縮。如果圖像已重新調整大小或被裁剪，則回傳 **True**，否則回傳 **False**。

```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | 如果為 true，方法將移除圖像的裁剪區域，可能進一步減少其大小。 |
| resolution | **float** | 目標解析度（以 DPI 為單位）。此值必須為正數，且決定圖像的重新調整大小方式。 |

### 備註

此方法會變更圖像的尺寸與解析度，類似於 PowerPoint 的「圖片格式 → 壓縮圖片」功能。

### 例外狀況

| 例外狀況 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當解析度不是正值時拋出此例外。 |

### 另請參閱
* 類別 [`IPictureFillFormat`](/slides/python-net/zh-hant/aspose.slides/ipicturefillformat)
* 列舉 [`PicturesCompression`](/slides/python-net/zh-hant/aspose.slides.export/picturescompression)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)