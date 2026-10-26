---
title: get_ZoomImage()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحصل على الصورة لكائن Zoom. اقرأ IPPImage.
type: docs
weight: 79
url: /ar/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() طريقة

يحصل على الصورة لكائن Zoom. اقرأ [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## ملاحظات

يوضح المثال تغيير صورة كائن Zoom:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IPPImage](../../ippimage/)
* فئة [IZoomObject](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)