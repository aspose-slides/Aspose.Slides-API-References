---
title: MasterSlide class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/masterslide/
---
## MasterSlide classe

Représente une diapositive maître dans une présentation.

**Héritage:**[`MasterSlide`](/slides/python-net/fr/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/fr/aspose.slides/baseslide)

Le type MasterSlide expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/fr/aspose.slides/masterslide/shapes/) | Renvoie les formes d’une diapositive.<br/>            Lecture seule [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fr/aspose.slides/masterslide/controls/) | Renvoie la collection de contrôles ActiveX d’une diapositive.<br/>            Lecture seule [`IControlCollection`](/slides/python-net/fr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fr/aspose.slides/masterslide/name/) | Renvoie ou définit le nom d’une diapositive maître.<br/>            Lecture/écriture **str**. |
| [`slide_id`](/slides/python-net/fr/aspose.slides/masterslide/slide_id/) | Renvoie l’ID d’une diapositive.<br/>            Lecture seule **int**. |
| [`custom_data`](/slides/python-net/fr/aspose.slides/masterslide/custom_data/) | Renvoie les données personnalisées de la diapositive.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fr/aspose.slides/masterslide/timeline/) | Renvoie l’objet de chronologie d’animation.<br/>            Lecture seule [`IAnimationTimeLine`](/slides/python-net/fr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fr/aspose.slides/masterslide/slide_show_transition/) | Renvoie l’objet Transition qui contient des informations sur<br/>            la façon dont la diapositive spécifiée avance pendant une présentation.<br/>            Lecture seule [`ISlideShowTransition`](/slides/python-net/fr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fr/aspose.slides/masterslide/background/) | Renvoie l’arrière-plan de la diapositive.<br/>            Lecture seule [`IBackground`](/slides/python-net/fr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/masterslide/hyperlink_queries/) | Fournit un accès facile aux hyperliens contenus.<br/>            Lecture seule [`IHyperlinkQueries`](/slides/python-net/fr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fr/aspose.slides/masterslide/show_master_shapes/) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non.<br/>            Pour la diapositive maître elle-même, cette propriété renvoie toujours `false`.<br/>            Lecture/écriture **bool**. |
| [`presentation`](/slides/python-net/fr/aspose.slides/masterslide/presentation/) | Renvoie l’interface IPresentation.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/fr/aspose.slides/masterslide/header_footer_manager/) | Renvoie le gestionnaire HeaderFooter de la diapositive maître.<br/>            Lecture seule [`IMasterSlideHeaderFooterManager`](/slides/python-net/fr/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/fr/aspose.slides/masterslide/title_style/) | Renvoie le style d’un texte de titre.<br/>            Lecture seule [`ITextStyle`](/slides/python-net/fr/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/fr/aspose.slides/masterslide/body_style/) | Renvoie le style d’un texte de corps.<br/>            Lecture seule [`ITextStyle`](/slides/python-net/fr/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/fr/aspose.slides/masterslide/other_style/) | Renvoie le style d’un autre texte.<br/>            Lecture seule [`ITextStyle`](/slides/python-net/fr/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/fr/aspose.slides/masterslide/layout_slides/) | Renvoie la collection des diapositives de mise en page enfant pour cette diapositive maître.<br/>            Lecture seule [`IMasterLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/fr/aspose.slides/masterslide/preserve/) | Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui suivent ce maître sont supprimées.<br/>            Note : Aspose.Slides ne supprimera jamais de maître inutilisé par lui-même, pour réellement supprimer les maîtres inutilisés appelez **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            Lecture/écriture **bool**. |
| [`has_depending_slides`](/slides/python-net/fr/aspose.slides/masterslide/has_depending_slides/) | Renvoie true si au moins une diapositive dépend de cette diapositive maître.<br/>            Lecture seule **bool**. |
| [`theme_manager`](/slides/python-net/fr/aspose.slides/masterslide/theme_manager/) | Renvoie le gestionnaire de thème.<br/>            Lecture seule [`IMasterThemeManager`](/slides/python-net/fr/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/fr/aspose.slides/masterslide/drawing_guides/) | Renvoie une collection de guides de dessin pour la diapositive maître.<br/>            Lecture seule [`IDrawingGuidesCollection`](/slides/python-net/fr/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/fr/aspose.slides/masterslide/slide/) |  |

## Méthodes

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Fusionne les runs avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/fr/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Fusionne les runs avec le même formatage dans tous les paragraphes de toutes les formes acceptables. |
| [`equals(self, slide)`](/slides/python-net/fr/aspose.slides/masterslide/equals/#ibaseslide) | Détermine si les deux instances IBaseSlide sont égales.<br/>            La valeur de retour est calculée en fonction de la structure de la diapositive et de son contenu statique.<br/>            Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne prend pas en compte les valeurs d’identifiants uniques, par exemple SlideId, ni le contenu dynamique, par exemple la valeur de date actuelle dans le champ de date. |
| [`create_theme_effective(self)`](/slides/python-net/fr/aspose.slides/masterslide/create_theme_effective/#) | Renvoie un thème effectif pour cette diapositive. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fr/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Trouve la première occurrence d’une forme avec le texte alternatif spécifié. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/fr/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Crée une nouvelle diapositive maître basée sur celle-ci, en appliquant un thème externe à celle-ci <br/>            et applique la diapositive maître créée à toutes les diapositives dépendantes. |
| [`get_depending_slides(self)`](/slides/python-net/fr/aspose.slides/masterslide/get_depending_slides/#) | Renvoie un tableau avec toutes les diapositives qui dépendent de cette diapositive maître. |

### Voir aussi
* classe [`BaseSlide`](/slides/python-net/fr/aspose.slides/baseslide)
* classe [`MasterSlide`](/slides/python-net/fr/aspose.slides/masterslide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)