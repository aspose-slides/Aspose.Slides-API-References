---
title: AddSectionZoomFrame()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新的 Section Zoom 框架，並將其添加到圖形集合的末端。
type: docs
weight: 118
url: /zh-hant/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) 方法

建立一個新的 [Section](../../section/) Zoom 框架，並將其添加到圖形集合的末端。

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新 [Section](../../section/) Zoom 框架的 x 座標（以點為單位）。 |
| y | **float** | 新 [Section](../../section/) Zoom 框架的 y 座標（以點為單位）。 |
| width | **float** | 新 [Section](../../section/) Zoom 框架的寬度（以點為單位）。 |
| height | **float** | 新 [Section](../../section/) Zoom 框架的高度（以點為單位）。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | 由 [Section](../../section/) Zoom 框架參考的 [ISection](../../isection/)；必須屬於此簡報且至少包含一張投影片。 |

### 回傳值

新建立的 [ISectionZoomFrame](../../isectionzoomframe/)。

## 備註

此範例示範將 [Section](../../section/) Zoom 物件添加到集合的末端（假設在 "Presentation.pptx" 簡報中至少有兩個節）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) 方法

建立一個帶有預先定義圖像的新的 [Section](../../section/) Zoom 框架，並將其添加到圖形集合的末端。

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 新 [Section](../../section/) Zoom 框架的 x 座標（以點為單位）。 |
| y | **float** | 新 [Section](../../section/) Zoom 框架的 y 座標（以點為單位）。 |
| width | **float** | 新 [Section](../../section/) Zoom 框架的寬度（以點為單位）。 |
| height | **float** | 新 [Section](../../section/) Zoom 框架的高度（以點為單位）。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | 由 [Section](../../section/) Zoom 框架參考的 [ISection](../../isection/)；必須屬於此簡報且至少包含一張投影片。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [Section](../../section/) Zoom 框架中要顯示的 [IPPImage](../../ippimage/)。 |

### 回傳值

新建立的 [ISectionZoomFrame](../../isectionzoomframe/)。

## 備註

此範例示範將 [Section](../../section/) Zoom 物件添加到集合的末端（假設在 "Presentation.pptx" 簡報中至少有兩個節）：
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISectionZoomFrame](../../isectionzoomframe/)
* 類別 [ISection](../../isection/)
* 類別 [IShapeCollection](../)
* 類別 [IPPImage](../../ippimage/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)