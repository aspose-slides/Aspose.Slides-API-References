---
title: set_TransitionDuration()
second_title: Aspose.Slides für C++ API-Referenz
description: "Legt die Dauer der Transition zwischen Zoom und Folie fest. Schreiben float. Standardwert: 1.0f"
type: docs
weight: 118
url: /de/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) Methode

Legt die Dauer der Transition zwischen Zoom und Folie fest. Schreiben **float**. Standardwert: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## Bemerkungen

Wenn nicht angegeben (TransitionDur = 0), wird die Zielfolien-Transition und die damit verbundenen Zeitangaben verwendet.

Das Beispiel zeigt, wie die Dauer der Transition zwischen Zoom und Folie geändert wird:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Siehe auch

* Klasse [ZoomObject](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)