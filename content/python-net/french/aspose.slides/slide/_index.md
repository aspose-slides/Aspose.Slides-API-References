---
title: Slide class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/slide/
---
## Classe Slide

Représente une diapositive dans une présentation.

**Héritage:**[`Slide`](/slides/python-net/fr/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/fr/aspose.slides/baseslide)

Le type Slide expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`shapes`](/slides/python-net/fr/aspose.slides/slide/shapes/) | Renvoie les formes d'une diapositive.<br/>            Lecture seule [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fr/aspose.slides/slide/controls/) | Renvoie la collection des contrôles ActiveX d'une diapositive.<br/>            Lecture seule [`IControlCollection`](/slides/python-net/fr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fr/aspose.slides/slide/name/) | Renvoie ou définit le nom d'une diapositive.<br/>            Lecture/écriture **str**. |
| [`slide_id`](/slides/python-net/fr/aspose.slides/slide/slide_id/) | Renvoie l'ID d'une diapositive.<br/>            Lecture seule **int**. |
| [`custom_data`](/slides/python-net/fr/aspose.slides/slide/custom_data/) | Renvoie les données personnalisées de la diapositive.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fr/aspose.slides/slide/timeline/) | Renvoie l'objet de la chronologie d'animation.<br/>            Lecture seule [`IAnimationTimeLine`](/slides/python-net/fr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fr/aspose.slides/slide/slide_show_transition/) | Renvoie l'objet Transition qui contient des informations sur<br/>            la façon dont la diapositive spécifiée avance pendant le diaporama.<br/>            Lecture seule [`ISlideShowTransition`](/slides/python-net/fr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fr/aspose.slides/slide/background/) | Renvoie l'arrière-plan de la diapositive.<br/>            Lecture seule [`IBackground`](/slides/python-net/fr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/slide/hyperlink_queries/) | Fournit un accès facile aux hyperliens contenus.<br/>            Lecture seule [`IHyperlinkQueries`](/slides/python-net/fr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fr/aspose.slides/slide/show_master_shapes/) | Spécifie si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non.<br/>            Lecture/écriture **bool**. |
| [`presentation`](/slides/python-net/fr/aspose.slides/slide/presentation/) | Renvoie l'interface IPresentation.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/fr/aspose.slides/slide/header_footer_manager/) | Renvoie le gestionnaire HeaderFooter de la diapositive.<br/>            Lecture seule [`ISlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/fr/aspose.slides/slide/theme_manager/) | Renvoie le gestionnaire de thème de substitution.<br/>            Lecture seule [`IOverrideThemeManager`](/slides/python-net/fr/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/fr/aspose.slides/slide/slide_number/) | Renvoie le numéro d'une diapositive.<br/>            L'indice de la diapositive dans la collection [`Presentation.slides`](/slides/python-net/fr/aspose.slides/presentation/slides) est toujours égal à SlideNumber - Presentation.FirstSlideNumber.<br/>            Lecture/écriture **int**. |
| [`hidden`](/slides/python-net/fr/aspose.slides/slide/hidden/) | Détermine si la diapositive spécifiée est masquée pendant le diaporama.<br/>            Lecture/écriture **bool**. |
| [`layout_slide`](/slides/python-net/fr/aspose.slides/slide/layout_slide/) | Renvoie ou définit la diapositive de mise en page pour la diapositive actuelle.<br/>            Lecture/écriture [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/fr/aspose.slides/slide/notes_slide_manager/) | Permet d'accéder à la diapositive de notes, de l'ajouter et de la supprimer.<br/>            Lecture seule [`INotesSlideManager`](/slides/python-net/fr/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/fr/aspose.slides/slide/slide/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/slide/join_portions_with_same_formatting/#) | Fusionne les séquences avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/fr/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Fusionne les séquences avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/slide/get_image/#float-float) | Renvoie un objet Image miniature avec une mise à l'échelle personnalisée. |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/slide/get_image/#) | Renvoie un objet Image miniature (20 % de la taille réelle). |
| [`get_image(self, image_size)`](/slides/python-net/fr/aspose.slides/slide/get_image/#asposeslidessize) | Renvoie un objet Image miniature avec la taille spécifiée. |
| [`get_image(self, options)`](/slides/python-net/fr/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Renvoie un objet image tiff miniature avec des paramètres spécifiés. |
| [`get_image(self, options)`](/slides/python-net/fr/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Renvoie un objet Image miniature. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Renvoie un objet Image miniature avec une mise à l'échelle personnalisée. |
| [`get_image(self, options, image_size)`](/slides/python-net/fr/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Renvoie un objet Image miniature avec la taille spécifiée. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/slide/write_as_svg/#iorawiobase) | Enregistre le contenu de la diapositive en tant que fichier SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de la diapositive en tant que fichier SVG. |
| [`equals(self, slide)`](/slides/python-net/fr/aspose.slides/slide/equals/#ibaseslide) | Détermine si les deux instances IBaseSlide sont égales.<br/>            La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique.<br/>            Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne tient pas compte des valeurs d'identifiants uniques, par exemple SlideId et du contenu dynamique, par exemple la valeur actuelle de la date dans le texte de substitution Date. |
| [`create_theme_effective(self)`](/slides/python-net/fr/aspose.slides/slide/create_theme_effective/#) | Renvoie un thème effectif pour cette diapositive. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fr/aspose.slides/slide/find_shape_by_alt_text/#str) | Trouve la première occurrence d'une forme avec le texte de remplacement spécifié. |
| [`write_as_emf(self, stream)`](/slides/python-net/fr/aspose.slides/slide/write_as_emf/#iorawiobase) | Enregistre le contenu de la diapositive en tant que fichier EMF. |
| [`remove(self)`](/slides/python-net/fr/aspose.slides/slide/remove/#) | Supprime la diapositive de la présentation. |
| [`reset(self)`](/slides/python-net/fr/aspose.slides/slide/reset/#) | Réinitialise la position, la taille et le formatage de chaque forme qui possède un prototype sur LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/fr/aspose.slides/slide/get_slide_comments/#icommentauthor) | Renvoie tous les commentaires de diapositive ajoutés par un auteur spécifique. |

### Voir aussi
* classe [`BaseSlide`](/slides/python-net/fr/aspose.slides/baseslide)
* classe [`Slide`](/slides/python-net/fr/aspose.slides/slide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)