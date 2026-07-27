---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides para C++ Referência da API
description: Usa a operação ROP ou Opacidade para renderizar o pincel.
type: docs
weight: 40
url: /pt/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) método


Usa a operação ROP ou Opacidade para renderizar o pincel.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## Observações


O valor padrão é verdadeiro. 

O próximo exemplo demonstra como definir usando ROP para exportar elementos [Ink](../../../aspose.slides.ink/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Ver Também

* Classe [IInkOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)