---
title: ForEach
second_title: Aspose.Slides for C++ API 参考
description: 表示一组用于遍历不同 Presentation 模型对象的方法。如果您需要遍历并更改某些 Presentation 元素的格式或内容，例如更改每个部分的格式，这些方法会很有用。
type: docs
weight: 40
url: /zh/aspose.slides.lowcode/foreach/
---
## ForEach 类

表示一组用于遍历不同 [Presentation](../../aspose.slides/presentation/) 模型对象的方法。如果您需要遍历并更改某些 [Presentation](../../aspose.slides/presentation/)' 元素的格式或内容，例如更改每个部分的格式，这些方法会很有用。

```cpp
class ForEach
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | 遍历 [Presentation](../../aspose.slides/presentation/) 中的每个 [ForEach::LayoutSlide](./layoutslide/)。 |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | 遍历 [Presentation](../../aspose.slides/presentation/) 中的每个 [ForEach::MasterSlide](./masterslide/)。 |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | 遍历 [Presentation](../../aspose.slides/presentation/) 中的每个 [ForEach::Paragraph](./paragraph/)。 |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | 遍历 [Presentation](../../aspose.slides/presentation/) 中的每个 [ForEach::Paragraph](./paragraph/)。 |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | 遍历 [Presentation](../../aspose.slides/presentation/) 中的每个 [ForEach::Portion](./portion/)。 |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | 遍历 [Presentation](../../aspose.slides/presentation/) 中的每个 [ForEach::Portion](./portion/)。 |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | 遍历 [Presentation](../../aspose.slides/presentation/) 中的每个 [ForEach::Shape](./shape/)。 |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | 遍历 [Presentation](../../aspose.slides/presentation/) 中的每个 [ForEach::Shape](./shape/)。 |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | 遍历 [BaseSlide](../../aspose.slides/baseslide/) 中的每个 [ForEach::Shape](./shape/)。 |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | 遍历 [Presentation](../../aspose.slides/presentation/) 中的每个 [ForEach::Slide](./slide/)。 |

## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | 将在 [Presentation](../../aspose.slides/presentation/) 中为每个 [ForEach::Slide](./slide/) 调用的回调。 |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | 将在 [Presentation](../../aspose.slides/presentation/) 中为每个 [ForEach::MasterSlide](./masterslide/) 调用的回调。 |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | 将在 [Presentation](../../aspose.slides/presentation/) 中为每个 [ForEach::LayoutSlide](./layoutslide/) 调用的回调。 |
| [ForEachShapeCallback](./foreachshapecallback/) | 将在 [Presentation](../../aspose.slides/presentation/) 中为每个 [ForEach::Shape](./shape/) 调用的回调。 |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | 将在 [BaseSlide](../../aspose.slides/baseslide/) 上为每个 [ForEach::Paragraph](./paragraph/) 调用的回调。 |
| [ForEachPortionCallback](./foreachportioncallback/) | 将在 [ForEach::Paragraph](./paragraph/) 中为每个 [ForEach::Portion](./portion/) 调用的回调，位于 [BaseSlide](../../aspose.slides/baseslide/)。 |

## 备注

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

## 另请参阅

* 命名空间 [Aspose::Slides::LowCode](../)
* 库 [Aspose.Slides](../../)