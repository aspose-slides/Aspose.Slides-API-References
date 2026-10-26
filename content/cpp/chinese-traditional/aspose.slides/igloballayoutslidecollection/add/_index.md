---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將新的版面投影片新增至簡報。
type: docs
weight: 14
url: /zh-hant/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) 方法

將新的版面投影片新增至簡報。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 用於新版面的母投影片。 |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 新版面的版面類型。支援的版面類型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。目前不支援的其他版面類型：Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | [System::String](../../../system/string/) | 新版面的名稱。如果提供的名稱已被使用，將拋出 ArgumentException。如果傳入 null 參數，則會根據傳入的版面類型自動產生名稱（例如 "Title Slide" 或 "1_Title Slide", "2_..", 等）。 |

### 回傳值

已新增的投影片。

## 備註

1) 為值 [SlideLayoutType::Custom](../../slidelayouttype/) 的 *layoutType* 所新增的版面不含任何佔位符和圖形。2) 此方法的類比是使用 [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) 屬性存取的 [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) 方法。

## 另見

* 列舉 [SlideLayoutType](../../slidelayouttype/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [IMasterSlide](../../imasterslide/)
* 類別 [String](../../../system/string/)
* 類別 [IGlobalLayoutSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)