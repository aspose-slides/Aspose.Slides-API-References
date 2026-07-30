---
title: get_HideInk()
second_title: Riferimento API Aspose.Slides per C++
description: Mostra o nasconde gli elementi Ink nel documento esportato.
type: docs
weight: 1
url: /it/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() metodo


Mostra o nasconde gli elementi [Ink](../../../aspose.slides.ink/) nel documento esportato.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
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

* Classe [InkOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)