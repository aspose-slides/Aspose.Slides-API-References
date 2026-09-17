---
title: BaseSlide class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/baseslide/
---
## BaseSlide classe

Représente les données communes à tous les types de diapositive.

Le type BaseSlide expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/fr/aspose.slides/baseslide/shapes/) | Renvoie les formes d’une diapositive.<br/>            Lecture seule [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fr/aspose.slides/baseslide/controls/) | Renvoie la collection des contrôles ActiveX d’une diapositive.<br/>            Lecture seule [`IControlCollection`](/slides/python-net/fr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fr/aspose.slides/baseslide/name/) | Renvoie ou définit le nom d’une diapositive.<br/>            Lecture/écriture **str**. |
| [`slide_id`](/slides/python-net/fr/aspose.slides/baseslide/slide_id/) | Renvoie l’ID d’une diapositive.<br/>            Lecture seule **int**. |
| [`custom_data`](/slides/python-net/fr/aspose.slides/baseslide/custom_data/) | Renvoie les données personnalisées de la diapositive.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fr/aspose.slides/baseslide/timeline/) | Renvoie l’objet de la timeline d’animation.<br/>            Lecture seule [`IAnimationTimeLine`](/slides/python-net/fr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fr/aspose.slides/baseslide/slide_show_transition/) | Renvoie l’objet Transition qui contient des informations sur<br/>            la façon dont la diapositive spécifiée avance pendant le diaporama.<br/>            Lecture seule [`ISlideShowTransition`](/slides/python-net/fr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fr/aspose.slides/baseslide/background/) | Renvoie l’arrière-plan de la diapositive.<br/>            Lecture seule [`IBackground`](/slides/python-net/fr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/baseslide/hyperlink_queries/) | Fournit un accès facile aux hyperliens contenus.<br/>            Lecture seule [`IHyperlinkQueries`](/slides/python-net/fr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fr/aspose.slides/baseslide/show_master_shapes/) | Spécifie si les formes de la diapositive maître doivent être affichées sur les diapositives ou non.<br/>            Pour la diapositive maître elle-même, cette propriété renvoie toujours `false`.<br/>            Lecture/écriture **bool**. |
| [`presentation`](/slides/python-net/fr/aspose.slides/baseslide/presentation/) | Renvoie l’interface IPresentation.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/fr/aspose.slides/baseslide/slide/) |  |

## Méthodes

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Fusionne les fragments de texte ayant le même formatage dans tous les paragraphes de toutes les formes admissibles. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/fr/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Fusionne les fragments de texte ayant le même formatage dans tous les paragraphes de toutes les formes admissibles. |
| [`equals(self, slide)`](/slides/python-net/fr/aspose.slides/baseslide/equals/#ibaseslide) | Détermine si les deux instances IBaseSlide sont égales.<br/>            La valeur de retour est calculée en fonction de la structure de la diapositive et du contenu statique.<br/>            Deux diapositives sont égales si toutes les formes, styles, textes, animations et autres paramètres, etc. sont égaux. La comparaison ne tient pas compte des valeurs d’identifiant uniques, comme SlideId, ni du contenu dynamique, comme la valeur actuelle de la date dans le marqueur de position Date. |
| [`create_theme_effective(self)`](/slides/python-net/fr/aspose.slides/baseslide/create_theme_effective/#) | Renvoie un thème effectif pour cette diapositive. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fr/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Trouve la première occurrence d’une forme avec le texte alternatif spécifié. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)