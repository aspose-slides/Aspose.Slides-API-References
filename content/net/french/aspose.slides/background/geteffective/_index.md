---
title: GetEffective
second_title: Référence de l'API Aspose.Slides pour .NET
description: Obtient les données darrièreplan effectives avec lhéritage appliqué.
type: docs
weight: 80
url: /fr/aspose.slides/background/geteffective/
---
## Background.GetEffective method

Obtient les données d'arrière-plan effectives avec l'héritage appliqué.

```csharp
public IBackgroundEffectiveData GetEffective()
```

### Return_Value

UN[`IBackgroundEffectiveData`](../../ibackgroundeffectivedata).

### Exemples

Cet exemple montre comment obtenir des propriétés d'arrière-plan efficaces.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	IBackgroundEffectiveData effectiveBackground = pres.Slides[0].Background.GetEffective();

	Console.WriteLine("Background fill type: " + effectiveBackground.FillFormat.FillType);
	Console.WriteLine("Any effects applied: " + !effectiveBackground.EffectFormat.IsNoEffects);
}
```

### Voir également

* interface [IBackgroundEffectiveData](../../ibackgroundeffectivedata)
* class [Background](../../background)
* espace de noms [Aspose.Slides](../../background)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
