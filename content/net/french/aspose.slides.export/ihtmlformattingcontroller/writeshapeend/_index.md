---
title: WriteShapeEnd
second_title: Aspose.Slides pour .NET API Référence
description: Appelé avant le rendu des formes. Appelé une fois par forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive actuelle sera terminée, un fragment HTML ajouté inséré et une nouvelle image sera commencée au-dessus de la précédente.
type: docs
weight: 30
url: /fr/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---

## IHtmlFormattingController.WriteShapeEnd méthode

Appelé avant le rendu d'une forme. Appelé une fois par forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive actuelle sera terminée, un fragment HTML ajouté inséré et une nouvelle image sera commencée au-dessus de la précédente.

```csharp
public void WriteShapeEnd(IHtmlGenerator generator, IShape shape)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| generator | IHtmlGenerator | Objet de sortie. |
| shape | IShape | Forme qui est rendue en dernier. |

### Voir aussi

* interface [IHtmlGenerator](../../ihtmlgenerator)
* interface [IShape](../../../aspose.slides/ishape)
* interface [IHtmlFormattingController](../../ihtmlformattingcontroller)
* namespace [Aspose.Slides.Export](../../ihtmlformattingcontroller)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->