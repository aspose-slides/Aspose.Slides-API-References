---
title: MasterHandoutSlide class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide classe

Représente la diapositive maître pour les fascicules.

**Héritage:**[`MasterHandoutSlide`](/slides/python-net/fr/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/fr/aspose.slides/baseslide)

Le type MasterHandoutSlide expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/fr/aspose.slides/masterhandoutslide/shapes/) | Renvoie les formes d'une diapositive.<br/>            Lecture seule [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fr/aspose.slides/masterhandoutslide/controls/) | Renvoie la collection des contrôles ActiveX d'une diapositive.<br/>            Lecture seule [`IControlCollection`](/slides/python-net/fr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fr/aspose.slides/masterhandoutslide/name/) | Renvoie ou définit le nom d'une diapositive.<br/>            Lecture/écriture **str**. |
| [`slide_id`](/slides/python-net/fr/aspose.slides/masterhandoutslide/slide_id/) | Renvoie l'identifiant d'une diapositive.<br/>            Lecture seule **int**. |
| [`custom_data`](/slides/python-net/fr/aspose.slides/masterhandoutslide/custom_data/) | Renvoie les données personnalisées de la diapositive.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fr/aspose.slides/masterhandoutslide/timeline/) | Renvoie l'objet de la chronologie d'animation.<br/>            Lecture seule [`IAnimationTimeLine`](/slides/python-net/fr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fr/aspose.slides/masterhandoutslide/slide_show_transition/) | Renvoie l'objet Transition qui contient les informations sur<br/>            la façon dont la diapositive spécifiée progresse pendant un diaporama.<br/>            Lecture seule [`ISlideShowTransition`](/slides/python-net/fr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fr/aspose.slides/masterhandoutslide/background/) | Renvoie l'arrière-plan de la diapositive.<br/>            Lecture seule [`IBackground`](/slides/python-net/fr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/masterhandoutslide/hyperlink_queries/) | Fournit un accès facile aux hyperliens contenus.<br/>            Lecture seule [`IHyperlinkQueries`](/slides/python-net/fr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fr/aspose.slides/masterhandoutslide/show_master_shapes/) | Spécifie si les formes de la diapositive maîtresse doivent être affichées sur les diapositives ou non.<br/>            Pour la diapositive maîtresse elle-même, cette propriété renvoie toujours `false`.<br/>            Lecture/écriture **bool**. |
| [`presentation`](/slides/python-net/fr/aspose.slides/masterhandoutslide/presentation/) | Renvoie l'interface IPresentation.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/fr/aspose.slides/masterhandoutslide/header_footer_manager/) | Renvoie le gestionnaire HeaderFooter de la diapositive principale du fascicule.<br/>            Lecture seule [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/fr/aspose.slides/masterhandoutslide/theme_manager/) | Renvoie le gestionnaire de thème.<br/>            Lecture seule [`IMasterThemeManager`](/slides/python-net/fr/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/fr/aspose.slides/masterhandoutslide/drawing_guides/) | Renvoie une collection de guides de dessin pour la diapositive principale du fascicule.<br/>            Lecture seule [`IDrawingGuidesCollection`](/slides/python-net/fr/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/fr/aspose.slides/masterhandoutslide/slide/) |  |

## Méthodes

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Regroupe les segments avec le même formatage dans tous les paragraphes de toutes les formes admissibles. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/fr/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Regroupe les segments avec le même formatage dans tous les paragraphes de toutes les formes admissibles. |
| [`equals(self, slide)`](/slides/python-net/fr/aspose.slides/masterhandoutslide/equals/#ibaseslide) | Détermine si les deux instances IBaseSlide sont égales.<br/>            La valeur retournée est calculée en fonction de la structure de la diapositive et du contenu statique.<br/>            Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc., sont identiques. La comparaison ne tient pas compte des valeurs d'identifiants uniques, par ex. SlideId, ni du contenu dynamique, par ex. la valeur de date actuelle dans le champ Date. |
| [`create_theme_effective(self)`](/slides/python-net/fr/aspose.slides/masterhandoutslide/create_theme_effective/#) | Renvoie un thème effectif pour cette diapositive. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fr/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Recherche la première occurrence d'une forme avec le texte de substitution spécifié. |

### Voir aussi
* classe [`BaseSlide`](/slides/python-net/fr/aspose.slides/baseslide)
* classe [`MasterHandoutSlide`](/slides/python-net/fr/aspose.slides/masterhandoutslide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)