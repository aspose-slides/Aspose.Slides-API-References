---
title: Insert()
second_title: Aspose.Slides C++ API 参考
description: 将新操作插入到集合中。
type: docs
weight: 79
url: /zh/aspose.slides/coloroperationcollection/insert/
---
## ColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) 方法

将新操作插入到集合中。

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| position | **int32_t** | 要插入操作的索引位置。 |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 操作类型。 |
| parameter | **float** | 操作的参数。 |

### 返回值

已插入的操作。

## ColorOperationCollection::Insert(int32_t, ColorTransformOperation) 方法

将新操作插入到集合中。

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| position | **int32_t** | 要插入操作的索引位置。 |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 操作类型。 |

### 返回值

已插入的操作。

## 另请参阅

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorOperation](../../icoloroperation/)
* Class [ColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)