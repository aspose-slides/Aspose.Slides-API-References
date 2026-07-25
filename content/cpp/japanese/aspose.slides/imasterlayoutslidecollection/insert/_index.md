---
title: Insert()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの指定位置に新しいレイアウト スライドを挿入します。
type: docs
weight: 40
url: /ja/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) メソッド


コレクションの指定位置に新しいレイアウト スライドを挿入します。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいスライドのインデックス。 |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | 新しいレイアウトのレイアウト タイプ。サポートされているレイアウト タイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 現在サポートされていないレイアウト タイプ: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | 新しいレイアウトの名前。指定された名前が既に使用されている場合は ArgumentException がスローされます。null が渡された場合は、指定されたレイアウト タイプに応じて自動的に名前が生成されます（例: "Title Slide"、"1_Title Slide"、"2_.." など）。 |

### 戻り値

挿入されたスライド。

## 備考

Inserted layout for value [SlideLayoutType::Custom](../../slidelayouttype/) of *layoutType*  contains no placeholders and no shapes. 

## 参照

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)