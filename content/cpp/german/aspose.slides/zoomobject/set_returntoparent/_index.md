---
title: set_ReturnToParent()
second_title: Aspose.Slides für C++ API Referenz
description: "Legt das Navigationsverhalten in der Diashow fest. Schreiben bool. Standardwert: false"
type: docs
weight: 40
url: /de/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) Methode


Legt das Navigationsverhalten in der Diashow fest. Schreiben **bool**. Standardwert: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Hinweise


Der wahre Wert der Eigenschaft gibt das Rückkehr-zu-Eltern-Navigationsverhalten in der Diashow an. 

Beispiel: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Siehe auch

* Klasse [ZoomObject](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)