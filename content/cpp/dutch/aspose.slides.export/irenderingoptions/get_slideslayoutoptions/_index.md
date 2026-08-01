---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de modus op waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie ISlidesLayoutOptions.
type: docs
weight: 1
url: /nl/aspose.slides.export/irenderingoptions/get_slideslayoutoptions/
---
## IRenderingOptions::get_SlidesLayoutOptions() methode


Haalt de modus op waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IRenderingOptions::get_SlidesLayoutOptions()=0
```

## Opmerkingen


Voorbeeld: 
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

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klasse [IRenderingOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)