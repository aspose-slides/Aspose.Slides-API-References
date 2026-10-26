---
title: Remove()
second_title: Aspose.Slides للغة C++ مرجع API
description: يزيل العنصر من المجموعة.
type: docs
weight: 79
url: /ar/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) طريقة


يزيل العنصر من المجموعة.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | نقطة البيانات لإزالتها. |

### قيمة الإرجاع

صحيح إذا تم إزالة العنصر بنجاح؛ وإلا، خطأ. تعيد هذه الطريقة أيضًا خطأ إذا لم يتم العثور على العنصر في [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) طريقة


يزيل العنصر من المجموعة حسب فهرسه في مجموعة نقاط السلسلة الأصلية.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dataPointIndex | **int32_t** | فهرس نقطة البيانات في مجموعة نقاط السلسلة الأصلية. |

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IChartDataPoint](../../ichartdatapoint/)
* فئة [PieSplitCustomPointCollection](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)