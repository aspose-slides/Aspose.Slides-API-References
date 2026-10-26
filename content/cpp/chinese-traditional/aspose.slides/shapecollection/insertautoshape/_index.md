---
title: InsertAutoShape()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個新的自動圖形，並將其插入至指定索引的形狀集合中，套用預設的範本格式化。
type: docs
weight: 378
url: /zh-hant/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) 方法

建立一個新的自動圖形，並將其插入至指定索引的形狀集合中，套用預設的範本格式化。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 在此零基索引處插入新的自動圖形。 |
| shapeType | [ShapeType](../../shapetype/) | 要插入之自動圖形的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形狀框架的 x 座標，單位為點。 |
| y | **float** | 形狀框架的 y 座標，單位為點。 |
| width | **float** | 形狀框架的寬度，單位為點。 |
| height | **float** | 形狀框架的高度，單位為點。 |

### 回傳值

新建立的 [IAutoShape](../../iautoshape/)。

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) 方法

建立一個新的自動圖形，並將其插入至指定索引的形狀集合中，可選擇性地以預設範本樣式進行初始化。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 在此零基索引處插入自動圖形。 |
| shapeType | [ShapeType](../../shapetype/) | 要插入之自動圖形的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形狀框架的 x 座標，單位為點。 |
| y | **float** | 形狀框架的 y 座標，單位為點。 |
| width | **float** | 形狀框架的寬度，單位為點。 |
| height | **float** | 形狀框架的高度，單位為點。 |
| createFromTemplate | **bool** | 若為 true，則套用預設的範本樣式（包含非空名稱、簡易樣式及置中對齊的文字）；若為 false，則以所有屬性預設值建立圖形。 |

### 回傳值

新建立的 [IAutoShape](../../iautoshape/)。

## 另請參閱

* 列舉 [ShapeType](../../shapetype/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)