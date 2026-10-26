---
title: set_HideInk()
second_title: Referência da API Aspose.Slides para C++
description: Mostra ou oculta elementos Ink no documento exportado.
type: docs
weight: 14
url: /pt/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) método


Mostra ou oculta elementos [Ink](../../../aspose.slides.ink/) no documento exportado.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
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

## Veja Também

* Classe [InkOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)