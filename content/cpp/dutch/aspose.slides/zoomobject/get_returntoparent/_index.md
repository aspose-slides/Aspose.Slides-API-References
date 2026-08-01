---
title: get_ReturnToParent()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt het navigatiegedrag op in de diavoorstelling. Leest bool. Standaardwaarde: false"
type: docs
weight: 27
url: /nl/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() methode


Haalt het navigatiegedrag op in de diavoorstelling. Leest **bool**. Standaardwaarde: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Opmerkingen


De ware waarde van de eigenschap specificeert het terugkeren naar het bovenliggende navigatiegedrag in de diavoorstelling. 

Voorbeeld: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Zie ook

* Klasse [ZoomObject](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)