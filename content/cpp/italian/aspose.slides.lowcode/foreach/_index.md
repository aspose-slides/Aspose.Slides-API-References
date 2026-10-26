---
title: ForEach
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un gruppo di metodi destinati a iterare su diversi oggetti modello Presentation. Questi metodi possono essere utili se è necessario iterare e modificare la formattazione o il contenuto di alcuni elementi Presentation, ad esempio modificare la formattazione di ciascuna porzione.
type: docs
weight: 40
url: /it/aspose.slides.lowcode/foreach/
---
## ForEach classe

Rappresenta un gruppo di metodi destinati a iterare su diversi oggetti modello [Presentation](../../aspose.slides/presentation/). Questi metodi possono essere utili se è necessario iterare e modificare la formattazione o il contenuto di alcuni elementi [Presentation](../../aspose.slides/presentation/), ad esempio modificare la formattazione di ciascuna porzione.

```cpp
class ForEach
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Itera ogni [ForEach::LayoutSlide](./layoutslide/) nel [Presentation](../../aspose.slides/presentation/). |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Itera ogni [ForEach::MasterSlide](./masterslide/) nel [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Itera ogni [ForEach::Paragraph](./paragraph/) nel [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Itera ogni [ForEach::Paragraph](./paragraph/) nel [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Itera ogni [ForEach::Portion](./portion/) nel [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Itera ogni [ForEach::Portion](./portion/) nel [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Itera ogni [ForEach::Shape](./shape/) nel [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Itera ogni [ForEach::Shape](./shape/) nel [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Itera ogni [ForEach::Shape](./shape/) nel [BaseSlide](../../aspose.slides/baseslide/). |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Itera ogni [ForEach::Slide](./slide/) nel [Presentation](../../aspose.slides/presentation/). |
## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Callback che verrà invocato per ogni [ForEach::Slide](./slide/) nel [Presentation](../../aspose.slides/presentation/). |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Callback che verrà invocato per ogni [ForEach::MasterSlide](./masterslide/) nel [Presentation](../../aspose.slides/presentation/). |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Callback che verrà invocato per ogni [ForEach::LayoutSlide](./layoutslide/) nel [Presentation](../../aspose.slides/presentation/). |
| [ForEachShapeCallback](./foreachshapecallback/) | Callback che verrà invocato per ogni [ForEach::Shape](./shape/) nel [Presentation](../../aspose.slides/presentation/). |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Callback che verrà invocato per ogni [ForEach::Paragraph](./paragraph/) sul [BaseSlide](../../aspose.slides/baseslide/). |
| [ForEachPortionCallback](./foreachportioncallback/) | Callback che verrà invocato per ogni [ForEach::Portion](./portion/) nel [ForEach::Paragraph](./paragraph/) sul [BaseSlide](../../aspose.slides/baseslide/). |
## Osservazioni



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

## Vedi anche

* Spazio dei nomi [Aspose::Slides::LowCode](../)
* Libreria [Aspose.Slides](../../)