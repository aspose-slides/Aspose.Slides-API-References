---
title: get_TargetSlide()
second_title: Aspose.Slides for C++ API Reference
description: Gets the slide object that the Slide Zoom object links to. Read ISlide.
type: docs
weight: 1
url: /aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() method


Gets the slide object that the [Slide](../../slide/) Zoom object links to. Read [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Remarks


Next example demonstrates changing target slide and creates new image for the [Slide](../../slide/) Zoom object: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)