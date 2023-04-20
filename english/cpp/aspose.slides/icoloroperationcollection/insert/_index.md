---
title: Insert()
second_title: Aspose.Slides for C++ API Reference
description: Inserts the new operation to a collection.
type: docs
weight: 40
url: /cpp/aspose.slides/icoloroperationcollection/insert/
---
## IColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) method


Inserts the new operation to a collection.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| position | **int32_t** | The index at which the operation will be inserted. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Operation type. |
| parameter | **float** | Operation's parameter. |

### Return Value

Inserted operation.

## IColorOperationCollection::Insert(int32_t, ColorTransformOperation) method


Inserts the new operation to a collection.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| position | **int32_t** | The index at which the operation will be inserted. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Operation type. |

### Return Value

Inserted operation.

## See Also

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorOperation](../../icoloroperation/)
* Class [IColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)