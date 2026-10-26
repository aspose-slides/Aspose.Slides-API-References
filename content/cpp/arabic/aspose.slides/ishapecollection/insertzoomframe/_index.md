---
title: InsertZoomFrame()
second_title: مرجع API ل Aspose.Slides للغة C++
description: ينشئ إطار Zoom جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.
type: docs
weight: 105
url: /ar/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) طريقة

ينشئ إطار Zoom جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يتم إدراج إطار Zoom فيه. |
| x | **float** | الإحداثي x لإطار Zoom الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي y لإطار Zoom الجديد، بوحدات النقاط. |
| width | **float** | عرض إطار Zoom الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بوحدات النقاط. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | ال[ISlide](../../islide/) المشار إليه بواسطة إطار Zoom. |

### قيمة الإرجاع

الـ[IZoomFrame](../../izoomframe/) الذي تم إنشاءه حديثًا.

## ملاحظات

هذا المثال يوضح إنشاء وإدراج كائن Zoom عند الفهرس المحدد لمجموعة (افترض أن هناك شريحتين على الأقل في عرض \"Presentation.pptx\"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) طريقة

ينشئ إطار Zoom جديد بصورة مُحددة مسبقًا ويُدخله في مجموعة الأشكال عند الفهرس المحدد.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يتم إدراج إطار Zoom فيه. |
| x | **float** | الإحداثي x لإطار Zoom الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي y لإطار Zoom الجديد، بوحدات النقاط. |
| width | **float** | عرض إطار Zoom الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بوحدات النقاط. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | ال[ISlide](../../islide/) المشار إليه بواسطة إطار Zoom. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | الصورة لل[IPPImage](../../ippimage/) المشار إليه. |

### قيمة الإرجاع

الـ[IZoomFrame](../../izoomframe/) الذي تم إنشاءه حديثًا.

## ملاحظات

هذا المثال يوضح إنشاء وإدراج كائن Zoom عند الفهرس المحدد لمجموعة (افترض أن هناك شريحتين على الأقل في عرض \"Presentation.pptx\"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)