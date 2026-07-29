---
title: ForEach
second_title: Aspose.Slides för C++ API-referens
description: Representerar en grupp metoder avsedda att iterera över olika Presentation-modellobjekt. Dessa metoder kan vara användbara om du behöver iterera och ändra formateringen eller innehållet för vissa Presentation-element, t.ex. ändra varje portions formatering.
type: docs
weight: 40
url: /sv/aspose.slides.lowcode/foreach/
---
## ForEach klass


Representerar en grupp metoder avsedda att iterera över olika [Presentation](../../aspose.slides/presentation/) modellobjekt. Dessa metoder kan vara användbara om du behöver iterera och ändra formateringen eller innehållet för några [Presentation](../../aspose.slides/presentation/)-element, t.ex. ändra varje portions formatering.

```cpp
class ForEach
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Iterera varje [ForEach::LayoutSlide](./layoutslide/) i [Presentation](../../aspose.slides/presentation/). |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Iterera varje [ForEach::MasterSlide](./masterslide/) i [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iterera varje [ForEach::Paragraph](./paragraph/) i [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iterera varje [ForEach::Paragraph](./paragraph/) i [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iterera varje [ForEach::Portion](./portion/) i [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iterera varje [ForEach::Portion](./portion/) i [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterera varje [ForEach::Shape](./shape/) i [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterera varje [ForEach::Shape](./shape/) i [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterera varje [ForEach::Shape](./shape/) i [BaseSlide](../../aspose.slides/baseslide/). |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Iterera varje [ForEach::Slide](./slide/) i [Presentation](../../aspose.slides/presentation/). |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Återanrop som kommer att anropas för varje [ForEach::Slide](./slide/) i [Presentation](../../aspose.slides/presentation/). |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Återanrop som kommer att anropas för varje [ForEach::MasterSlide](./masterslide/) i [Presentation](../../aspose.slides/presentation/). |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Återanrop som kommer att anropas för varje [ForEach::LayoutSlide](./layoutslide/) i [Presentation](../../aspose.slides/presentation/). |
| [ForEachShapeCallback](./foreachshapecallback/) | Återanrop som kommer att anropas för varje [ForEach::Shape](./shape/) i [Presentation](../../aspose.slides/presentation/). |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Återanrop som kommer att anropas för varje [ForEach::Paragraph](./paragraph/) på [BaseSlide](../../aspose.slides/baseslide/). |
| [ForEachPortionCallback](./foreachportioncallback/) | Återanrop som kommer att anropas för varje [ForEach::Portion](./portion/) i [ForEach::Paragraph](./paragraph/) på [BaseSlide](../../aspose.slides/baseslide/). |

## Anmärkningar



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

## Se också

* Namnrymd [Aspose::Slides::LowCode](../)
* Bibliotek [Aspose.Slides](../../)