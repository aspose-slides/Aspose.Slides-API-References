---
title: Add()
second_title: Aspose.Slides for C++ APIリファレンス
description: プレゼンテーションに新しいレイアウトスライドを追加します。
type: docs
weight: 14
url: /ja/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) メソッド

プレゼンテーションに新しいレイアウトスライドを追加します。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新しいレイアウトのマスタースライド。 |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 新しいレイアウトのレイアウトタイプ。サポートされているレイアウトタイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 現在サポートされていないレイアウトタイプ: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | 新しいレイアウトの名前。指定された名前がすでに使用されている場合は ArgumentException がスローされます。null パラメーターが渡された場合、渡されたレイアウトタイプに応じて名前が自動的に生成されます（例: "Title Slide" や "1_Title Slide", "2_..", など）。 |

### 戻り値

追加されたスライド。

## 備考

1) *layoutType* の値 [SlideLayoutType::Custom](../../slidelayouttype/) 用に追加されたレイアウトにはプレースホルダーもシェイプも含まれていません。2) このメソッドの類似は、[IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) メソッドで、[IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) プロパティでアクセスできます。

## 関連項目

* 列挙型 [SlideLayoutType](../../slidelayouttype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [IMasterSlide](../../imasterslide/)
* クラス [String](../../../system/string/)
* クラス [IGlobalLayoutSlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)