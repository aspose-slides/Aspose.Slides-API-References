---
title: set_DisableFontLigatures()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta un valore che indica se il testo viene visualizzato senza utilizzare legature. Quando impostato su true, le legature saranno disabilitate nell'output generato. Per impostazione predefinita, questa proprietà è impostata su false.
type: docs
weight: 105
url: /it/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) metodo


Imposta un valore che indica se il testo viene visualizzato senza utilizzare legature. Quando impostato su **true**, le legature saranno disabilitate nell'output generato. Per impostazione predefinita, questa proprietà è impostata su **false**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
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