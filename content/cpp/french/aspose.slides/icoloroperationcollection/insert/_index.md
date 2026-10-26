---
title: Insert()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insère la nouvelle opération dans une collection.
type: docs
weight: 40
url: /fr/aspose.slides/icoloroperationcollection/insert/
---
## IColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) méthode


Insère la nouvelle opération dans une collection.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| position | **int32_t** | L’index auquel l’opération sera insérée. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Type d’opération. |
| parameter | **float** | Paramètre de l’opération. |

### Valeur de retour

Opération insérée.

## IColorOperationCollection::Insert(int32_t, ColorTransformOperation) méthode


Insère la nouvelle opération dans une collection.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| position | **int32_t** | L’index auquel l’opération sera insérée. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Type d’opération. |

### Valeur de retour

Opération insérée.

## Voir aussi

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorOperation](../../icoloroperation/)
* Class [IColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)