---
title: Insert()
second_title: Référence API Aspose.Slides pour C++
description: Insère la nouvelle opération dans une collection.
type: docs
weight: 79
url: /fr/aspose.slides/coloroperationcollection/insert/
---
## ColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) méthode


Insère la nouvelle opération dans une collection.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| position | **int32_t** | L'index à laquelle l'opération sera insérée. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Type d'opération. |
| parameter | **float** | Paramètre de l'opération. |

### Valeur de retour

Opération insérée.

## ColorOperationCollection::Insert(int32_t, ColorTransformOperation) méthode


Insère la nouvelle opération dans une collection.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| position | **int32_t** | L'index à laquelle l'opération sera insérée. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Type d'opération. |

### Valeur de retour

Opération insérée.

## Voir aussi

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorOperation](../../icoloroperation/)
* Class [ColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)