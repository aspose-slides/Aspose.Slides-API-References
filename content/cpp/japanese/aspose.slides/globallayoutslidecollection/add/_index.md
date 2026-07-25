---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションに新しいレイアウト スライドを追加します。
type: docs
weight: 14
url: /ja/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) メソッド

プレゼンテーションに新しいレイアウト スライドを追加します。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新しいレイアウト用のマスタースライド。 |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 新しいレイアウトのレイアウトタイプ。サポートされているレイアウトタイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 現在サポートされていないレイアウトタイプ: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | 新しいレイアウトの名前。指定した名前が既に使用されている場合は ArgumentException がスローされます。null が渡された場合、レイアウトタイプに応じて自動的に名前が生成されます（例: "Title Slide" や "1_Title Slide", "2_.." など）。 |

### 戻り値

追加されたスライド。

## 備考

1) *layoutType* の値 [SlideLayoutType::Custom](../../slidelayouttype/) に対して追加されたレイアウトにはプレースホルダーもシェイプも含まれません。 2) このメソッドに相当するメソッドは [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) で、[IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) プロパティでアクセスできます。

## 関連項目

* 列挙型 [SlideLayoutType](../../slidelayouttype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [IMasterSlide](../../imasterslide/)
* クラス [String](../../../system/string/)
* クラス [GlobalLayoutSlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)