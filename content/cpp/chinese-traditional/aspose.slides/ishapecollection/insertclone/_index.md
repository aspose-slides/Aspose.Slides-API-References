---
title: InsertClone()
second_title: Aspose.Slides for C++ API 參考
description: 建立指定形狀的副本，並將其插入至形狀集合中的指定索引位置。
type: docs
weight: 508
url: /zh-hant/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) 方法

建立指定形狀的副本，並將其插入至形狀集合中的指定索引位置。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入克隆形狀的零基索引。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |
| x | **float** | 克隆形狀框架的 x 座標，以點為單位。 |
| y | **float** | 克隆形狀框架的 y 座標，以點為單位。 |
| width | **float** | 克隆形狀框架的寬度，以點為單位。 |
| height | **float** | 克隆形狀框架的高度，以點為單位。 |

### 返回值

新建立的 [IShape](../../ishape/)。

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) 方法

建立指定形狀的副本，並將其插入至形狀集合中的指定索引位置。新形狀保留 *sourceShape* 的寬度和高度。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入克隆形狀的零基索引。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |
| x | **float** | 克隆形狀框架的 x 座標，以點為單位。 |
| y | **float** | 克隆形狀框架的 y 座標，以點為單位。 |

### 返回值

新建立的 [IShape](../../ishape/)。

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) 方法

建立指定形狀的副本，並將其插入至形狀集合中的指定索引位置。克隆形狀保留原始形狀的位置和大小。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入克隆形狀的零基索引。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |

### 返回值

新建立的 [IShape](../../ishape/)。

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IShape](../../ishape/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)