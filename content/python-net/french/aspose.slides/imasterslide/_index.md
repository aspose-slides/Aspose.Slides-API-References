---
title: IMasterSlide class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/imasterslide/
---
## IMasterSlide classe

Représente une diapositive principale dans une présentation.

Le type IMasterSlide expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/fr/aspose.slides/imasterslide/header_footer_manager/) | Renvoie le gestionnaire HeaderFooter de la diapositive principale.<br/>            Lecture seule [`IMasterSlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/fr/aspose.slides/imasterslide/title_style/) | Renvoie le style d'un texte de titre.<br/>            Lecture seule [`ITextStyle`](/slides/python-net/fr/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/fr/aspose.slides/imasterslide/body_style/) | Renvoie le style d'un texte de corps.<br/>            Lecture seule [`ITextStyle`](/slides/python-net/fr/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/fr/aspose.slides/imasterslide/other_style/) | Renvoie le style d'un autre texte.<br/>            Lecture seule [`ITextStyle`](/slides/python-net/fr/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/fr/aspose.slides/imasterslide/layout_slides/) | Renvoie la collection de diapositives de mise en page enfant pour cette diapositive principale.<br/>            Lecture seule [`IMasterLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/fr/aspose.slides/imasterslide/preserve/) | Détermine si le maître correspondant est supprimé lorsque toutes <br/>            les diapositives qui suivent ce maître sont supprimées.<br/>            Remarque : Aspose.Slides ne supprimera jamais aucun maître inutilisé par lui-même, <br/>            pour réellement supprimer les maîtres inutilisés, appelez **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            Lecture/écriture **bool**. |
| [`has_depending_slides`](/slides/python-net/fr/aspose.slides/imasterslide/has_depending_slides/) | Renvoie vrai s'il existe au moins une diapositive qui dépend de cette diapositive principale.<br/>            Lecture seule **bool**. |
| [`drawing_guides`](/slides/python-net/fr/aspose.slides/imasterslide/drawing_guides/) | Renvoie une collection de guides de dessin pour la diapositive principale.<br/>            Lecture seule [`IDrawingGuidesCollection`](/slides/python-net/fr/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/fr/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/fr/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/fr/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/fr/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/fr/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/fr/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/fr/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/fr/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/fr/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/fr/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/fr/aspose.slides/imasterslide/theme_manager/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/fr/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Crée une nouvelle diapositive principale basée sur celle actuelle, en appliquant un thème externe à celle-ci <br/>            et applique la diapositive principale créée à toutes les diapositives dépendantes. |
| [`get_depending_slides(self)`](/slides/python-net/fr/aspose.slides/imasterslide/get_depending_slides/#) | Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive principale. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fr/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/fr/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/fr/aspose.slides/imasterslide/create_theme_effective/#) |  |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)