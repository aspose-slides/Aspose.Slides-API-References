---
title: get_ReturnToParent()
second_title: Aspose.Slides für C++ API-Referenz
description: "Ermittelt das Navigationsverhalten in der Diashow. Nur lesbar bool. Standardwert: false"
type: docs
weight: 27
url: /de/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() Methode


Ermittelt das Navigationsverhalten in der Diashow. Nur lesbar **bool**. Standardwert: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Anmerkungen


Der wahre Wert der Eigenschaft legt das Rückkehr-zum-Eltern-Navigationsverhalten in der Diashow fest. 

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