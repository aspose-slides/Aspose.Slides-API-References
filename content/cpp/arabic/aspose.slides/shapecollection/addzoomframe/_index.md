---
title: AddZoomFrame()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ إطار Zoom جديدًا ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 105
url: /ar/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) طريقة

ينشئ إطار Zoom جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي X لإطار Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي Y لإطار Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بالنقاط. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | ال[ISlide](../../islide/) المشار إليه بواسطة إطار Zoom؛ يجب أن يكون تابعًا لهذا العرض التقديمي. |

### قيمة الإرجاع

ال[IZoomFrame](../../izoomframe/) الذي تم إنشاؤه حديثًا.

## ملحوظات

هذا المثال يوضح إضافة كائن Zoom إلى نهاية مجموعة (افترض وجود شريحتين على الأقل في عرض تقديمي "Presentation.pptx"):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) طريقة

ينشئ إطار Zoom جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي X لإطار Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي Y لإطار Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بالنقاط. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | ال[ISlide](../../islide/) المشار إليه بواسطة إطار Zoom؛ يجب أن يكون تابعًا لهذا العرض التقديمي. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | الصورة للشريحة [IPPImage](../../ippimage/). |

### قيمة الإرجاع

ال[IZoomFrame](../../izoomframe/) الذي تم إنشاؤه حديثًا.

## ملحوظات

هذا المثال يوضح إضافة كائن Zoom إلى نهاية مجموعة (افترض وجود شريحتين على الأقل في عرض تقديمي "Presentation.pptx"):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IZoomFrame](../../izoomframe/)
* فئة [ISlide](../../islide/)
* فئة [ShapeCollection](../)
* فئة [IPPImage](../../ippimage/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)