---
title: GetEffective
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene datos de formato de porción efectivo con la herencia aplicada.
type: docs
weight: 70
url: /es/net/aspose.slides/portionformat/geteffective/
---
## PortionFormat.GetEffective method

Obtiene datos de formato de porción efectivo con la herencia aplicada.

```csharp
public IPortionFormatEffectiveData GetEffective()
```

### Valor_devuelto

A[`IPortionFormatEffectiveData`](../../iportionformateffectivedata).

### Ejemplos

Este ejemplo demuestra cómo obtener algunas propiedades de formato de porción efectivas.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	IAutoShape shape = pres.Slides[0].Shapes[0] as IAutoShape;
	IPortionFormatEffectiveData effectivePortionFormat = shape.TextFrame.Paragraphs[0].Portions[0].PortionFormat.GetEffective();

	Console.WriteLine("Latin font: " + effectivePortionFormat.LatinFont.FontName);
	Console.WriteLine("Font height: " + effectivePortionFormat.FontHeight);
	Console.WriteLine("Fill type: " + effectivePortionFormat.FillFormat.FillType);
}
```

### Ver también

* interface [IPortionFormatEffectiveData](../../iportionformateffectivedata)
* class [PortionFormat](../../portionformat)
* espacio de nombres [Aspose.Slides](../../portionformat)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->