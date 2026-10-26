---
title: get_TransitionDuration()
second_title: Aspose.Slides für C++ API-Referenz
description: "Ermittelt die Dauer der Übergabe zwischen Zoom und Folie. Lese float. Standardwert: 1.0f"
type: docs
weight: 105
url: /de/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() Methode

Ermittelt die Dauer der Übergabe zwischen Zoom und Folie. Lese **float**. Standardwert: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## Anmerkungen

Wenn nicht angegeben (TransitionDur = 0), wird die Zielfolien-Übergabe und die damit verbundenen Zeitangaben verwendet.

Das Beispiel demonstriert das Ändern der Dauer der Übergabe zwischen Zoom und Folie:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Siehe auch

* Klasse [ZoomObject](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)