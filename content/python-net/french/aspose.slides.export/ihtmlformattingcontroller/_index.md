---
title: IHtmlFormattingController class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController classe

Contrôle la génération d'un fichier html.

Le type IHtmlFormattingController expose les membres suivants :

## Méthodes

| Méthode | Description |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/fr/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Appelé pour écrire l'en-tête du document html. Appelé une fois par conversion de présentation. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/fr/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Appelé pour écrire le pied de page du document html. Appelé une fois par conversion de présentation. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/fr/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | Appelé pour écrire l'en-tête de la diapositive html. Appelé une fois pour chaque diapositive. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/fr/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | Appelé pour écrire le pied de page de la diapositive html. Appelé une fois pour chaque diapositive. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/fr/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive courante sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/fr/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive courante sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

### Voir aussi
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)