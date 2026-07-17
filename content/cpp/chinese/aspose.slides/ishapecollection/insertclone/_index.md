---
title: InsertClone()
second_title: Aspose.Slides for C++ API 参考
description: 创建指定形状的副本并将其插入到形状集合中指定的索引位置。
type: docs
weight: 508
url: /zh/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) 方法

创建指定形状的副本并将其插入到形状集合中指定的索引位置。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 要插入克隆形状的零基索引。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的[IShape](../../ishape/)。 |
| x | **float** | 克隆形状帧的 x 坐标（以点为单位）。 |
| y | **float** | 克隆形状帧的 y 坐标（以点为单位）。 |
| width | **float** | 克隆形状帧的宽度（以点为单位）。 |
| height | **float** | 克隆形状帧的高度（以点为单位）。 |

### 返回值

新创建的[IShape](../../ishape/)。

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) 方法

创建指定形状的副本并将其插入到形状集合中指定的索引位置。新形状保留 *sourceShape* 的宽度和高度。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 要插入克隆形状的零基索引。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的[IShape](../../ishape/)。 |
| x | **float** | 克隆形状帧的 x 坐标（以点为单位）。 |
| y | **float** | 克隆形状帧的 y 坐标（以点为单位）。 |

### 返回值

新创建的[IShape](../../ishape/)。

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) 方法

创建指定形状的副本并将其插入到形状集合中指定的索引位置。克隆形状保留原始的位置信息和大小。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 要插入克隆形状的零基索引。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的[IShape](../../ishape/)。 |

### 返回值

新创建的[IShape](../../ishape/)。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)