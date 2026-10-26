---
title: get_ReturnToParent()
second_title: Aspose.Slides für C++ API Referenz
description: "Ermittelt das Navigationsverhalten in der Diashow. Lese bool. Standardwert: false"
type: docs
weight: 27
url: /de/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() Methode


Ermittelt das Navigationsverhalten in der Diashow. Lesen **bool**. Standardwert: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Anmerkungen


Der wahre Wert der Eigenschaft gibt das Rückkehr-zum-Eltern-Navigationsverhalten in der Diashow an. 

Beispiel: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Siehe auch

* Klasse [ZoomObject](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)