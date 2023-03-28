---
title: get_ReturnToParent()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the navigation behavior in slideshow. Read bool. Default value: false"
type: docs
weight: 27
url: /cpp/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() method


Gets the navigation behavior in slideshow. Read **bool**. Default value: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Remarks


True value of the property specifies return to parent navigation behavior in slideshow. 

Example: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## See Also

* Class [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
