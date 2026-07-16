---
title: get_ReturnToParent()
second_title: Référence API Aspose.Slides pour C++
description: "Obtient le comportement de navigation dans le diaporama. Lecture bool. Valeur par défaut: false"
type: docs
weight: 27
url: /fr/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() méthode

Obtient le comportement de navigation dans le diaporama. Lecture **bool**. Valeur par défaut: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Remarques

La valeur vraie de la propriété indique le comportement de navigation retour au parent dans le diaporama. 

Exemple:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Voir aussi

* Classe [IZoomObject](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)