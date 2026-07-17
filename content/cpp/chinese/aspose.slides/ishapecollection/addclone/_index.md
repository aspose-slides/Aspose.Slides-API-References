---
title: AddClone()
second_title: Aspose.Slides C++ API 参考
description: 创建指定形状的副本并将其添加到形状集合的末尾。
type: docs
weight: 495
url: /zh/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

创建指定形状的副本并将其添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的形状。 |
| x | **float** | 克隆形状框架的 x 坐标，单位为点。 |
| y | **float** | 克隆形状框架的 y 坐标，单位为点。 |
| width | **float** | 克隆形状框架的宽度，单位为点。 |
| height | **float** | 克隆形状框架的高度，单位为点。 |

### 返回值

新创建的 [IShape](../../ishape/)。

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method

创建指定形状的副本并将其添加到形状集合的末尾。新形状保留 *sourceShape* 的宽度和高度。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |
| x | **float** | 克隆形状框架的 x 坐标，单位为点。 |
| y | **float** | 克隆形状框架的 y 坐标，单位为点。 |

### 返回值

新创建的 [IShape](../../ishape/)。

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始形状的位置和尺寸。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |

### 返回值

新创建的 [IShape](../../ishape/)。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IShape](../../ishape/)
* 类 [IShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)