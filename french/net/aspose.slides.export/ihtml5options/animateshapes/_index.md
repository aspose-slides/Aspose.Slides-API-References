---
title: AnimateShapes
second_title: Référence de l'API Aspose.Slides pour .NET
description: Renvoie ou définit loption danimation des formes. Lecture/écritureBoolean .
type: docs
weight: 10
url: /fr/net/aspose.slides.export/ihtml5options/animateshapes/
---
## IHtml5Options.AnimateShapes property

Renvoie ou définit l'option d'animation des formes. Lecture/écritureBoolean .

```csharp
public bool AnimateShapes { get; set; }
```

### Exemples

Exemple :

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-animate-shapes.html", SaveFormat.Html5, new Html5Options()
  {
      AnimateShapes = true
  });
}
```

### Voir également

* interface [IHtml5Options](../../ihtml5options)
* espace de noms [Aspose.Slides.Export](../../ihtml5options)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->