---
title: get_images method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
返回簡報所有投影片的 Thumbnail Image 物件。

### 返回

Bitmap 物件。



```python
def get_images(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 呈現選項。 |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
返回簡報指定投影片的 Thumbnail Bitmap 物件。

### 返回

Bitmap 物件。



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 呈現選項。 |
| slides | **List[int]** | 包含投影片位置的陣列，從 1 開始。 |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
返回簡報所有投影片的 Thumbnail Image 物件，使用指定的大小。

### 返回

Bitmap 物件。



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 呈現選項。 |
| image_size | [`Size`](/slides/python-net/zh-hant/aspose.slides/size) | 要建立的影像大小。 |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
返回簡報所有投影片的 Thumbnail Image 物件，使用自訂比例。

### 返回

Bitmap 物件。



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 呈現選項。 |
| scale_x | **float** | 在 x 軸方向上縮放此 Thumbnail 的比例值。 |
| scale_y | **float** | 在 y 軸方向上縮放此 Thumbnail 的比例值。 |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
返回簡報指定投影片的 Thumbnail Image 物件，使用指定的大小。

### 返回

Bitmap 物件。



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 呈現選項。 |
| slides | **List[int]** | 包含投影片位置的陣列，從 1 開始。 |
| image_size | [`Size`](/slides/python-net/zh-hant/aspose.slides/size) | 要建立的影像大小。 |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
返回簡報指定投影片的 Thumbnail Image 物件，使用自訂比例。

### 返回

Bitmap 物件。



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 呈現選項。 |
| slides | **List[int]** | 包含投影片位置的陣列，從 1 開始。 |
| scale_x | **float** | 在 x 軸方向上縮放此 Thumbnail 的比例值。 |
| scale_y | **float** | 在 y 軸方向上縮放此 Thumbnail 的比例值。 |



### 另見
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 類別 [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions)
* 類別 [`Size`](/slides/python-net/zh-hant/aspose.slides/size)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)