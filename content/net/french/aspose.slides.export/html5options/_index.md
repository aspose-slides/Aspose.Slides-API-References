---
title: Html5Options
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une option dexportation HTML5.
type: docs
weight: 3560
url: /fr/aspose.slides.export/html5options/
---
## Html5Options class

Représente une option d'exportation HTML5.

```csharp
public class Html5Options : SaveOptions, IHtml5Options
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Html5Options](html5options)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [AnimateShapes](../../aspose.slides.export/html5options/animateshapes) { get; set; } | Renvoie ou définit l'option d'animation des formes. Lecture/écritureBoolean . |
| [AnimateTransitions](../../aspose.slides.export/html5options/animatetransitions) { get; set; } | Renvoie ou définit l'option d'animation des transitions. Lecture/écritureBoolean . |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police utilisée dans le cas où la police source est introuvable. Lecture-écritureString . |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Représente un objet de rappel pour enregistrer les mises à jour de progression en pourcentage. Voir[`IProgressCallback`](../../aspose.slides/iprogresscallback) . |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Renvoie des ensembles d'un objet qui reçoit des avertissements et décide si le processus de chargement va continuer ou sera abandonné. Lecture/écriture[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) . |

### Exemples

Exemple :

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, new Html5Options()
  {
      AnimateShapes = true,
      AnimateTransitions = true
  });
}
```

### Voir également

* class [SaveOptions](../saveoptions)
* interface [IHtml5Options](../ihtml5options)
* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
