---
title: get_SlidesLayoutOptions()
second_title: Riferimento API per Aspose.Slides per C++
description: Ottiene la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione ISlidesLayoutOptions.
type: docs
weight: 157
url: /it/aspose.slides.export/ihtml5options/get_slideslayoutoptions/
---
## IHtml5Options::get_SlidesLayoutOptions() metodo

Ottiene la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IHtml5Options::get_SlidesLayoutOptions()=0
```

## Osservazioni

Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Classe [IHtml5Options](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)