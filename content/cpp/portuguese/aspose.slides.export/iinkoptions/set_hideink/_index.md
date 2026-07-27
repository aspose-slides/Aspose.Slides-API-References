---
title: set_HideInk()
second_title: Referência da API Aspose.Slides para C++
description: Exibe ou oculta elementos Ink no documento exportado.
type: docs
weight: 14
url: /pt/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) método


Exibe ou oculta elementos [Ink](../../../aspose.slides.ink/) no documento exportado.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
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
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)