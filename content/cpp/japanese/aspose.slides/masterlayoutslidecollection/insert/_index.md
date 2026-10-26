---
title: Insert()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの指定された位置に新しいレイアウトスライドを挿入します。
type: docs
weight: 40
url: /ja/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) メソッド

指定されたコレクションの位置に新しいレイアウト スライドを挿入します。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しい Slide のインデックス。 |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 新しいレイアウトのレイアウト タイプ。サポートされているレイアウト タイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 現在サポートされていないレイアウト タイプ: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | 新しいレイアウトの名前。指定された名前がすでに使用されている場合は ArgumentException がスローされます。null パラメーターが渡された場合、指定されたレイアウト タイプに従って名前が自動的に生成されます（例: "Title Slide" や "1_Title Slide", "2_..", etc.）。 |

### 戻り値

挿入された Slide。

## 備考

値 [SlideLayoutType::Custom](../../slidelayouttype/) の *layoutType* 用に挿入されたレイアウトにはプレースホルダーもシェイプも含まれていません。

## 関連項目

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)