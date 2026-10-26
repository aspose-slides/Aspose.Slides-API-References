---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides for C++ API 参考
description: 在指定索引处创建一个新的 Section Zoom 框并将其插入到形状集合中。
type: docs
weight: 144
url: /zh/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) method

在指定索引处创建一个新的 [Section](../../section/) Zoom 框并插入到形状集合中。

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要插入 [Section](../../section/) Zoom 框的零基索引。 |
| x | **float** | 新 [Section](../../section/) Zoom 框的 x 坐标，单位为点。 |
| y | **float** | 新 [Section](../../section/) Zoom 框的 y 坐标，单位为点。 |
| width | **float** | 新 [Section](../../section/) Zoom 框的宽度，单位为点。 |
| height | **float** | 新 [Section](../../section/) Zoom 框的高度，单位为点。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) 被 [Section](../../section/) Zoom 框引用；必须属于此演示文稿并包含至少一张幻灯片。 |

### 返回值

新创建的 [ISectionZoomFrame](../../isectionzoomframe/)。

## 备注

此示例演示了在集合的指定索引处创建并插入 [Section](../../section/) Zoom 对象（假设在 "Presentation.pptx" 演示文稿中至少有两个节）：

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method

在指定索引处创建一个带有预定义图像的新的 [Section](../../section/) Zoom 框，并插入到形状集合中。

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要插入 [Section](../../section/) Zoom 框的零基索引。 |
| x | **float** | 新 [Section](../../section/) Zoom 框的 x 坐标，单位为点。 |
| y | **float** | 新 [Section](../../section/) Zoom 框的 y 坐标，单位为点。 |
| width | **float** | 新 [Section](../../section/) Zoom 框的宽度，单位为点。 |
| height | **float** | 新 [Section](../../section/) Zoom 框的高度，单位为点。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) 被 [Section](../../section/) Zoom 框引用；必须属于此演示文稿并包含至少一张幻灯片。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 要在 [Section](../../section/) Zoom 框中显示的图像。 |

### 返回值

新创建的 [ISectionZoomFrame](../../isectionzoomframe/)。

## 备注

此示例演示了在集合的指定索引处创建并插入 [Section](../../section/) Zoom 对象（假设在 "Presentation.pptx" 演示文稿中至少有两个节）：

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)