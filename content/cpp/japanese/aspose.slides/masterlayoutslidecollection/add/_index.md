---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に新しいレイアウト スライドを追加します。
type: docs
weight: 27
url: /ja/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) メソッド

コレクションの末尾に新しいレイアウト スライドを追加します。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 新しいレイアウトのレイアウト タイプ。サポートされているレイアウト タイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。現在サポートされていないレイアウト タイプ: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | 新しいレイアウトの名前。指定した名前が既に使用されている場合は ArgumentException がスローされます。null パラメータが渡された場合、指定されたレイアウト タイプに基づいて自動的に名前が生成されます（例: 「Title Slide」や「1_Title Slide」「2_…」など）。 |

### 戻り値

追加されたスライド。

## 備考

1) *layoutType* の値 [SlideLayoutType::Custom](../../slidelayouttype/) に対して追加されたレイアウトはプレースホルダーもシェイプも含みません。  
2) このメソッドの類似は、[IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) メソッドで、[IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) プロパティからアクセスできます。

## 関連項目

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)