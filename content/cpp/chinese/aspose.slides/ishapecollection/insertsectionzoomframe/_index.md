---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides C++ API 参考
description: 在指定索引处创建一个新的 Section Zoom 框架并将其插入到形状集合中。
type: docs
weight: 131
url: /zh/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) 方法

创建一个新的[Section](../../section/) Zoom 框架并将其插入到指定索引的形状集合中。

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 要插入[Section](../../section/) Zoom 框架的基于零的索引。 |
| x | **float** | 新[Section](../../section/) Zoom 框架的 x 坐标，单位为点。 |
| y | **float** | 新[Section](../../section/) Zoom 框架的 y 坐标，单位为点。 |
| width | **float** | 新[Section](../../section/) Zoom 框架的宽度，单位为点。 |
| height | **float** | 新[Section](../../section/) Zoom 框架的高度，单位为点。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom 框架引用的[ISection](../../isection/)；必须属于此演示文稿并包含至少一张幻灯片。 |

### 返回值

新创建的[ISectionZoomFrame](../../isectionzoomframe/)。

## 备注

此示例演示了在集合的指定索引处创建并插入[Section](../../section/) Zoom 对象（假设在 "Presentation.pptx" 演示文稿中至少有两个节）：

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) 方法

创建一个带有预定义图像的新的[Section](../../section/) Zoom 框架，并将其插入到指定索引的形状集合中。

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 要插入[Section](../../section/) Zoom 框架的基于零的索引。 |
| x | **float** | 新[Section](../../section/) Zoom 框架的 x 坐标，单位为点。 |
| y | **float** | 新[Section](../../section/) Zoom 框架的 y 坐标，单位为点。 |
| width | **float** | 新[Section](../../section/) Zoom 框架的宽度，单位为点。 |
| height | **float** | 新[Section](../../section/) Zoom 框架的高度，单位为点。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) Zoom 框架引用的[ISection](../../isection/)；必须属于此演示文稿并包含至少一张幻灯片。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 在[Section](../../section/) Zoom 框架中显示的图像。 |

### 返回值

新创建的[ISectionZoomFrame](../../isectionzoomframe/)。

## 备注

此示例演示了在集合的指定索引处创建并插入[Section](../../section/) Zoom 对象（假设在 "Presentation.pptx" 演示文稿中至少有两个节）：

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ISectionZoomFrame](../../isectionzoomframe/)
* 类 [ISection](../../isection/)
* 类 [IShapeCollection](../)
* 类 [IPPImage](../../ippimage/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)