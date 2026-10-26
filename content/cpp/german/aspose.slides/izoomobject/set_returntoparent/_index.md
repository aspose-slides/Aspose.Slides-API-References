---
title: set_ReturnToParent()
second_title: Aspose.Slides für C++ API-Referenz
description: "Legt das Navigationsverhalten in der Diashow fest. Schreiben bool. Standardwert: false"
type: docs
weight: 40
url: /de/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) Methode

Legt das Navigationsverhalten in der Diashow fest. Schreiben **bool**. Standardwert: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Anmerkungen

Der wahre Wert der Eigenschaft gibt das Rückkehr-zum-Eltern-Navigationsverhalten in der Diashow an.

Beispiel: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Siehe auch

* Klasse [IZoomObject](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)