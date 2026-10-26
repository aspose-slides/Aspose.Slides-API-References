---
title: get_TargetSlide()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt het dia-object op waarnaar het Slide Zoom object linkt. Lees ISlide.
type: docs
weight: 1
url: /nl/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() methode

Haalt het dia-object op waarnaar het [Slide](../../slide/) Zoom object linkt. Lees [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Opmerkingen

Het volgende voorbeeld toont het wijzigen van de doel-dia en maakt een nieuw beeld voor het [Slide](../../slide/) Zoom object: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [ZoomFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)