---
title: get_DisableFontLigatures()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene un valore che indica se il testo viene visualizzato senza utilizzare le legature. Quando impostato su true, le legature saranno disabilitate nell'output visualizzato. Per impostazione predefinita, questa proprietà è impostata su false.
type: docs
weight: 326
url: /it/aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISSVGOptions::get_DisableFontLigatures() metodo


Ottiene un valore che indica se il testo viene visualizzato senza utilizzare le legature. Quando impostato su **true**, le legature saranno disabilitate nell'output visualizzato. Per impostazione predefinita, questa proprietà è impostata su **false**.

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
```

## Note


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Disabilita le legature nella resa del testo

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Vedi anche

* Classe [ISVGOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)