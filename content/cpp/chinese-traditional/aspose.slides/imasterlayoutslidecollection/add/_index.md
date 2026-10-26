---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將新的版面配置投影片新增至集合的末端。
type: docs
weight: 27
url: /zh-hant/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) 方法


將新的版面配置投影片新增至集合的末端。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 新版面的版面配置類型。支援的版面配置類型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。目前不支援的其他版面配置類型：Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | [System::String](../../../system/string/) | 新版面的名稱。如果傳入的名稱已被使用，將拋出 ArgumentException。如果傳入 null 參數，則會根據傳入的版面配置類型自動產生名稱（例如 \"Title Slide\" 或 \"1_Title Slide\", \"2_..\", 等等）。 |

### 回傳值

已新增的投影片。

## 備註



1) 為 *layoutType* 的值 [SlideLayoutType::Custom](../../slidelayouttype/) 新增的版面配置不包含佔位符和圖形。2) 此方法的對應方法是 [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/)，可透過 [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) 屬性存取。

## 另請參閱

* 列舉 [SlideLayoutType](../../slidelayouttype/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [String](../../../system/string/)
* 類別 [IMasterLayoutSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)