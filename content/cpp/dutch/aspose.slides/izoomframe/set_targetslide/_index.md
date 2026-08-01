---
title: set_TargetSlide()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt het slide-object in waarnaar het Slide Zoom-object linkt. Schrijf ISlide.
type: docs
weight: 14
url: /nl/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) method


Stelt het slide-object in waarnaar het [Slide](../../slide/) Zoom-object linkt. Schrijf [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## Opmerkingen


Het volgende voorbeeld toont het wijzigen van de doel-slide en maakt een nieuwe afbeelding voor het [Slide](../../slide/) Zoom-object: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [IZoomFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)