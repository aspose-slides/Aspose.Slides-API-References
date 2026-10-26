---
title: get_TransitionDuration()
second_title: Référence API Aspose.Slides pour C++
description: "Obtient la durée de la transition entre Zoom et la diapo. Lecture float. Valeur par défaut: 1.0f"
type: docs
weight: 105
url: /fr/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() méthode


Obtient la durée de la transition entre Zoom et la diapo. Lecture **float**. Valeur par défaut : 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## Remarques


Si non spécifié (TransitionDur = 0), il utilisera la transition de la diapo de destination ainsi que les temporisations associées à cette transition. 

L'exemple montre la modification de la durée de la transition entre Zoom et la diapo : 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Voir aussi

* Classe [ZoomObject](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)