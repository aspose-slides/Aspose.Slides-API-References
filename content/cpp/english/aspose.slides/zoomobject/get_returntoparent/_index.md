---
title: get_ReturnToParent()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the navigation behavior in slideshow. Read bool. Default value: false"
type: docs
weight: 27
url: /aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() method


Gets the navigation behavior in slideshow. Read **bool**. Default value: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Remarks


True value of the property specifies return to parent navigation behavior in slideshow. 

Example: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## See Also

* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)