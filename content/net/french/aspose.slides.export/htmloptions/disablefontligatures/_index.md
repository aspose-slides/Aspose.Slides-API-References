---
title: DisableFontLigatures
second_title: Aspose.Slides pour .NET Référence API
description: Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsqu'elle est définie sur true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur false.
type: docs
weight: 30
url: /fr/aspose.slides.export/htmloptions/disablefontligatures/
---

## HtmlOptions.DisableFontLigatures propriété

Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsqu'elle est définie sur `true`, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur `false`.

```csharp
public bool DisableFontLigatures { get; set; }
```

### Exemples

Exemple :

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    HtmlOptions options = new HtmlOptions
    {
        DisableFontLigatures = true // Désactiver les ligatures dans le rendu du texte
    };
    
    pres.Save(outputSlidePath, SaveFormat.Html, options);
}
```

### Voir Aussi

* classe [HtmlOptions](../../htmloptions)
* espace de noms [Aspose.Slides.Export](../../htmloptions)
* assemblage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->