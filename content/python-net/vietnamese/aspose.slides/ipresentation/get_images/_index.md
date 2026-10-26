---
title: get_images method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Trả về các đối tượng Thumbnail Image cho tất cả các slide của một bản trình chiếu.

### Trả về

Các đối tượng Bitmap.



```python
def get_images(self, options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/vi/aspose.slides.export/irenderingoptions) | Rendering options. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Trả về các đối tượng Thumbnail Bitmap cho các slide được chỉ định của một bản trình chiếu.

### Trả về

Các đối tượng Bitmap.



```python
def get_images(self, options, slides):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/vi/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Trả về các đối tượng Thumbnail Image cho tất cả các slide của một bản trình chiếu với kích thước được chỉ định.

### Trả về

Các đối tượng Bitmap.



```python
def get_images(self, options, image_size):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/vi/aspose.slides.export/irenderingoptions) | Rendering options. |
| image_size | [`Size`](/slides/python-net/vi/aspose.slides/size) | Size of the image to create. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Trả về các đối tượng Thumbnail Image cho tất cả các slide của một bản trình chiếu với tỷ lệ tùy chỉnh.

### Trả về

Các đối tượng Bitmap.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/vi/aspose.slides.export/irenderingoptions) | Rendering options. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của một bản trình chiếu với kích thước được chỉ định.

### Trả về

Các đối tượng Bitmap.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/vi/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| image_size | [`Size`](/slides/python-net/vi/aspose.slides/size) | Size of the image to create. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của một bản trình chiếu với tỷ lệ tùy chỉnh.

### Trả về

Các đối tượng Bitmap.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/vi/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |



### Xem thêm
* lớp [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation)
* lớp [`IRenderingOptions`](/slides/python-net/vi/aspose.slides.export/irenderingoptions)
* lớp [`Size`](/slides/python-net/vi/aspose.slides/size)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)