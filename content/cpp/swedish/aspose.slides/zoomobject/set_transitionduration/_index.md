---
title: set_TransitionDuration()
second_title: Aspose.Slides för C++ API-referens
description: "Anger varaktigheten för övergången mellan Zoom och bild. Använd float. Standardvärde: 1.0f"
type: docs
weight: 118
url: /sv/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) metod

Anger varaktigheten för övergången mellan Zoom och bild. Använd **float**. Standardvärde: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## Anmärkningar

Om den inte anges (TransitionDur = 0) används destinationens bildövergång och tidsinställningarna som är associerade med den övergången. 

Exemplet visar hur varaktigheten för övergången mellan Zoom och bild ändras: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Se även

* Klass [ZoomObject](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)