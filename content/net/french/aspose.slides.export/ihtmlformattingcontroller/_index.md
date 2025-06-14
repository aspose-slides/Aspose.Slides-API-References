---
title: IHtmlFormattingController
second_title: Référence API Aspose.Slides pour .NET
description: Contrôle la génération d'un fichier html.
type: docs
weight: 3780
url: /fr/aspose.slides.export/ihtmlformattingcontroller/
---

## Interface IHtmlFormattingController

Contrôle la génération d'un fichier html.

```csharp
public interface IHtmlFormattingController
```

## Méthodes

| Nom | Description |
| --- | --- |
| [WriteDocumentEnd](../../aspose.slides.export/ihtmlformattingcontroller/writedocumentend)(IHtmlGenerator, IPresentation) | Appelé pour écrire le pied de page du document html. Appelé une fois par conversion de présentation. |
| [WriteDocumentStart](../../aspose.slides.export/ihtmlformattingcontroller/writedocumentstart)(IHtmlGenerator, IPresentation) | Appelé pour écrire l'en-tête du document html. Appelé une fois par conversion de présentation. |
| [WriteShapeEnd](../../aspose.slides.export/ihtmlformattingcontroller/writeshapeend)(IHtmlGenerator, IShape) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive actuelle sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera commencée au-dessus de la précédente. |
| [WriteShapeStart](../../aspose.slides.export/ihtmlformattingcontroller/writeshapestart)(IHtmlGenerator, IShape) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive actuelle sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera commencée au-dessus de la précédente. |
| [WriteSlideEnd](../../aspose.slides.export/ihtmlformattingcontroller/writeslideend)(IHtmlGenerator, ISlide) | Appelé pour écrire le pied de page de la diapositive html. Appelé une fois pour chaque diapositive. |
| [WriteSlideStart](../../aspose.slides.export/ihtmlformattingcontroller/writeslidestart)(IHtmlGenerator, ISlide) | Appelé pour écrire l'en-tête de la diapositive html. Appelé une fois pour chaque diapositive. |

### Voir aussi

* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->