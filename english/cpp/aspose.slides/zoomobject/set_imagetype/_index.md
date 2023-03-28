---
title: set_ImageType()
second_title: Aspose.Slides for C++ API Reference
description: "Sets the image type of a zoom object. Write ZoomImageType. Default value: Preview"
type: docs
weight: 14
url: /cpp/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType([ZoomImageType](../../zoomimagetype/)) method


Sets the image type of a zoom object. Write [ZoomImageType](../../zoomimagetype/). Default value: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## Remarks


Specifies whether the Zoom object is using the slide preview or a cover image. 

Next example demonstrates changing Image Type to Preview value. In this case current image of a Zoom object changes to slide image: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## See Also

* Enum [ZoomImageType](../../zoomimagetype/)
* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
