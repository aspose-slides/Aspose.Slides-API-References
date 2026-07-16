---
title: set_ShowBackground()
second_title: Référence API Aspose.Slides pour C++ 
description: "Définit la valeur qui indique si le Zoom utilisera l'arrière-plan de la diapositive de destination. Écrire bool. Valeur par défaut: true"
type: docs
weight: 66
url: /fr/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) méthode

Définit la valeur qui indique si le Zoom utilisera l'arrière-plan de la diapositive de destination. Écrire **bool**. Valeur par défaut : true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
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

* Classe [ZoomObject](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)