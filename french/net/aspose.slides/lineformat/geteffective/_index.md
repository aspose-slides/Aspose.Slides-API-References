---
title: GetEffective
second_title: Référence de l'API Aspose.Slides pour .NET
description: Obtient les données de mise en forme de ligne effectives avec lhéritage appliqué.
type: docs
weight: 190
url: /fr/net/aspose.slides/lineformat/geteffective/
---
## LineFormat.GetEffective method

Obtient les données de mise en forme de ligne effectives avec l'héritage appliqué.

```csharp
public ILineFormatEffectiveData GetEffective()
```

### Return_Value

UN[`ILineFormatEffectiveData`](../../ilineformateffectivedata).

### Exemples

Cet exemple illustre l'obtention des propriétés de format de ligne efficaces de la forme.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	ILineFormatEffectiveData effectiveLineFormat = pres.Slides[0].Shapes[0].LineFormat.GetEffective();

	Console.WriteLine("Style: " + effectiveLineFormat.Style);
	Console.WriteLine("Width: " + effectiveLineFormat.Width);
	Console.WriteLine("Fill type: " + effectiveLineFormat.FillFormat.FillType);
}
```

### Voir également

* interface [ILineFormatEffectiveData](../../ilineformateffectivedata)
* class [LineFormat](../../lineformat)
* espace de noms [Aspose.Slides](../../lineformat)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->