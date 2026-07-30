---
title: set_InterpretMaskOpAsOpacity()
second_title: Riferimento API Aspose.Slides per C++
description: Utilizza l'operazione ROP o l'opacità per il rendering del pennello.
type: docs
weight: 40
url: /it/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) metodo


Utilizza l'operazione ROP o l'opacità per il rendering del pennello.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
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

* Classe [IInkOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)