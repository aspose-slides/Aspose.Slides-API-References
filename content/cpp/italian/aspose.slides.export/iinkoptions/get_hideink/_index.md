---
title: get_HideInk()
second_title: Riferimento API di Aspose.Slides per C++
description: Mostra o nasconde gli elementi Ink nel documento esportato.
type: docs
weight: 1
url: /it/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() metodo

Mostra o nasconde gli elementi [Ink](../../../aspose.slides.ink/) nel documento esportato.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## Osservazioni

Il valore predefinito è false. 

Il prossimo esempio dimostra come nascondere gli elementi [Ink](../../../aspose.slides.ink/) nel documento PDF esportato: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Vedi anche

* Classe [IInkOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)