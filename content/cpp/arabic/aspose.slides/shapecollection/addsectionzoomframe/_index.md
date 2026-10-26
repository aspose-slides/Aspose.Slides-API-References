---
title: AddSectionZoomFrame()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ إطار Zoom جديد للقسم ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 131
url: /ar/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) method

ينشئ إطار Zoom جديد [Section](../../section/) ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | الإحداثي x للإطار Zoom الجديد [Section](../../section/)، بالنقاط. |
| y | **float** | الإحداثي y للإطار Zoom الجديد [Section](../../section/)، بالنقاط. |
| width | **float** | العرض للإطار Zoom الجديد [Section](../../section/)، بالنقاط. |
| height | **float** | الارتفاع للإطار Zoom الجديد [Section](../../section/)، بالنقاط. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) المشار إليه بواسطة إطار Zoom [Section](../../section/)؛ يجب أن يكون تابعًا لهذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |

### قيمة الإرجاع

الـ[ISectionZoomFrame](../../isectionzoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يوضح هذا المثال إضافة كائن Zoom [Section](../../section/) إلى نهاية مجموعة (افترض أنه يوجد قسمان على الأقل في عرض "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method

ينشئ إطار Zoom جديد [Section](../../section/) مع صورة معرفة مسبقًا ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | الإحداثي x للإطار Zoom الجديد [Section](../../section/)، بالنقاط. |
| y | **float** | الإحداثي y للإطار Zoom الجديد [Section](../../section/)، بالنقاط. |
| width | **float** | العرض للإطار Zoom الجديد [Section](../../section/)، بالنقاط. |
| height | **float** | الارتفاع للإطار Zoom الجديد [Section](../../section/)، بالنقاط. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) المشار إليه بواسطة إطار Zoom [Section](../../section/)؛ يجب أن يكون تابعًا لهذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) لعرضه داخل إطار Zoom [Section](../../section/). |

### قيمة الإرجاع

الـ[ISectionZoomFrame](../../isectionzoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يوضح هذا المثال إضافة كائن Zoom [Section](../../section/) إلى نهاية مجموعة (افترض أنه يوجد قسمان على الأقل في عرض "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)