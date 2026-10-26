---
title: InsertClone()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié.
type: docs
weight: 560
url: /fr/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) method

Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’index basé sur zéro où insérer la forme clonée. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Le [IShape](../../ishape/) à cloner. |
| x | **float** | La coordonnée x du cadre de la forme clonée, en points. |
| y | **float** | La coordonnée y du cadre de la forme clonée, en points. |
| width | **float** | La largeur du cadre de la forme clonée, en points. |
| height | **float** | La hauteur du cadre de la forme clonée, en points. |

### Return Value

Le [IShape](../../ishape/) nouvellement créé.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) method

Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur du *sourceShape*.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’index basé sur zéro où insérer la forme clonée. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Le [IShape](../../ishape/) à cloner. |
| x | **float** | La coordonnée x du cadre de la forme clonée, en points. |
| y | **float** | La coordonnée y du cadre de la forme clonée, en points. |

### Return Value

Le [IShape](../../ishape/) nouvellement créé.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) method

Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille originales.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’index basé sur zéro où insérer la forme clonée. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Le [IShape](../../ishape/) à cloner. |

### Return Value

Le [IShape](../../ishape/) nouvellement créé.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)