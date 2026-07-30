---
title: ForEach
second_title: Aspose.Slides pro C++ reference API
description: Representuje skupinu metod určených k iteraci přes různé modelové objekty Presentation. Tyto metody mohou být užitečné, pokud potřebujete iterovat a měnit formátování nebo obsah některých elementů Presentation, např. změnit formátování každé části.
type: docs
weight: 40
url: /cs/aspose.slides.lowcode/foreach/
---
## ForEach třída

Representuje skupinu metod určených k iteraci přes různé [Presentation](../../aspose.slides/presentation/) modelové objekty. Tyto metody mohou být užitečné, pokud potřebujete iterovat a měnit formátování nebo obsah některých [Presentation](../../aspose.slides/presentation/) elementů, např. změnit formátování každé části.

```cpp
class ForEach
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Iterovat každé [ForEach::LayoutSlide](./layoutslide/) v [Presentation](../../aspose.slides/presentation/). |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Iterovat každé [ForEach::MasterSlide](./masterslide/) v [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iterovat každé [ForEach::Paragraph](./paragraph/) v [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iterovat každé [ForEach::Paragraph](./paragraph/) v [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iterovat každé [ForEach::Portion](./portion/) v [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iterovat každé [ForEach::Portion](./portion/) v [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterovat každé [ForEach::Shape](./shape/) v [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterovat každé [ForEach::Shape](./shape/) v [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterovat každé [ForEach::Shape](./shape/) v [BaseSlide](../../aspose.slides/baseslide/). |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Iterovat každé [ForEach::Slide](./slide/) v [Presentation](../../aspose.slides/presentation/). |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Callback, který bude vyvolán pro každý [ForEach::Slide](./slide/) v [Presentation](../../aspose.slides/presentation/). |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Callback, který bude vyvolán pro každý [ForEach::MasterSlide](./masterslide/) v [Presentation](../../aspose.slides/presentation/). |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Callback, který bude vyvolán pro každý [ForEach::LayoutSlide](./layoutslide/) v [Presentation](../../aspose.slides/presentation/). |
| [ForEachShapeCallback](./foreachshapecallback/) | Callback, který bude vyvolán pro každý [ForEach::Shape](./shape/) v [Presentation](../../aspose.slides/presentation/). |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Callback, který bude vyvolán pro každý [ForEach::Paragraph](./paragraph/) na [BaseSlide](../../aspose.slides/baseslide/). |
| [ForEachPortionCallback](./foreachportioncallback/) | Callback, který bude vyvolán pro každý [ForEach::Portion](./portion/) v [ForEach::Paragraph](./paragraph/) na [BaseSlide](../../aspose.slides/baseslide/). |

## Poznámky



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

## Viz také

* jmenný prostor [Aspose::Slides::LowCode](../)
* Knihovna [Aspose.Slides](../../)