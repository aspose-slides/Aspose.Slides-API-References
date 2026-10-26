---
title: ZoomFrame class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/zoomframe/
---
## classe ZoomFrame

Représente un objet Slide Zoom dans une diapositive.

**Inheritance:**[`ZoomFrame`](/slides/python-net/fr/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/fr/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fr/aspose.slides/shape)

Le type ZoomFrame expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/zoomframe/is_text_holder/) | Détermine si la forme est TextHolder_PPT.<br/>            Lecture seule **bool**. |
| [`placeholder`](/slides/python-net/fr/aspose.slides/zoomframe/placeholder/) | Renvoie l’espace réservé d’une forme. Renvoie None si la forme n’a aucun espace réservé.<br/>            Lecture seule [`IPlaceholder`](/slides/python-net/fr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fr/aspose.slides/zoomframe/custom_data/) | Renvoie les données personnalisées de la forme.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/zoomframe/raw_frame/) | Renvoie ou définit les propriétés du cadre brut de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fr/aspose.slides/zoomframe/frame/) | Renvoie ou définit les propriétés du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fr/aspose.slides/zoomframe/line_format/) | Renvoie l’objet LineFormat qui contient les propriétés de formatage des lignes d’une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés de ligne.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/zoomframe/three_d_format/) | Renvoie l’objet ThreeDFormat qui contient les propriétés d’effet 3D d’une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés 3D.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides/zoomframe/effect_format/) | Renvoie l’objet EffectFormat qui contient les effets pixel appliqués à une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés d’effet.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides/zoomframe/fill_format/) | Renvoie l’objet FillFormat qui contient les propriétés de formatage du remplissage d’une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés de remplissage.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/zoomframe/hyperlink_click/) | Renvoie ou définit le lien hypertexte défini pour le clic de souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/zoomframe/hyperlink_mouse_over/) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/zoomframe/hyperlink_manager/) | Renvoie le gestionnaire de liens hypertexte.<br/>            Lecture seule [`IHyperlinkManager`](/slides/python-net/fr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fr/aspose.slides/zoomframe/hidden/) | Détermine si la forme est masquée.<br/>            Lecture/écriture **bool**. |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/zoomframe/z_order_position/) | Renvoie la position d’une forme dans l’ordre z.<br/>            Shapes[0] renvoie la forme à l’arrière de l’ordre z,<br/>            et Shapes[Shapes.Count - 1] renvoie la forme à l’avant de l’ordre z.<br/>            Lecture seule **int**. |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/zoomframe/connection_site_count/) | Renvoie le nombre de points de connexion sur la forme.<br/>            Lecture seule **int**. |
| [`rotation`](/slides/python-net/fr/aspose.slides/zoomframe/rotation/) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l’axe z.<br/>            Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire.<br/>            Lecture/écriture **float**. |
| [`x`](/slides/python-net/fr/aspose.slides/zoomframe/x/) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides/zoomframe/y/) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides/zoomframe/width/) | Obtient ou définit la largeur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides/zoomframe/height/) | Obtient ou définit la hauteur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/zoomframe/black_white_mode/) | La propriété spécifie comment une forme sera rendue en mode d’affichage noir et blanc.<br/>            Lecture/écriture [`BlackWhiteMode`](/slides/python-net/fr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fr/aspose.slides/zoomframe/unique_id/) | Renvoie un identifiant interne limité à la présentation, destiné à être utilisé par des modules complémentaires ou autre code.<br/>            Comme cette valeur peut être réassignée par l’utilisateur ou programmatiquement, elle ne doit pas être considérée comme une clé unique persistante.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.office_interop_shape_id`](/slides/python-net/fr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/zoomframe/office_interop_shape_id/) | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et<br/>            permet à PowerPoint ou au code d’interopérabilité de référencer de manière fiable la forme depuis n’importe où dans le document.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.unique_id`](/slides/python-net/fr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/zoomframe/alternative_text/) | Renvoie ou définit le texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/zoomframe/alternative_text_title/) | Renvoie ou définit le titre du texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`name`](/slides/python-net/fr/aspose.slides/zoomframe/name/) | Renvoie ou définit le nom d’une forme.<br/>            Ne doit pas être None. Utilisez une chaîne vide si nécessaire.<br/>            Lecture/écriture **str**. |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/zoomframe/is_decorative/) | Obtient ou définit l’option « Mark as decorative »<br/>            Lecture/écriture **bool**. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/zoomframe/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/zoomframe/is_grouped/) | Détermine si la forme est groupée.<br/>            Lecture seule **bool**. |
| [`parent_group`](/slides/python-net/fr/aspose.slides/zoomframe/parent_group/) | Renvoie l’objet GroupShape parent si la forme est groupée. Sinon renvoie None.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fr/aspose.slides/zoomframe/slide/) | Renvoie la diapositive parente d’une forme.<br/>            Lecture seule [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fr/aspose.slides/zoomframe/presentation/) | Renvoie la présentation parente d’une diapositive.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fr/aspose.slides/zoomframe/graphical_object_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/fr/aspose.slides/zoomframe/image_type/) | Obtient ou définit le type d’image d’un objet zoom.<br/>            Lecture/écriture [`ZoomImageType`](/slides/python-net/fr/aspose.slides/zoomimagetype).<br/>            Valeur par défaut : Preview |
| [`return_to_parent`](/slides/python-net/fr/aspose.slides/zoomframe/return_to_parent/) | Obtient ou définit le comportement de navigation dans le diaporama.<br/>            Lecture/écriture **bool**.<br/>            Valeur par défaut : false |
| [`show_background`](/slides/python-net/fr/aspose.slides/zoomframe/show_background/) | Obtient ou définit la valeur qui indique si le Zoom utilisera l’arrière-plan de la diapositive de destination.<br/>            Lecture/écriture **bool**.<br/>            Valeur par défaut : true |
| [`zoom_image`](/slides/python-net/fr/aspose.slides/zoomframe/zoom_image/) | Obtient ou définit l’image pour l’objet zoom.<br/>            Lecture/écriture [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/fr/aspose.slides/zoomframe/transition_duration/) | Obtient ou définit la durée de la transition entre le Zoom et la diapositive.<br/>            Lecture/écriture **float**.<br/>            Valeur par défaut : 1.0f |
| [`target_slide`](/slides/python-net/fr/aspose.slides/zoomframe/target_slide/) | Obtient ou définit l’objet diapositive vers lequel l’objet Slide Zoom crée un lien.<br/>            Lecture/écriture [`ISlide`](/slides/python-net/fr/aspose.slides/islide). |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/zoomframe/get_image/#) | Renvoie la miniature de la forme.<br/>            Le type ShapeThumbnailBounds.Shape est utilisé par défaut pour les limites de la miniature. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | Renvoie la miniature de la forme. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | Enregistre le contenu de la forme en tant que fichier SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de la forme en tant que fichier SVG. |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/zoomframe/remove_placeholder/#) | Indique que cette forme n’est pas un espace réservé. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | Ajoute un nouvel espace réservé s’il n’en existe pas et définit les propriétés de l’espace réservé à un spécifié. |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/zoomframe/get_base_placeholder/#) | Renvoie une forme d’espace réservé basique (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle hérite).<br/>            None est renvoyé si la forme actuelle n’est pas héritée. |
| [`get_visual_bounds(self)`](/slides/python-net/fr/aspose.slides/zoomframe/get_visual_bounds/#) | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |

### Voir aussi
* classe [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject)
* classe [`Shape`](/slides/python-net/fr/aspose.slides/shape)
* classe [`ZoomFrame`](/slides/python-net/fr/aspose.slides/zoomframe)
* classe [`ZoomObject`](/slides/python-net/fr/aspose.slides/zoomobject)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)