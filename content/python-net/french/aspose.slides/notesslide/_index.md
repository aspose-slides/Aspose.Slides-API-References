---
title: NotesSlide class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/notesslide/
---
## NotesSlide classe

Représente une diapositive de notes dans une présentation.

**Héritage:**[`NotesSlide`](/slides/python-net/fr/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/fr/aspose.slides/baseslide)

Le type NotesSlide expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`shapes`](/slides/python-net/fr/aspose.slides/notesslide/shapes/) | Renvoie les formes d'une diapositive.<br/>            Lecture seule [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fr/aspose.slides/notesslide/controls/) | Renvoie la collection de contrôles ActiveX sur une diapositive.<br/>            Lecture seule [`IControlCollection`](/slides/python-net/fr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fr/aspose.slides/notesslide/name/) | Renvoie ou définit le nom d'une diapositive.<br/>            Lecture/écriture **str**. |
| [`slide_id`](/slides/python-net/fr/aspose.slides/notesslide/slide_id/) | Renvoie l'ID d'une diapositive.<br/>            Lecture seule **int**. |
| [`custom_data`](/slides/python-net/fr/aspose.slides/notesslide/custom_data/) | Renvoie les données personnalisées de la diapositive.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fr/aspose.slides/notesslide/timeline/) | Renvoie l'objet de chronologie d'animation.<br/>            Lecture seule [`IAnimationTimeLine`](/slides/python-net/fr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fr/aspose.slides/notesslide/slide_show_transition/) | Renvoie l'objet Transition qui contient des informations sur<br/>            comment la diapositive spécifiée progresse pendant un diaporama.<br/>            Lecture seule [`ISlideShowTransition`](/slides/python-net/fr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fr/aspose.slides/notesslide/background/) | Renvoie l'arrière-plan de la diapositive.<br/>            Lecture seule [`IBackground`](/slides/python-net/fr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/notesslide/hyperlink_queries/) | Fournit un accès facile aux hyperliens contenus.<br/>            Lecture seule [`IHyperlinkQueries`](/slides/python-net/fr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fr/aspose.slides/notesslide/show_master_shapes/) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non.<br/>            Lecture/écriture **bool**. |
| [`presentation`](/slides/python-net/fr/aspose.slides/notesslide/presentation/) | Renvoie l'interface IPresentation.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/fr/aspose.slides/notesslide/header_footer_manager/) | Renvoie le gestionnaire HeaderFooter de la diapositive de notes.<br/>            Lecture seule [`INotesSlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/fr/aspose.slides/notesslide/notes_text_frame/) | Renvoie un TextFrame contenant le texte des notes s'il existe.<br/>            Lecture seule [`ITextFrame`](/slides/python-net/fr/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/fr/aspose.slides/notesslide/theme_manager/) | Renvoie le gestionnaire de thème de substitution.<br/>            Lecture seule [`IOverrideThemeManager`](/slides/python-net/fr/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/fr/aspose.slides/notesslide/parent_slide/) | Renvoie la diapositive parente.<br/>            Lecture seule [`ISlide`](/slides/python-net/fr/aspose.slides/islide). |
| [`slide`](/slides/python-net/fr/aspose.slides/notesslide/slide/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Joint les segments avec la même mise en forme dans tous les paragraphes de toutes les formes acceptables. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/fr/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Joint les segments avec la même mise en forme dans tous les paragraphes de toutes les formes acceptables. |
| [`equals(self, slide)`](/slides/python-net/fr/aspose.slides/notesslide/equals/#ibaseslide) | Détermine si les deux instances IBaseSlide sont égales.<br/>            La valeur de retour est calculée en fonction de la structure de la diapositive et du contenu statique.<br/>            Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d'identifiants uniques, par exemple SlideId, ni le contenu dynamique, par exemple la valeur de la date actuelle dans le champ Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/fr/aspose.slides/notesslide/create_theme_effective/#) | Renvoie un thème effectif pour cette diapositive. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fr/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Trouve la première occurrence d'une forme avec le texte alternatif spécifié. |

### Voir aussi
* classe [`BaseSlide`](/slides/python-net/fr/aspose.slides/baseslide)
* classe [`NotesSlide`](/slides/python-net/fr/aspose.slides/notesslide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)