---
title: get_ShowBackground()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Obtient la valeur qui indique si le Zoom utilisera l'arrière-plan de la diapositive de destination. Lire bool. Valeur par défaut : true"
type: docs
weight: 53
url: /fr/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() method


Obtient la valeur qui indique si le Zoom utilisera l'arrière-plan de la diapositive de destination. Lire **bool**. Valeur par défaut : true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## Remarques


L'exemple montre la suppression de l'arrière-plan d'une image d'un objet Zoom : 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Voir aussi

* Classe [IZoomObject](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)