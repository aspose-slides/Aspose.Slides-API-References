---
title: AddSectionZoomFrame()
second_title: Aspose.Slides C++ API 参考
description: 创建一个新的 Section Zoom 框并将其添加到形状集合的末尾。
type: docs
weight: 118
url: /zh/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) 方法

创建一个新的 [Section](../../section/) Zoom 框并将其添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| x | **float** | 新 [Section](../../section/) Zoom 框的 x 坐标，单位为点。 |
| y | **float** | 新 [Section](../../section/) Zoom 框的 y 坐标，单位为点。 |
| width | **float** | 新 [Section](../../section/) Zoom 框的宽度，单位为点。 |
| height | **float** | 新 [Section](../../section/) Zoom 框的高度，单位为点。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) 被 [Section](../../section/) Zoom 框引用；必须属于此演示文稿并包含至少一个幻灯片。 |

### 返回值

新创建的 [ISectionZoomFrame](../../isectionzoomframe/)。

## 备注

此示例演示将 [Section](../../section/) Zoom 对象添加到集合的末尾（假设在 "Presentation.pptx" 演示文稿中至少有两个节）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) 方法

创建一个带有预定义图像的新 [Section](../../section/) Zoom 框，并将其添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| x | **float** | 新 [Section](../../section/) Zoom 框的 x 坐标，单位为点。 |
| y | **float** | 新 [Section](../../section/) Zoom 框的 y 坐标，单位为点。 |
| width | **float** | 新 [Section](../../section/) Zoom 框的宽度，单位为点。 |
| height | **float** | 新 [Section](../../section/) Zoom 框的高度，单位为点。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) 被 [Section](../../section/) Zoom 框引用；必须属于此演示文稿并包含至少一个幻灯片。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 在 [Section](../../section/) Zoom 框内显示的 [IPPImage](../../ippimage/)。 |

### 返回值

新创建的 [ISectionZoomFrame](../../isectionzoomframe/)。

## 备注

此示例演示将 [Section](../../section/) Zoom 对象添加到集合的末尾（假设在 "Presentation.pptx" 演示文稿中至少有两个节）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISectionZoomFrame](../../isectionzoomframe/)
* 类 [ISection](../../isection/)
* 类 [IShapeCollection](../)
* 类 [IPPImage](../../ippimage/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)