---
title: ForEach
second_title: Aspose.Slides C++ API 參考
description: 代表一組用於遍歷不同 Presentation 模型物件的方法。如果您需要遍歷並更改某些 Presentation 元素的格式或內容，例如更改每個部分的格式，這些方法會非常有用。
type: docs
weight: 40
url: /zh-hant/aspose.slides.lowcode/foreach/
---
## ForEach 類別

表示一組旨在遍歷不同 [Presentation](../../aspose.slides/presentation/) 模型物件的方法。如果您需要遍歷並更改某些 [Presentation](../../aspose.slides/presentation/) 元素的格式或內容，例如更改每個部分的格式，這些方法會很有用。

```cpp
class ForEach
```

## 方法

| 方法 | 說明 |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | 遍歷 [Presentation](../../aspose.slides/presentation/) 中的每個 [ForEach::LayoutSlide](./layoutslide/)。 |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | 遍歷 [Presentation](../../aspose.slides/presentation/) 中的每個 [ForEach::MasterSlide](./masterslide/)。 |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | 遍歷 [Presentation](../../aspose.slides/presentation/) 中的每個 [ForEach::Paragraph](./paragraph/)。 |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | 遍歷 [Presentation](../../aspose.slides/presentation/) 中的每個 [ForEach::Paragraph](./paragraph/)。 |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | 遍歷 [Presentation](../../aspose.slides/presentation/) 中的每個 [ForEach::Portion](./portion/)。 |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | 遍歷 [Presentation](../../aspose.slides/presentation/) 中的每個 [ForEach::Portion](./portion/)。 |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | 遍歷 [Presentation](../../aspose.slides/presentation/) 中的每個 [ForEach::Shape](./shape/)。 |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | 遍歷 [Presentation](../../aspose.slides/presentation/) 中的每個 [ForEach::Shape](./shape/)。 |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | 遍歷 [BaseSlide](../../aspose.slides/baseslide/) 中的每個 [ForEach::Shape](./shape/)。 |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | 遍歷 [Presentation](../../aspose.slides/presentation/) 中的每個 [ForEach::Slide](./slide/)。 |

## 型別定義

| 型別別名 | 說明 |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | 在 [Presentation](../../aspose.slides/presentation/) 中對每個 [ForEach::Slide](./slide/) 觸發的回呼。 |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | 在 [Presentation](../../aspose.slides/presentation/) 中對每個 [ForEach::MasterSlide](./masterslide/) 觸發的回呼。 |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | 在 [Presentation](../../aspose.slides/presentation/) 中對每個 [ForEach::LayoutSlide](./layoutslide/) 觸發的回呼。 |
| [ForEachShapeCallback](./foreachshapecallback/) | 在 [Presentation](../../aspose.slides/presentation/) 中對每個 [ForEach::Shape](./shape/) 觸發的回呼。 |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | 在 [BaseSlide](../../aspose.slides/baseslide/) 上對每個 [ForEach::Paragraph](./paragraph/) 觸發的回呼。 |
| [ForEachPortionCallback](./foreachportioncallback/) | 在 [BaseSlide](../../aspose.slides/baseslide/) 上的 [ForEach::Paragraph](./paragraph/) 中對每個 [ForEach::Portion](./portion/) 觸發的回呼。 |

## 備註

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

## 另請參閱

* 命名空間 [Aspose::Slides::LowCode](../)
* 函式庫 [Aspose.Slides](../../)