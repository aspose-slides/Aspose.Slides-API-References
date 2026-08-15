---
title: InsertConnector()
second_title: Aspose.Slides C++ API 參考
description: 建立一個新的連接線形狀，並在指定的索引處將其插入到形狀集合中，套用預設的範本樣式。
type: docs
weight: 391
url: /zh-hant/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) 方法

建立一個新的連接線形狀，並在指定的索引處將其插入到形狀集合中，套用預設的範本樣式。

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要插入連接線形狀的零基索引。 |
| shapeType | [ShapeType](../../shapetype/) | 要插入的連接線形狀的 [ShapeType](../../shapetype/)。 |
| x | **float** | 連接線框架的 x 座標，單位為點。 |
| y | **float** | 連接線框架的 y 座標，單位為點。 |
| width | **float** | 連接線框架的寬度，單位為點。 |
| height | **float** | 連接線框架的高度，單位為點。 |

### 回傳值

新建立的 [IConnector](../../iconnector/)。

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) 方法

建立一個新的連接線形狀，並在指定的索引處將其插入到形狀集合中，若需要可套用預設的範本樣式。

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 要插入連接線形狀的零基索引。 |
| shapeType | [ShapeType](../../shapetype/) | 要插入的連接線形狀的 [ShapeType](../../shapetype/)。 |
| x | **float** | 連接線框架的 x 座標，單位為點。 |
| y | **float** | 連接線框架的 y 座標，單位為點。 |
| width | **float** | 連接線框架的寬度，單位為點。 |
| height | **float** | 連接線框架的高度，單位為點。 |
| createFromTemplate | **bool** | 若為 true 則套用預設的範本樣式（非空名稱、簡單樣式）；若為 false 則以預設屬性值建立連接線。 |

### 回傳值

新建立的 [IConnector](../../iconnector/)。

## 參見

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)