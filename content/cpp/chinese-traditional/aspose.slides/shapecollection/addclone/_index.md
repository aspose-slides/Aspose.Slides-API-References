---
title: AddClone()
second_title: Aspose.Slides C++ API 參考
description: 建立指定圖形的副本，並將其新增至圖形集合的末端。
type: docs
weight: 547
url: /zh-hant/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

建立指定圖形的副本，並將其新增至圖形集合的末端。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的圖形。 |
| x | **float** | 新圖形框架的 x 座標（以點為單位）。 |
| y | **float** | 新圖形框架的 y 座標（以點為單位）。 |
| width | **float** | 新圖形框架的寬度（以點為單位）。 |
| height | **float** | 新圖形框架的高度（以點為單位）。 |

### 返回值

新建立的 [IShape](../../ishape/)。

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method

建立指定圖形的副本，並將其新增至圖形集合的末端。新圖形保留 *sourceShape* 的寬度與高度。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的圖形。 |
| x | **float** | 新圖形框架的 x 座標（以點為單位）。 |
| y | **float** | 新圖形框架的 y 座標（以點為單位）。 |

### 返回值

新建立的 [IShape](../../ishape/)。

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

建立指定圖形的副本，並將其新增至圖形集合的末端。克隆的圖形保留原始圖形的位置與大小。

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |

### 返回值

新建立的 [IShape](../../ishape/)。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)