---
title: AddAutoShape()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個具有預設格式的新自動圖形，並將其加入圖形集合的末端。
type: docs
weight: 352
url: /zh-hant/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) 方法

建立一個具有預設格式的新自動圖形，並將其加入圖形集合的末尾。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要加入的自動圖形的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形狀框架的 x 座標，以點為單位。 |
| y | **float** | 形狀框架的 y 座標，以點為單位。 |
| width | **float** | 形狀框架的寬度，以點為單位。 |
| height | **float** | 形狀框架的高度，以點為單位。 |

### 回傳值

新建立的 [IAutoShape](../../iautoshape/)。

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) 方法

建立一個新自動圖形，將其加入圖形集合的末尾，並可選擇以預設模板格式初始化它。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要加入的自動圖形的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形狀框架的 x 座標，以點為單位。 |
| y | **float** | 形狀框架的 y 座標，以點為單位。 |
| width | **float** | 形狀框架的寬度，以點為單位。 |
| height | **float** | 形狀框架的高度，以點為單位。 |
| createFromTemplate | **bool** | true 表示對新圖形套用預設模板樣式（簡單樣式、文字置中且名稱不為空）；false 表示以所有屬性預設值建立圖形。 |

### 回傳值

新建立的 [IAutoShape](../../iautoshape/)。

## 另見

* 列舉 [ShapeType](../../shapetype/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)