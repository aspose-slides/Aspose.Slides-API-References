---
title: get_TransitionDuration()
second_title: Aspose.Slides pour C++ Référence API
description: "Obtient la durée de la transition entre Zoom et la diapositive. Lecture float. Valeur par défaut: 1.0f"
type: docs
weight: 105
url: /fr/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() méthode

Obtient la durée de la transition entre Zoom et la diapositive. Lecture **float**. Valeur par défaut : 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Remarques

Si non spécifié (TransitionDur = 0), il utilisera la transition de la diapositive de destination ainsi que les temporisations associées à cette transition.

L'exemple montre comment modifier la durée de la transition entre Zoom et diapositive :
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Voir aussi

* Classe [IZoomObject](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)