---
title: set_ShowBackground()
second_title: Aspose.Slides for C++ API Reference
description: "Sets value that specifies whether the Zoom will use the background of the destination slide. Write bool. Default value: true"
type: docs
weight: 66
url: /aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) method


Sets value that specifies whether the Zoom will use the background of the destination slide. Write **bool**. Default value: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## Remarks


The example demonstrates removing the background of an image of a Zoom object: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## See Also

* Class [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)