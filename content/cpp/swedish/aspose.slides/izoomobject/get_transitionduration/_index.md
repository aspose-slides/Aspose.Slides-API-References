---
title: get_TransitionDuration()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar varaktigheten för övergången mellan Zoom och bild. Läser float. Standardvärde: 1.0f"
type: docs
weight: 105
url: /sv/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() metod


Hämtar varaktigheten för övergången mellan Zoom och bild. Läs **float**. Standardvärde: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Anmärkningar


Om inte specificerad (TransitionDur = 0) används destinationens bildövergång och tidsinställningarna som är associerade med den övergången. 

Exemplet visar hur man ändrar varaktigheten för övergången mellan Zoom och bild: 
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