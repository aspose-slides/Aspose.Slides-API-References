---
title: ISlide class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/islide/
---
## ISlide classe

Représente une diapositive dans une présentation.

Le type ISlide expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/fr/aspose.slides/islide/header_footer_manager/) | Renvoie le gestionnaire HeaderFooter de la diapositive.<br/>            Lecture seule [`ISlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/fr/aspose.slides/islide/slide_number/) | Renvoie le numéro de la diapositive.<br/>            L'index de la diapositive dans la collection [`IPresentation.slides`](/slides/python-net/fr/aspose.slides/ipresentation/slides) est toujours égal à SlideNumber - 1.<br/>            Lecture/écriture **int**. |
| [`hidden`](/slides/python-net/fr/aspose.slides/islide/hidden/) | Détermine si la diapositive spécifiée est masquée pendant le diaporama.<br/>            Lecture/écriture **bool**. |
| [`layout_slide`](/slides/python-net/fr/aspose.slides/islide/layout_slide/) | Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle.<br/>            Lecture/écriture [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/fr/aspose.slides/islide/notes_slide_manager/) | Permet d'accéder à la diapositive de notes, de l'ajouter et de la supprimer.<br/>            Lecture seule [`INotesSlideManager`](/slides/python-net/fr/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/fr/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/fr/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/fr/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/fr/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/fr/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/fr/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/fr/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/fr/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/fr/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/fr/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/fr/aspose.slides/islide/theme_manager/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/islide/get_image/#float-float) | Renvoie un objet image avec un redimensionnement personnalisé. |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/islide/get_image/#) | Renvoie un objet Image miniature (20 % de la taille réelle). |
| [`get_image(self, image_size)`](/slides/python-net/fr/aspose.slides/islide/get_image/#asposeslidessize) | Renvoie un objet image avec la taille spécifiée. |
| [`get_image(self, options)`](/slides/python-net/fr/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Renvoie un objet bitmap tiff miniature avec les paramètres spécifiés. |
| [`get_image(self, options)`](/slides/python-net/fr/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Renvoie un objet Bitmap miniature. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Renvoie un objet Bitmap miniature avec un redimensionnement personnalisé. |
| [`get_image(self, options, image_size)`](/slides/python-net/fr/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Renvoie un objet Bitmap miniature avec la taille spécifiée. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/islide/write_as_svg/#iorawiobase) | Enregistre le contenu de la diapositive en tant que fichier SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de la diapositive en tant que fichier SVG. |
| [`get_slide_comments(self, author)`](/slides/python-net/fr/aspose.slides/islide/get_slide_comments/#icommentauthor) | Renvoie tous les commentaires de diapositive ajoutés par un auteur spécifique. |
| [`write_as_emf(self, stream)`](/slides/python-net/fr/aspose.slides/islide/write_as_emf/#iorawiobase) | Enregistre le contenu de la diapositive en tant que fichier EMF. |
| [`remove(self)`](/slides/python-net/fr/aspose.slides/islide/remove/#) | Supprime la diapositive de la présentation. |
| [`reset(self)`](/slides/python-net/fr/aspose.slides/islide/reset/#) | Réinitialise la position, la taille et le formatage de chaque forme qui possède un prototype sur LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fr/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/fr/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/fr/aspose.slides/islide/create_theme_effective/#) |  |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)