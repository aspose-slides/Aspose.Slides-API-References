---
title: InsertClone()
second_title: Référence API Aspose.Slides pour C++
description: Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué.
type: docs
weight: 508
url: /fr/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) méthode


Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’index basé sur zéro où insérer la forme clonée. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Le [IShape](../../ishape/) à cloner. |
| x | **float** | La coordonnée x du cadre de la forme clonée, en points. |
| y | **float** | La coordonnée y du cadre de la forme clonée, en points. |
| width | **float** | La largeur du cadre de la forme clonée, en points. |
| height | **float** | La hauteur du cadre de la forme clonée, en points. |

### Valeur de retour

Le [IShape](../../ishape/) nouvellement créé.

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) méthode


Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La nouvelle forme conserve la largeur et la hauteur de la *sourceShape*.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’index basé sur zéro où insérer la forme clonée. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Le [IShape](../../ishape/) à cloner. |
| x | **float** | La coordonnée x du cadre de la forme clonée, en points. |
| y | **float** | La coordonnée y du cadre de la forme clonée, en points. |

### Valeur de retour

Le [IShape](../../ishape/) nouvellement créé.

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) méthode


Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La forme clonée conserve la position et la taille originales.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’index basé sur zéro où insérer la forme clonée. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Le [IShape](../../ishape/) à cloner. |

### Valeur de retour

Le [IShape](../../ishape/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [IShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)