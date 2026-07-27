---
title: set_InterpretMaskOpAsOpacity()
second_title: Referencia de API de Aspose.Slides para C++
description: Utiliza la operación ROP o Opacity para renderizar el pincel.
type: docs
weight: 40
url: /es/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) método


Utiliza la operación ROP o Opacity para renderizar el pincel.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## Observaciones


El valor predeterminado es true. 

El siguiente ejemplo muestra cómo establecer usando ROP para exportar elementos [Ink](../../../aspose.slides.ink/): 
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