---
title: IHtmlGenerator class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator classe

Générateur Html.

Le type IHtmlGenerator expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`slide_image_size`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Renvoie la taille de l'image de la diapositive.<br/>            Lecture seule [`SizeF`](/slides/python-net/fr/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Renvoie l'unité dans laquelle la taille de l'image de la diapositive est spécifiée.<br/>            Lecture seule [`SvgCoordinateUnit`](/slides/python-net/fr/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Renvoie le code css de l'unité dans laquelle la taille de l'image de la diapositive est spécifiée.<br/>            Lecture seule **str**. |
| [`previous_slide_index`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Renvoie l'indice de la diapositive précédemment rendue ou -1 si c'est la première diapositive rendue.<br/>            Lecture seule **int**. |
| [`slide_index`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/slide_index/) | Renvoie l'indice de la diapositive en cours de rendu.<br/>            Lecture seule **int**. |
| [`next_slide_index`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Renvoie l'indice d'une diapositive qui sera rendue après la diapositive actuelle ou -1 si la dernière diapositive est en cours de rendu.<br/>            Lecture seule **int**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/add_html/#str) | Ajoute du texte HTML formaté. |
| [`add_html(self, html)`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Ajoute du texte HTML formaté. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Ajoute du texte HTML formaté. |
| [`add_text(self, text)`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/add_text/#str) | Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html.<br/>            Les sauts de ligne et les espaces blancs ne sont pas remplacés. |
| [`add_text(self, text)`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html.<br/>            Les sauts de ligne et les espaces blancs ne sont pas remplacés. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | Ajoute du texte brut aux fichiers html, en remplaçant les caractères spéciaux par des entités html.<br/>            Les sauts de ligne et les espaces blancs ne sont pas remplacés. |
| [`add_attribute_value(self, value)`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Cite la valeur de l'attribut et l'ajoute au fichier html. |
| [`add_attribute_value(self, value)`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Cite la valeur de l'attribut et l'ajoute au fichier html. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/fr/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Cite la valeur de l'attribut et l'ajoute au fichier html. |

### Voir aussi
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)