---
title: get_InterpretMaskOpAsOpacity()
second_title: Riferimento API di Aspose.Slides per C++
description: Utilizza l'operazione ROP o l'opacità per il rendering del pennello.
type: docs
weight: 27
url: /it/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() metodo

Utilizza l'operazione ROP o opacità per il rendering del pennello.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## Note

Il valore predefinito è true. 

Il prossimo esempio dimostra come impostare usando ROP per esportare gli elementi [Ink](../../../aspose.slides.ink/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Vedi anche

* Classe [InkOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)