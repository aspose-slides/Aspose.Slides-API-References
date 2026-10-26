---
title: get_TargetSlide()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère l'objet diapositive auquel l'objet Slide Zoom fait référence. Lire ISlide.
type: docs
weight: 1
url: /fr/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() method

Récupère l'objet diapositive vers lequel l'objet Zoom [Slide](../../slide/) pointe. Lire [ISlide](../../islide/).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## Remarques

L'exemple suivant montre comment modifier la diapositive cible et crée une nouvelle image pour l'objet Zoom [Slide](../../slide/) :
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [IZoomFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)