---
title: GetEffective
second_title: Aspose.Sildes für .NET API Referenz
description: Ruft effektive Hintergrunddaten mit der angewendeten Vererbung ab.
type: docs
weight: 80
url: /de/aspose.slides/background/geteffective/
---

## Background.GetEffective Methode

Ruft effektive Hintergrunddaten mit der angewendeten Vererbung ab.

```csharp
public IBackgroundEffectiveData GetEffective()
```

### Rückgabewert

Ein [`IBackgroundEffectiveData`](../../ibackgroundeffectivedata).

### Beispiele

Dieses Beispiel demonstriert das Abrufen effektiver Hintergrundeigenschaften.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	IBackgroundEffectiveData effectiveBackground = pres.Slides[0].Background.GetEffective();

	Console.WriteLine("Hintergrundfülltyp: " + effectiveBackground.FillFormat.FillType);
	Console.WriteLine("Angewandte Effekte: " + !effectiveBackground.EffectFormat.IsNoEffects);
}
```

### Siehe auch

* interface [IBackgroundEffectiveData](../../ibackgroundeffectivedata)
* class [Background](../../background)
* namespace [Aspose.Slides](../../background)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->