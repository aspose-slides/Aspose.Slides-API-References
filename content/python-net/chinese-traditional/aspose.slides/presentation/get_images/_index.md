---
title: get_images method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
返回所有投影片的 Image 物件。

### 返回

Image 物件。



```python
def get_images(self, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Tiff options. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
返回指定投影片的 Thumbnail Image 物件。

### 返回

Image 物件。



```python
def get_images(self, options, slides):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Tiff options. |
| slides | **List[int]** | Array 包含投影片位置，起始值為 1。 |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
返回所有投影片的 Thumbnail Image 物件，使用指定的大小。

### 返回

Image 物件.



```python
def get_images(self, options, image_size):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Tiff options. |
| image_size | [`Size`](/slides/python-net/zh-hant/aspose.slides/size) | 要建立的影像大小。 |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
返回所有投影片的 Thumbnail Image 物件，使用自訂縮放。

### 返回

Image 物件.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Tiff options. |
| scale_x | **float** | 在 x 軸方向上縮放此 Thumbnail 的值。 |
| scale_y | **float** | 在 y 軸方向上縮放此 Thumbnail 的值。 |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
返回指定投影片的 Thumbnail Image 物件，使用指定的大小。

### 返回

Image 物件.



```python
def get_images(self, options, slides, image_size):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Tiff options. |
| slides | **List[int]** | Array 包含投影片位置，起始值為 1。 |
| image_size | [`Size`](/slides/python-net/zh-hant/aspose.slides/size) | 要建立的影像大小。 |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
返回指定投影片的 Thumbnail Image 物件，使用自訂縮放。

### 返回

Image 物件.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Tiff options. |
| slides | **List[int]** | Array 包含投影片位置，起始值為 1。 |
| scale_x | **float** | 在 x 軸方向上縮放此 Thumbnail 的值。 |
| scale_y | **float** | 在 y 軸方向上縮放此 Thumbnail 的值。 |



### 另請參閱
* 類別 [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions)
* 類別 [`Presentation`](/slides/python-net/zh-hant/aspose.slides/presentation)
* 類別 [`Size`](/slides/python-net/zh-hant/aspose.slides/size)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)