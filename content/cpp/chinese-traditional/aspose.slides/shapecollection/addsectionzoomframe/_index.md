---
title: AddSectionZoomFrame()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的 Section Zoom 框架，並將其新增至形狀集合的末端。
type: docs
weight: 131
url: /zh-hant/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) 方法

建立一個新的 [Section](../../section/) Zoom 框架，並將其添加到形狀集合的末端。

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新 [Section](../../section/) Zoom 框架的 x 坐標（單位：點）。 |
| y | **float** | 新 [Section](../../section/) Zoom 框架的 y 坐標（單位：點）。 |
| width | **float** | 新 [Section](../../section/) Zoom 框架的寬度（單位：點）。 |
| height | **float** | 新 [Section](../../section/) Zoom 框架的高度（單位：點）。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | 被 [Section](../../section/) Zoom 框架參照的 [ISection](../../isection/)；必須屬於此簡報且至少包含一張投影片。 |

### 傳回值

新建立的 [ISectionZoomFrame](../../isectionzoomframe/)。

## 備註

此範例示範將 [Section](../../section/) Zoom 物件新增至集合的末端（假設 "Presentation.pptx" 簡報中至少有兩個章節）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) 方法

建立一個帶有預先定義影像的新的 [Section](../../section/) Zoom 框架，並將其添加到形狀集合的末端。

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新 [Section](../../section/) Zoom 框架的 x 坐標（單位：點）。 |
| y | **float** | 新 [Section](../../section/) Zoom 框架的 y 坐標（單位：點）。 |
| width | **float** | 新 [Section](../../section/) Zoom 框架的寬度（單位：點）。 |
| height | **float** | 新 [Section](../../section/) Zoom 框架的高度（單位：點）。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | 被 [Section](../../section/) Zoom 框架參照的 [ISection](../../isection/)；必須屬於此簡報且至少包含一張投影片。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 在 [Section](../../section/) Zoom 框架內顯示的 [IPPImage](../../ippimage/)。 |

### 傳回值

新建立的 [ISectionZoomFrame](../../isectionzoomframe/)。

## 備註

此範例示範將 [Section](../../section/) Zoom 物件新增至集合的末端（假設 "Presentation.pptx" 簡報中至少有兩個章節）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)