---
title: get_DisableFontLigatures()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un valore che indica se il testo viene visualizzato senza utilizzare le legature. Quando impostato su true, le legature saranno disabilitate nell'output visualizzato. Per impostazione predefinita, questa proprietà è impostata su false.
type: docs
weight: 92
url: /it/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() metodo

Restituisce un valore che indica se il testo viene visualizzato senza utilizzare le legature. Quando impostato su **true**, le legature saranno disabilitate nell'output visualizzato. Per impostazione predefinita, questa proprietà è impostata su **false**.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## Osservazioni

Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Disabilita le legature nella resa del testo

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Vedi anche

* Classe [HtmlOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)