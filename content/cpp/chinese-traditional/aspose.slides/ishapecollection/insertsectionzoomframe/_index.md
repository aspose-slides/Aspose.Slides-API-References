---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides for C++ API 參考
description: 在指定索引處建立新的 Section Zoom 框架，並將其插入形狀集合中。
type: docs
weight: 131
url: /zh-hant/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) 方法


建立一個新的 [Section](../../section/) Zoom 框架，並將其插入到指定索引的形狀集合中。

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 用於插入 [Section](../../section/) Zoom 框架的零基索引。 |
| x | **float** | 新 [Section](../../section/) Zoom 框架的 x 坐標（以點為單位）。 |
| y | **float** | 新 [Section](../../section/) Zoom 框架的 y 坐標（以點為單位）。 |
| width | **float** | 新 [Section](../../section/) Zoom 框架的寬度（以點為單位）。 |
| height | **float** | 新 [Section](../../section/) Zoom 框架的高度（以點為單位）。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) 由 [Section](../../section/) Zoom 框架參照；必須屬於此簡報且至少包含一張投影片。 |

### 傳回值

新建立的 [ISectionZoomFrame](../../isectionzoomframe/)。

## 備註


此範例示範在集合的指定索引處建立並插入 [Section](../../section/) Zoom 物件（假設 "Presentation.pptx" 簡報中至少有兩個節）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) 方法


建立一個帶有預定義圖像的 [Section](../../section/) Zoom 框架，並將其插入到指定索引的形狀集合中。

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 用於插入 [Section](../../section/) Zoom 框架的零基索引。 |
| x | **float** | 新 [Section](../../section/) Zoom 框架的 x 坐標（以點為單位）。 |
| y | **float** | 新 [Section](../../section/) Zoom 框架的 y 坐標（以點為單位）。 |
| width | **float** | 新 [Section](../../section/) Zoom 框架的寬度（以點為單位）。 |
| height | **float** | 新 [Section](../../section/) Zoom 框架的高度（以點為單位）。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) 由 [Section](../../section/) Zoom 框架參照；必須屬於此簡報且至少包含一張投影片。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 在 [Section](../../section/) Zoom 框架內顯示的圖像。 |

### 傳回值

新建立的 [ISectionZoomFrame](../../isectionzoomframe/)。

## 備註


此範例示範在集合的指定索引處建立並插入 [Section](../../section/) Zoom 物件（假設 "Presentation.pptx" 簡報中至少有兩個節）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISectionZoomFrame](../../isectionzoomframe/)
* 類別 [ISection](../../isection/)
* 類別 [IShapeCollection](../)
* 類別 [IPPImage](../../ippimage/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)