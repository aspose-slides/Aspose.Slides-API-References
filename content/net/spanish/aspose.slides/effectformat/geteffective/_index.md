---
title: GetEffective
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene datos de formato de efecto efectivo con la herencia aplicada.
type: docs
weight: 250
url: /es/aspose.slides/effectformat/geteffective/
---
## EffectFormat.GetEffective method

Obtiene datos de formato de efecto efectivo con la herencia aplicada.

```csharp
public IEffectFormatEffectiveData GetEffective()
```

### Valor_devuelto

A[`IEffectFormatEffectiveData`](../../ieffectformateffectivedata).

### Ejemplos

Este ejemplo demuestra cómo obtener algunas de las propiedades de efectos efectivos de la forma.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	IEffectFormatEffectiveData effectiveEffectFormat = pres.Slides[0].Shapes[0].EffectFormat.GetEffective();

	if (effectiveEffectFormat.IsNoEffects)
	{
		Console.WriteLine("The shape has not effects applied.");
	}
	else
	{
		if (effectiveEffectFormat.BlurEffect != null)
			Console.WriteLine("Blur effect radius: " + effectiveEffectFormat.BlurEffect.Radius);
		if (effectiveEffectFormat.FillOverlayEffect != null)
			Console.WriteLine("Fill overlay effect fill type: " + effectiveEffectFormat.FillOverlayEffect.FillFormat.FillType);
		if (effectiveEffectFormat.GlowEffect != null)
			Console.WriteLine("Glow effect color: " + effectiveEffectFormat.GlowEffect.Color);
		if (effectiveEffectFormat.InnerShadowEffect != null)
			Console.WriteLine("Inner shadow effect shadow color: " + effectiveEffectFormat.InnerShadowEffect.ShadowColor);
		if (effectiveEffectFormat.OuterShadowEffect != null)
			Console.WriteLine("Outer shadow effect shadow color: " + effectiveEffectFormat.OuterShadowEffect.ShadowColor);
		if (effectiveEffectFormat.PresetShadowEffect != null)
			Console.WriteLine("Preset shadow effect shadow color: " + effectiveEffectFormat.PresetShadowEffect.ShadowColor);
		if (effectiveEffectFormat.ReflectionEffect != null)
			Console.WriteLine("Reflection effect distance: " + effectiveEffectFormat.ReflectionEffect.Distance);
		if (effectiveEffectFormat.SoftEdgeEffect != null)
			Console.WriteLine("Soft edge effect radius: " + effectiveEffectFormat.SoftEdgeEffect.Radius);
	}
}
```

### Ver también

* interface [IEffectFormatEffectiveData](../../ieffectformateffectivedata)
* class [EffectFormat](../../effectformat)
* espacio de nombres [Aspose.Slides](../../effectformat)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
