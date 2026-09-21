---
title: get_image method
second_title: Aspose.Slides 用於 Python 的 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
傳回一個 Thumbnail Image 物件（實際大小的 20%）。


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposepydrawingsize}
傳回具有指定大小的 Thumbnail Image 物件。

### Returns

Image 物件。



```python
def get_image(self, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | 要建立的影像大小。 |


## get_image(self, options) {#asposeslidesexportitiffoptions}
傳回具有指定參數的 Thumbnail tiff 影像物件。

### Returns

Image 物件。



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions) | Tiff 選項。 |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當 options.SlideLayoutOption 為 NotesCommentsLayoutingOptions 且其屬性 NotesPosition 取得值 NotesPositions.BottomFull 時拋出。 |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
傳回一個 Thumbnail Image 物件。

### Returns

Image 物件。



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Rendering 選項。 |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當 notesCommentsLayouting.NotesPosition 取得值 NotesPositions.BottomFull 時拋出。 |


## get_image(self, scale_x, scale_y) {#float-float}
傳回具有自訂縮放的 Thumbnail Image 物件。

### Returns

IImage 物件。



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| scale_x | **float** | 在 x 軸方向縮放此 Thumbnail 的數值。 |
| scale_y | **float** | 在 y 軸方向縮放此 Thumbnail 的數值。 |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
傳回具有指定大小的 Thumbnail Image 物件。

### Returns

Image 物件。



```python
def get_image(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Rendering 選項。 |
| image_size | **aspose.slides.Size** | 要建立的影像大小。 |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當 options.SlideLayoutOption 為 NotesCommentsLayoutingOptions 且其屬性 NotesPosition 取得值 NotesPositions.BottomFull 時拋出。 |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
傳回具有自訂縮放的 Thumbnail Image 物件。

### Returns

Bitmap 物件。



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Rendering 選項。 |
| scale_x | **float** | 在 x 軸方向縮放此 Thumbnail 的數值。 |
| scale_y | **float** | 在 y 軸方向縮放此 Thumbnail 的數值。 |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當 notesCommentsLayouting.NotesPosition 取得值 NotesPositions.BottomFull 時拋出。 |



### See Also
* 類別 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 類別 [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions)
* 類別 [`ITiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions)
* 類別 [`Slide`](/slides/python-net/zh-hant/aspose.slides/slide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)