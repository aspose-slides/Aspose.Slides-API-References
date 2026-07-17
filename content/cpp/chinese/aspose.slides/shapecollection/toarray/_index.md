---
title: ToArray()
second_title: Aspose.Slides for C++ API 参考
description: 创建并返回包含所有形状的数组。
type: docs
weight: 326
url: /zh/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() 方法

创建并返回包含所有形状的数组。

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### 返回值

一个包含 [IShape](../../ishape/) 对象的数组。

## ShapeCollection::ToArray(int32_t, int32_t) 方法

创建并返回包含指定范围内所有形状的数组。

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | **int32_t** | 要返回的第一个形状的索引。 |
| count | **int32_t** | 要返回的形状数量。 |

### 返回值

一个包含 [IShape](../../ishape/) 对象的数组。

## 另请参阅

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IShape](../../ishape/)
* 类 [ShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)