---
title: AddClone()
second_title: Aspose.Slides for C++ API 参考
description: 创建指定形状的副本并将其添加到形状集合的末尾。
type: docs
weight: 547
url: /zh/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

创建指定形状的副本并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的形状。 |
| x | **float** | 新形状框的 x 坐标，单位为点。 |
| y | **float** | 新形状框的 y 坐标，单位为点。 |
| width | **float** | 新形状框的宽度，单位为点。 |
| height | **float** | 新形状框的高度，单位为点。 |

### 返回值

新创建的 [IShape](../../ishape/)。

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method

创建指定形状的副本并将其添加到形状集合的末尾。新形状保留 *sourceShape* 的宽度和高度。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的形状。 |
| x | **float** | 新形状框的 x 坐标，单位为点。 |
| y | **float** | 新形状框的 y 坐标，单位为点。 |

### 返回值

新创建的 [IShape](../../ishape/)。

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置信息和大小。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |

### 返回值

新创建的 [IShape](../../ishape/)。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)