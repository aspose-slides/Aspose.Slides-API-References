---
title: set_InterpretMaskOpAsOpacity()
second_title: Riferimento API Aspose.Slides per C++
description: Utilizza l'operazione ROP o Opacità per il rendering del pennello.
type: docs
weight: 40
url: /it/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) metodo

Utilizza l'operazione ROP o Opacità per il rendering del pennello.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## Osservazioni

Il valore predefinito è true. 

Il prossimo esempio dimostra come impostare l'uso di ROP per esportare gli elementi [Ink](../../../aspose.slides.ink/): 
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