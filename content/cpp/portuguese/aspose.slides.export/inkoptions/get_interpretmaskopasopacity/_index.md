---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides para C++ Referência da API
description: Usa a operação ROP ou Opacidade para renderizar o pincel.
type: docs
weight: 27
url: /pt/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() method

Usa operação ROP ou Opacidade para renderizar o pincel.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
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

* Classe [InkOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)