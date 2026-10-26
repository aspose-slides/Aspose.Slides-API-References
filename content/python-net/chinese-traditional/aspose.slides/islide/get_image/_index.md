---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/islide/get_image/
weight: 40
---
## get_image(self) {#}
返回一個縮圖圖像物件（實際大小的 20%）。

### 返回

圖像物件 **aspose.slides.IImage**



```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
返回具有指定大小的圖像物件。

### 返回

位圖物件。



```python
def get_image(self, image_size):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/zh-hant/aspose.slides/size) | 要建立的圖像大小。 |


## get_image(self, options) {#asposeslidesexportitiffoptions}
返回具有指定參數的縮圖 TIFF 位圖物件。

### 返回

圖像物件。



```python
def get_image(self, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions) | TIFF 選項。 |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
返回縮圖位圖物件。

### 返回

位圖物件。



```python
def get_image(self, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 渲染選項。 |


## get_image(self, scale_x, scale_y) {#float-float}
返回具有自訂縮放的圖像物件。

### 返回

圖像物件 **aspose.slides.IImage**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| scale_x | **float** | 用於在 x 軸方向縮放此縮圖的值。 |
| scale_y | **float** | 用於在 y 軸方向縮放此縮圖的值。 |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
返回具有指定大小的縮圖位圖物件。

### 返回

位圖物件。



```python
def get_image(self, options, image_size):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 渲染選項。 |
| image_size | [`Size`](/slides/python-net/zh-hant/aspose.slides/size) | 要建立的圖像大小。 |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
返回具有自訂縮放的縮圖位圖物件。

### 返回

位圖物件。



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | 渲染選項。 |
| scale_x | **float** | 用於在 x 軸方向縮放此縮圖的值。 |
| scale_y | **float** | 用於在 y 軸方向縮放此縮圖的值。 |



### 另請參閱
* 類別 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 類別 [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions)
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 類別 [`ITiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions)
* 類別 [`Size`](/slides/python-net/zh-hant/aspose.slides/size)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)