---
title: get_images method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
傳回所有投影片的縮圖 Image 物件。

### 傳回

Bitmap 物件。

```python
def get_images(self, options):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 渲染選項。 |

## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
傳回指定投影片的縮圖 Bitmap 物件。

### 傳回

Bitmap 物件。

```python
def get_images(self, options, slides):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 渲染選項。 |
| slides | **List[int]** | 陣列，包含投影片位置，起始值為 1。 |

## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
傳回所有投影片的縮圖 Image 物件，使用指定大小。

### 傳回

Bitmap 物件。

```python
def get_images(self, options, image_size):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 渲染選項。 |
| image_size | **aspose.slides.Size** | 要建立之影像的大小。 |

## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
傳回所有投影片的縮圖 Image 物件，使用自訂縮放。

### 傳回

Bitmap 物件。

```python
def get_images(self, options, scale_x, scale_y):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 渲染選項。 |
| scale_x | **float** | 在 x 軸方向縮放此縮圖的值。 |
| scale_y | **float** | 在 y 軸方向縮放此縮圖的值。 |

## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
傳回指定投影片的縮圖 Image 物件，使用指定大小。

### 傳回

Bitmap 物件。

```python
def get_images(self, options, slides, image_size):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 渲染選項。 |
| slides | **List[int]** | 陣列，包含投影片位置，起始值為 1。 |
| image_size | **aspose.slides.Size** | 要建立之影像的大小。 |

## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
傳回指定投影片的縮圖 Image 物件，使用自訂縮放。

### 傳回

Bitmap 物件。

```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 渲染選項。 |
| slides | **List[int]** | 陣列，包含投影片位置，起始值為 1。 |
| scale_x | **float** | 在 x 軸方向縮放此縮圖的值。 |
| scale_y | **float** | 在 y 軸方向縮放此縮圖的值。 |

### 參見
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 類別 [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)