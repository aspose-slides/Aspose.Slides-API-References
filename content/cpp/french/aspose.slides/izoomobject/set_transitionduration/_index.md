---
title: set_TransitionDuration()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Définit la durée de la transition entre le Zoom et la diapositive. Écrire float. Valeur par défaut : 1.0f"
type: docs
weight: 118
url: /fr/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) méthode

Définit la durée de la transition entre le Zoom et la diapositive. Écrire **float**. Valeur par défaut : 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## Remarques

Si non spécifié (TransitionDur = 0), il utilisera la transition de la diapositive de destination ainsi que les durées associées à cette transition.

l'exemple montre comment modifier la durée de la transition entre le Zoom et la diapositive : 
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