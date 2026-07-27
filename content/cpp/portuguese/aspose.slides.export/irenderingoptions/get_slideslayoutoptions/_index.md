---
title: get_SlidesLayoutOptions()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o modo como os slides são posicionados na página ao exportar uma apresentação ISlidesLayoutOptions.
type: docs
weight: 1
url: /pt/aspose.slides.export/irenderingoptions/get_slideslayoutoptions/
---
## IRenderingOptions::get_SlidesLayoutOptions() método

Obtém o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IRenderingOptions::get_SlidesLayoutOptions()=0
```

## Observações

Exemplo: 
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

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Classe [IRenderingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)