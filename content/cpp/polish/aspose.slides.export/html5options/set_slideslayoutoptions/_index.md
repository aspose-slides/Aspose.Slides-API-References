---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji ISlidesLayoutOptions.
type: docs
weight: 170
url: /pl/aspose.slides.export/html5options/set_slideslayoutoptions/
---
## Html5Options::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metoda


Ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::Html5Options::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klasa [Html5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)