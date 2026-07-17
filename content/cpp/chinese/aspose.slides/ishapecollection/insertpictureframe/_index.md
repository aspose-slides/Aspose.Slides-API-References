---
title: InsertPictureFrame()
second_title: Aspose.Slides for C++ API 参考文档
description: 创建一个包含指定图像的新图片框，并将其插入到指定索引处的形状集合中。
type: docs
weight: 417
url: /zh/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) 方法

创建一个包含指定图像的新图片框，并将其插入到指定索引处的形状集合中。

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要插入图片框的零基索引。 |
| shapeType | [ShapeType](../../shapetype/) | 指定 [ShapeType](../../shapetype/) 中包含的形状类型，但不包括所有类型的线：

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/)。 |
| x | **float** | 图片框的 x 坐标，单位为点。 |
| y | **float** | 图片框的 y 坐标，单位为点。 |
| width | **float** | 图片框的宽度，单位为点。 |
| height | **float** | 图片框的高度，单位为点。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 要在图片框中显示的 [IPPImage](../../ippimage/)。 |

### 返回值

新创建的 [IPictureFrame](../../ipictureframe/)。

## 另请参阅

* 枚举 [ShapeType](../../shapetype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPictureFrame](../../ipictureframe/)
* 类 [IPPImage](../../ippimage/)
* 类 [IShapeCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)