---
title: ForEach
second_title: Aspose.Slides C++ API referenciája
description: Representál egy módszercsoportot, amelynek célja a különböző Presentation modellobjektumokon való iterálás. Ezek a módszerek hasznosak lehetnek, ha iterálnia kell és módosítania kell a Presentation elemeinek formázását vagy tartalmát, például minden részlet formázását.
type: docs
weight: 40
url: /hu/aspose.slides.lowcode/foreach/
---
## ForEach osztály


A [Presentation](../../aspose.slides/presentation/) modellobjektumok különböző példányainak iterálására szolgáló módszercsoportot reprezentál. Ezek a módszerek hasznosak lehetnek, ha iterálnia kell és módosítania néhány [Presentation](../../aspose.slides/presentation/) elem formázását vagy tartalmát, például minden részlet formázását.

```cpp
class ForEach
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Iteráljon minden [ForEach::LayoutSlide](./layoutslide/) a [Presentation](../../aspose.slides/presentation/)-ban. |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Iteráljon minden [ForEach::MasterSlide](./masterslide/) a [Presentation](../../aspose.slides/presentation/)-ban. |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iteráljon minden [ForEach::Paragraph](./paragraph/) a [Presentation](../../aspose.slides/presentation/)-ban. |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iteráljon minden [ForEach::Paragraph](./paragraph/) a [Presentation](../../aspose.slides/presentation/)-ban. |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iteráljon minden [ForEach::Portion](./portion/) a [Presentation](../../aspose.slides/presentation/)-ban. |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iteráljon minden [ForEach::Portion](./portion/) a [Presentation](../../aspose.slides/presentation/)-ban. |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iteráljon minden [ForEach::Shape](./shape/) a [Presentation](../../aspose.slides/presentation/)-ban. |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iteráljon minden [ForEach::Shape](./shape/) a [Presentation](../../aspose.slides/presentation/)-ban. |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iteráljon minden [ForEach::Shape](./shape/) a [BaseSlide](../../aspose.slides/baseslide/)-ban. |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Iteráljon minden [ForEach::Slide](./slide/) a [Presentation](../../aspose.slides/presentation/)-ban. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Visszahívás, amely minden [ForEach::Slide](./slide/) esetén meghívódik a [Presentation](../../aspose.slides/presentation/)-ban. |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Visszahívás, amely minden [ForEach::MasterSlide](./masterslide/) esetén meghívódik a [Presentation](../../aspose.slides/presentation/)-ban. |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Visszahívás, amely minden [ForEach::LayoutSlide](./layoutslide/) esetén meghívódik a [Presentation](../../aspose.slides/presentation/)-ban. |
| [ForEachShapeCallback](./foreachshapecallback/) | Visszahívás, amely minden [ForEach::Shape](./shape/) esetén meghívódik a [Presentation](../../aspose.slides/presentation/)-ban. |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Visszahívás, amely minden [ForEach::Paragraph](./paragraph/) esetén meghívódik a [BaseSlide](../../aspose.slides/baseslide/)-on. |
| [ForEachPortionCallback](./foreachportioncallback/) | Visszahívás, amely minden [ForEach::Portion](./portion/) esetén meghívódik a [ForEach::Paragraph](./paragraph/)-ban a [BaseSlide](../../aspose.slides/baseslide/)-on. |

## Megjegyzések



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

## Lásd még

* Névtér [Aspose::Slides::LowCode](../)
* Könyvtár [Aspose.Slides](../../)