---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca tryb, w którym slajdy są umieszczane na stronie podczas eksportowania prezentacji ISlidesLayoutOptions.
type: docs
weight: 157
url: /pl/aspose.slides.export/ihtml5options/get_slideslayoutoptions/
---
## IHtml5Options::get_SlidesLayoutOptions() metoda


Zwraca tryb, w którym slajdy są umieszczane na stronie podczas eksportowania prezentacji [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IHtml5Options::get_SlidesLayoutOptions()=0
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klasa [IHtml5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)