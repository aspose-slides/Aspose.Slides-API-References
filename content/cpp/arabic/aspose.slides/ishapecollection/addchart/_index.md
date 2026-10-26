---
title: AddChart()
second_title: مرجع API Aspose.Slides للـ C++
description: ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة عينية وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 27
url: /ar/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) طريقة

ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة عينية وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع المخطط المراد إضافته. |
| x | **float** | الإحداثي السيني للمخطط الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي للمخطط الجديد، بالنقاط. |
| width | **float** | عرض المخطط، بالنقاط. |
| height | **float** | ارتفاع المخطط، بالنقاط. |

### قيمة الإرجاع

الـ[Charts::IChart](../../../aspose.slides.charts/ichart/) الذي تم إنشاؤه حديثًا.

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) طريقة

ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة عينية وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع المخطط المراد إضافته. |
| x | **float** | الإحداثي السيني للمخطط الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي للمخطط الجديد، بالنقاط. |
| width | **float** | عرض المخطط، بالنقاط. |
| height | **float** | ارتفاع المخطط، بالنقاط. |
| initWithSample | **bool** | صحيح لتهيئة المخطط الجديد ببيانات سلسلة عينية وإعدادات؛ خطأ لإنشاء المخطط بدون سلاسل وبإعدادات قليلة فقط، مما يجعل الإنشاء أسرع. |

### قيمة الإرجاع

الـ[Charts::IChart](../../../aspose.slides.charts/ichart/) الذي تم إنشاؤه حديثًا.

## انظر أيضاً

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)