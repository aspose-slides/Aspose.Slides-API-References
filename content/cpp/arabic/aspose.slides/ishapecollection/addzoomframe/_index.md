---
title: AddZoomFrame()
second_title: مرجع Aspose.Slides للغة C++
description: ينشئ إطار Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 92
url: /ar/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) method

ينشئ إطار Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي السيني لإطار Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بالنقاط. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | الـ [ISlide](../../islide/) المشار إليه بواسطة إطار Zoom؛ يجب أن يكون جزءًا من هذا العرض التقديمي. |

### قيمة الإرجاع

الـ [IZoomFrame](../../izoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يوضح هذا المثال إضافة كائن Zoom إلى نهاية مجموعة (افترض وجود شريحتين على الأقل في عرض "Presentation.pptx"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

ينشئ إطار Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي السيني لإطار Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بالنقاط. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | الـ [ISlide](../../islide/) المشار إليه بواسطة إطار Zoom؛ يجب أن يكون جزءًا من هذا العرض التقديمي. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | الصورة للشفرة المشار إليها [IPPImage](../../ippimage/). |

### قيمة الإرجاع

الـ [IZoomFrame](../../izoomframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يوضح هذا المثال إضافة كائن Zoom إلى نهاية مجموعة (افترض وجود شريحتين على الأقل في عرض "Presentation.pptx"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)