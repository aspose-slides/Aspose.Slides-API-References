---
title: InsertSectionZoomFrame()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ إطار تكبير القسم الجديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.
type: docs
weight: 144
url: /ar/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) طريقة

ينشئ إطار Zoom جديد [Section](../../section/) ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يتم عنده إدراج إطار Zoom [Section](../../section/). |
| x | **float** | الإحداثي x لإطار Zoom [Section](../../section/) الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار Zoom [Section](../../section/) الجديد، بالنقاط. |
| width | **float** | عرض إطار Zoom [Section](../../section/) الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Zoom [Section](../../section/) الجديد، بالنقاط. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | ال[ISection](../../isection/) المشار إليه بواسطة إطار Zoom [Section](../../section/)؛ يجب أن ينتمي إلى هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |

### قيمة الإرجاع

الكائن [ISectionZoomFrame](../../isectionzoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يوضح هذا المثال إنشاء وإدراج كائن Zoom [Section](../../section/) عند الفهرس المحدد لمجموعة (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) طريقة

ينشئ إطار Zoom جديد [Section](../../section/) مع صورة محددة مسبقًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يتم عنده إدراج إطار Zoom [Section](../../section/). |
| x | **float** | الإحداثي x لإطار Zoom [Section](../../section/) الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار Zoom [Section](../../section/) الجديد، بالنقاط. |
| width | **float** | عرض إطار Zoom [Section](../../section/) الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Zoom [Section](../../section/) الجديد، بالنقاط. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | ال[ISection](../../isection/) المشار إليه بواسطة إطار Zoom [Section](../../section/)؛ يجب أن ينتمي إلى هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | الصورة التي سيتم عرضها داخل إطار Zoom [Section](../../section/). |

### قيمة الإرجاع

الكائن [ISectionZoomFrame](../../isectionzoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

هذا المثال يوضح إنشاء وإدراج كائن Zoom [Section](../../section/) عند الفهرس المحدد لمجموعة (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISectionZoomFrame](../../isectionzoomframe/)
* فئة [ISection](../../isection/)
* فئة [ShapeCollection](../)
* فئة [IPPImage](../../ippimage/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)