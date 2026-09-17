---
title: SlideUtil class
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides.util/slideutil/
---
## SlideUtil classe

Propose des méthodes qui aident à rechercher des formes et du texte dans une présentation.

Le type SlideUtil expose les membres suivants :

## Méthodes

| Méthode | Description |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/fr/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | Recherche une forme par texte alternatif dans une présentation PPTX. |
| [`find_shape(slide, alt_text)`](/slides/python-net/fr/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | Recherche une forme par texte alternatif sur une diapositive d’une présentation PPTX. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/fr/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | Modifie le placement de toutes les formes sur la diapositive. Aligne les formes aux marges ou au bord de la diapositive<br/>            ou les aligne les unes par rapport aux autres. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/fr/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | Modifie le placement des formes sélectionnées sur la diapositive. Aligne les formes aux marges ou au bord de la diapositive<br/>            ou les aligne les unes par rapport aux autres. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/fr/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | Modifie le placement de toutes les formes au sein d'un groupe de formes. Aligne les formes aux marges ou au bord de la diapositive<br/>            ou les aligne les unes par rapport aux autres. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/fr/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | Modifie le placement des formes sélectionnées au sein d'un groupe de formes. Aligne les formes aux marges ou au bord de la diapositive<br/>            ou les aligne les unes par rapport aux autres. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/fr/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | Recherche toutes les formes sur la diapositive spécifiée qui correspondent au type d’espace réservé donné. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/fr/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | Recherche et remplace du texte dans la présentation avec le format donné. |
| [`get_all_text_boxes(slide)`](/slides/python-net/fr/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | Renvoie tous les cadres de texte sur une diapositive d’une présentation PPTX. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/fr/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | Renvoie tous les cadres de texte sur la diapositive spécifiée contenant le texte donné. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/fr/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | Renvoie tous les cadres de texte dans une présentation PPTX. |
| [`to_save_format(format)`](/slides/python-net/fr/aspose.slides.util/slideutil/to_save_format/#sourceformat) | Convertit un format de fichier source au [`SaveFormat`](/slides/python-net/fr/aspose.slides.export/saveformat) correspondant. |

### Voir aussi
* module [`aspose.slides.util`](/slides/python-net/fr/aspose.slides.util)
* bibliothèque [`Aspose.Slides`](/slides/python-net)