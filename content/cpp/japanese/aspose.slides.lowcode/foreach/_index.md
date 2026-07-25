---
title: ForEach
second_title: Aspose.Slides for C++ API リファレンス
description: さまざまな Presentation モデルオブジェクトを反復処理することを目的としたメソッドのグループを表します。これらのメソッドは、Presentation の要素の書式やコンテンツを反復して変更する必要がある場合に便利です。例えば、各部分の書式を変更することができます。
type: docs
weight: 40
url: /ja/aspose.slides.lowcode/foreach/
---
## ForEach クラス

さまざまな [Presentation](../../aspose.slides/presentation/) モデルオブジェクトを反復処理することを目的としたメソッドのグループを表します。これらのメソッドは、[Presentation](../../aspose.slides/presentation/) の要素の書式や内容を反復して変更する必要がある場合に便利です。例えば、各部分の書式を変更することができます。

```cpp
class ForEach
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | [Presentation](../../aspose.slides/presentation/) の各 [ForEach::LayoutSlide](./layoutslide/) を反復処理します。 |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | [Presentation](../../aspose.slides/presentation/) の各 [ForEach::MasterSlide](./masterslide/) を反復処理します。 |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | [Presentation](../../aspose.slides/presentation/) の各 [ForEach::Paragraph](./paragraph/) を反復処理します。 |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | [Presentation](../../aspose.slides/presentation/) の各 [ForEach::Paragraph](./paragraph/) を反復処理します。 |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | [Presentation](../../aspose.slides/presentation/) の各 [ForEach::Portion](./portion/) を反復処理します。 |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | [Presentation](../../aspose.slides/presentation/) の各 [ForEach::Portion](./portion/) を反復処理します。 |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | [Presentation](../../aspose.slides/presentation/) の各 [ForEach::Shape](./shape/) を反復処理します。 |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | [Presentation](../../aspose.slides/presentation/) の各 [ForEach::Shape](./shape/) を反復処理します。 |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | [BaseSlide](../../aspose.slides/baseslide/) の各 [ForEach::Shape](./shape/) を反復処理します。 |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | [Presentation](../../aspose.slides/presentation/) の各 [ForEach::Slide](./slide/) を反復処理します。 |

## 型定義

| 型定義 | 説明 |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | [Presentation](../../aspose.slides/presentation/) の各 [ForEach::Slide](./slide/) に対して呼び出されるコールバック。 |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | [Presentation](../../aspose.slides/presentation/) の各 [ForEach::MasterSlide](./masterslide/) に対して呼び出されるコールバック。 |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | [Presentation](../../aspose.slides/presentation/) の各 [ForEach::LayoutSlide](./layoutslide/) に対して呼び出されるコールバック。 |
| [ForEachShapeCallback](./foreachshapecallback/) | [Presentation](../../aspose.slides/presentation/) の各 [ForEach::Shape](./shape/) に対して呼び出されるコールバック。 |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | [BaseSlide](../../aspose.slides/baseslide/) 上の各 [ForEach::Paragraph](./paragraph/) に対して呼び出されるコールバック。 |
| [ForEachPortionCallback](./foreachportioncallback/) | [BaseSlide](../../aspose.slides/baseslide/) 上の [ForEach::Paragraph](./paragraph/) の各 [ForEach::Portion](./portion/) に対して呼び出されるコールバック。 |

## 備考



```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"Times New Roman"));
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(presentation, callback);

presentation->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 参照

* 名前空間 [Aspose::Slides::LowCode](../)
* ライブラリ [Aspose.Slides](../../)