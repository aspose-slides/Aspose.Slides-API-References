---
title: Insert()
second_title: Aspose.Slides för C++ API-referens
description: Infogar den nya operationen i en samling.
type: docs
weight: 40
url: /sv/aspose.slides/icoloroperationcollection/insert/
---
## IColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) metod


Infogar den nya operationen i en samling.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | **int32_t** | Indexet där operationen kommer att infogas. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Operationstyp. |
| parameter | **float** | Operationsparameter. |

### Returvärde

Infogad operation.

## IColorOperationCollection::Insert(int32_t, ColorTransformOperation) metod


Infogar den nya operationen i en samling.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | **int32_t** | Indexet där operationen kommer att infogas. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Operationstyp. |

### Returvärde

Infogad operation.

## Se även

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorOperation](../../icoloroperation/)
* Class [IColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)