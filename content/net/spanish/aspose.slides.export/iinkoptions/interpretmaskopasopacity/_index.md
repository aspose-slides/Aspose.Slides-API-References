---
title: InterpretarMaskOpComoOpacidad
second_title: Referencia de API de Aspose.Slides para .NET
description: Utiliza la operación ROP o la Opacidad para renderizar el pincel.
type: docs
weight: 20
url: /es/aspose.slides.export/iinkoptions/interpretmaskopasopacity/
---

## Propiedad IInkOptions.InterpretMaskOpAsOpacity

Utiliza la operación ROP o la Opacidad para renderizar el pincel.

```csharp
public bool InterpretMaskOpAsOpacity { get; set; }
```

### Comentarios

El valor predeterminado es verdadero.

### Ejemplos

El siguiente ejemplo demuestra cómo establecer el uso de ROP para exportar elementos de tinta:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    PdfOptions pdfOptions = new PdfOptions();
    pdfOptions.InkOptions.InterpretMaskOpAsOpacity = false;
    pres.Save("output.pptx", SaveFormat.Pdf, pdfOptions);
}
```

### Ver También

* interfaz [IInkOptions](../../iinkoptions)
* espacio de nombres [Aspose.Slides.Export](../../iinkoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->