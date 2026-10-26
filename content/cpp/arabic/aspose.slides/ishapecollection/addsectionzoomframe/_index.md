---
title: AddSectionZoomFrame()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ إطار Zoom قسم جديد ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 118
url: /ar/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) طريقة

ينشئ إطار Zoom جديد [Section](../../section/) ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي السيني للإطار Zoom الجديد [Section](../../section/) ، بوحدات النقاط. |
| y | **float** | الإحداثي الصادي للإطار Zoom الجديد [Section](../../section/) ، بوحدات النقاط. |
| width | **float** | العرض للإطار Zoom الجديد [Section](../../section/) ، بوحدات النقاط. |
| height | **float** | الارتفاع للإطار Zoom الجديد [Section](../../section/) ، بوحدات النقاط. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | ال[ISection](../../isection/) المشار إليه بواسطة إطار Zoom [Section](../../section/)؛ يجب أن يكون تابعًا لهذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |

### قيمة الإرجاع

ال[ISectionZoomFrame](../../isectionzoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يوضح هذا المثال إضافة كائن Zoom [Section](../../section/) إلى نهاية مجموعة (افترض وجود مقطعين على الأقل في عرض "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) طريقة

ينشئ إطار Zoom جديد [Section](../../section/) مع صورة محددة مسبقًا ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي السيني للإطار Zoom الجديد [Section](../../section/) ، بوحدات النقاط. |
| y | **float** | الإحداثي الصادي للإطار Zoom الجديد [Section](../../section/) ، بوحدات النقاط. |
| width | **float** | العرض للإطار Zoom الجديد [Section](../../section/) ، بوحدات النقاط. |
| height | **float** | الارتفاع للإطار Zoom الجديد [Section](../../section/) ، بوحدات النقاط. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | ال[ISection](../../isection/) المشار إليه بواسطة إطار Zoom [Section](../../section/)؛ يجب أن يكون تابعًا لهذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | ال[IPPImage](../../ippimage/) للعرض داخل إطار Zoom [Section](../../section/). |

### قيمة الإرجاع

ال[ISectionZoomFrame](../../isectionzoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يوضح هذا المثال إضافة كائن Zoom [Section](../../section/) إلى نهاية مجموعة (افترض وجود مقطعين على الأقل في عرض "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISectionZoomFrame](../../isectionzoomframe/)
* فئة [ISection](../../isection/)
* فئة [IShapeCollection](../)
* فئة [IPPImage](../../ippimage/)
* مساحة أسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)