---
title: InsertChart()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مخططًا جديدًا، يبادئه ببيانات السلاسل النموذجية والإعدادات، ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.
type: docs
weight: 53
url: /ar/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) طريقة

ينشئ مخططًا جديدًا، يبادئه ببيانات السلاسل النموذجية والإعدادات، ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```


### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع المخطط المطلوب إنشاؤه. |
| x | **float** | الإحداثي السيني للمخطط الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي للمخطط الجديد، بالنقاط. |
| width | **float** | عرض المخطط الجديد، بالنقاط. |
| height | **float** | ارتفاع المخطط الجديد، بالنقاط. |
| index | **int32_t** | الفهرس القائم على الصفر الذي يتم عنده إدراج المخطط الجديد في مجموعة الأشكال. |

### قيمة الإرجاع

الكائن الجديد الذي تم إنشاؤه [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) طريقة

ينشئ مخططًا جديدًا، يبادئه ببيانات السلاسل النموذجية والإعدادات، ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```


### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع المخطط المطلوب إنشاؤه. |
| x | **float** | الإحداثي السيني للمخطط الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي للمخطط الجديد، بالنقاط. |
| width | **float** | عرض المخطط الجديد، بالنقاط. |
| height | **float** | ارتفاع المخطط الجديد، بالنقاط. |
| index | **int32_t** | الفهرس القائم على الصفر الذي يتم عنده إدراج المخطط الجديد في مجموعة الأشكال. |
| initWithSample | **bool** | صحيح لبدء المخطط الجديد ببيانات السلاسل النموذجية والإعدادات؛ خطأ لإنشاء المخطط بدون سلاسل ومع إعدادات الحد الأدنى فقط، مما يجعل الإنشاء أسرع. |

### قيمة الإرجاع

الكائن الجديد الذي تم إنشاؤه [Charts::IChart](../../../aspose.slides.charts/ichart/).

## انظر أيضًا

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IChart](../../../aspose.slides.charts/ichart/)
* فئة [IShapeCollection](../)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)