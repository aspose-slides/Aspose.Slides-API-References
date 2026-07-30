---
title: set_DisableFontLigatures()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta un valore che indica se il testo viene renderizzato senza utilizzare le legature. Quando impostato su true, le legature saranno disattivate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su false.
type: docs
weight: 339
url: /it/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISVGOptions::set_DisableFontLigatures(bool) metodo


Imposta un valore che indica se il testo viene visualizzato senza utilizzare le legature. Quando impostato su **true**, le legature saranno disattivate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su **false**.

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
```

## Osservazioni


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