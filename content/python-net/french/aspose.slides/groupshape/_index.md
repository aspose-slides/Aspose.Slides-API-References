---
title: GroupShape class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/groupshape/
---
## classe GroupShape

Représente un groupe de formes sur une diapositive.

**Inheritance:**[`GroupShape`](/slides/python-net/fr/aspose.slides/groupshape) → [`Shape`](/slides/python-net/fr/aspose.slides/shape)

Le type GroupShape expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/groupshape/is_text_holder/) | Détermine si la forme est TextHolder_PPT.<br/>            Lecture seule **bool**. |
| [`placeholder`](/slides/python-net/fr/aspose.slides/groupshape/placeholder/) | Renvoie l’espace réservé d’une forme. Renvoie None si la forme n’a pas d’espace réservé.<br/>            Lecture seule [`IPlaceholder`](/slides/python-net/fr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fr/aspose.slides/groupshape/custom_data/) | Renvoie les données personnalisées de la forme.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/groupshape/raw_frame/) | Renvoie ou définit les propriétés du cadre brut de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fr/aspose.slides/groupshape/frame/) | Renvoie ou définit les propriétés du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fr/aspose.slides/groupshape/line_format/) | Renvoie l’objet LineFormat qui contient les propriétés de format de ligne pour une forme.<br/>            Note : renvoie None pour les objets GroupShape car ils n’ont pas de propriétés de ligne.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/groupshape/three_d_format/) | Renvoie l’objet ThreeDFormat qui contient les propriétés d’effet 3 d pour une forme.<br/>            Note : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés 3 d.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides/groupshape/effect_format/) | Renvoie l’objet EffectFormat qui contient les effets pixel appliqués à une forme.<br/>            Note : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés d’effet.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides/groupshape/fill_format/) | Renvoie l’objet FillFormat qui contient les propriétés de format de remplissage pour une forme.<br/>            Note : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés de remplissage.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/groupshape/hyperlink_click/) | Renvoie ou définit le lien hypertexte défini pour le clic de souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/groupshape/hyperlink_mouse_over/) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/groupshape/hyperlink_manager/) | Renvoie le gestionnaire de liens hypertexte.<br/>            Lecture seule [`IHyperlinkManager`](/slides/python-net/fr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fr/aspose.slides/groupshape/hidden/) | Détermine si la forme est masquée.<br/>            Lecture/écriture **bool**. |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/groupshape/z_order_position/) | Renvoie la position d’une forme dans l’ordre Z.<br/>            Shapes[0] renvoie la forme à l’arrière de l’ordre Z,<br/>            et Shapes[Shapes.Count - 1] renvoie la forme à l’avant de l’ordre Z.<br/>            Lecture seule **int**. |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/groupshape/connection_site_count/) | Renvoie le nombre de points de connexion sur la forme.<br/>            Lecture seule **int**. |
| [`rotation`](/slides/python-net/fr/aspose.slides/groupshape/rotation/) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l’axe Z.<br/>            Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire.<br/>            Lecture/écriture **float**. |
| [`x`](/slides/python-net/fr/aspose.slides/groupshape/x/) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides/groupshape/y/) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides/groupshape/width/) | Obtient ou définit la largeur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides/groupshape/height/) | Obtient ou définit la hauteur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/groupshape/black_white_mode/) | La propriété spécifie comment une forme sera rendue en mode d’affichage noir et blanc.<br/>            Lecture/écriture [`BlackWhiteMode`](/slides/python-net/fr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fr/aspose.slides/groupshape/unique_id/) | Renvoie un identifiant interne, limité à la présentation, destiné à être utilisé par des compléments ou autre code.<br/>            Comme cette valeur peut être réaffectée par l’utilisateur ou programmé, elle ne doit pas être traitée comme une clé unique persistante.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.office_interop_shape_id`](/slides/python-net/fr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/groupshape/office_interop_shape_id/) | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant toute la durée de vie de la forme et permet à PowerPoint ou au code d’interopérabilité de référencer la forme de façon fiable depuis n’importe où dans le document.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.unique_id`](/slides/python-net/fr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/groupshape/alternative_text/) | Renvoie ou définit le texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/groupshape/alternative_text_title/) | Renvoie ou définit le titre du texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`name`](/slides/python-net/fr/aspose.slides/groupshape/name/) | Renvoie ou définit le nom d’une forme.<br/>            Ne doit pas être None. Utilisez une chaîne vide si nécessaire.<br/>            Lecture/écriture **str**. |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/groupshape/is_decorative/) | Obtient ou définit l’option « Mark as decorative »<br/>            Lecture/écriture **bool**. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/groupshape/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGroupShapeLock`](/slides/python-net/fr/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/groupshape/is_grouped/) | Détermine si la forme est groupée.<br/>            Lecture seule **bool**. |
| [`parent_group`](/slides/python-net/fr/aspose.slides/groupshape/parent_group/) | Renvoie l’objet GroupShape parent si la forme est groupée. Sinon, renvoie None.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fr/aspose.slides/groupshape/slide/) | Renvoie la diapositive parent d’une forme.<br/>            Lecture seule [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fr/aspose.slides/groupshape/presentation/) | Renvoie la présentation parent d’une diapositive.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/fr/aspose.slides/groupshape/group_shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGroupShapeLock`](/slides/python-net/fr/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/fr/aspose.slides/groupshape/shapes/) | Renvoie la collection de formes à l’intérieur du groupe.<br/>            Lecture seule [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection). |

## Méthodes

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/groupshape/get_image/#) | Renvoie la miniature de la forme.<br/>            Le type ShapeThumbnailBounds.Shape de la zone de la miniature de forme est utilisé par défaut. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | Renvoie la miniature de la forme. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/groupshape/write_as_svg/#iorawiobase) | Enregistre le contenu de la forme sous forme de fichier SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de la forme sous forme de fichier SVG. |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/groupshape/remove_placeholder/#) | Définit que cette forme n’est pas un espace réservé. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/groupshape/add_placeholder/#iplaceholder) | Ajoute un nouvel espace réservé s’il n’en existe pas et définit les propriétés de l’espace réservé sur celui spécifié. |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/groupshape/get_base_placeholder/#) | Renvoie une forme d’espace réservé de base (forme du diaporama modèle ou de la disposition dont la forme actuelle hérite).<br/>            None est renvoyé si la forme actuelle n’hérite pas. |
| [`get_visual_bounds(self)`](/slides/python-net/fr/aspose.slides/groupshape/get_visual_bounds/#) | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |


### Voir aussi
* class [`GroupShape`](/slides/python-net/fr/aspose.slides/groupshape)
* class [`Shape`](/slides/python-net/fr/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)