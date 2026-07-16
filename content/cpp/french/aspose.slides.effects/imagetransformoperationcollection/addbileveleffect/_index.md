---
title: AddBiLevelEffect()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute le nouvel effet Bi-Level (noir/blanc) à la fin d'une collection.
type: docs
weight: 144
url: /fr/aspose.slides.effects/imagetransformoperationcollection/addbileveleffect/
---
## ImageTransformOperationCollection::AddBiLevelEffect(float) méthode


Ajoute le nouvel effet Bi-Level (noir/blanc) à la fin d’une collection.

```cpp
System::SharedPtr<IBiLevel> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBiLevelEffect(float threshold) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | **float** | le seuil de luminance pour l’effet Bi-Level. Les valeurs supérieures ou égales au seuil sont définies sur blanc. Les valeurs inférieures au seuil sont définies sur noir. |

### Valeur de retour

Indice du nouvel effet d’image dans une collection.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBiLevel](../../ibilevel/)
* Class [ImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)