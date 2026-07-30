---
title: set_DisableFontLigatures()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta un valore che indica se il testo è renderizzato senza utilizzare le legature. Quando impostato su true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su false.
type: docs
weight: 196
url: /it/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) metodo

Imposta un valore che indica se il testo è visualizzato senza utilizzare le legature. Quando impostato su **true**, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su **false**.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
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

* Classe [IHtmlOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)