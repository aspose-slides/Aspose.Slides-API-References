---
title: get_InterpretMaskOpAsOpacity()
second_title: Referencia de la API de Aspose.Slides para C++
description: Utiliza la operación ROP o Opacidad para renderizar el pincel.
type: docs
weight: 27
url: /es/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() método


Utiliza la operación ROP o Opacity para renderizar el pincel.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## Observaciones


El valor predeterminado es true.

El siguiente ejemplo demuestra cómo configurar usando ROP para exportar elementos [Ink](../../../aspose.slides.ink/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Ver también

* Clase [IInkOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)