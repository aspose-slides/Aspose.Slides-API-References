---
title: get_TransitionDuration()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the duration of the transition between Zoom and slide. Read float. Default value: 1.0f"
type: docs
weight: 105
url: /cpp/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() method


Gets the duration of the transition between Zoom and slide. Read **float**. Default value: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Remarks


If not specified (TransitionDur = 0), it will use the destination slide transition and the timings associated with that transition. 

the example demonstrates changing the duration of the transition between Zoom and slide: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## See Also

* Class [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
