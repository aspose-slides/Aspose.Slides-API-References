---
title: ForEach
second_title: Aspose.Slides for C++ API Reference
description: Represents a group of methods intended to iterate over different Presentation model objects. These methods can be useful if you need to iterate and change some Presentation' elements formatting or content, e.g. change each portion formatting.
type: docs
weight: 40
url: /cpp/aspose.slides.lowcode/foreach/
---
## ForEach class


Represents a group of methods intended to iterate over different [Presentation](../../aspose.slides/presentation/) model objects. These methods can be useful if you need to iterate and change some [Presentation](../../aspose.slides/presentation/)' elements formatting or content, e.g. change each portion formatting.

```cpp
class ForEach
```

## Methods

| Method | Description |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Iterate each [ForEach::LayoutSlide](./layoutslide/) in the [Presentation](../../aspose.slides/presentation/). |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Iterate each [ForEach::MasterSlide](./masterslide/) in the [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iterate each [ForEach::Paragraph](./paragraph/) in the [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iterate each [ForEach::Paragraph](./paragraph/) in the [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iterate each [ForEach::Portion](./portion/) in the [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iterate each [ForEach::Portion](./portion/) in the [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterate each [ForEach::Shape](./shape/) in the [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterate each [ForEach::Shape](./shape/) in the [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterate each [ForEach::Shape](./shape/) in the [BaseSlide](../../aspose.slides/baseslide/). |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Iterate each [ForEach::Slide](./slide/) in the [Presentation](../../aspose.slides/presentation/). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Callback that will be invoked for each [ForEach::Slide](./slide/) in the [Presentation](../../aspose.slides/presentation/). |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Callback that will be invoked for each [ForEach::MasterSlide](./masterslide/) in the [Presentation](../../aspose.slides/presentation/). |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Callback that will be invoked for each [ForEach::LayoutSlide](./layoutslide/) in the [Presentation](../../aspose.slides/presentation/). |
| [ForEachShapeCallback](./foreachshapecallback/) | Callback that will be invoked for each [ForEach::Shape](./shape/) in the [Presentation](../../aspose.slides/presentation/). |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Callback that will be invoked for each [ForEach::Paragraph](./paragraph/) on the [BaseSlide](../../aspose.slides/baseslide/). |
| [ForEachPortionCallback](./foreachportioncallback/) | Callback that will be invoked for each [ForEach::Portion](./portion/) in the [ForEach::Paragraph](./paragraph/) on the [BaseSlide](../../aspose.slides/baseslide/). |
## Remarks



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

## See Also

* Namespace [Aspose::Slides::LowCode](../)
* Library [Aspose.Slides](../../)