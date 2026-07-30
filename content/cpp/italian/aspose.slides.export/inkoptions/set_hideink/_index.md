---
title: set_HideInk()
second_title: Riferimento API Aspose.Slides per C++
description: Mostra o nasconde gli elementi Ink nel documento esportato.
type: docs
weight: 14
url: /it/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) metodo

Mostra o nasconde gli elementi [Ink](../../../aspose.slides.ink/) nel documento esportato.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## Note

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