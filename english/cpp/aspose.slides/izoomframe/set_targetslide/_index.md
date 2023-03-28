---
title: set_TargetSlide()
second_title: Aspose.Slides for C++ API Reference
description: Sets the slide object that the Slide Zoom object links to. Write ISlide.
type: docs
weight: 14
url: /cpp/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide([System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>) method


Sets the slide object that the [Slide](../../slide/) Zoom object links to. Write [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
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
* Class [IZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
