---
title: GetOrCreateDataPointByIdx()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "إذا كانت المجموعة تحتوي بالفعل على نقطة بيانات ذات الفهرس index فإنها تُعيد هذه النقطة. إذا لم تحتوي المجموعة على نقطة بيانات ذات الفهرس index ==N (عندما يكون عدد نقاط البيانات في هذه المجموعة أقل أو يساوي N) فإنها تضيف نقاط بيانات مفقودة وتُعيد الأخيرة (التي لها الفهرس المطلوب). على سبيل المثال، فهارس المجموعة هي {0, 1, 2}، والفهرس المطلوب هو 5. ثم تضيف الطريقة نقاط البيانات المفقودة: {0, 1, 2, 3, 4, 5}. وتعيد نقطة البيانات ذات الفهرس 5."
type: docs
weight: 170
url: /ar/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) طريقة

إذا كانت المجموعة تحتوي بالفعل على نقطة بيانات ذات الفهرس *index* فإنها تُعيد هذه النقطة. إذا لم تحتوي المجموعة على نقطة بيانات ذات الفهرس *index* ==N (عند كون عدد نقاط البيانات في هذه المجموعة أقل أو يساوي N) فإنها تضيف نقاط بيانات مفقودة وتُعيد الأخيرة (التي لها الفهرس المطلوب). على سبيل المثال، فهارس المجموعة هي {0, 1, 2}، والفهرس المطلوب هو 5. ثم تُضيف الطريقة نقاط البيانات المفقودة: {0, 1, 2, 3, 4, 5}. وتُعيد نقطة البيانات ذات الفهرس 5.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | **uint32_t** | الفهرس. |

### قيمة الإرجاع

يعيد نقطة البيانات ذات الفهرس المطلوب.

## أنظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChartDataPoint](../../ichartdatapoint/)
* فئة [ChartDataPointCollection](../)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)