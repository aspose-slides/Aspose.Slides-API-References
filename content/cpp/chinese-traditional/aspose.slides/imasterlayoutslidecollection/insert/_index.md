---
title: Insert()
second_title: Aspose.Slides for C++ API 參考
description: 在集合的指定位置插入新的版面投影片。
type: docs
weight: 40
url: /zh-hant/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) 方法


在集合的指定位置插入新的版面投影片。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 新投影片的索引。 |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 新版面的版面類型。支援的版面類型包括：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。現在不支援的其他版面類型有：Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | [System::String](../../../system/string/) | 新版面的名稱。若傳入的名稱已被使用，將拋出 ArgumentException。若傳入 null 參數，則會根據傳入的版面類型自動產生名稱（例如「Title Slide」或「1_Title Slide」、「2_..」等）。 |

### 傳回值

已插入的投影片。

## 備註



已插入的版面（*layoutType* 為 [SlideLayoutType::Custom](../../slidelayouttype/)）不包含任何佔位符和形狀。 

## 另見

* 列舉 [SlideLayoutType](../../slidelayouttype/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [String](../../../system/string/)
* 類別 [IMasterLayoutSlideCollection](../)
* 名稱空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)