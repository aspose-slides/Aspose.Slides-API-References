---
title: AddControl()
second_title: Référence API Aspose.Slides pour C++
description: Crée et ajoute un nouveau contrôle à la collection.
type: docs
weight: 40
url: /fr/aspose.slides/controlcollection/addcontrol/
---
## ControlCollection::AddControl(ControlType, float, float, float, float) méthode

Crée et ajoute un nouveau contrôle à la collection.

```cpp
System::SharedPtr<IControl> Aspose::Slides::ControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | Type d'un contrôle à ajouter. |
| x | **float** | La coordonnée X pour le côté gauche du cadre de la forme. |
| y | **float** | La coordonnée Y pour le côté supérieur du cadre de la forme. |
| width | **float** | La largeur du cadre de la forme. |
| height | **float** | La hauteur du cadre de la forme. |

### Valeur de retour

Contrôle créé.

## Voir aussi

* Enum [ControlType](../../controltype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IControl](../../icontrol/)
* Class [ControlCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)