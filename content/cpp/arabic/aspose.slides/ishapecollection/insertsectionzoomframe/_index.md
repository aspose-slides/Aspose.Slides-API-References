---
title: InsertSectionZoomFrame()
second_title: مرجع API Aspose.Slides لـ C++
description: ينشئ إطار Zoom قسم جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.
type: docs
weight: 131
url: /ar/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) طريقة

إنشاء إطار Zoom جديد [Section](../../section/) وإدراجه في مجموعة الأشكال عند الفهرس المحدد.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### الوسائط

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يتم عنده إدراج إطار Zoom [Section](../../section/). |
| x | **float** | إحداثي x لإطار Zoom الجديد [Section](../../section/)، بوحدات النقاط. |
| y | **float** | إحداثي y لإطار Zoom الجديد [Section](../../section/)، بوحدات النقاط. |
| width | **float** | العرض لإطار Zoom الجديد [Section](../../section/)، بوحدات النقاط. |
| height | **float** | الارتفاع لإطار Zoom الجديد [Section](../../section/)، بوحدات النقاط. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | الـ[ISection](../../isection/) المشار إليه بواسطة إطار Zoom [Section](../../section/)؛ يجب أن يكون تابعًا لهذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |

### قيمة الإرجاع

الكائن [ISectionZoomFrame](../../isectionzoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يُظهر هذا المثال إنشاء وإدراج كائن Zoom [Section](../../section/) عند الفهرس المحدد لمجموعة (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) طريقة

إنشاء إطار Zoom جديد [Section](../../section/) بصورة مسبقة التعريف وإدراجه في مجموعة الأشكال عند الفهرس المحدد.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### الوسائط

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يتم عنده إدراج إطار Zoom [Section](../../section/). |
| x | **float** | إحداثي x لإطار Zoom الجديد [Section](../../section/)، بوحدات النقاط. |
| y | **float** | إحداثي y لإطار Zoom الجديد [Section](../../section/)، بوحدات النقاط. |
| width | **float** | العرض لإطار Zoom الجديد [Section](../../section/)، بوحدات النقاط. |
| height | **float** | الارتفاع لإطار Zoom الجديد [Section](../../section/)، بوحدات النقاط. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | الـ[ISection](../../isection/) المشار إليه بواسطة إطار Zoom [Section](../../section/)؛ يجب أن يكون تابعًا لهذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | الصورة التي سيتم عرضها داخل إطار Zoom [Section](../../section/). |

### قيمة الإرجاع

الكائن [ISectionZoomFrame](../../isectionzoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يُظهر هذا المثال إنشاء وإدراج كائن Zoom [Section](../../section/) عند الفهرس المحدد لمجموعة (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):

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
* فئة [IShapeCollection](../)
* فئة [IPPImage](../../ippimage/)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)