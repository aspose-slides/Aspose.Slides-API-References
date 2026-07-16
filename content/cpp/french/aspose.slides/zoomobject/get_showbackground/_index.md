---
title: get_ShowBackground()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Obtient la valeur qui indique si le Zoom utilisera l'arrière-plan de la diapositive de destination. Lecture bool. Valeur par défaut : true"
type: docs
weight: 53
url: /fr/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() méthode


Obtient la valeur qui indique si le Zoom utilisera l'arrière-plan de la diapositive de destination. Lecture **bool**. Valeur par défaut : true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## Remarques


l'exemple montre la suppression de l'arrière-plan d'une image d'un objet Zoom :
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Voir aussi

* Classe [ZoomObject](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)