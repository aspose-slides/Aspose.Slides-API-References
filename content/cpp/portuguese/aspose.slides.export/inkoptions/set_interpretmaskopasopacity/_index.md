---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ Referência da API
description: Usa a operação ROP ou Opacidade para renderizar o pincel.
type: docs
weight: 40
url: /pt/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) método


Usa a operação ROP ou Opacidade para renderizar o pincel.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
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

## Veja Também

* Classe [InkOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)