---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/islide/get_image/
weight: 40
---
## get_image(self) {#}
傳回縮圖影像物件（實際大小的 20%）。

### 傳回

Image object **aspose.slides.Bitmap**



```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposepydrawingsize}
傳回具有指定大小的影像物件。

### 傳回

Bitmap object.



```python
def get_image(self, image_size):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | 要建立之影像的大小。 |


## get_image(self, options) {#asposeslidesexportitiffoptions}
傳回具有指定參數的縮圖 tiff 位圖物件。

### 傳回

Image object.



```python
def get_image(self, options):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions) | Tiff 選項。 |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
傳回縮圖位圖物件。

### 傳回

Bitmap objects.



```python
def get_image(self, options):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 呈現選項。 |


## get_image(self, scale_x, scale_y) {#float-float}
傳回具有自訂縮放的影像物件。

### 傳回

Image object **aspose.slides.Bitmap**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| scale_x | **float** | 在 x 軸方向上縮放此縮圖的數值。 |
| scale_y | **float** | 在 y 軸方向上縮放此縮圖的數值。 |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
傳回具有指定大小的縮圖位圖物件。

### 傳回

Bitmap objects.



```python
def get_image(self, options, image_size):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 呈現選項。 |
| image_size | **aspose.slides.Size** | 要建立之影像的大小。 |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
傳回具有自訂縮放的縮圖位圖物件。

### 傳回

Bitmap objects.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 呈現選項。 |
| scale_x | **float** | 在 x 軸方向上縮放此縮圖的數值。 |
| scale_y | **float** | 在 y 軸方向上縮放此縮圖的數值。 |



### 另見
* 類別 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 類別 [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions)
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 類別 [`ITiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)