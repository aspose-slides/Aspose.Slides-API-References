---
title: AddSummaryZoomFrame()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ إطار Summary Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 144
url: /ar/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) طريقة

ينشئ إطار Summary Zoom ملخص جديد ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي x للإطار Summary Zoom الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي y للإطار Summary Zoom الجديد، بوحدات النقاط. |
| width | **float** | العرض للإطار Summary Zoom الجديد، بوحدات النقاط. |
| height | **float** | الارتفاع للإطار Summary Zoom الجديد، بوحدات النقاط. |

### قيمة الإرجاع

الـ[ISummaryZoomFrame](../../isummaryzoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

هذه الطريقة تنشئ إطار Summary Zoom يجمع روابط الملخص لجميع الأقسام في العرض التقديمي.

يوضح هذا المثال إضافة كائن Summary Zoom إلى نهاية مجموعة (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [ISummaryZoomFrame](../../isummaryzoomframe/)
* الفئة [IShapeCollection](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)