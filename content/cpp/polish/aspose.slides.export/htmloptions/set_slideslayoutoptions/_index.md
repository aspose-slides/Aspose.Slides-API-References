---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides dla C++ – odwołanie API
description: Ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji ISlidesLayoutOptions.
type: docs
weight: 14
url: /pl/aspose.slides.export/htmloptions/set_slideslayoutoptions/
---
## HtmlOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metoda


Ustawia tryb, w którym slajdy są umieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::HtmlOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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