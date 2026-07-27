---
title: ForEach
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa un grupo de métodos destinados a iterar sobre diferentes objetos modelo Presentation. Estos métodos pueden ser útiles si necesita iterar y cambiar el formato o contenido de algunos elementos de Presentation, por ejemplo, cambiar el formato de cada porción.
type: docs
weight: 40
url: /es/aspose.slides.lowcode/foreach/
---
## Clase ForEach


Representa un grupo de métodos destinado a iterar sobre diferentes objetos modelo [Presentation](../../aspose.slides/presentation/). Estos métodos pueden ser útiles si necesita iterar y cambiar el formato o el contenido de algunos elementos [Presentation](../../aspose.slides/presentation/), por ejemplo, cambiar el formato de cada porción.

```cpp
class ForEach
```

## Métodos

| Método | Descripción |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Itera cada [ForEach::LayoutSlide](./layoutslide/) en el [Presentation](../../aspose.slides/presentation/). |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Itera cada [ForEach::MasterSlide](./masterslide/) en el [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Itera cada [ForEach::Paragraph](./paragraph/) en el [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Itera cada [ForEach::Paragraph](./paragraph/) en el [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Itera cada [ForEach::Portion](./portion/) en el [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Itera cada [ForEach::Portion](./portion/) en el [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Itera cada [ForEach::Shape](./shape/) en el [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Itera cada [ForEach::Shape](./shape/) en el [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Itera cada [ForEach::Shape](./shape/) en el [BaseSlide](../../aspose.slides/baseslide/). |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Itera cada [ForEach::Slide](./slide/) en el [Presentation](../../aspose.slides/presentation/). |

## Tipos definidos

| Tipo definido | Descripción |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Callback que se invocará para cada [ForEach::Slide](./slide/) en el [Presentation](../../aspose.slides/presentation/). |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Callback que se invocará para cada [ForEach::MasterSlide](./masterslide/) en el [Presentation](../../aspose.slides/presentation/). |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Callback que se invocará para cada [ForEach::LayoutSlide](./layoutslide/) en el [Presentation](../../aspose.slides/presentation/). |
| [ForEachShapeCallback](./foreachshapecallback/) | Callback que se invocará para cada [ForEach::Shape](./shape/) en el [Presentation](../../aspose.slides/presentation/). |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Callback que se invocará para cada [ForEach::Paragraph](./paragraph/) en el [BaseSlide](../../aspose.slides/baseslide/). |
| [ForEachPortionCallback](./foreachportioncallback/) | Callback que se invocará para cada [ForEach::Portion](./portion/) en el [ForEach::Paragraph](./paragraph/) sobre el [BaseSlide](../../aspose.slides/baseslide/). |

## Observaciones



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

## Ver también

* Espacio de nombres [Aspose::Slides::LowCode](../)
* Biblioteca [Aspose.Slides](../../)