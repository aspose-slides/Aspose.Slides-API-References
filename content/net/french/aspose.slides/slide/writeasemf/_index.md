---
title: WriteAsEmf
second_title: Référence API Aspose.Slides pour .NET
description: Enregistre le contenu de la diapositive en tant que fichier EMF.
type: docs
weight: 130
url: /fr/aspose.slides/slide/writeasemf/
---

## Méthode Slide.WriteAsEmf

Enregistre le contenu de la diapositive en tant que fichier EMF.

```csharp
public void WriteAsEmf(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux cible |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Le flux cible est `null` |

### Exemples

L'exemple de code suivant démontre comment convertir la première diapositive d'une présentation PowerPoint en un fichier métadonnées.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    using (Stream fileStream = System.IO.File.Create("slide_1.emf"))
    {
        // Enregistre la première diapositive en tant que métadonnées
        pres.Slides[0].WriteAsEmf(fileStream);
    }
}
```

### Voir aussi

* classe [Slide](../../slide)
* espace de noms [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)