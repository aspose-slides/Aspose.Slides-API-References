---
title: AddClone()
second_title: Aspose.Slides for C++ API 參考
description: 建立指定形狀的副本，並將其新增至形狀集合的末端。
type: docs
weight: 495
url: /zh-hant/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) 方法

建立指定形狀的副本，並將其新增至形狀集合的末端。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的形狀。 |
| x | **float** | 克隆形狀\\u2019的框架的 x 座標（以點為單位）。 |
| y | **float** | 克隆形狀\\u2019的框架的 y 座標（以點為單位）。 |
| width | **float** | 克隆形狀\\u2019的框架的寬度（以點為單位）。 |
| height | **float** | 克殖形狀\\u2019的框架的高度（以點為單位）。 |

### 返回值

新建立的 [IShape](../../ishape/)。

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) 方法

建立指定形狀的副本，並將其新增至形狀集合的末端。新形狀保留 *sourceShape* 的寬度與高度。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |
| x | **float** | 克隆形狀\\u2019的框架的 x 座標（以點為單位）。 |
| y | **float** | 克隆形狀\\u2019的框架的 y 座標（以點為單位）。 |

### 返回值

新建立的 [IShape](../../ishape/)。

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) 方法

建立指定形狀的副本，並將其新增至形狀集合的末端。克隆的形狀保留原始形狀的位置與大小。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要克隆的 [IShape](../../ishape/)。 |

### 返回值

新建立的 [IShape](../../ishape/)。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IShape](../../ishape/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)