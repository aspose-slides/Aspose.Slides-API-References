---
title: Insert()
second_title: Aspose.Slides för C++ API-referens
description: Infogar den nya operationen i en samling.
type: docs
weight: 79
url: /sv/aspose.slides/coloroperationcollection/insert/
---
## ColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) metod

Infogar den nya operationen i en samling.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | **int32_t** | Indexet där operationen ska infogas. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Operationstyp. |
| parameter | **float** | Operationens parameter. |

### Returvärde

Infogad operation.

## ColorOperationCollection::Insert(int32_t, ColorTransformOperation) metod

Infogar den nya operationen i en samling.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | **int32_t** | Indexet där operationen ska infogas. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Operationstyp. |

### Returvärde

Infogad operation.

## Se även

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IColorOperation](../../icoloroperation/)
* Klass [ColorOperationCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)