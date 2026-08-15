---
title: Add()
second_title: Aspose.Slides for C++ API 參考文件
description: 將新的版面投影片新增至簡報。
type: docs
weight: 14
url: /zh-hant/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) method

在簡報中加入新的版面投影片。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新版面的母投影片。 |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 支援的版面類型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。其他版面類型目前不支援：Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | [System::String](../../../system/string/) | 新版面的名稱。若傳入的名稱已被使用，將拋出 ArgumentException。若傳入 null 參數，則會根據傳入的版面類型自動產生名稱（例如 "Title Slide" 或 "1_Title Slide", "2_..", 等）。 |

### 傳回值

已新增的投影片。

## 備註

1) 為 *layoutType* 的值 [SlideLayoutType::Custom](../../slidelayouttype/) 新增的版面不包含佔位符與形狀。2) 此方法的類似方法是 [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/)，可透過 [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) 屬性存取。

## 另請參見

* 列舉 [SlideLayoutType](../../slidelayouttype/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [IMasterSlide](../../imasterslide/)
* 類別 [String](../../../system/string/)
* 類別 [GlobalLayoutSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)