---
title: get_InterpretMaskOpAsOpacity()
second_title: Referência da API Aspose.Slides para C++
description: Usa a operação ROP ou Opacidade para renderizar o pincel.
type: docs
weight: 27
url: /pt/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() método


Usa a operação ROP ou Opacidade para renderizar o pincel.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## Observações


O valor padrão é true. 

O próximo exemplo demonstra como definir usando ROP para exportar elementos [Ink](../../../aspose.slides.ink/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Veja também

* Classe [IInkOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)