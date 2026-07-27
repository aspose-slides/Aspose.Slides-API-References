---
title: set_SlidesLayoutOptions()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece el modo en que las diapositivas se colocan en la página al exportar una presentación ISlidesLayoutOptions.
type: docs
weight: 14
url: /es/aspose.slides.export/renderingoptions/set_slideslayoutoptions/
---
## RenderingOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) método

Establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::RenderingOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## Observaciones

Ejemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);
slidesLayoutOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> handoutSlides = pres->GetThumbnails(options);
for (int32_t index = 0; index < handoutSlides->get_Length(); index++)
{
    auto handoutSlide = handoutSlides[index];
    handoutSlide->Save(System::String::Format(u"handout-{0}.png", index));
}
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Clase [RenderingOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)