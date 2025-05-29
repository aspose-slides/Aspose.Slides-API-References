---
title: GetEffective
second_title: Aspose.Slides para .NET Referencia de API
description: Obtiene los datos de formato de línea efectivos con la herencia aplicada.
type: docs
weight: 190
url: /es/aspose.slides/lineformat/geteffective/
---

## Método LineFormat.GetEffective

Obtiene los datos de formato de línea efectivos con la herencia aplicada.

```csharp
public ILineFormatEffectiveData GetEffective()
```

### Valor de retorno

Un [`ILineFormatEffectiveData`](../../ilineformateffectivedata).

### Ejemplos

Este ejemplo demuestra cómo obtener las propiedades efectivas del formato de línea de una forma.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	ILineFormatEffectiveData effectiveLineFormat = pres.Slides[0].Shapes[0].LineFormat.GetEffective();

	Console.WriteLine("Estilo: " + effectiveLineFormat.Style);
	Console.WriteLine("Ancho: " + effectiveLineFormat.Width);
	Console.WriteLine("Tipo de relleno: " + effectiveLineFormat.FillFormat.FillType);
}
```

### Véase también

* interfaz [ILineFormatEffectiveData](../../ilineformateffectivedata)
* clase [LineFormat](../../lineformat)
* espacio de nombres [Aspose.Slides](../../lineformat)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->