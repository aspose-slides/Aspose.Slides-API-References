---
title: get_ShowBackground()
second_title: Aspose.Slides for C++ API Reference
description: "Gets value that specifies whether the Zoom will use the background of the destination slide. Read bool. Default value: true"
type: docs
weight: 53
url: /cpp/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() method


Gets value that specifies whether the Zoom will use the background of the destination slide. Read **bool**. Default value: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
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
