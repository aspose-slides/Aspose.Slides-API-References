---
title: get_ShowBackground()
second_title: Aspose.Slides for C++ API Reference
description: "Gets value that specifies whether the Zoom will use the background of the destination slide. Read bool. Default value: true"
type: docs
weight: 53
url: /aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() method


Gets value that specifies whether the Zoom will use the background of the destination slide. Read **bool**. Default value: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## Remarks


the example demonstrates removing the background of an image of a Zoom object: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## See Also

* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)