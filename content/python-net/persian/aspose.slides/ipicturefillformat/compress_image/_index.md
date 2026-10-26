---
title: compress_image method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. به‌صورت اختیاری، همچنین نواحی برش‌خورده را حذف می‌کند.

### Returns
یک **bool** که نشان می‌دهد آیا تصویر با موفقیت فشرده شده است یا خیر. در صورتی که تصویر تغییر اندازه یا برش خورده باشد **True** برگردانده می‌شود، در غیر این صورت **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | اگر true باشد، متد نواحی برش‌خورده تصویر را حذف خواهد کرد که می‌تواند اندازه آن را بیشتر کاهش دهد. |
| resolution | [`PicturesCompression`](/slides/python-net/fa/aspose.slides.export/picturescompression) | وضوح هدف برای فشرده‌سازی، که به عنوان مقدار enum [`PicturesCompression`](/slides/python-net/fa/aspose.slides.export/picturescompression) مشخص می‌شود. |

### Remarks
این متد اندازه و وضوح تصویر را مشابه ویژگی «Picture Format -> Compress Pictures» در PowerPoint تغییر می‌دهد.

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | زمانی که وضوح مقدار معتبری نیست، رخ می‌دهد. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. به‌صورت اختیاری، همچنین نواحی برش‌خورده را حذف می‌کند.

### Returns
یک **bool** که نشان می‌دهد آیا تصویر با موفقیت فشرده شده است یا خیر. در صورتی که تصویر تغییر اندازه یا برش خورده باشد **True** برگردانده می‌شود، در غیر این صورت **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | اگر true باشد، متد نواحی برش‌خورده تصویر را حذف خواهد کرد که می‌تواند اندازه آن را بیشتر کاهش دهد. |
| resolution | **float** | وضوح هدف به DPI. این مقدار باید مثبت باشد و تعیین می‌کند تصویر چگونه تغییر اندازه خواهد یافت. |

### Remarks
این متد اندازه و وضوح تصویر را مشابه ویژگی «Picture Format -> Compress Pictures» در PowerPoint تغییر می‌دهد.

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | زمانی که وضوح مقدار مثبت نیست، رخ می‌دهد. |



### See Also
* کلاس [`IPictureFillFormat`](/slides/python-net/fa/aspose.slides/ipicturefillformat)
* enumeration [`PicturesCompression`](/slides/python-net/fa/aspose.slides.export/picturescompression)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)