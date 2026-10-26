---
title: set_TransitionDuration()
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in varaktigheten för övergången mellan Zoom och bild. Skriv float. Standardvärde: 1.0f"
type: docs
weight: 118
url: /sv/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) method

Ställer in varaktigheten för övergången mellan Zoom och bild. Skriv **float**. Standardvärde: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## Anmärkningar

Om den inte anges (TransitionDur = 0) kommer den att använda destinationens bildövergång och tidpunkterna som är kopplade till den övergången.

exemplet visar hur man ändrar varaktigheten av övergången mellan Zoom och bild:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Se även

* Klass [IZoomObject](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)