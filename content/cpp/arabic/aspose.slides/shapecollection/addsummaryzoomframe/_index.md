---
title: AddSummaryZoomFrame()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ إطار Summary Zoom جديدًا ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 157
url: /ar/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) طريقة

ينشئ إطار Summary Zoom جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي السيني للإطار الجديد Summary Zoom، بوحدة النقاط. |
| y | **float** | الإحداثي الصادي للإطار الجديد Summary Zoom، بوحدة النقاط. |
| width | **float** | عرض الإطار الجديد Summary Zoom، بوحدة النقاط. |
| height | **float** | ارتفاع الإطار الجديد Summary Zoom، بوحدة النقاط. |

### قيمة الإرجاع

The newly created [ISummaryZoomFrame](../../isummaryzoomframe/).

## ملاحظات

This method creates a new Summary Zoom and puts a collection of objects into it for all the sections in this presentation. 

This example demonstrates adding a Summary Zoom object to the end of a collection (assume that there are at least two sections in the "Presentation.pptx" presentation): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [ISummaryZoomFrame](../../isummaryzoomframe/)
* الفئة [ShapeCollection](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)