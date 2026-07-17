---
title: AddPictureFrame()
second_title: Aspose.Slides C++ API 参考
description: 创建一个包含指定图像的新图片框，并将其添加到形状集合的末尾。
type: docs
weight: 443
url: /zh/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) 方法

创建一个包含指定图像的新图片框，并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 指定 [ShapeType](../../shapetype/) 中包含的形状类型，除所有类型的线之外：

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
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 用于在图片框中显示的 [IPPImage](../../ippimage/)。 |

### 返回值

新创建的 [IPictureFrame](../../ipictureframe/)。

## 另请参见

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)