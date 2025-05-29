---
title: GetEffective
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene datos de formato de relleno efectivos con la herencia aplicada.
type: docs
weight: 70
url: /es/aspose.slides/fillformat/geteffective/
---

## Método FillFormat.GetEffective

Obtiene datos de formato de relleno efectivos con la herencia aplicada.

```csharp
public IFillFormatEffectiveData GetEffective()
```

### Valor de retorno

Un [`IFillFormatEffectiveData`](../../ifillformateffectivedata).

### Ejemplos

Este ejemplo demuestra cómo obtener las propiedades de formato de relleno efectivo de una forma.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	IFillFormatEffectiveData effectiveFillFormat = pres.Slides[0].Shapes[0].FillFormat.GetEffective();

	Console.WriteLine("Tipo: " + effectiveFillFormat.FillType);
	switch (effectiveFillFormat.FillType)
	{
		case FillType.Solid:
			Console.WriteLine("Color de relleno: " + effectiveFillFormat.SolidFillColor);
			break;
		case FillType.Pattern:
			Console.WriteLine("Estilo de patrón: " + effectiveFillFormat.PatternFormat.PatternStyle);
			Console.WriteLine("Color frontal: " + effectiveFillFormat.PatternFormat.ForeColor);
			Console.WriteLine("Color de fondo: " + effectiveFillFormat.PatternFormat.BackColor);
			break;
		case FillType.Gradient:
			Console.WriteLine("Dirección del degradado: " + effectiveFillFormat.GradientFormat.GradientDirection);
			Console.WriteLine("Cantidad de paradas de degradado: " + effectiveFillFormat.GradientFormat.GradientStops.Count);
			break;
		case FillType.Picture:
			Console.WriteLine("Ancho de la imagen: " + effectiveFillFormat.PictureFillFormat.Picture.Image.Width);
			Console.WriteLine("Altura de la imagen: " + effectiveFillFormat.PictureFillFormat.Picture.Image.Height);
			break;
	}
}
```

### Véase también

* interfaz [IFillFormatEffectiveData](../../ifillformateffectivedata)
* clase [FillFormat](../../fillformat)
* espacio de nombres [Aspose.Slides](../../fillformat)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->