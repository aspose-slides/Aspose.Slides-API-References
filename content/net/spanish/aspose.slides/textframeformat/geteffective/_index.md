---
title: GetEffective
second_title: Aspose.Sildes para .NET Referencia de API
description: Obtiene datos de formato efectivo del marco de texto con la herencia aplicada.
type: docs
weight: 170
url: /es/aspose.slides/textframeformat/geteffective/
---

## Método TextFrameFormat.GetEffective

Obtiene datos de formato efectivo del marco de texto con la herencia aplicada.

```csharp
public ITextFrameFormatEffectiveData GetEffective()
```

### Valor de Retorno

Un [`ITextFrameFormatEffectiveData`](../../itextframeformateffectivedata).

### Ejemplos

Este ejemplo demuestra cómo obtener algunas de las propiedades de formato efectivo del marco de texto.

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
    Console.WriteLine("   Izquierda: " + effectiveTextFrameFormat.MarginLeft);
    Console.WriteLine("   Arriba: " + effectiveTextFrameFormat.MarginTop);
    Console.WriteLine("   Derecha: " + effectiveTextFrameFormat.MarginRight);
    Console.WriteLine("   Abajo: " + effectiveTextFrameFormat.MarginBottom);
}
```

### También Vea

* interface [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata)
* class [TextFrameFormat](../../textframeformat)
* namespace [Aspose.Slides](../../textframeformat)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->