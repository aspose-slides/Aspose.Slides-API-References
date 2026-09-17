---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController classe

La classe du contrôleur de formatage à utiliser pour incorporer toutes les polices de présentation au format WOFF.

Le type EmbedAllFontsHtmlController expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Creates new instance |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/fr/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Creates new instance |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/fr/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Appelé pour écrire l'en-tête du document html. Appelé une fois par conversion de présentation. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/fr/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Appelé pour écrire le pied de page du document html. Appelé une fois par conversion de présentation. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/fr/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Appelé pour écrire l'en-tête de la diapositive html. Appelé une fois pour chaque diapositive. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/fr/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Appelé pour écrire le pied de page de la diapositive html. Appelé une fois pour chaque diapositive. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/fr/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive actuelle sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/fr/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive actuelle sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/fr/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Écrire toutes les polices contenues dans [`Presentation`](/slides/python-net/fr/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/fr/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Écrit les données en base64 dans le document HTML lui-même |

### Voir aussi
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)