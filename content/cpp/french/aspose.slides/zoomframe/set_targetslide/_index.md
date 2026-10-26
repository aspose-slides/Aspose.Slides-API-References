---
title: set_TargetSlide()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit l'objet diapositive auquel l'objet Slide Zoom fait référence. Écrivez ISlide.
type: docs
weight: 14
url: /fr/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) méthode


Définit l’objet diapositive auquel l’objet Zoom [Slide](../../slide/) fait référence. Écrivez [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
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
* Classe [ZoomFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)