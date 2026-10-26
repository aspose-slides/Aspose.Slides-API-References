---
title: get_TargetSlide()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft das Folienobjekt ab, auf das das Slide Zoom-Objekt verweist. Lesen Sie ISlide.
type: docs
weight: 1
url: /de/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() Methode


Ruft das Folienobjekt ab, auf das das [Slide](../../slide/) Zoom-Objekt verweist. Lesen Sie [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Hinweise


Das nächste Beispiel zeigt, wie die Zielfolie geändert wird und ein neues Bild für das [Slide](../../slide/) Zoom-Objekt erstellt wird: 
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