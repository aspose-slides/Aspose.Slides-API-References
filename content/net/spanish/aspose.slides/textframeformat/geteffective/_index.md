---
title: GetEffective
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene datos de formato de marco de texto efectivo con la herencia aplicada.
type: docs
weight: 170
url: /es/aspose.slides/textframeformat/geteffective/
---

## Método TextFrameFormat.GetEffective

Obtiene datos de formato de marco de texto efectivo con la herencia aplicada.

```csharp
public ITextFrameFormatEffectiveData GetEffective()
```

### Valor de retorno

Un [`ITextFrameFormatEffectiveData`](../../itextframeformateffectivedata).

### Ejemplos

Este ejemplo demuestra cómo obtener algunas propiedades efectivas de formato de marco de texto.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
    IAutoShape shape = pres.Slides[0].Shapes[0] as IAutoShape;
    ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.TextFrame.TextFrameFormat.GetEffective();
   
    Console.WriteLine("Tipo de anclaje: " + effectiveTextFrameFormat.AnchoringType);
    Console.WriteLine("Tipo de ajuste automático: " + effectiveTextFrameFormat.AutofitType);
    Console.WriteLine("Tipo de texto vertical: " + effectiveTextFrameFormat.TextVerticalType);
    Console.WriteLine("Márgenes");
    Console.WriteLine("   Izquierdo: " + effectiveTextFrameFormat.MarginLeft);
    Console.WriteLine("   Superior: " + effectiveTextFrameFormat.MarginTop);
    Console.WriteLine("   Derecho: " + effectiveTextFrameFormat.MarginRight);
    Console.WriteLine("   Inferior: " + effectiveTextFrameFormat.MarginBottom);
}
```

### Véase también

* interfaz [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata)
* clase [TextFrameFormat](../../textframeformat)
* espacio de nombres [Aspose.Slides](../../textframeformat)
* ensamblaje [Aspose.Slides](../../../) 

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->