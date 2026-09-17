---
title: set_size method
second_title: Aspose.Slides لبايثون عبر .NET دليل API
description: 
type: docs
url: /ar/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
يضبط حجم الشريحة وفق النوع ويقوم بتكبير المحتوى الموجود.

```python
def set_size(self, type, scale_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/ar/aspose.slides/slidesizetype) | حجم الشريحة المحدد مسبقًا لتطبيقه. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ar/aspose.slides/slidesizescaletype) | وضعية تكبير المحتوى للاستخدام. |

### ملاحظات
تعيين أي قيمة غير [`SlideSizeType.CUSTOM`](/slides/python-net/ar/aspose.slides/slidesizetype/CUSTOM) يضبط [`SlideSize.size`](/slides/python-net/ar/aspose.slides/slidesize/size) بناءً على النوع المحدد، مع الحفاظ على [`SlideSize.orientation`](/slides/python-net/ar/aspose.slides/slidesize/orientation).

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
يضبط أبعاد الشريحة صراحةً ويقوم بتكبير المحتوى الموجود.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| width | **float** | عرض الشريحة الجديد، بالنقاط. |
| height | **float** | ارتفاع الشريحة الجديد، بالنقاط. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ar/aspose.slides/slidesizescaletype) | وضعية تكبير المحتوى للاستخدام. |

### ملاحظات
يعمل هذا على إعادة تعيين خاصية [`SlideSize.type`](/slides/python-net/ar/aspose.slides/slidesize/type) إلى [`SlideSizeType.CUSTOM`](/slides/python-net/ar/aspose.slides/slidesizetype/CUSTOM) ويضبط [`SlideSize.orientation`](/slides/python-net/ar/aspose.slides/slidesize/orientation).

### انظر أيضًا
* الفئة [`SlideSize`](/slides/python-net/ar/aspose.slides/slidesize)
* التعداد [`SlideSizeScaleType`](/slides/python-net/ar/aspose.slides/slidesizescaletype)
* التعداد [`SlideSizeType`](/slides/python-net/ar/aspose.slides/slidesizetype)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)