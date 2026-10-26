---
title: get_ZoomImage()
second_title: مرجع API Aspose.Slides لـ C++
description: يحصل على صورة لكائن Zoom. اقرأ IPPImage.
type: docs
weight: 79
url: /ar/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() طريقة

يحصل على صورة لكائن Zoom. اقرأ [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## ملاحظات

يُظهر المثال تغيير صورة لكائن Zoom:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IPPImage](../../ippimage/)
* فئة [ZoomObject](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)