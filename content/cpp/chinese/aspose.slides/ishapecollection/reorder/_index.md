---
title: Reorder()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的形状移动到形状集合中的新位置。
type: docs
weight: 300
url: /zh/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) 方法

将指定的形状移动到形状集合中的新位置。

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 零基目标索引，形状将被放置在此位置。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要在集合中移动的[IShape](../../ishape/)。 |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) 方法

将指定的形状在形状集合中移动，从给定索引开始放置。

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 零基目标索引，第一指定的形状将被放置在此位置；随后形状按提供的顺序依次放置。 |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | 一个或多个[IShape](../../ishape/)实例，用于在集合中移动。 |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [IShape](../../ishape/)
* 类 [IShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)