---
title: IShape class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ishape/
---
## IShape classe

Represente une forme sur une diapositive.

Le type IShape expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/ishape/is_text_holder/) | Détermine si la forme est TextHolder.<br/>            Lecture seule **bool**. |
| [`placeholder`](/slides/python-net/fr/aspose.slides/ishape/placeholder/) | Renvoie l'espace réservé pour une forme.<br/>            Lecture seule [`IPlaceholder`](/slides/python-net/fr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fr/aspose.slides/ishape/custom_data/) | Renvoie les données personnalisées de la forme.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/ishape/raw_frame/) | Renvoie ou définit les propriétés brutes du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fr/aspose.slides/ishape/frame/) | Renvoie ou définit les propriétés du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fr/aspose.slides/ishape/line_format/) | Renvoie l'objet LineFormat qui contient les propriétés de formatage de ligne pour une forme.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/ishape/three_d_format/) | Renvoie l'objet ThreeDFormat qui contient les propriétés de formatage de ligne pour une forme.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides/ishape/effect_format/) | Renvoie l'objet EffectFormat qui contient les effets pixélisés appliqués à une forme.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides/ishape/fill_format/) | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/fr/aspose.slides/ishape/hidden/) | Détermine si la forme est cachée.<br/>            Lecture/écriture **bool**. |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/ishape/z_order_position/) | Renvoie la position d'une forme dans l'ordre Z.<br/>            Shapes[0] renvoie la forme à l'arrière de l'ordre Z,<br/>            et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre Z.<br/>            Lecture seule **int**. |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/ishape/connection_site_count/) | Renvoie le nombre de sites de connexion sur la forme.<br/>            Lecture seule **int**. |
| [`rotation`](/slides/python-net/fr/aspose.slides/ishape/rotation/) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour<br/>            de l'axe Z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative<br/>            indique une rotation dans le sens inverse.<br/>            Lecture/écriture **float**. |
| [`x`](/slides/python-net/fr/aspose.slides/ishape/x/) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides/ishape/y/) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides/ishape/width/) | Obtient ou définit la largeur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides/ishape/height/) | Obtient ou définit la hauteur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/ishape/alternative_text/) | Renvoie ou définit le texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/ishape/alternative_text_title/) | Renvoie ou définit le titre du texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`name`](/slides/python-net/fr/aspose.slides/ishape/name/) | Renvoie ou définit le nom d'une forme.<br/>            Lecture/écriture **str**. |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/ishape/is_decorative/) | Obtient ou définit l'option « Mark as decorative »<br/>            Lecture/écriture **bool**. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/ishape/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IBaseShapeLock`](/slides/python-net/fr/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/fr/aspose.slides/ishape/unique_id/) | Renvoie un identifiant interne, propre à la présentation, destiné à être utilisé par les modules complémentaires ou autre code.<br/>            Parce que cette valeur peut être réassignée par l'utilisateur ou programmé, elle ne doit pas être considérée<br/>            comme une clé unique persistante.<br/>            Lecture seule **int**.<br/>            Voir aussi [`IShape.office_interop_shape_id`](/slides/python-net/fr/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/ishape/office_interop_shape_id/) | Renvoie un identifiant unique propre à la diapositive qui reste constant pendant la vie de la forme et<br/>            permet à PowerPoint ou au code d'interopérabilité de référencer la forme de manière fiable depuis n'importe où dans le document.<br/>            Lecture seule **int**.<br/>            Voir aussi [`IShape.unique_id`](/slides/python-net/fr/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/ishape/is_grouped/) | Détermine si la forme est groupée.<br/>            Lecture seule **bool**. |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/ishape/black_white_mode/) | La propriété indique comment une forme sera rendue en mode d'affichage noir et blanc..<br/>            Lecture/écriture [`BlackWhiteMode`](/slides/python-net/fr/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/fr/aspose.slides/ishape/parent_group/) | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon renvoie None.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fr/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/ishape/hyperlink_manager/) |  |

## Méthodes

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/ishape/get_image/#) | Renvoie la miniature de la forme.<br/>            Le type ShapeThumbnailBounds.Shape est utilisé par défaut pour les limites de la miniature. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Renvoie la miniature de la forme. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/ishape/write_as_svg/#iorawiobase) | Enregistre le contenu de la forme au format SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de la forme au format SVG. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/ishape/add_placeholder/#iplaceholder) | Ajoute un nouvel espace réservé s'il n'existe pas et définit les propriétés de l'espace réservé sur celui spécifié. |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/ishape/remove_placeholder/#) | Indique que cette forme n'est pas un espace réservé. |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/ishape/get_base_placeholder/#) | Renvoie une forme d'espace réservé basique (forme provenant de la diapositive modèle et/ou maître dont la forme actuelle est héritée).<br/>            Renvoie None si la forme actuelle n'est pas héritée. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)