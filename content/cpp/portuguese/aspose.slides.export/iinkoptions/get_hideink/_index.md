---
title: get_HideInk()
second_title: Referência da API Aspose.Slides for C++
description: Exibe ou oculta elementos Ink no documento exportado.
type: docs
weight: 1
url: /pt/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() método

Exibe ou oculta elementos [Ink](../../../aspose.slides.ink/) no documento exportado.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## Observações

O valor padrão é false. 

O próximo exemplo demonstra como ocultar elementos [Ink](../../../aspose.slides.ink/) no documento PDF exportado: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Ver também

* Classe [IInkOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)