---
title: get_SlidesLayoutOptions()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la modalità in cui le diapositive vengono posizionate nella pagina durante l'esportazione di una presentazione ISlidesLayoutOptions.
type: docs
weight: 1
url: /it/aspose.slides.export/pdfoptions/get_slideslayoutoptions/
---
## PdfOptions::get_SlidesLayoutOptions() metodo

Restituisce la modalità in cui le diapositive vengono posizionate nella pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::PdfOptions::get_SlidesLayoutOptions() override
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [ISlidesLayoutOptions](../../islideslayoutoptions/)
* classe [PdfOptions](../)
* namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)