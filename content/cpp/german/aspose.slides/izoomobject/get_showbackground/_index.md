---
title: get_ShowBackground()
second_title: Aspose.Slides für C++ API-Referenz
description: "Liefert den Wert, der angibt, ob der Zoom den Hintergrund der Zielfolie verwendet. Lesen bool. Standardwert: true"
type: docs
weight: 53
url: /de/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() Methode

Ruft den Wert ab, der angibt, ob der Zoom den Hintergrund der Zielfolie verwendet. Lesen **bool**. Standardwert: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## Anmerkungen

Das Beispiel zeigt das Entfernen des Hintergrunds eines Bildes eines Zoom-Objekts:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Siehe auch

* Klasse [IZoomObject](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)