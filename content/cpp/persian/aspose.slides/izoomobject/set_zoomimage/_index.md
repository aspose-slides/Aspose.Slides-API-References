---
title: set_ZoomImage()
second_title: Aspose.Slides برای C++ مرجع API
description: تصویر را برای شی زوم تنظیم می‌کند. IPPImage را بنویسید.
type: docs
weight: 92
url: /fa/aspose.slides/izoomobject/set_zoomimage/
---
## IZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) متد


تصویر را برای شی زوم تنظیم می‌کند. [IPPImage](../../ippimage/) را بنویسید.

```cpp
virtual void Aspose::Slides::IZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value)=0
```

## یادداشت‌ها


مثال نشان می‌دهد که چگونه تصویر یک شی زوم را تغییر می‌دهیم: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IPPImage](../../ippimage/)
* کلاس [IZoomObject](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)