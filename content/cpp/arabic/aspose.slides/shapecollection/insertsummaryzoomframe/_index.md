---
title: InsertSummaryZoomFrame()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينشئ إطار Summary Zoom جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.
type: docs
weight: 170
url: /ar/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) طريقة

ينشئ إطار Summary Zoom جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يتم عنده إدراج إطار Summary Zoom. |
| x | **float** | الإحداثي x لإطار Summary Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار Summary Zoom الجديد، بالنقاط. |
| width | **float** | العرض لإطار Summary Zoom الجديد، بالنقاط. |
| height | **float** | الارتفاع لإطار Summary Zoom الجديد، بالنقاط. |

### قيمة الإرجاع

الكائن [ISummaryZoomFrame](../../isummaryzoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

تنشئ هذه الطريقة إطار Summary Zoom يجمع روابط الملخص لجميع الأقسام في العرض التقديمي. 

يوضح هذا المثال إنشاء وإدراج كائن Summary Zoom عند الفهرس المحدد لمجموعة (افترض أنه يوجد على الأقل قسمان في عرض "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## راجع أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)