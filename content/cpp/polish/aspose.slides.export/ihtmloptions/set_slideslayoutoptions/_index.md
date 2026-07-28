---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji ISlidesLayoutOptions.
type: docs
weight: 222
url: /pl/aspose.slides.export/ihtmloptions/set_slideslayoutoptions/
---
## IHtmlOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metoda


Ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klasa [IHtmlOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)