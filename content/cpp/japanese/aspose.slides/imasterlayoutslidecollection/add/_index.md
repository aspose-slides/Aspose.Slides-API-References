---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に新しいレイアウトスライドを追加します。
type: docs
weight: 27
url: /ja/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) メソッド

新しいレイアウトスライドをコレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 新しいレイアウトのレイアウトタイプ。サポートされているレイアウトタイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 現在サポートされていないレイアウトタイプ: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | 新しいレイアウトの名前。指定された名前が既に使用されている場合は ArgumentException がスローされます。null パラメータが渡された場合、指定されたレイアウトタイプに応じて名前が自動的に生成されます（例: "Title Slide" や "1_Title Slide", "2_..", など）。 |

### 戻り値

追加されたスライド。

## 備考

1) 値 [SlideLayoutType::Custom](../../slidelayouttype/) の *layoutType* 用に追加されたレイアウトは、プレースホルダーもシェイプも含まれていません。  
2) このメソッドの類似は、[IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) メソッドで、[IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) プロパティを使用してアクセスします。

## 関連項目

* 列挙型 [SlideLayoutType](../../slidelayouttype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [String](../../../system/string/)
* クラス [IMasterLayoutSlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)