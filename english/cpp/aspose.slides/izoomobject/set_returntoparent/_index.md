---
title: set_ReturnToParent()
second_title: Aspose.Slides for C++ API Reference
description: "Sets the navigation behavior in slideshow. Write bool. Default value: false"
type: docs
weight: 40
url: /cpp/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(**bool**) method


Sets the navigation behavior in slideshow. Write **bool**. Default value: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
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
