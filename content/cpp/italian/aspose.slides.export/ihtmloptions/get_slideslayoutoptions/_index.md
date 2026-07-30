---
title: get_SlidesLayoutOptions()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione ISlidesLayoutOptions.
type: docs
weight: 209
url: /it/aspose.slides.export/ihtmloptions/get_slideslayoutoptions/
---
## IHtmlOptions::get_SlidesLayoutOptions() metodo

Ottiene la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IHtmlOptions::get_SlidesLayoutOptions()=0
```

## Note

Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Classe [IHtmlOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)