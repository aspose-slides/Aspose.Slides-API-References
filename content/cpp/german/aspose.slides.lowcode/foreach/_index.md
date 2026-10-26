---
title: ForEach
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, über verschiedene Presentation-Modelobjekte zu iterieren. Diese Methoden können nützlich sein, wenn Sie iterieren und die Formatierung oder den Inhalt einiger Presentation-Elemente ändern müssen, z. B. die Formatierung jedes Abschnitts ändern.
type: docs
weight: 40
url: /de/aspose.slides.lowcode/foreach/
---
## ForEach Klasse

Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, über verschiedene [Presentation](../../aspose.slides/presentation/) Modellobjekte zu iterieren. Diese Methoden können nützlich sein, wenn Sie iterieren und die Formatierung oder den Inhalt einiger [Presentation](../../aspose.slides/presentation/)' Elemente ändern müssen, z. B. die Formatierung jedes Abschnitts ändern.

```cpp
class ForEach
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Iteriere jedes [ForEach::LayoutSlide](./layoutslide/) im [Presentation](../../aspose.slides/presentation/). |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Iteriere jedes [ForEach::MasterSlide](./masterslide/) im [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iteriere jedes [ForEach::Paragraph](./paragraph/) im [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iteriere jedes [ForEach::Paragraph](./paragraph/) im [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iteriere jedes [ForEach::Portion](./portion/) im [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iteriere jedes [ForEach::Portion](./portion/) im [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iteriere jedes [ForEach::Shape](./shape/) im [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iteriere jedes [ForEach::Shape](./shape/) im [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iteriere jedes [ForEach::Shape](./shape/) im [BaseSlide](../../aspose.slides/baseslide/). |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Iteriere jedes [ForEach::Slide](./slide/) im [Presentation](../../aspose.slides/presentation/). |

## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Callback, der für jedes [ForEach::Slide](./slide/) im [Presentation](../../aspose.slides/presentation/) aufgerufen wird. |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Callback, der für jedes [ForEach::MasterSlide](./masterslide/) im [Presentation](../../aspose.slides/presentation/) aufgerufen wird. |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Callback, der für jedes [ForEach::LayoutSlide](./layoutslide/) im [Presentation](../../aspose.slides/presentation/) aufgerufen wird. |
| [ForEachShapeCallback](./foreachshapecallback/) | Callback, der für jedes [ForEach::Shape](./shape/) im [Presentation](../../aspose.slides/presentation/) aufgerufen wird. |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Callback, der für jedes [ForEach::Paragraph](./paragraph/) auf dem [BaseSlide](../../aspose.slides/baseslide/) aufgerufen wird. |
| [ForEachPortionCallback](./foreachportioncallback/) | Callback, der für jedes [ForEach::Portion](./portion/) im [ForEach::Paragraph](./paragraph/) auf dem [BaseSlide](../../aspose.slides/baseslide/) aufgerufen wird. |

## Anmerkungen

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

## Siehe auch

* Namensraum [Aspose::Slides::LowCode](../)
* Bibliothek [Aspose.Slides](../../)