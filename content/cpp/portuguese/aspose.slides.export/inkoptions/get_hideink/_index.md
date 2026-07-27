---
title: get_HideInk()
second_title: Aspose.Slides para C++ Referência da API
description: Exibe ou oculta elementos Ink no documento exportado.
type: docs
weight: 1
url: /pt/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() método


Exibe ou oculta [Ink](../../../aspose.slides.ink/) elementos no documento exportado.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## Observações


O valor padrão é false. 

O próximo exemplo demonstra como ocultar [Ink](../../../aspose.slides.ink/) elementos no documento PDF exportado: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Ver também

* Classe [InkOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)