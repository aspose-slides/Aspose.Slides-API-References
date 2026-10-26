---
title: LayoutSlide class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/layoutslide/
---
## LayoutSlide classe

Représente une diapositive de mise en page.

**Héritage:**[`LayoutSlide`](/slides/python-net/fr/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/fr/aspose.slides/baseslide)

Le type LayoutSlide expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`shapes`](/slides/python-net/fr/aspose.slides/layoutslide/shapes/) | Renvoie les formes d'une diapositive.<br/>            Lecture seule [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fr/aspose.slides/layoutslide/controls/) | Renvoie la collection des contrôles ActiveX d'une diapositive.<br/>            Lecture seule [`IControlCollection`](/slides/python-net/fr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fr/aspose.slides/layoutslide/name/) | Renvoie ou définit le nom d'une diapositive.<br/>            Lecture/écriture **str**. |
| [`slide_id`](/slides/python-net/fr/aspose.slides/layoutslide/slide_id/) | Renvoie l'ID d'une diapositive.<br/>            Lecture seule **int**. |
| [`custom_data`](/slides/python-net/fr/aspose.slides/layoutslide/custom_data/) | Renvoie les données personnalisées de la diapositive.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fr/aspose.slides/layoutslide/timeline/) | Renvoie l'objet de la chronologie d'animation.<br/>            Lecture seule [`IAnimationTimeLine`](/slides/python-net/fr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fr/aspose.slides/layoutslide/slide_show_transition/) | Renvoie l'objet Transition qui contient des informations sur<br/>            la façon dont la diapositive spécifiée avance pendant un diaporama.<br/>            Lecture seule [`ISlideShowTransition`](/slides/python-net/fr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fr/aspose.slides/layoutslide/background/) | Renvoie l'arrière-plan de la diapositive.<br/>            Lecture seule [`IBackground`](/slides/python-net/fr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/layoutslide/hyperlink_queries/) | Fournit un accès facile aux hyperliens contenus.<br/>            Lecture seule [`IHyperlinkQueries`](/slides/python-net/fr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fr/aspose.slides/layoutslide/show_master_shapes/) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non.<br/>            Lecture/écriture **bool**. |
| [`presentation`](/slides/python-net/fr/aspose.slides/layoutslide/presentation/) | Renvoie l'interface IPresentation.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/fr/aspose.slides/layoutslide/header_footer_manager/) | Renvoie le gestionnaire HeaderFooter de la diapositive de mise en page.<br/>            Lecture seule [`ILayoutSlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/fr/aspose.slides/layoutslide/placeholder_manager/) | Renvoie le gestionnaire de zones réservées de la diapositive de mise en page.<br/>            Lecture seule [`ILayoutPlaceholderManager`](/slides/python-net/fr/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/fr/aspose.slides/layoutslide/master_slide/) | Renvoie ou définit la diapositive maîtresse pour une mise en page.<br/>            Lecture/écriture [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/fr/aspose.slides/layoutslide/theme_manager/) | Renvoie le gestionnaire de thème de substitution.<br/>            Lecture seule [`IOverrideThemeManager`](/slides/python-net/fr/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/fr/aspose.slides/layoutslide/layout_type/) | Renvoie le type de mise en page de cette diapositive de mise en page.<br/>            Lecture seule [`SlideLayoutType`](/slides/python-net/fr/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/fr/aspose.slides/layoutslide/has_depending_slides/) | Renvoie vrai s'il existe au moins une diapositive qui dépend de cette diapositive de mise en page.<br/>            Lecture seule **bool**. |
| [`drawing_guides`](/slides/python-net/fr/aspose.slides/layoutslide/drawing_guides/) | Renvoie une collection de guides de dessin pour la diapositive de mise en page.<br/>            Lecture seule [`IDrawingGuidesCollection`](/slides/python-net/fr/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/fr/aspose.slides/layoutslide/slide/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Fusionne les groupes de texte avec le même formatage dans tous les paragraphes de toutes les formes admissibles. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/fr/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Fusionne les groupes de texte avec le même formatage dans tous les paragraphes de toutes les formes admissibles. |
| [`equals(self, slide)`](/slides/python-net/fr/aspose.slides/layoutslide/equals/#ibaseslide) | Détermine si les deux instances IBaseSlide sont égales.<br/>            La valeur de retour est calculée en fonction de la structure de la diapositive et du contenu statique.<br/>            Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres réglages, etc., sont égaux. La comparaison ne tient pas compte des valeurs d'identifiants uniques, par ex. SlideId, ni du contenu dynamique, par ex. la valeur de date actuelle dans le champ Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/fr/aspose.slides/layoutslide/create_theme_effective/#) | Renvoie un thème effectif pour cette diapositive. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fr/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Recherche la première occurrence d'une forme avec le texte alternatif spécifié. |
| [`remove(self)`](/slides/python-net/fr/aspose.slides/layoutslide/remove/#) | Supprime la mise en page de la présentation. |
| [`get_depending_slides(self)`](/slides/python-net/fr/aspose.slides/layoutslide/get_depending_slides/#) | Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive de mise en page. |

### Voir aussi
* classe [`BaseSlide`](/slides/python-net/fr/aspose.slides/baseslide)
* classe [`LayoutSlide`](/slides/python-net/fr/aspose.slides/layoutslide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)