---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides لـ C++ مرجع API
description: "إذا كان التجميع يحتوي بالفعل على نقطة بيانات بالرقم index فإنّه يُعيد هذه النقطة. إذا لم يحتوي التجميع على نقطة بيانات بالرقم index ==N (عندما يكون عدد نقاط البيانات في هذا التجميع أقل أو يساوي N) فسيضيف نقاط البيانات الناقصة ويعيد الأخيرة (التي لها الرقم المطلوب). على سبيل المثال، أرقام التجميع هي {0, 1, 2}، والرقم المطلوب هو 5. حينها تضيف الطريقة نقاط البيانات الناقصة: {0, 1, 2, 3, 4, 5}. وتعيد نقطة البيانات بالرقم 5."
type: docs
weight: 131
url: /ar/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) طريقة


إذا كان التجميع يحتوي بالفعل على نقطة بيانات بالرقم *index* فستُرجع هذه النقطة. إذا لم يحتوي التجميع على نقطة بيانات بالرقم *index* ==N (عندما يكون عدد نقاط البيانات في هذا التجميع أقل أو يساوي N) فستضيف نقاط البيانات الناقصة وتُرجع الأخيرة (التي لها الرقم المطلوب). على سبيل المثال، أرقام التجميع هي {0, 1, 2}، والرقم المطلوب هو 5. عندها تُضيف الطريقة نقاط البيانات الناقصة: {0, 1, 2, 3, 4, 5}. وتُرجع نقطة البيانات بالرقم 5.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```


### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| index | **uint32_t** | الفهرس. |

### قيمة الإرجاع

ترجع نقطة البيانات بالرقم المطلوب.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChartDataPoint](../../ichartdatapoint/)
* فئة [IChartDataPointCollection](../)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)