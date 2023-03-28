---
title: set_ReturnToParent()
second_title: Aspose.Slides for C++ API Reference
description: "Sets the navigation behavior in slideshow. Write bool. Default value: false"
type: docs
weight: 40
url: /cpp/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(**bool**) method


Sets the navigation behavior in slideshow. Write **bool**. Default value: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
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
