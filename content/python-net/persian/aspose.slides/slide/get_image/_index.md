---
title: get_image method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
یک شیء تصویر بندانگشتی (Thumbnail Image) را برمی‌گرداند (20٪ از اندازه واقعی).

```python
def get_image(self):
    ...
```

## get_image(self, image_size) {#asposepydrawingsize}
یک شیء تصویر بندانگشتی (Thumbnail Image) را با اندازه مشخص برمی‌گرداند.

### بازگشت
شیء Image.

```python
def get_image(self, image_size):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | اندازهٔ تصویری که باید ساخته شود. |

## get_image(self, options) {#asposeslidesexportitiffoptions}
یک شیء تصویر tiff بندانگشتی را با پارامترهای مشخص برمی‌گرداند.

### بازگشت
شیء Image.

```python
def get_image(self, options):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/fa/aspose.slides.export/itiffoptions) | گزینه‌های tiff. |

### استثناء‌ها
| استثناء | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | در صورتی که options.SlideLayoutOption برابر NotesCommentsLayoutingOptions باشد و ویژگی NotesPosition آن مقدار NotesPositions.BottomFull را داشته باشد، پرتاب می‌شود. |

## get_image(self, options) {#asposeslidesexportirenderingoptions}
یک شیء تصویر بندانگشتی (Thumbnail Image) را برمی‌گرداند.

### بازگشت
شیء Image.

```python
def get_image(self, options):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions) | گزینه‌های رندرینگ. |

### استثناء‌ها
| استثناء | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | در صورتی که notesCommentsLayouting.NotesPosition مقدار NotesPositions.BottomFull را بگیرد، پرتاب می‌شود. |

## get_image(self, scale_x, scale_y) {#float-float}
یک شیء تصویر بندانگشتی (Thumbnail Image) را با مقیاس‌گذاری سفارشی برمی‌گرداند.

### بازگشت
شیء IImage.

```python
def get_image(self, scale_x, scale_y):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| scale_x | **float** | مقداری که برای مقیاس‌گذاری این تصویر بندانگشتی در جهت محور x استفاده می‌شود. |
| scale_y | **float** | مقداری که برای مقیاس‌گذاری این تصویر بندانگشتی در جهت محور y استفاده می‌شود. |

## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
یک شیء تصویر بندانگشتی (Thumbnail Image) را با اندازه مشخص برمی‌گرداند.

### بازگشت
شیء Image.

```python
def get_image(self, options, image_size):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions) | گزینه‌های رندرینگ. |
| image_size | **aspose.slides.Size** | اندازهٔ تصویری که باید ساخته شود. |

### استثناء‌ها
| استثناء | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | در صورتی که options.SlideLayoutOption برابر NotesCommentsLayoutingOptions باشد و ویژگی NotesPosition آن مقدار NotesPositions.BottomFull را داشته باشد، پرتاب می‌شود. |

## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
یک شیء تصویر بندانگشتی (Thumbnail Image) را با مقیاس‌گذاری سفارشی برمی‌گرداند.

### بازگشت
شیء Bitmap.

```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions) | گزینه‌های رندرینگ. |
| scale_x | **float** | مقداری که برای مقیاس‌گذاری این تصویر بندانگشتی در جهت محور x استفاده می‌شود. |
| scale_y | **float** | مقداری که برای مقیاس‌گذاری این تصویر بندانگشتی در جهت محور y استفاده می‌شود. |

### استثناء‌ها
| استثناء | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | در صورتی که notesCommentsLayouting.NotesPosition مقدار NotesPositions.BottomFull را بگیرد، پرتاب می‌شود. |

### موارد مرتبط
* کلاس [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* کلاس [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions)
* کلاس [`ITiffOptions`](/slides/python-net/fa/aspose.slides.export/itiffoptions)
* کلاس [`Slide`](/slides/python-net/fa/aspose.slides/slide)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)