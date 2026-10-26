---
title: ForEach
second_title: Справочник API Aspose.Slides для C++
description: Представляет группу методов, предназначенных для итерации по различным объектам модели Presentation. Эти методы могут быть полезны, если вам нужно выполнять итерацию и изменять форматирование или содержимое некоторых элементов Presentation', например изменять форматирование каждой части.
type: docs
weight: 40
url: /ru/aspose.slides.lowcode/foreach/
---
## ForEach класс

Представляет группу методов, предназначенных для итерации по различным объектам модели [Presentation](../../aspose.slides/presentation/). Эти методы могут быть полезны, если вам нужно выполнять итерацию и изменять форматирование или содержимое некоторых элементов [Presentation](../../aspose.slides/presentation/), например изменять форматирование каждой части.

```cpp
class ForEach
```

## Методы

| Method | Description |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Итерировать каждый [ForEach::LayoutSlide](./layoutslide/) в [Presentation](../../aspose.slides/presentation/). |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Итерировать каждый [ForEach::MasterSlide](./masterslide/) в [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Итерировать каждый [ForEach::Paragraph](./paragraph/) в [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Итерировать каждый [ForEach::Paragraph](./paragraph/) в [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Итерировать каждый [ForEach::Portion](./portion/) в [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Итерировать каждый [ForEach::Portion](./portion/) в [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Итерировать каждый [ForEach::Shape](./shape/) в [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Итерировать каждый [ForEach::Shape](./shape/) в [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Итерировать каждый [ForEach::Shape](./shape/) в [BaseSlide](../../aspose.slides/baseslide/). |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Итерировать каждый [ForEach::Slide](./slide/) в [Presentation](../../aspose.slides/presentation/). |

## Типedefs

| Typedef | Description |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Обратный вызов, который будет вызываться для каждого [ForEach::Slide](./slide/) в [Presentation](../../aspose.slides/presentation/). |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Обратный вызов, который будет вызываться для каждого [ForEach::MasterSlide](./masterslide/) в [Presentation](../../aspose.slides/presentation/). |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Обратный вызов, который будет вызываться для каждого [ForEach::LayoutSlide](./layoutslide/) в [Presentation](../../aspose.slides/presentation/). |
| [ForEachShapeCallback](./foreachshapecallback/) | Обратный вызов, который будет вызываться для каждого [ForEach::Shape](./shape/) в [Presentation](../../aspose.slides/presentation/). |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Обратный вызов, который будет вызываться для каждого [ForEach::Paragraph](./paragraph/) на [BaseSlide](../../aspose.slides/baseslide/). |
| [ForEachPortionCallback](./foreachportioncallback/) | Обратный вызов, который будет вызываться для каждого [ForEach::Portion](./portion/) в [ForEach::Paragraph](./paragraph/) на [BaseSlide](../../aspose.slides/baseslide/). |

## Примечания



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

## См. также

* Пространство имён [Aspose::Slides::LowCode](../)
* Библиотека [Aspose.Slides](../../)