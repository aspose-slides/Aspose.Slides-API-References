---
title: ForEach
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un groupe de méthodes destinées à itérer sur différents objets modèle Presentation. Ces méthodes peuvent être utiles si vous devez itérer et modifier le formatage ou le contenu de certains éléments Presentation', par exemple changer le formatage de chaque portion.
type: docs
weight: 40
url: /fr/aspose.slides.lowcode/foreach/
---
## ForEach classe


Représente un groupe de méthodes destinées à itérer sur différents objets modèle [Presentation](../../aspose.slides/presentation/). Ces méthodes peuvent être utiles si vous devez itérer et modifier le formatage ou le contenu de certains éléments [Presentation](../../aspose.slides/presentation/)', par exemple modifier le formatage de chaque portion.

```cpp
class ForEach
```

## Méthodes

| Méthode | Description |
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
## Remarques



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

## Voir aussi

* Namespace [Aspose::Slides::LowCode](../)
* Library [Aspose.Slides](../../)