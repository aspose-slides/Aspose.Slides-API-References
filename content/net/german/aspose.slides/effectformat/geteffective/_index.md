---
title: GetEffective
second_title: Aspose.Slides für .NET API-Referenz
description: Ruft die effektiven Effektformatierungsdaten ab, bei denen die Vererbung angewendet wurde.
type: docs
weight: 250
url: /de/aspose.slides/effectformat/geteffective/
---

## EffectFormat.GetEffective Methode

Ruft die effektiven Effektformatierungsdaten ab, bei denen die Vererbung angewendet wurde.

```csharp
public IEffectFormatEffectiveData GetEffective()
```

### Rückgabewert

Ein [`IEffectFormatEffectiveData`](../../ieffectformateffectivedata).

### Beispiele

Dieses Beispiel demonstriert das Abrufen einiger effektiver Eigenschafteneigenschaften einer Form.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	IEffectFormatEffectiveData effectiveEffectFormat = pres.Slides[0].Shapes[0].EffectFormat.GetEffective();

	if (effectiveEffectFormat.IsNoEffects)
	{
		Console.WriteLine("Die Form hat keine Effekte angewendet.");
	}
	else
	{
		if (effectiveEffectFormat.BlurEffect != null)
			Console.WriteLine("Unschärfeneffekt-Radius: " + effectiveEffectFormat.BlurEffect.Radius);
		if (effectiveEffectFormat.FillOverlayEffect != null)
			Console.WriteLine("Füllüberlagerungseffekt Fülltyp: " + effectiveEffectFormat.FillOverlayEffect.FillFormat.FillType);
		if (effectiveEffectFormat.GlowEffect != null)
			Console.WriteLine("Glüheffekt Farbe: " + effectiveEffectFormat.GlowEffect.Color);
		if (effectiveEffectFormat.InnerShadowEffect != null)
			Console.WriteLine("Innenschattenfarbe des Schattens: " + effectiveEffectFormat.InnerShadowEffect.ShadowColor);
		if (effectiveEffectFormat.OuterShadowEffect != null)
			Console.WriteLine("Außenschattenfarbe des Schattens: " + effectiveEffectFormat.OuterShadowEffect.ShadowColor);
		if (effectiveEffectFormat.PresetShadowEffect != null)
			Console.WriteLine("Voreingestellter Schattenschattenfarbe: " + effectiveEffectFormat.PresetShadowEffect.ShadowColor);
		if (effectiveEffectFormat.ReflectionEffect != null)
			Console.WriteLine("Reflektionseffekt Abstand: " + effectiveEffectFormat.ReflectionEffect.Distance);
		if (effectiveEffectFormat.SoftEdgeEffect != null)
			Console.WriteLine("Weichkanteneffekt-Radius: " + effectiveEffectFormat.SoftEdgeEffect.Radius);
	}
}
```

### Siehe auch

* Schnittstelle [IEffectFormatEffectiveData](../../ieffectformateffectivedata)
* Klasse [EffectFormat](../../effectformat)
* Namespace [Aspose.Slides](../../effectformat)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->