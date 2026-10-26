---
title: InsertZoomFrame()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ إطار Zoom جديد ويدخله في مجموعة الأشكال عند الفهرس المحدد.
type: docs
weight: 118
url: /ar/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) method

ينشئ إطار Zoom جديد ويدمجه في ShapeCollection في الفهرس المحدد.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يُدخل فيه إطار Zoom. |
| x | **float** | الإحداثي السيني لإطار Zoom الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي الصادي لإطار Zoom الجديد، بوحدات النقاط. |
| width | **float** | العرض لإطار Zoom الجديد، بوحدات النقاط. |
| height | **float** | الارتفاع لإطار Zoom الجديد، بوحدات النقاط. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | الـ [ISlide](../../islide/) الذي يشير إليه إطار Zoom. |

### قيمة الإرجاع

الـ [IZoomFrame](../../izoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يوضح هذا المثال إنشاء وإدراج كائن Zoom في الفهرس المحدد لمجموعة (يفترض وجود شرائحين على الأقل في عرض "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

ينشئ إطار Zoom جديد بصورة محددة مسبقًا ويدمجه في ShapeCollection في الفهرس المحدد.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يُدخل فيه إطار Zoom. |
| x | **float** | الإحداثي السيني لإطار Zoom الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي الصادي لإطار Zoom الجديد، بوحدات النقاط. |
| width | **float** | العرض لإطار Zoom الجديد، بوحدات النقاط. |
| height | **float** | الارتفاع لإطار Zoom الجديد، بوحدات النقاط. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | الـ [ISlide](../../islide/) الذي يشير إليه إطار Zoom. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | الصورة للشرائح المشار إليها [IPPImage](../../ippimage/). |

### قيمة الإرجاع

الـ [IZoomFrame](../../izoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يوضح هذا المثال إنشاء وإدراج كائن Zoom في الفهرس المحدد لمجموعة (يفترض وجود شرائحين على الأقل في عرض "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## أنظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IZoomFrame](../../izoomframe/)
* فئة [ISlide](../../islide/)
* فئة [ShapeCollection](../)
* فئة [IPPImage](../../ippimage/)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)