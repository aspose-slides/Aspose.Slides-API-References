---
title: set_size method
second_title: Aspose.Slides برای Python از طریق مرجع API .NET
description: 
type: docs
url: /fa/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
اندازه اسلاید را بر اساس نوع تنظیم می‌کند و محتوای موجود را مقیاس می‌دهد.

```python
def set_size(self, type, scale_type):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/fa/aspose.slides/slidesizetype) | اندازه پیش‌تعریف‌شده اسلاید که باید اعمال شود. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/fa/aspose.slides/slidesizescaletype) | نوع مقیاس‌بندی محتوا که باید استفاده شود. |

### نکات
تعیین هر مقدار غیر از [`SlideSizeType.CUSTOM`](/slides/python-net/fa/aspose.slides/slidesizetype/CUSTOM)، [`SlideSize.size`](/slides/python-net/fa/aspose.slides/slidesize/size) را بر اساس نوع انتخاب‌شده تنظیم می‌کند، در حالی که [`SlideSize.orientation`](/slides/python-net/fa/aspose.slides/slidesize/orientation) را حفظ می‌سازد.

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
ابعاد اسلاید را به‌صورت صریح تنظیم می‌کند و محتوای موجود را مقیاس می‌دهد.

```python
def set_size(self, width, height, scale_type):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| width | **float** | عرض جدید اسلاید، به نقطه. |
| height | **float** | ارتفاع جدید اسلاید، به نقطه. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/fa/aspose.slides/slidesizescaletype) | نوع مقیاس‌بندی محتوا که باید استفاده شود. |

### نکات
این ویژگی [`SlideSize.type`](/slides/python-net/fa/aspose.slides/slidesize/type) را به [`SlideSizeType.CUSTOM`](/slides/python-net/fa/aspose.slides/slidesizetype/CUSTOM) بازنشانی می‌کند و [`SlideSize.orientation`](/slides/python-net/fa/aspose.slides/slidesize/orientation) را تنظیم می‌نماید.

### موارد مرتبط
* کلاس [`SlideSize`](/slides/python-net/fa/aspose.slides/slidesize)
* شمارش [`SlideSizeScaleType`](/slides/python-net/fa/aspose.slides/slidesizescaletype)
* شمارش [`SlideSizeType`](/slides/python-net/fa/aspose.slides/slidesizetype)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)