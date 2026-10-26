---
title: get_InterpretMaskOpAsOpacity()
second_title: Riferimento API di Aspose.Slides per C++
description: Utilizza l'operazione ROP o Opacity per il rendering del pennello.
type: docs
weight: 27
url: /it/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() metodo


Utilizza l'operazione ROP o Opacity per il rendering del pennello.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## Osservazioni


Il valore predefinito è true. 

Il prossimo esempio dimostra come impostare utilizzando ROP per l'esportazione degli elementi [Ink](../../../aspose.slides.ink/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Vedi anche

* Classe [IInkOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)