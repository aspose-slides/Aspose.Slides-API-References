---
title: DefaultDelay
second_title: Référence de l'API Aspose.Slides pour .NET
description: Obtient ou définit le temps de retard par défaut ms. Cette valeur sera utilisée siAdvanceAfterTimeaspose.slides/islideshowtransition/advanceaftertime nest pas défini. La valeur par défaut est 1000.
type: docs
weight: 20
url: /fr/aspose.slides.export/igifoptions/defaultdelay/
---
## IGifOptions.DefaultDelay property

Obtient ou définit le temps de retard par défaut [ms]. Cette valeur sera utilisée si[`AdvanceAfterTime`](../../../aspose.slides/islideshowtransition/advanceaftertime) n'est pas défini. La valeur par défaut est 1000.

```csharp
public int DefaultDelay { get; set; }
```

### Exemples

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save("pres.gif", SaveFormat.Gif, new GifOptions { DefaultDelay = 2000 });
}
```

### Voir également

* interface [IGifOptions](../../igifoptions)
* espace de noms [Aspose.Slides.Export](../../igifoptions)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
