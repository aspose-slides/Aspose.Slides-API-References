---
title: get_InterpretMaskOpAsOpacity()
second_title: Referencia de API de Aspose.Slides para C++
description: Utiliza la operación ROP u Opacidad para renderizar el pincel.
type: docs
weight: 27
url: /es/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() método


Utiliza la operación ROP u Opacidad para renderizar el pincel.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
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