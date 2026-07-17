---
title: InsertClone()
second_title: Aspose.Slides C++ API 参考
description: 创建指定形状的副本并将其插入到形状集合中的指定索引位置。
type: docs
weight: 560
url: /zh/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) 方法

创建指定形状的副本并将其插入到形状集合中的指定索引位置。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 要插入克隆形状的零基索引。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |
| x | **float** | 克隆形状框架的 x 坐标，单位为点。 |
| y | **float** | 克隆形状框架的 y 坐标，单位为点。 |
| width | **float** | 克隆形状框架的宽度，单位为点。 |
| height | **float** | 克隆形状框架的高度，单位为点。 |

### 返回值

新创建的 [IShape](../../ishape/)。

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) 方法

创建指定形状的副本并将其插入到形状集合中的指定索引位置。新形状保留 *sourceShape* 的宽度和高度。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 要插入克隆形状的零基索引。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |
| x | **float** | 克隆形状框架的 x 坐标，单位为点。 |
| y | **float** | 克隆形状框架的 y 坐标，单位为点。 |

### 返回值

新创建的 [IShape](../../ishape/)。

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) 方法

创建指定形状的副本并将其插入到形状集合中的指定索引位置。克隆形状保留原始形状的位置和大小。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 要插入克隆形状的零基索引。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |

### 返回值

新创建的 [IShape](../../ishape/)。

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)