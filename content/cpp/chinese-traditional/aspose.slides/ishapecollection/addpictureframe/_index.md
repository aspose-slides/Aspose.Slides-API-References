---
title: AddPictureFrame()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個包含指定影像的新圖片框，並將其加入形狀集合的末端。
type: docs
weight: 404
url: /zh-hant/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) 方法

建立一個包含指定影像的新圖片框，並將其加入形狀集合的末端。

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 指定 [ShapeType](../../shapetype/) 中包含的形狀類型，但不包括各種線條：

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | 圖片框的 x 坐標，單位為點。 |
| y | **float** | 圖片框的 y 坐標，單位為點。 |
| width | **float** | 圖片框的寬度，單位為點。 |
| height | **float** | 圖片框的高度，單位為點。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 要在圖片框中顯示的 [IPPImage](../../ippimage/)。 |

### 傳回值

新建立的 [IPictureFrame](../../ipictureframe/)。

## 另請參閱

* 列舉 [ShapeType](../../shapetype/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPictureFrame](../../ipictureframe/)
* 類別 [IPPImage](../../ippimage/)
* 類別 [IShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)