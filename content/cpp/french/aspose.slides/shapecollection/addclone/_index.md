---
title: AddClone()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes.
type: docs
weight: 547
url: /fr/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) méthode

Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | La forme à cloner. |
| x | **float** | La coordonnée x du cadre de la nouvelle forme\\u2019s, en points. |
| y | **float** | La coordonnée y du cadre de la nouvelle forme\\u2019s, en points. |
| width | **float** | La largeur du cadre de la nouvelle forme\\u2019s, en points. |
| height | **float** | La hauteur du cadre de la nouvelle forme\\u2019s, en points. |

### Valeur de retour

Le [IShape](../../ishape/) nouvellement créé.

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) méthode

Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de la *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | La forme à cloner. |
| x | **float** | La coordonnée x du cadre de la nouvelle forme\\u2019s, en points. |
| y | **float** | La coordonnée y du cadre de la nouvelle forme\\u2019s, en points. |

### Valeur de retour

Le [IShape](../../ishape/) nouvellement créé.

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) méthode

Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille de l’original.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Le [IShape](../../ishape/) à cloner. |

### Valeur de retour

Le [IShape](../../ishape/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [ShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)