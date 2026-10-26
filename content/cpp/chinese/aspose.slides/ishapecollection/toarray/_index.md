---
title: ToArray()
second_title: Aspose.Slides for C++ API 参考
description: 创建并返回一个包含所有形状的数组。
type: docs
weight: 287
url: /zh/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() 方法

创建并返回一个包含所有形状的数组。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```

### 返回值

一个 [IShape](../../ishape/) 对象数组。

## IShapeCollection::ToArray(int32_t, int32_t) 方法

创建并返回一个包含指定范围内所有形状的数组。

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | **int32_t** | 要返回的第一个形状的索引。 |
| count | **int32_t** | 要返回的形状数量。 |

### 返回值

一个 [IShape](../../ishape/) 对象数组。

## 另请参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IShape](../../ishape/)
* 类 [IShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)