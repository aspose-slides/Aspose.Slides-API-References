---
title: AddZoomFrame()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个新的 Zoom 框并将其添加到形状集合的末尾。
type: docs
weight: 105
url: /zh/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) 方法

创建一个新的 Zoom 框并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新 Zoom 框的 x 坐标（以点为单位）。 |
| y | **float** | 新 Zoom 框的 y 坐标（以点为单位）。 |
| width | **float** | 新 Zoom 框的宽度（以点为单位）。 |
| height | **float** | 新 Zoom 框的高度（以点为单位）。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 框引用的 [ISlide](../../islide/)；必须属于此演示文稿。 |

### 返回值

新创建的 [IZoomFrame](../../izoomframe/)。

## 备注

此示例演示了将 Zoom 对象添加到集合的末尾（假设在 "Presentation.pptx" 演示文稿中至少有两个幻灯片）：

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) 方法

创建一个新的 Zoom 框并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新 Zoom 框的 x 坐标（以点为单位）。 |
| y | **float** | 新 Zoom 框的 y 坐标（以点为单位）。 |
| width | **float** | 新 Zoom 框的宽度（以点为单位）。 |
| height | **float** | 新 Zoom 框的高度（以点为单位）。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Zoom 框引用的 [ISlide](../../islide/)；必须属于此演示文稿。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 引用的幻灯片 [IPPImage](../../ippimage/) 的图像。 |

### 返回值

新创建的 [IZoomFrame](../../izoomframe/)。

## 备注

此示例演示了将 Zoom 对象添加到集合的末尾（假设在 "Presentation.pptx" 演示文稿中至少有两个幻灯片）：

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IZoomFrame](../../izoomframe/)
* 类 [ISlide](../../islide/)
* 类 [ShapeCollection](../)
* 类 [IPPImage](../../ippimage/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)