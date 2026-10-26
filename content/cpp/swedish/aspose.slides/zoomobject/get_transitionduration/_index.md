---
title: get_TransitionDuration()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar varaktigheten för övergången mellan Zoom och bild. Läs float. Standardvärde: 1.0f"
type: docs
weight: 105
url: /sv/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() metod


Hämtar varaktigheten för övergången mellan Zoom och bild. Läs **float**. Standardvärde: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## Anmärkningar


Om den inte anges (TransitionDur = 0) kommer den att använda destinationens bildövergång och tidsinställningarna som är associerade med den övergången. 

exemplet visar hur man ändrar varaktigheten för övergången mellan Zoom och bild: 
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