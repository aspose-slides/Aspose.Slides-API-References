---
title: Shape class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/shape/
---
## Shape classe

Représente une forme sur une diapositive.

Le type Shape expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/shape/is_text_holder/) | Détermine si la forme est TextHolder_PPT.<br/>            Lecture seule **bool**. |
| [`placeholder`](/slides/python-net/fr/aspose.slides/shape/placeholder/) | Renvoie l’espace réservé d’une forme. Renvoie None si la forme n’a pas d’espace réservé.<br/>            Lecture seule [`IPlaceholder`](/slides/python-net/fr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fr/aspose.slides/shape/custom_data/) | Renvoie les données personnalisées de la forme.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/shape/raw_frame/) | Renvoie ou définit les propriétés brutes du cadre de forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fr/aspose.slides/shape/frame/) | Renvoie ou définit les propriétés du cadre de forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fr/aspose.slides/shape/line_format/) | Renvoie l’objet LineFormat qui contient les propriétés de formatage de ligne pour une forme.<br/>            Note : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés de ligne.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/shape/three_d_format/) | Renvoie l’objet ThreeDFormat qui contient les propriétés d’effet 3D pour une forme.<br/>            Note : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés 3D.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides/shape/effect_format/) | Renvoie l’objet EffectFormat qui contient les effets pixel appliqués à une forme.<br/>            Note : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés d’effet.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides/shape/fill_format/) | Renvoie l’objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme.<br/>            Note : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés de remplissage.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/shape/hyperlink_click/) | Renvoie ou définit le lien hypertexte défini pour le clic de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/shape/hyperlink_mouse_over/) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/shape/hyperlink_manager/) | Renvoie le gestionnaire de liens hypertexte.<br/>            Lecture seule [`IHyperlinkManager`](/slides/python-net/fr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fr/aspose.slides/shape/hidden/) | Détermine si la forme est masquée.<br/>            Lecture/écriture **bool**. |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/shape/z_order_position/) | Renvoie la position d’une forme dans l’ordre z.<br/>            Shapes[0] renvoie la forme à l’arrière de l’ordre z,<br/>            et Shapes[Shapes.Count - 1] renvoie la forme à l’avant de l’ordre z.<br/>            Lecture seule **int**. |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/shape/connection_site_count/) | Renvoie le nombre de points de connexion sur la forme.<br/>            Lecture seule **int**. |
| [`rotation`](/slides/python-net/fr/aspose.slides/shape/rotation/) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour<br/>            de l’axe z. Une valeur positive indique une rotation horaire ; une valeur négative<br/>            indique une rotation antihoraire.<br/>            Lecture/écriture **float**. |
| [`x`](/slides/python-net/fr/aspose.slides/shape/x/) | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides/shape/y/) | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides/shape/width/) | Renvoie ou définit la largeur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides/shape/height/) | Renvoie ou définit la hauteur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/shape/black_white_mode/) | Propriété qui spécifie comment une forme sera rendue en mode d’affichage noir et blanc.<br/>            Lecture/écriture [`BlackWhiteMode`](/slides/python-net/fr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fr/aspose.slides/shape/unique_id/) | Renvoie un identifiant interne, propre à la présentation, destiné à être utilisé par des modules complémentaires ou d’autres code.<br/>            Puisque cette valeur peut être réassignée par l’utilisateur ou par programme, elle ne doit pas être considérée<br/>            comme une clé unique persistante.<br/>            Lecture seule **int**.<br/>            Voir également [`Shape.office_interop_shape_id`](/slides/python-net/fr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/shape/office_interop_shape_id/) | Renvoie un identifiant unique propre à la diapositive qui reste constant pendant la durée de vie de la forme et<br/>            permet à PowerPoint ou au code d’interopération de référencer de façon fiable la forme depuis n’importe où dans le document.<br/>            Lecture seule **int**.<br/>            Voir également [`Shape.unique_id`](/slides/python-net/fr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/shape/alternative_text/) | Renvoie ou définit le texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/shape/alternative_text_title/) | Renvoie ou définit le titre du texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`name`](/slides/python-net/fr/aspose.slides/shape/name/) | Renvoie ou définit le nom d’une forme.<br/>            Doit ne pas être None. Utilisez une chaîne vide si nécessaire.<br/>            Lecture/écriture **str**. |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/shape/is_decorative/) | Renvoie ou définit l’option « Mark as decorative »<br/>            Lecture/écriture **bool**. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/shape/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IBaseShapeLock`](/slides/python-net/fr/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/shape/is_grouped/) | Détermine si la forme est groupée.<br/>            Lecture seule **bool**. |
| [`parent_group`](/slides/python-net/fr/aspose.slides/shape/parent_group/) | Renvoie l’objet GroupShape parent si la forme est groupée. Sinon renvoie None.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fr/aspose.slides/shape/slide/) | Renvoie la diapositive parente d’une forme.<br/>            Lecture seule [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fr/aspose.slides/shape/presentation/) | Renvoie la présentation parente d’une diapositive.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/shape/get_image/#) | Renvoie la miniature de la forme.<br/>            Le type ShapeThumbnailBounds.Shape est utilisé par défaut pour les limites de la miniature de forme. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | Renvoie la miniature de la forme. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/shape/write_as_svg/#iorawiobase) | Enregistre le contenu de Shape en fichier SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de Shape en fichier SVG. |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/shape/remove_placeholder/#) | Définit que cette forme n’est pas un espace réservé. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/shape/add_placeholder/#iplaceholder) | Ajoute un nouvel espace réservé s’il n’y en a pas et définit les propriétés de l’espace réservé à un spécifié. |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/shape/get_base_placeholder/#) | Renvoie une forme d’espace réservé de base (forme provenant de la diapositive modèle et/ou maîtresse dont la forme actuelle hérite).<br/>            None est renvoyé si la forme actuelle n’est pas héritée. |
| [`get_visual_bounds(self)`](/slides/python-net/fr/aspose.slides/shape/get_visual_bounds/#) | Renvoie les limites visuelles de la forme calculées à partir de son contenu rendu. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)