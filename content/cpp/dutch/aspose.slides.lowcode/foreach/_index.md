---
title: ForEach
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een groep methoden voor die bedoeld zijn om over verschillende Presentation-modelobjecten te itereren. Deze methoden kunnen handig zijn als u moet itereren en de opmaak of inhoud van enkele Presentation' elementen wilt wijzigen, bijv. de opmaak van elk gedeelte wilt aanpassen.
type: docs
weight: 40
url: /nl/aspose.slides.lowcode/foreach/
---
## ForEach klasse


Stelt een groep methoden voor die bedoeld zijn om over verschillende [Presentation](../../aspose.slides/presentation/) modelobjecten te itereren. Deze methoden kunnen nuttig zijn als u moet itereren en de opmaak of inhoud van enkele [Presentation](../../aspose.slides/presentation/)' elementen wilt wijzigen, bijv. de opmaak van elk gedeelte wilt wijzigen.

```cpp
class ForEach
```

## Methods

| Method | Description |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Itereer elke [ForEach::LayoutSlide](./layoutslide/) in de [Presentation](../../aspose.slides/presentation/). |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Itereer elke [ForEach::MasterSlide](./masterslide/) in de [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Itereer elke [ForEach::Paragraph](./paragraph/) in de [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Itereer elke [ForEach::Paragraph](./paragraph/) in de [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Itereer elke [ForEach::Portion](./portion/) in de [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Itereer elke [ForEach::Portion](./portion/) in de [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Itereer elke [ForEach::Shape](./shape/) in de [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Itereer elke [ForEach::Shape](./shape/) in de [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Itereer elke [ForEach::Shape](./shape/) in de [BaseSlide](../../aspose.slides/baseslide/). |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Itereer elke [ForEach::Slide](./slide/) in de [Presentation](../../aspose.slides/presentation/). |

## Typedefs

| Typedef | Description |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Callback die wordt aangeroepen voor elke [ForEach::Slide](./slide/) in de [Presentation](../../aspose.slides/presentation/). |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Callback die wordt aangeroepen voor elke [ForEach::MasterSlide](./masterslide/) in de [Presentation](../../aspose.slides/presentation/). |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Callback die wordt aangeroepen voor elke [ForEach::LayoutSlide](./layoutslide/) in de [Presentation](../../aspose.slides/presentation/). |
| [ForEachShapeCallback](./foreachshapecallback/) | Callback die wordt aangeroepen voor elke [ForEach::Shape](./shape/) in de [Presentation](../../aspose.slides/presentation/). |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Callback die wordt aangeroepen voor elke [ForEach::Paragraph](./paragraph/) op de [BaseSlide](../../aspose.slides/baseslide/). |
| [ForEachPortionCallback](./foreachportioncallback/) | Callback die wordt aangeroepen voor elke [ForEach::Portion](./portion/) in de [ForEach::Paragraph](./paragraph/) op de [BaseSlide](../../aspose.slides/baseslide/). |

## Opmerkingen



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

## Zie ook

* Naamruimte [Aspose::Slides::LowCode](../)
* Bibliotheek [Aspose.Slides](../../)