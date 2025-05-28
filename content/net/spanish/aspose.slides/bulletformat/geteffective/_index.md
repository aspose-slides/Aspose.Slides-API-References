---
title: GetEffective
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene datos efectivos de formato de viñetas con la herencia aplicada.
type: docs
weight: 120
url: /es/aspose.slides/bulletformat/geteffective/
---

## Método BulletFormat.GetEffective

Obtiene datos efectivos de formato de viñetas con la herencia aplicada.

```csharp
public IBulletFormatEffectiveData GetEffective()
```

### Valor de Retorno

Un [`IBulletFormatEffectiveData`](../../ibulletformateffectivedata).

### Ejemplos

Este ejemplo demuestra cómo obtener algunas propiedades efectivas del formato de viñetas.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	IAutoShape shape = pres.Slides[0].Shapes[0] as IAutoShape;
	IBulletFormatEffectiveData effectiveBulletFormat = shape.TextFrame.Paragraphs[0].ParagraphFormat.Bullet.GetEffective();

	Console.WriteLine("Tipo de viñeta: " + effectiveBulletFormat.Type);
	if (effectiveBulletFormat.Type == BulletType.Numbered)
	{
	    Console.WriteLine("Estilo numerado: " + effectiveBulletFormat.NumberedBulletStyle);
	    Console.WriteLine("Número inicial: " + effectiveBulletFormat.NumberedBulletStartWith);
	}
}
```

### Ver También

* interfaz [IBulletFormatEffectiveData](../../ibulletformateffectivedata)
* clase [BulletFormat](../../bulletformat)
* espacio de nombres [Aspose.Slides](../../bulletformat)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->