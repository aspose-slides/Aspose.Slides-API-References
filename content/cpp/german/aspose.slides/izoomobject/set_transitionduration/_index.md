---
title: set_TransitionDuration()
second_title: Aspose.Slides für C++ API-Referenz
description: "Setzt die Dauer der Transition zwischen Zoom und Folie. Schreiben float. Standardwert: 1.0f"
type: docs
weight: 118
url: /de/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) Methode

Setzt die Dauer der Transition zwischen Zoom und Folie. Schreiben **float**. Standardwert: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## Hinweise

Wenn nicht angegeben (TransitionDur = 0), wird die Zielfolien-Transition und die damit verbundenen Zeitangaben verwendet.

Das Beispiel zeigt, wie die Dauer der Transition zwischen Zoom und Folie geändert wird: 
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