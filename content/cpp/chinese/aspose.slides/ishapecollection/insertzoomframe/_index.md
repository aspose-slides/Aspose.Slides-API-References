---
title: InsertZoomFrame()
second_title: Aspose.Slides 用于 C++ 的 API 参考
description: 在指定索引处创建一个新的 Zoom 框并将其插入到形状集合中。
type: docs
weight: 105
url: /zh/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) method

创建一个新的 Zoom 框，并将其插入到在指定索引处的形状集合中。

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要在其中插入 Zoom 框的从零开始的索引。 |
| x | **float** | 新 Zoom 框的 x 坐标，以点为单位。 |
| y | **float** | 新 Zoom 框的 y 坐标，以点为单位。 |
| width | **float** | 新 Zoom 框的宽度，以点为单位。 |
| height | **float** | 新 Zoom 框的高度，以点为单位。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 框所引用的 [ISlide](../../islide/)。 |

### 返回值

新创建的 [IZoomFrame](../../izoomframe/)。

## 备注

此示例演示了在集合的指定索引处创建并插入 Zoom 对象（假设 \"Presentation.pptx\" 演示文稿中至少有两张幻灯片）：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

创建一个带有预定义图像的新的 Zoom 框，并将其插入到在指定索引处的形状集合中。

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要在其中插入 Zoom 框的从零开始的索引。 |
| x | **float** | 新 Zoom 框的 x 坐标，以点为单位。 |
| y | **float** | 新 Zoom 框的 y 坐标，以点为单位。 |
| width | **float** | 新 Zoom 框的宽度，以点为单位。 |
| height | **float** | 新 Zoom 框的高度，以点为单位。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 框所引用的 [ISlide](../../islide/)。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 引用的幻灯片 [IPPImage](../../ippimage/) 的图像。 |

### 返回值

新创建的 [IZoomFrame](../../izoomframe/)。

## 备注

此示例演示了在集合的指定索引处创建并插入 Zoom 对象（假设 \"Presentation.pptx\" 演示文稿中至少有两张幻灯片）：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IZoomFrame](../../izoomframe/)
* 类 [ISlide](../../islide/)
* 类 [IShapeCollection](../)
* 类 [IPPImage](../../ippimage/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)