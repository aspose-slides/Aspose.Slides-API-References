---
title: get_DisableFontLigatures()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un valore che indica se il testo viene visualizzato senza utilizzare le legature. Quando impostato su true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su false.
type: docs
weight: 131
url: /it/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() metodo

Ottiene un valore che indica se il testo viene visualizzato senza utilizzare legature. Quando impostato su **true**, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su **false**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## Osservazioni

Esempio:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Disabilita le legature nella resa del testo

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Vedi anche

* Classe [Html5Options](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)