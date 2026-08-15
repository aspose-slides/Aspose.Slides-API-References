---
title: AddAutoShape()
second_title: Aspose.Slides for C++ API 參考
description: 建立具有預設格式的新自動圖形，並將其加入圖形集合的末端。
type: docs
weight: 313
url: /zh-hant/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) 方法


建立具有預設格式的新自動圖形，並將其加入圖形集合的末端。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要新增之自動圖形的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形狀框架的 x 坐標（單位為點）。 |
| y | **float** | 形狀框架的 y 坐標（單位為點）。 |
| width | **float** | 形狀框架的寬度（單位為點）。 |
| height | **float** | 形狀框架的高度（單位為點）。 |

### 回傳值

新建立的 [IAutoShape](../../iautoshape/)。

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) 方法


建立新自動圖形並將其加入圖形集合的末端，可選擇以預設範本格式初始化。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 要新增之自動圖形的 [ShapeType](../../shapetype/)。 |
| x | **float** | 形狀框架的 x 坐標（單位為點）。 |
| y | **float** | 形狀框架的 y 坐標（單位為點）。 |
| width | **float** | 形狀框架的寬度（單位為點）。 |
| height | **float** | 形狀框架的高度（單位為點）。 |
| createFromTemplate | **bool** | true：將預設範本樣式（簡易樣式、文字居中且名稱非空）套用至新圖形； false：以所有屬性預設值建立圖形。 |

### 回傳值

新建立的 [IAutoShape](../../iautoshape/)。

## 另請參閱

* 列舉 [ShapeType](../../shapetype/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAutoShape](../../iautoshape/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)