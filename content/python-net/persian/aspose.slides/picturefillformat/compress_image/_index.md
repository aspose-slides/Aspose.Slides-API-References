---
title: compress_image method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
تصویر را با کاهش اندازه‌اش بر اساس ابعاد شکل و وضوح مشخص‌شده فشرده می‌کند. به‌صورت اختیاری، نواحی برش‌خورده را نیز حذف می‌کند.

### بازگشت
یک **bool** که نشان می‌دهد آیا تصویر با موفقیت فشرده شده است یا خیر. اگر تصویر تغییر اندازه یا برش داده شود **True** باز می‌گرداند، در غیر این صورت **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | اگر مقدار true باشد، متد نواحی برش‌خورده تصویر را حذف می‌کند که ممکن است اندازه آن را بیشتر کاهش دهد. |
| resolution | [`PicturesCompression`](/slides/python-net/fa/aspose.slides.export/picturescompression) | رزولوشن هدف برای فشرده‌سازی، به‌عنوان مقدار enum [`PicturesCompression`](/slides/python-net/fa/aspose.slides.export/picturescompression) مشخص می‌شود. |

### ملاحظات
این متد اندازه و وضوح تصویر را مشابه ویژگی "Picture Format -> Compress Pictures" در PowerPoint تغییر می‌دهد.

### استثناها
| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | وقتی وضوح مقدار معتبری نباشد، پرتاب می‌شود. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
تصویر را با کاهش اندازه‌اش بر اساس ابعاد شکل و وضوح مشخص‌شده فشرده می‌کند. به‌صورت اختیاری، نواحی برش‌خورده را نیز حذف می‌کند.

### بازگشت
یک **bool** که نشان می‌دهد آیا تصویر با موفقیت فشرده شده است یا خیر. اگر تصویر تغییر اندازه یا برش داده شود **True** باز می‌گرداند، در غیر این صورت **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | اگر مقدار true باشد، متد نواحی برش‌خورده تصویر را حذف می‌کند که ممکن است اندازه آن را بیشتر کاهش دهد. |
| resolution | **float** | وضوح هدف بر حسب DPI. این مقدار باید مثبت باشد و نحوه تغییر اندازه تصویر را تعیین می‌کند. |

### ملاحظات
این متد اندازه و وضوح تصویر را مشابه ویژگی "Picture Format -> Compress Pictures" در PowerPoint تغییر می‌دهد.

### استثناها
| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | وقتی وضوح مقدار مثبت نباشد، پرتاب می‌شود. |



### مراجع
* کلاس [`PictureFillFormat`](/slides/python-net/fa/aspose.slides/picturefillformat)
* شمارش [`PicturesCompression`](/slides/python-net/fa/aspose.slides.export/picturescompression)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)