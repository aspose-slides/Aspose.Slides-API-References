---
title: set_ShowBackground()
second_title: Aspose.Slides für C++ API Referenz
description: "Legt den Wert fest, der angibt, ob das Zoom den Hintergrund der Zielfolie verwendet. Schreiben bool. Standardwert: true"
type: docs
weight: 66
url: /de/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) Methode


Legt den Wert fest, der angibt, ob das Zoom den Hintergrund der Zielfolie verwendet. Schreiben **bool**. Standardwert: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
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