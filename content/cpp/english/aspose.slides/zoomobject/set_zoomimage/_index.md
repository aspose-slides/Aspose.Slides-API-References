---
title: set_ZoomImage()
second_title: Aspose.Slides for C++ API Reference
description: Sets image for zoom object. Write IPPImage.
type: docs
weight: 92
url: /aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) method


Sets image for zoom object. Write [IPPImage](../../ippimage/).

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
```

## Remarks


The example demonstrates changing an image of a Zoom object: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPPImage](../../ippimage/)
* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)