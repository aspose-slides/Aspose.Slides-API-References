---
title: set_size method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
يقوم بتعيين حجم الشريحة وفقًا للنوع ويضبط حجم المحتوى الموجود.

```python
def set_size(self, type, scale_type):
    ...
```

| معامل | النوع | الوصف |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/ar/aspose.slides/slidesizetype) | حجم الشريحة المحدد مسبقًا لتطبيقه. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ar/aspose.slides/slidesizescaletype) | وضعية تعديل حجم المحتوى المستخدمة. |

### ملاحظات
تعيين أي قيمة غير [`SlideSizeType.CUSTOM`](/slides/python-net/ar/aspose.slides/slidesizetype/CUSTOM) يضبط [`ISlideSize.size`](/slides/python-net/ar/aspose.slides/islidesize/size) بناءً على النوع المختار، مع الحفاظ على [`ISlideSize.orientation`](/slides/python-net/ar/aspose.slides/islidesize/orientation).

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
يقوم بتعيين أبعاد الشريحة صراحةً ويضبط حجم المحتوى الموجود.

```python
def set_size(self, width, height, scale_type):
    ...
```

| معامل | النوع | الوصف |
| :- | :- | :- |
| width | **float** | عرض الشريحة الجديد، بالنقاط. |
| height | **float** | ارتفاع الشريحة الجديد، بالنقاط. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ar/aspose.slides/slidesizescaletype) | وضعية تعديل حجم المحتوى المستخدمة. |

### ملاحظات
هذه تُعيد تعيين الخاصية [`ISlideSize.type`](/slides/python-net/ar/aspose.slides/islidesize/type) إلى [`SlideSizeType.CUSTOM`](/slides/python-net/ar/aspose.slides/slidesizetype/CUSTOM) وتضبط [`ISlideSize.orientation`](/slides/python-net/ar/aspose.slides/islidesize/orientation).

### انظر أيضًا
* فئة [`ISlideSize`](/slides/python-net/ar/aspose.slides/islidesize)
* تعداد [`SlideSizeScaleType`](/slides/python-net/ar/aspose.slides/slidesizescaletype)
* تعداد [`SlideSizeType`](/slides/python-net/ar/aspose.slides/slidesizetype)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)