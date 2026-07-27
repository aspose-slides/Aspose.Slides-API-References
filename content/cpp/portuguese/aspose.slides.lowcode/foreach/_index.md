---
title: ForEach
second_title: Aspose.Slides para Referência da API C++
description: Representa um grupo de métodos destinados a iterar sobre diferentes objetos de modelo Presentation. Esses métodos podem ser úteis se você precisar iterar e alterar a formatação ou o conteúdo de alguns elementos Presentation', por exemplo, alterar a formatação de cada porção.
type: docs
weight: 40
url: /pt/aspose.slides.lowcode/foreach/
---
## ForEach classe

Representa um grupo de métodos destinados a iterar sobre diferentes objetos de modelo [Presentation](../../aspose.slides/presentation/). Esses métodos podem ser úteis se você precisar iterar e alterar a formatação ou o conteúdo de alguns elementos [Presentation](../../aspose.slides/presentation/)', por exemplo, alterar a formatação de cada porção.

```cpp
class ForEach
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Iterar cada [ForEach::LayoutSlide](./layoutslide/) no [Presentation](../../aspose.slides/presentation/). |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Iterar cada [ForEach::MasterSlide](./masterslide/) no [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iterar cada [ForEach::Paragraph](./paragraph/) no [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iterar cada [ForEach::Paragraph](./paragraph/) no [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iterar cada [ForEach::Portion](./portion/) no [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iterar cada [ForEach::Portion](./portion/) no [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterar cada [ForEach::Shape](./shape/) no [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterar cada [ForEach::Shape](./shape/) no [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterar cada [ForEach::Shape](./shape/) no [BaseSlide](../../aspose.slides/baseslide/). |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Iterar cada [ForEach::Slide](./slide/) no [Presentation](../../aspose.slides/presentation/). |

## Tipos definidos

| Typedef | Descrição |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Callback que será invocado para cada [ForEach::Slide](./slide/) no [Presentation](../../aspose.slides/presentation/). |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Callback que será invocado para cada [ForEach::MasterSlide](./masterslide/) no [Presentation](../../aspose.slides/presentation/). |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Callback que será invocado para cada [ForEach::LayoutSlide](./layoutslide/) no [Presentation](../../aspose.slides/presentation/). |
| [ForEachShapeCallback](./foreachshapecallback/) | Callback que será invocado para cada [ForEach::Shape](./shape/) no [Presentation](../../aspose.slides/presentation/). |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Callback que será invocado para cada [ForEach::Paragraph](./paragraph/) no [BaseSlide](../../aspose.slides/baseslide/). |
| [ForEachPortionCallback](./foreachportioncallback/) | Callback que será invocado para cada [ForEach::Portion](./portion/) no [ForEach::Paragraph](./paragraph/) no [BaseSlide](../../aspose.slides/baseslide/). |

## Observações

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

## Ver também

* Namespace [Aspose::Slides::LowCode](../)
* Biblioteca [Aspose.Slides](../../)