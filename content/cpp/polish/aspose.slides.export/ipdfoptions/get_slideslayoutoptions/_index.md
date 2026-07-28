---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides dla C++ – Odniesienie API
description: Pobiera tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji ISlidesLayoutOptions.
type: docs
weight: 365
url: /pl/aspose.slides.export/ipdfoptions/get_slideslayoutoptions/
---
## IPdfOptions::get_SlidesLayoutOptions() metoda


Pobiera tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IPdfOptions::get_SlidesLayoutOptions()=0
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klasa [IPdfOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)