---
title: insert_clone method
second_title: مرجع Aspose.Slides للـ Python عبر .NET API
description: 
type: docs
url: /ar/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
يدرج نسخة من شريحة تخطيط محددة في الموضع المحدد من المجموعة.

### الإرجاع

الشريحة المُدْرَجَة.



```python
def insert_clone(self, index, source_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | فهرس الشريحة الجديدة. |
| source_layout | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | الشريحة التي سيتم استنساخها. |

### ملاحظات

سيتم ربط التخطيط الجديد بشريحة الماستر الأصلية لهذا التجميع من شرائح التخطيط.
            وهذا ما يعادل النسخ/اللصق مع خيار "Use Destination Theme" في PowerPoint.



### انظر أيضًا
* class [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* class [`MasterLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/masterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)