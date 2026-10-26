---
title: get_image method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
یک شیء Thumbnail Image بر می‌گرداند (20٪ از اندازه واقعی).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
یک شیء Thumbnail Image با اندازهٔ مشخص بر می‌گرداند.

### بازگشت

شیء Image.



```python
def get_image(self, image_size):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/fa/aspose.slides/size) | اندازهٔ تصویری که باید ایجاد شود. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
یک شیء Thumbnail tiff image با پارامترهای مشخص بر می‌گرداند.

### بازگشت

شیء Image.



```python
def get_image(self, options):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/fa/aspose.slides.export/itiffoptions) | گزینه‌های Tiff. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | هنگامی که options.SlideLayoutOption مقدار NotesCommentsLayoutingOptions باشد و ویژگی NotesPosition آن مقدار NotesPositions.BottomFull را بگیرد. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
یک شیء Thumbnail Image بر می‌گرداند.

### بازگشت

شیء Image.



```python
def get_image(self, options):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions) | گزینه‌های Rendering. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | هنگامی که notesCommentsLayouting.NotesPosition مقدار NotesPositions.BottomFull را بگیرد. |


## get_image(self, scale_x, scale_y) {#float-float}
یک شیء Thumbnail Image با مقیاس سفارشی بر می‌گرداند.

### بازگشت

شیء IImage.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| scale_x | **float** | مقداری که این Thumbnail در جهت محور x مقیاس می‌شود. |
| scale_y | **float** | مقداری که این Thumbnail در جهت محور y مقیاس می‌شود. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
یک شیء Thumbnail Image با اندازهٔ مشخص بر می‌گرداند.

### بازگشت

شیء Image.



```python
def get_image(self, options, image_size):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions) | گزینه‌های Rendering. |
| image_size | [`Size`](/slides/python-net/fa/aspose.slides/size) | اندازهٔ تصویری که باید ایجاد شود. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | هنگامی که options.SlideLayoutOption مقدار NotesCommentsLayoutingOptions باشد و ویژگی NotesPosition آن مقدار NotesPositions.BottomFull را بگیرد. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
یک شیء Thumbnail Image با مقیاس سفارشی بر می‌گرداند.

### بازگشت

شیء Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions) | گزینه‌های Rendering. |
| scale_x | **float** | مقداری که این Thumbnail در جهت محور x مقیاس می‌شود. |
| scale_y | **float** | مقداری که این Thumbnail در جهت محور y مقیاس می‌شود. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | هنگامی که notesCommentsLayouting.NotesPosition مقدار NotesPositions.BottomFull را بگیرد. |



### موارد مرتبط
* کلاس [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* کلاس [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions)
* کلاس [`ITiffOptions`](/slides/python-net/fa/aspose.slides.export/itiffoptions)
* کلاس [`Slide`](/slides/python-net/fa/aspose.slides/slide)
* کلاس [`Size`](/slides/python-net/fa/aspose.slides/size)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)