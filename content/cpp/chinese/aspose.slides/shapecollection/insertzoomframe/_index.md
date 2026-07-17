---
title: InsertZoomFrame()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新的 Zoom 框架并将其插入到指定索引的形状集合中。
type: docs
weight: 118
url: /zh/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) 方法

创建一个新的 Zoom 框架并将其插入到指定索引的形状集合中。

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入 Zoom 框架的零基索引。 |
| x | **float** | 新 Zoom 框架的 x 坐标，单位为点。 |
| y | **float** | 新 Zoom 框架的 y 坐标，单位为点。 |
| width | **float** | 新 Zoom 框架的宽度，单位为点。 |
| height | **float** | 新 Zoom 框架的高度，单位为点。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 框架引用的 [ISlide](../../islide/)。 |

### 返回值

新创建的 [IZoomFrame](../../izoomframe/)。

## 备注

此示例演示在集合的指定索引处创建并插入 Zoom 对象（假设在 "Presentation.pptx" 演示文稿中至少有两张幻灯片）：

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) 方法

创建一个带有预定义图像的新 Zoom 框架并将其插入到指定索引的形状集合中。

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 插入 Zoom 框架的零基索引。 |
| x | **float** | 新 Zoom 框架的 x 坐标，单位为点。 |
| y | **float** | 新 Zoom 框架的 y 坐标，单位为点。 |
| width | **float** | 新 Zoom 框架的宽度，单位为点。 |
| height | **float** | 新 Zoom 框架的高度，单位为点。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 框架引用的 [ISlide](../../islide/)。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 为引用的幻灯片 [IPPImage](../../ippimage/) 提供的图像。 |

### 返回值

新创建的 [IZoomFrame](../../izoomframe/)。

## 备注

此示例演示在集合的指定索引处创建并插入 Zoom 对象（假设在 "Presentation.pptx" 演示文稿中至少有两张幻灯片）：

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IZoomFrame](../../izoomframe/)
* 类 [ISlide](../../islide/)
* 类 [ShapeCollection](../)
* 类 [IPPImage](../../ippimage/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)