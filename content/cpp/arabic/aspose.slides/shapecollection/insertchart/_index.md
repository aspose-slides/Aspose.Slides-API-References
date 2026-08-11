---
title: InsertChart()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إنشاء مخطط جديد، تهيئته ببيانات سلسلة نموذجية وإعدادات، وإدخاله في مجموعة الأشكال عند الفهرس المحدد.
type: docs
weight: 92
url: /ar/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) طريقة

يقوم بإنشاء مخطط جديد، يتهيئه ببيانات سلسلة نموذجية وإعدادات، ويدخله في مجموعة الأشكال عند الفهرس المحدد.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع المخطط المطلوب إنشاؤه. |
| x | **float** | الإحداثي السيني للمخطط الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي للمخطط الجديد، بالنقاط. |
| width | **float** | عرض المخطط الجديد، بالنقاط. |
| height | **float** | ارتفاع المخطط الجديد، بالنقاط. |
| index | **int32_t** | الفهرس الصفري الذي يُدرج فيه المخطط الجديد داخل مجموعة الأشكال. |

### قيمة الإرجاع

الـ[Charts::IChart](../../../aspose.slides.charts/ichart/) الذي تم إنشاؤه حديثًا.

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) طريقة

يقوم بإنشاء مخطط جديد، يتهيئه ببيانات سلسلة نموذجية وإعدادات، ويدخله في مجموعة الأشكال عند الفهرس المحدد.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع المخطط المطلوب إنشاؤه. |
| x | **float** | الإحداثي السيني للمخطط الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي للمخطط الجديد، بالنقاط. |
| width | **float** | عرض المخطط الجديد، بالنقاط. |
| height | **float** | ارتفاع المخطط الجديد، بالنقاط. |
| index | **int32_t** | الفهرس الصفري الذي يُدرج فيه المخطط الجديد داخل مجموعة الأشكال. |
| initWithSample | **bool** | True لتجهيز المخطط الجديد ببيانات سلسلة نموذجية وإعدادات؛ false لإنشاء المخطط بدون سلاسل وإعدادات قليلة، مما يجعل الإنشاء أسرع. |

### قيمة الإرجاع

الـ[Charts::IChart](../../../aspose.slides.charts/ichart/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* تعداد [ChartType](../../../aspose.slides.charts/charttype/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChart](../../../aspose.slides.charts/ichart/)
* فئة [ShapeCollection](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)