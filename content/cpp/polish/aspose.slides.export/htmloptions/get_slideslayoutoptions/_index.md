---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides dla C++ - referencja API
description: Pobiera tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji ISlidesLayoutOptions.
type: docs
weight: 1
url: /pl/aspose.slides.export/htmloptions/get_slideslayoutoptions/
---
## HtmlOptions::get_SlidesLayoutOptions() method

Pobiera tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::HtmlOptions::get_SlidesLayoutOptions() override
```

## Uwagi

Przykład:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klasa [HtmlOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)