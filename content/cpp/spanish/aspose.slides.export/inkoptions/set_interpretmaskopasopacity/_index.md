---
title: set_InterpretMaskOpAsOpacity()
second_title: Referencia de API de Aspose.Slides para C++
description: Utiliza la operación ROP u Opacity para renderizar la brocha.
type: docs
weight: 40
url: /es/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) método

Utiliza la operación ROP u Opacity para renderizar la brocha.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## Observaciones

El valor predeterminado es true.

El siguiente ejemplo muestra cómo configurar usando ROP para exportar elementos [Ink](../../../aspose.slides.ink/):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Ver también

* Clase [InkOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)