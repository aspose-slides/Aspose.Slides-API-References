---
title: InsertAutoShape()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新的自動圖形並將其插入至指定索引的圖形集合，套用預設範本格式。
type: docs
weight: 339
url: /zh-hant/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) 方法

Creates a new auto shape and inserts it into the shape collection at the specified index, applying default template formatting.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要在其中插入新自動圖形的零基索引。 |
| shapeType | [ShapeType](../../shapetype/) | 要插入的自動圖形的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形狀框架的 x 座標（以點為單位）。 |
| y | **float** | 形狀框架的 y 座標（以點為單位）。 |
| width | **float** | 形狀框架的寬度（以點為單位）。 |
| height | **float** | 形狀框架的高度（以點為單位）。 |

### 返回值

新建立的 [IAutoShape](../../iautoshape/)。

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) 方法

Creates a new auto shape and inserts it into the shape collection at the specified index, optionally initializing it with default template styling.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要在其中插入自動圖形的零基索引。 |
| shapeType | [ShapeType](../../shapetype/) | 要插入的自動圖形的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形狀框架的 x 座標（以點為單位）。 |
| y | **float** | 形狀框架的 y 座標（以點為單位）。 |
| width | **float** | 形狀框架的寬度（以點為單位）。 |
| height | **float** | 形狀框架的高度（以點為單位）。 |
| createFromTemplate | **bool** | True 表示套用預設範本樣式（包括非空名稱、簡單樣式和置中文字）；false 表示以所有屬性預設值建立圖形。 |

### 返回值

新建立的 [IAutoShape](../../iautoshape/)。

## 另請參閱

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)