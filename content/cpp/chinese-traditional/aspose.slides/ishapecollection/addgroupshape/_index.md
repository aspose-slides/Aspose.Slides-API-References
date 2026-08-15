---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新的空白群組圖形，並將其新增至圖形集合的末端。群組的框架會自動調整以容納所有加入的圖形。
type: docs
weight: 352
url: /zh-hant/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() 方法

建立一個新的空白群組圖形，並將其新增至圖形集合的末端。群組的框架會自動調整以容納所有加入的圖形。

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### 傳回值

新建立的 [IGroupShape](../../igroupshape/)。

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) 方法

建立一個新的群組圖形，將指定的 SVG 圖像轉換為個別圖形，並將產生的群組新增至圖形集合的末端。

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | 包含向量內容以轉換為圖形的 [ISvgImage](../../isvgimage/)。 |
| x | **float** | 群組的框架的 x 座標，以點為單位。 |
| y | **float** | 群組的框架的 y 座標，以點為單位。 |
| width | **float** | 群組的框架的寬度，以點為單位。 |
| height | **float** | 群組的框架的高度，以點為單位。 |

### 傳回值

新建立的 [IGroupShape](../../igroupshape/)。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IGroupShape](../../igroupshape/)
* 類別 [IShapeCollection](../)
* 類別 [ISvgImage](../../isvgimage/)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)