---
title: get_TargetSlide()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient l'objet diapositive auquel l'objet Slide Zoom fait référence. Lire ISlide.
type: docs
weight: 1
url: /fr/aspose.slides/zoomframe/get_targetslide/
---
## Méthode ZoomFrame::get_TargetSlide()

Obtient l'objet diapositive auquel l'objet [Slide](../../slide/) Zoom fait référence. Lire [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Remarques

L'exemple suivant montre comment changer la diapositive cible et crée une nouvelle image pour l'objet [Slide](../../slide/) Zoom :

```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)