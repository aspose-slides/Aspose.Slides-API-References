---
title: get_ShowBackground()
second_title: Aspose.Slides für C++ API-Referenz
description: "Ermittelt den Wert, der angibt, ob der Zoom den Hintergrund der Zielfolie verwendet. Lesen bool. Standardwert: true"
type: docs
weight: 53
url: /de/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() Methode


Liefert den Wert, der angibt, ob der Zoom den Hintergrund der Zielfolie verwendet. Lesen **bool**. Standardwert: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## Hinweise


Das Beispiel demonstriert das Entfernen des Hintergrunds eines Bildes eines Zoom-Objekts: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Siehe auch

* Klasse [ZoomObject](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)