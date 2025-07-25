---
title: GetEffective
second_title: Aspose.Sildes para referencia de API de .NET
description: Obtiene datos de fondo efectivos con la herencia aplicada.
type: docs
weight: 80
url: /es/aspose.slides/background/geteffective/
---

## Método Background.GetEffective

Obtiene datos de fondo efectivos con la herencia aplicada.

```csharp
public IBackgroundEffectiveData GetEffective()
```

### Valor de retorno

Un [`IBackgroundEffectiveData`](../../ibackgroundeffectivedata).

### Ejemplos

Este ejemplo demuestra cómo obtener propiedades de fondo efectivas.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	IBackgroundEffectiveData effectiveBackground = pres.Slides[0].Background.GetEffective();

	Console.WriteLine("Tipo de relleno de fondo: " + effectiveBackground.FillFormat.FillType);
	Console.WriteLine("Efectos aplicados: " + !effectiveBackground.EffectFormat.IsNoEffects);
}
```

### Véase también

* interfaz [IBackgroundEffectiveData](../../ibackgroundeffectivedata)
* clase [Background](../../background)
* espacio de nombres [Aspose.Slides](../../background)
* ensamblado [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->