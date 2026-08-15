---
title: InsertClone()
second_title: Aspose.Slides for C++ API 參考
description: 建立指定圖形的副本，並將其插入到圖形集合中指定的索引位置。
type: docs
weight: 560
url: /zh-hant/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) 方法

建立指定圖形的副本，並將其插入到圖形集合中指定的索引位置。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要插入克隆圖形的零基索引。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |
| x | **float** | 克隆圖形框架的 x 坐標（單位為點）。 |
| y | **float** | 克隆圖形框架的 y 坐標（單位為點）。 |
| width | **float** | 克隆圖形框架的寬度（單位為點）。 |
| height | **float** | 克隆圖形框架的高度（單位為點）。 |

### 返回值

新建立的 [IShape](../../ishape/)。

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) 方法

建立指定圖形的副本，並將其插入到圖形集合中指定的索引位置。新圖形保留 *sourceShape* 的寬度和高度。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要插入克隆圖形的零基索引。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |
| x | **float** | 克隆圖形框架的 x 坐標（單位為點）。 |
| y | **float** | 克隆圖形框架的 y 坐標（單位為點）。 |

### 返回值

新建立的 [IShape](../../ishape/)。

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) 方法

建立指定圖形的副本，並將其插入到圖形集合中指定的索引位置。此克隆圖形保留原始圖形的位置與大小。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要插入克隆圖形的零基索引。 |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |

### 返回值

新建立的 [IShape](../../ishape/)。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IShape](../../ishape/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)