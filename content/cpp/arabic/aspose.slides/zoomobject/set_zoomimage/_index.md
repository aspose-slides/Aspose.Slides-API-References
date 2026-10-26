---
title: set_ZoomImage()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد الصورة لكائن التكبير. اكتب IPPImage.
type: docs
weight: 92
url: /ar/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) طريقة


يحدد الصورة لكائن التكبير. اكتب [IPPImage](../../ippimage/).

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
```

## ملاحظات


المثال يوضح تغيير صورة كائن التكبير: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IPPImage](../../ippimage/)
* فئة [ZoomObject](../)
* نطاق الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)