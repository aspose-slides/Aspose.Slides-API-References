---
title: ForEach
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje grupę metod przeznaczonych do iteracji po różnych obiektach modelu Presentation. Metody te mogą być przydatne, jeśli potrzebujesz iterować i zmieniać formatowanie lub zawartość niektórych elementów Presentation, np. zmienić formatowanie każdego fragmentu.
type: docs
weight: 40
url: /pl/aspose.slides.lowcode/foreach/
---
## ForEach klasa

Reprezentuje grupę metod przeznaczonych do iteracji po różnych obiektach modelu [Presentation](../../aspose.slides/presentation/). Metody te mogą być użyteczne, jeśli trzeba iterować i zmieniać formatowanie lub zawartość niektórych elementów [Presentation](../../aspose.slides/presentation/), np. zmienić formatowanie każdego fragmentu.

```cpp
class ForEach
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Iteruj każdy [ForEach::LayoutSlide](./layoutslide/) w [Presentation](../../aspose.slides/presentation/). |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Iteruj każdy [ForEach::MasterSlide](./masterslide/) w [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iteruj każdy [ForEach::Paragraph](./paragraph/) w [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iteruj każdy [ForEach::Paragraph](./paragraph/) w [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iteruj każdy [ForEach::Portion](./portion/) w [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iteruj każdy [ForEach::Portion](./portion/) w [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iteruj każdy [ForEach::Shape](./shape/) w [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iteruj każdy [ForEach::Shape](./shape/) w [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iteruj każdy [ForEach::Shape](./shape/) w [BaseSlide](../../aspose.slides/baseslide/). |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Iteruj każdy [ForEach::Slide](./slide/) w [Presentation](../../aspose.slides/presentation/). |

## Typedefy

| Typedef | Opis |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Callback, który zostanie wywołany dla każdego [ForEach::Slide](./slide/) w [Presentation](../../aspose.slides/presentation/). |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Callback, który zostanie wywołany dla każdego [ForEach::MasterSlide](./masterslide/) w [Presentation](../../aspose.slides/presentation/). |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Callback, który zostanie wywołany dla każdego [ForEach::LayoutSlide](./layoutslide/) w [Presentation](../../aspose.slides/presentation/). |
| [ForEachShapeCallback](./foreachshapecallback/) | Callback, który zostanie wywołany dla każdego [ForEach::Shape](./shape/) w [Presentation](../../aspose.slides/presentation/). |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Callback, który zostanie wywołany dla każdego [ForEach::Paragraph](./paragraph/) na [BaseSlide](../../aspose.slides/baseslide/). |
| [ForEachPortionCallback](./foreachportioncallback/) | Callback, który zostanie wywołany dla każdego [ForEach::Portion](./portion/) w [ForEach::Paragraph](./paragraph/) na [BaseSlide](../../aspose.slides/baseslide/). |

## Uwagi



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

## Zobacz także

* Przestrzeń nazw [Aspose::Slides::LowCode](../)
* Biblioteka [Aspose.Slides](../../)