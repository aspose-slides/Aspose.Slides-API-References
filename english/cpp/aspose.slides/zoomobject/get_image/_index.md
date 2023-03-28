---
title: get_Image()
second_title: Aspose.Slides for C++ API Reference
description: Gets image for zoom object. Read IPPImage.
type: docs
weight: 79
url: /cpp/aspose.slides/zoomobject/get_image/
---
## ZoomObject::get_Image() method


Gets image for zoom object. Read [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_Image() override
```

## Remarks


the example demonstrates changing an image of a Zoom object: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
zoomFrame->set_Image(image);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPPImage](../../ippimage/)
* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
