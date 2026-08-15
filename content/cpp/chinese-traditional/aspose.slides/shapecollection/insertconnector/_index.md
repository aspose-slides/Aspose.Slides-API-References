---
title: InsertConnector()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新的連接器形狀，並在指定的索引處插入至形狀集合，同時套用預設範本樣式。
type: docs
weight: 430
url: /zh-hant/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) 方法

建立一個新的連接器形狀，並在指定的索引處插入至形狀集合，同時套用預設範本樣式。

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入連接器形狀的零基索引。 |
| shapeType | [ShapeType](../../shapetype/) | 要插入的連接器形狀的[ShapeType](../../shapetype/)。 |
| x | **float** | 連接器框架的 x 座標（單位：點）。 |
| y | **float** | 連接器框架的 y 座標（單位：點）。 |
| width | **float** | 連接器框架的寬度（單位：點）。 |
| height | **float** | 連接器框架的高度（單位：點）。 |

### 返回值

新建立的 [IConnector](../../iconnector/)。

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) 方法

建立一個新的連接器形狀，並在指定的索引處插入至形狀集合，若需要可套用預設範本樣式。

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 插入連接器形狀的零基索引。 |
| shapeType | [ShapeType](../../shapetype/) | 要插入的連接器形狀的[ShapeType](../../shapetype/)。 |
| x | **float** | 連接器框架的 x 座標（單位：點）。 |
| y | **float** | 連接器框架的 y 座標（單位：點）。 |
| width | **float** | 連接器框架的寬度（單位：點）。 |
| height | **float** | 連接器框架的高度（單位：點）。 |
| createFromTemplate | **bool** | True 以套用預設範本樣式（非空名稱、簡單樣式）；false 以使用預設屬性值建立連接器。 |

### 返回值

新建立的 [IConnector](../../iconnector/)。

## 另請參閱

* 列舉 [ShapeType](../../shapetype/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IConnector](../../iconnector/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)