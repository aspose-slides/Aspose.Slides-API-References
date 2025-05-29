---
title: LinkPathRelative
second_title: Référence de l'API Aspose.Sldes pour .NET
description: Renvoie le chemin relatif vers un fichier lié s'il est présent, sinon renvoie une chaîne vide. Chaîne en lecture seule.
type: docs
weight: 90
url: /fr/aspose.slides/oleobjectframe/linkpathrelative/
---

## Propriété OleObjectFrame.LinkPathRelative

Renvoie le chemin relatif vers un fichier lié s'il est présent, sinon renvoie une chaîne vide. Chaîne en lecture seule.

```csharp
public string LinkPathRelative { get; }
```

### Remarques

Dans les présentations Ppt, certains liens d'objets Ole peuvent avoir une représentation relative.

### Exemples

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.ppt"))
{
    IOleObjectFrame oleFrame = presentation.Slides[0].Shapes[0] as IOleObjectFrame;

    if (oleFrame != null)
    {
        Console.WriteLine("Le chemin relatif : " + oleFrame.LinkPathRelative);
    } 
}
```

### Voir aussi

* classe [OleObjectFrame](../../oleobjectframe)
* espace de noms [Aspose.Slides](../../oleobjectframe)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->