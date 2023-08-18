---
title: Insert()
second_title: Aspose.Slides for C++ API Reference
description: Inserts the new operation to a collection.
type: docs
weight: 79
url: /aspose.slides/coloroperationcollection/insert/
---
## ColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) method


Inserts the new operation to a collection.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| position | **int32_t** | The index at which the operation will be inserted. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Operation type. |
| parameter | **float** | Operation's parameter. |

### Return Value

Inserted operation.

## ColorOperationCollection::Insert(int32_t, ColorTransformOperation) method


Inserts the new operation to a collection.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation) override
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
* Class [ColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)