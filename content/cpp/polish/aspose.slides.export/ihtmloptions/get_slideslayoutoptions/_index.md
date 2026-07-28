---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji ISlidesLayoutOptions.
type: docs
weight: 209
url: /pl/aspose.slides.export/ihtmloptions/get_slideslayoutoptions/
---
## IHtmlOptions::get_SlidesLayoutOptions() metoda


Pobiera tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IHtmlOptions::get_SlidesLayoutOptions()=0
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
* Library [Aspose.Slides](../../../)