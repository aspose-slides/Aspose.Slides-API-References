---
title: set_size method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
اندازه اسلاید را بر اساس نوع تنظیم می‌کند و محتوا را مقیاس‌بندی می‌کند.

```python
def set_size(self, type, scale_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/fa/aspose.slides/slidesizetype) | اندازه پیش‌تعریف‌شدهٔ اسلاید برای اعمال. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/fa/aspose.slides/slidesizescaletype) | حالت مقیاس‌بندی محتوا برای استفاده. |

### توضیحات

اختصاص هر مقدار غیر از [`SlideSizeType.CUSTOM`](/slides/python-net/fa/aspose.slides/slidesizetype/CUSTOM)، [`ISlideSize.size`](/slides/python-net/fa/aspose.slides/islidesize/size) را بر اساس نوع انتخاب‌شده تنظیم می‌کند، در حالی که [`ISlideSize.orientation`](/slides/python-net/fa/aspose.slides/islidesize/orientation) را حفظ می‌دارد.

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
ابعاد اسلاید را به‌وضوح تنظیم می‌کند و محتوا را مقیاس‌بندی می‌کند.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| width | **float** | عرض جدید اسلاید، به پوینت. |
| height | **float** | ارتفاع جدید اسلاید، به پوینت. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/fa/aspose.slides/slidesizescaletype) | حالت مقیاس‌بندی محتوا برای استفاده. |

### توضیحات

این ویژگی [`ISlideSize.type`](/slides/python-net/fa/aspose.slides/islidesize/type) را به [`SlideSizeType.CUSTOM`](/slides/python-net/fa/aspose.slides/slidesizetype/CUSTOM) بازنشانی می‌کند و [`ISlideSize.orientation`](/slides/python-net/fa/aspose.slides/islidesize/orientation) را تنظیم می‌نماید.

### موارد مرتبط
* کلاس [`ISlideSize`](/slides/python-net/fa/aspose.slides/islidesize)
* شمارش [`SlideSizeScaleType`](/slides/python-net/fa/aspose.slides/slidesizescaletype)
* شمارش [`SlideSizeType`](/slides/python-net/fa/aspose.slides/slidesizetype)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)