---
title: get_images method
second_title: Aspose.Slides 針對 Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
傳回所有投影片的 Image 物件。

### 回傳
Image 物件。

```python
def get_images(self, options):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Tiff 選項。 |

## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
傳回指定投影片的 Thumbnail Image 物件。

### 回傳
Image 物件。

```python
def get_images(self, options, slides):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Tiff 選項。 |
| slides | **List[int]** | 包含投影片位置的陣列，起始值為 1。 |

## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
傳回所有投影片的 Thumbnail Image 物件，使用指定的大小。

### 回傳
Image 物件。

```python
def get_images(self, options, image_size):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Tiff 選項。 |
| image_size | **aspose.slides.Size** | 要建立的影像大小。 |

## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
傳回所有投影片的 Thumbnail Image 物件，使用自訂縮放。

### 回傳
Image 物件。

```python
def get_images(self, options, scale_x, scale_y):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Tiff 選項。 |
| scale_x | **float** | 在 x 軸方向上縮放此 Thumbnail 的值。 |
| scale_y | **float** | 在 y 軸方向上縮放此 Thumbnail 的值。 |

## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
傳回指定投影片的 Thumbnail Image 物件，使用指定的大小。

### 回傳
Image 物件。

```python
def get_images(self, options, slides, image_size):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Tiff 選項。 |
| slides | **List[int]** | 包含投影片位置的陣列，起始值為 1。 |
| image_size | **aspose.slides.Size** | 要建立的影像大小。 |

## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
傳回指定投影片的 Thumbnail Image 物件，使用自訂縮放。

### 回傳
Image 物件。

```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Tiff 選項。 |
| slides | **List[int]** | 包含投影片位置的陣列，起始值為 1。 |
| scale_x | **float** | 在 x 軸方向上縮放此 Thumbnail 的值。 |
| scale_y | **float** | 在 y 軸方向上縮放此 Thumbnail 的值。 |

### 另見
* 類別 [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions)
* 類別 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)