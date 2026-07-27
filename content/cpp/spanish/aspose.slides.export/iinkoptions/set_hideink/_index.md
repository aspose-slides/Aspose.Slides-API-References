---
title: set_HideInk()
second_title: Referencia de API de Aspose.Slides para C++
description: Muestra u oculta elementos Ink en el documento exportado.
type: docs
weight: 14
url: /es/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) método

Muestra u oculta [Ink](../../../aspose.slides.ink/) elementos en el documento exportado.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## Observaciones

El valor predeterminado es false.

El siguiente ejemplo demuestra cómo ocultar [Ink](../../../aspose.slides.ink/) elementos en el documento PDF exportado:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Ver también

* Clase [IInkOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)