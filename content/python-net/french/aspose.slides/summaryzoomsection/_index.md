---
title: SummaryZoomSection class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection classe

Représente un objet Summary Zoom Section dans un cadre Summary Zoom.

**Héritage:**[`SummaryZoomSection`](/slides/python-net/fr/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/fr/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/fr/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fr/aspose.slides/shape)

Le type SummaryZoomSection expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/summaryzoomsection/is_text_holder/) | Détermine si la forme est TextHolder_PPT.<br/>            Lecture seule **bool**. |
| [`placeholder`](/slides/python-net/fr/aspose.slides/summaryzoomsection/placeholder/) | Renvoie l'espace réservé d’une forme. Renvoie None si la forme n’a pas d'espace réservé.<br/>            Lecture seule [`IPlaceholder`](/slides/python-net/fr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fr/aspose.slides/summaryzoomsection/custom_data/) | Renvoie les données personnalisées de la forme.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/summaryzoomsection/raw_frame/) | Renvoie ou définit les propriétés brutes du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fr/aspose.slides/summaryzoomsection/frame/) | Renvoie ou définit les propriétés du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fr/aspose.slides/summaryzoomsection/line_format/) | Renvoie l’objet LineFormat qui contient les propriétés de mise en forme des lignes pour une forme.<br/>            Remarque: peut renvoyer None pour certains types de formes qui n’ont pas de propriétés de ligne.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/summaryzoomsection/three_d_format/) | Renvoie l’objet ThreeDFormat qui contient les propriétés d’effet 3D pour une forme.<br/>            Remarque: peut renvoyer None pour certains types de formes qui n’ont pas de propriétés 3D.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides/summaryzoomsection/effect_format/) | Renvoie l’objet EffectFormat qui contient les effets pixel appliqués à une forme.<br/>            Remarque: peut renvoyer None pour certains types de formes qui n’ont pas de propriétés d’effet.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides/summaryzoomsection/fill_format/) | Renvoie l’objet FillFormat qui contient les propriétés de remplissage pour une forme.<br/>            Remarque: peut renvoyer None pour certains types de formes qui n’ont pas de propriétés de remplissage.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/summaryzoomsection/hyperlink_click/) | Renvoie ou définit le lien hypertexte défini pour le clic de souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/summaryzoomsection/hyperlink_manager/) | Renvoie le gestionnaire de liens hypertexte.<br/>            Lecture seule [`IHyperlinkManager`](/slides/python-net/fr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fr/aspose.slides/summaryzoomsection/hidden/) | Détermine si la forme est masquée.<br/>            Lecture/écriture **bool**. |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/summaryzoomsection/z_order_position/) | Renvoie la position d’une forme dans l’ordre Z.<br/>            Shapes[0] renvoie la forme à l’arrière de l’ordre Z,<br/>            et Shapes[Shapes.Count - 1] renvoie la forme à l’avant de l’ordre Z.<br/>            Lecture seule **int**. |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/summaryzoomsection/connection_site_count/) | Renvoie le nombre de points de connexion sur la forme.<br/>            Lecture seule **int**. |
| [`rotation`](/slides/python-net/fr/aspose.slides/summaryzoomsection/rotation/) | Renvoie ou définit le nombre de degrés dont la forme spécifiée est pivotée autour de<br/>            l’axe Z. Une valeur positive indique une rotation horaire ; une valeur négative<br/>            indique une rotation antihoraire.<br/>            Lecture/écriture **float**. |
| [`x`](/slides/python-net/fr/aspose.slides/summaryzoomsection/x/) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides/summaryzoomsection/y/) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides/summaryzoomsection/width/) | Obtient ou définit la largeur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides/summaryzoomsection/height/) | Obtient ou définit la hauteur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/summaryzoomsection/black_white_mode/) | Propriété indique comment une forme sera rendue en mode d’affichage noir et blanc..<br/>            Lecture/écriture [`BlackWhiteMode`](/slides/python-net/fr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fr/aspose.slides/summaryzoomsection/unique_id/) | Renvoie un identifiant interne, propre à la présentation, destiné à être utilisé par des modules complémentaires ou autre code.<br/>            Parce que cette valeur peut être réassignée par l’utilisateur ou programmatiquement, elle ne doit pas être considérée<br/>            comme une clé unique persistante.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.office_interop_shape_id`](/slides/python-net/fr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/summaryzoomsection/office_interop_shape_id/) | Renvoie un identifiant unique propre à la diapositive qui reste constant pendant la durée de vie de la forme et<br/>            permet à PowerPoint ou au code d’interopération de référencer fiablement la forme depuis n’importe où dans le document.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.unique_id`](/slides/python-net/fr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/summaryzoomsection/alternative_text/) | Renvoie ou définit le texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/summaryzoomsection/alternative_text_title/) | Renvoie ou définit le titre du texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`name`](/slides/python-net/fr/aspose.slides/summaryzoomsection/name/) | Renvoie ou définit le nom d’une forme.<br/>            Ne doit pas être None. Utilisez une chaîne vide si nécessaire.<br/>            Lecture/écriture **str**. |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/summaryzoomsection/is_decorative/) | Obtient ou définit l’option ‘Mark as decorative’<br/>            Lecture/écriture **bool**. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/summaryzoomsection/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/summaryzoomsection/is_grouped/) | Détermine si la forme est groupée.<br/>            Lecture seule **bool**. |
| [`parent_group`](/slides/python-net/fr/aspose.slides/summaryzoomsection/parent_group/) | Renvoie l’objet GroupShape parent si la forme est groupée. Sinon renvoie None.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fr/aspose.slides/summaryzoomsection/slide/) | Renvoie la diapositive parente d’une forme.<br/>            Lecture seule [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fr/aspose.slides/summaryzoomsection/presentation/) | Renvoie la présentation parente d’une diapositive.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fr/aspose.slides/summaryzoomsection/graphical_object_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/fr/aspose.slides/summaryzoomsection/image_type/) | Obtient ou définit le type d’image d’un objet Zoom.<br/>            Lecture/écriture [`ZoomImageType`](/slides/python-net/fr/aspose.slides/zoomimagetype).<br/>            Valeur par défaut : Preview |
| [`return_to_parent`](/slides/python-net/fr/aspose.slides/summaryzoomsection/return_to_parent/) | Obtient ou définit le comportement de navigation dans le diaporama.<br/>            Lecture/écriture **bool**.<br/>            Valeur par défaut : false |
| [`show_background`](/slides/python-net/fr/aspose.slides/summaryzoomsection/show_background/) | Obtient ou définit la valeur qui spécifie si le Zoom utilisera l’arrière-plan de la diapositive de destination.<br/>            Lecture/écriture **bool**.<br/>            Valeur par défaut : true |
| [`zoom_image`](/slides/python-net/fr/aspose.slides/summaryzoomsection/zoom_image/) | Obtient ou définit l’image pour l’objet Zoom.<br/>            Lecture/écriture [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/fr/aspose.slides/summaryzoomsection/transition_duration/) | Obtient ou définit la durée de la transition entre le Zoom et la diapositive.<br/>            Lecture/écriture **float**.<br/>            Valeur par défaut : 1.0f |
| [`target_section`](/slides/python-net/fr/aspose.slides/summaryzoomsection/target_section/) | Obtient ou définit l’objet section vers lequel l’objet Section Zoom crée un lien.<br/>            Lecture/écriture [`ISection`](/slides/python-net/fr/aspose.slides/isection). |
| [`title`](/slides/python-net/fr/aspose.slides/summaryzoomsection/title/) | Renvoie le titre texte de l’objet Summary Zoom Section. |
| [`description`](/slides/python-net/fr/aspose.slides/summaryzoomsection/description/) | Renvoie la description texte de l’objet Summary Zoom Section. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/summaryzoomsection/get_image/#) | Renvoie la miniature de la forme.<br/>            Le type ShapeThumbnailBounds.Shape des limites de la miniature de forme est utilisé par défaut. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/summaryzoomsection/get_image/#shapethumbnailbounds-float-float) | Renvoie la miniature de la forme. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase) | Enregistre le contenu de la forme en tant que fichier SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de la forme en tant que fichier SVG. |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/summaryzoomsection/remove_placeholder/#) | Définit que cette forme n’est pas un espace réservé. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | Ajoute un nouvel espace réservé s’il n’en existe pas et définit les propriétés de l’espace réservé sur un spécifié. |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/summaryzoomsection/get_base_placeholder/#) | Renvoie une forme espace réservé de base (forme provenant de la disposition et/ou de la diapositive principale dont la forme actuelle hérite).<br/>            None est renvoyé si la forme actuelle n’est pas héritée. |
| [`get_visual_bounds(self)`](/slides/python-net/fr/aspose.slides/summaryzoomsection/get_visual_bounds/#) | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |

### Voir aussi
* classe [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject)
* classe [`SectionZoomFrame`](/slides/python-net/fr/aspose.slides/sectionzoomframe)
* classe [`Shape`](/slides/python-net/fr/aspose.slides/shape)
* classe [`SummaryZoomSection`](/slides/python-net/fr/aspose.slides/summaryzoomsection)
* classe [`ZoomObject`](/slides/python-net/fr/aspose.slides/zoomobject)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)