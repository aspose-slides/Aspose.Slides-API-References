---
title: set_TargetSlide()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt das Folienobjekt fest, auf das das Slide Zoom-Objekt verlinkt. Schreiben Sie ISlide.
type: docs
weight: 14
url: /de/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) method

Legt das Folienobjekt fest, auf das das [Slide](../../slide/) Zoom-Objekt verlinkt. Schreiben Sie [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## Hinweise

Das nächste Beispiel zeigt, wie die Zielfolie geändert wird und erzeugt ein neues Bild für das [Slide](../../slide/) Zoom-Objekt:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [ZoomFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)