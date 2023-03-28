---
title: set_TransitionDuration()
second_title: Aspose.Slides for C++ API Reference
description: "Sets the duration of the transition between Zoom and slide. Write float. Default value: 1.0f"
type: docs
weight: 118
url: /cpp/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(**float**) method


Sets the duration of the transition between Zoom and slide. Write **float**. Default value: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
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

* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
