---
title: Add()
second_title: Aspose.Slides C++ API 參考
description: 將新的版面投影片新增至集合的末端。
type: docs
weight: 27
url: /zh-hant/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) method


將新的版面投影片新增至集合的末端。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 新版面的版面類型。支援的版面類型有：Title、TitleOnly、Blank、TitleAndObject、VerticalText、VerticalTitleAndText、TwoObjects、SectionHeader、TwoTextAndTwoObjects、TitleObjectAndCaption、PictureAndCaption、Custom。其他版面類型目前不受支援：Text、TwoColumnText、[Table](../../table/)、TextAndChart、ChartAndText、Diagram、Chart、TextAndClipArt、ClipArtAndText、TextAndObject、ObjectAndText、Object、TextAndMedia、MediaAndText、ObjectOverText、TextOverObject、TextAndTwoObjects、TwoObjectsAndText、TwoObjectsOverText、FourObjects、ClipArtAndVerticalText、VerticalTitleAndTextOverChart、ObjectAndTwoObject、TwoObjectsAndObject。 |
| layoutName | [System::String](../../../system/string/) | 新版面的名稱。如果傳入的名稱已被使用，將拋出 ArgumentException。若傳入 null 參數，則會根據傳入的版面類型自動產生名稱（例如「Title Slide」或「1_Title Slide」、「2_..」等）。 |

### Return Value

已新增的投影片。

## Remarks

1) 為 *layoutType* 的值 [SlideLayoutType::Custom](../../slidelayouttype/) 所新增的版面不包含任何佔位符與圖形。2) 此方法的類似方法為 [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/)，透過 [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) 屬性存取。 

## See Also

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [String](../../../system/string/)
* 類別 [MasterLayoutSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)