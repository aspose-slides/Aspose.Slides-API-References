---
title: InsertSummaryZoomFrame()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينشئ إطار تكبير ملخّص جديد ويُدرجه في مجموعة الأشكال في الموضع المحدد.
type: docs
weight: 157
url: /ar/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) طريقة


ينشئ إطار تكبير ملخّص جديد ويُدرجه في مجموعة الأشكال في الموضع المحدد.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري-المستند إلى الصفر الذي يتم منه إدراج إطار تكبير الملخّص. |
| x | **float** | إحداثي x لإطار تكبير الملخّص الجديد، بالنقاط. |
| y | **float** | إحداثي y لإطار تكبير الملخّص الجديد، بالنقاط. |
| width | **float** | عرض إطار تكبير الملخّص الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار تكبير الملخّص الجديد، بالنقاط. |

### قيمة الإرجاع

[ISummaryZoomFrame](../../isummaryzoomframe/) الذي تم إنشاؤه حديثًا.
## ملاحظات


هذه الطريقة تنشئ إطار تكبير ملخّص يجمع روابط الملخص لجميع الأقسام في العرض التقديمي.

هذا المثال يوضح إنشاء وإدراج كائن تكبير ملخّص في الفهرس المحدد لمجموعة (افترض وجود قسمين على الأقل في العرض التقديمي \"Presentation.pptx\"):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [ISummaryZoomFrame](../../isummaryzoomframe/)
* الفئة [IShapeCollection](../)
* نطاق الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)