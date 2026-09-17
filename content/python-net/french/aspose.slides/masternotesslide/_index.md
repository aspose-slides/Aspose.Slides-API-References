---
title: MasterNotesSlide class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/masternotesslide/
---
## Classe MasterNotesSlide

Représente la diapositive maîtresse pour les notes.

**Inheritance:**[`MasterNotesSlide`](/slides/python-net/fr/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/fr/aspose.slides/baseslide)

Le type MasterNotesSlide expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`shapes`](/slides/python-net/fr/aspose.slides/masternotesslide/shapes/) | Renvoie les formes d'une diapositive.<br/>            Lecture seule [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fr/aspose.slides/masternotesslide/controls/) | Renvoie la collection des contrôles ActiveX d'une diapositive.<br/>            Lecture seule [`IControlCollection`](/slides/python-net/fr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fr/aspose.slides/masternotesslide/name/) | Renvoie ou définit le nom d'une diapositive.<br/>            Lecture/écriture **str**. |
| [`slide_id`](/slides/python-net/fr/aspose.slides/masternotesslide/slide_id/) | Renvoie l'ID d'une diapositive.<br/>            Lecture seule **int**. |
| [`custom_data`](/slides/python-net/fr/aspose.slides/masternotesslide/custom_data/) | Renvoie les données personnalisées de la diapositive.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fr/aspose.slides/masternotesslide/timeline/) | Renvoie l'objet de ligne de temps d'animation.<br/>            Lecture seule [`IAnimationTimeLine`](/slides/python-net/fr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fr/aspose.slides/masternotesslide/slide_show_transition/) | Renvoie l'objet Transition qui contient des informations sur<br/>            la façon dont la diapositive spécifiée avance pendant le diaporama.<br/>            Lecture seule [`ISlideShowTransition`](/slides/python-net/fr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fr/aspose.slides/masternotesslide/background/) | Renvoie l'arrière-plan de la diapositive.<br/>            Lecture seule [`IBackground`](/slides/python-net/fr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/masternotesslide/hyperlink_queries/) | Fournit un accès facile aux hyperliens contenus.<br/>            Lecture seule [`IHyperlinkQueries`](/slides/python-net/fr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fr/aspose.slides/masternotesslide/show_master_shapes/) | Spécifie si les formes de la diapositive maîtresse doivent être affichées sur les diapositives ou non.<br/>            Pour la diapositive maîtresse elle-même, cette propriété renvoie toujours `false`.<br/>            Lecture/écriture **bool**. |
| [`presentation`](/slides/python-net/fr/aspose.slides/masternotesslide/presentation/) | Renvoie l'interface IPresentation.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/fr/aspose.slides/masternotesslide/header_footer_manager/) | Renvoie le gestionnaire HeaderFooter de la diapositive maîtresse des notes.<br/>            Lecture seule [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/fr/aspose.slides/masternotesslide/theme_manager/) | Renvoie le gestionnaire de thème.<br/>            Lecture seule [`IMasterThemeManager`](/slides/python-net/fr/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/fr/aspose.slides/masternotesslide/notes_style/) | Renvoie le style d'un texte de notes.<br/>            Lecture seule [`ITextStyle`](/slides/python-net/fr/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/fr/aspose.slides/masternotesslide/drawing_guides/) | Renvoie une collection de guides de dessin pour la diapositive maîtresse des notes.<br/>            Lecture seule [`IDrawingGuidesCollection`](/slides/python-net/fr/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/fr/aspose.slides/masternotesslide/slide/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Joint les runs avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/fr/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Joint les runs avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| [`equals(self, slide)`](/slides/python-net/fr/aspose.slides/masternotesslide/equals/#ibaseslide) | Détermine si les deux instances IBaseSlide sont égales.<br/>            La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique.<br/>            Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc., sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiants uniques, par ex. SlideId et le contenu dynamique, par ex. la valeur de date actuelle dans Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/fr/aspose.slides/masternotesslide/create_theme_effective/#) | Renvoie un thème effectif pour cette diapositive. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fr/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Trouve la première occurrence d'une forme avec le texte alternatif spécifié. |

### Voir aussi
* classe [`BaseSlide`](/slides/python-net/fr/aspose.slides/baseslide)
* classe [`MasterNotesSlide`](/slides/python-net/fr/aspose.slides/masternotesslide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)