---
title: get_TransitionDuration()
second_title: Aspose.Slides für C++ API-Referenz
description: "Ermittelt die Dauer des Übergangs zwischen Zoom und Folie. Lese float. Standardwert: 1.0f"
type: docs
weight: 105
url: /de/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() Methode

Ermittelt die Dauer des Übergangs zwischen Zoom und Folie. Lese **float**. Standardwert: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Bemerkungen

Wenn nicht angegeben (TransitionDur = 0), wird der Zielfolien-Übergang und die damit verbundenen Zeitangaben verwendet.

Das Beispiel zeigt, wie die Dauer des Übergangs zwischen Zoom und Folie geändert wird:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Siehe auch

* Klasse [IZoomObject](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)