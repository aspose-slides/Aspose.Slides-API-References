---
title: Insert()
second_title: Aspose.Slides for C++ API 参考
description: 将新操作插入到集合中。
type: docs
weight: 40
url: /zh/aspose.slides/icoloroperationcollection/insert/
---
## IColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) 方法

将新操作插入到集合中。

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | **int32_t** | 要插入操作的索引。 |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 操作类型。 |
| parameter | **float** | 操作的参数。 |

### 返回值

已插入的操作。

## IColorOperationCollection::Insert(int32_t, ColorTransformOperation) 方法

将新操作插入到集合中。

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | **int32_t** | 要插入操作的索引。 |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 操作类型。 |

### 返回值

已插入的操作。

## 另请参阅

* 枚举 [ColorTransformOperation](../../colortransformoperation/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IColorOperation](../../icoloroperation/)
* 类 [IColorOperationCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)