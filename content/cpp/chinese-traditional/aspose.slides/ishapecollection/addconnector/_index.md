---
title: AddConnector()
second_title: Aspose.Slides for C++ API 參考
description: 建立具有預設範本樣式的新連接器形狀，並將其新增至形狀集合的末端。
type: docs
weight: 378
url: /zh-hant/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) 方法

建立一個具有預設範本樣式的新連接器形狀，並將其新增至形狀集合的末端。

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要新增之連接器形狀的 [ShapeType](../../shapetype/)。 |
| x | **float** | 連接器框架的 X 座標（單位：點）。 |
| y | **float** | 連接器框架的 Y 座標（單位：點）。 |
| width | **float** | 連接器框架的寬度（單位：點）。 |
| height | **float** | 連接器框架的高度（單位：點）。 |

### 回傳值

新建立的 [IConnector](../../iconnector/)。

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) 方法

建立一個新連接器形狀，並將其新增至形狀集合的末端，亦可選擇套用預設範本樣式。

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要建立之連接器形狀的 [ShapeType](../../shapetype/)。 |
| x | **float** | 連接器框架的 X 座標（單位：點）。 |
| y | **float** | 連接器框架的 Y 座標（單位：點）。 |
| width | **float** | 連接器框架的寬度（單位：點）。 |
| height | **float** | 連接器框架的高度（單位：點）。 |
| createFromTemplate | **bool** | True 代表套用預設範本樣式（非空名稱、簡單樣式）；false 代表以預設屬性值建立連接器。 |

### 回傳值

新建立的 [IConnector](../../iconnector/)。

## 另請參閱

* 列舉 [ShapeType](../../shapetype/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IConnector](../../iconnector/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)