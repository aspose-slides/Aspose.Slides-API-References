---
title: Ink class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.ink/ink/
---
## Ink classe

Représente un objet d'encre sur une diapositive.

**Héritage:**[`Ink`](/slides/python-net/fr/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fr/aspose.slides/shape)

Le type Ink expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides.ink/ink/is_text_holder/) | Détermine si la forme est TextHolder_PPT.<br/>            Lecture seule **bool**. |
| [`placeholder`](/slides/python-net/fr/aspose.slides.ink/ink/placeholder/) | Renvoie l'espace réservé d'une forme. Renvoie None si la forme n'a pas d'espace réservé.<br/>            Lecture seule [`IPlaceholder`](/slides/python-net/fr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fr/aspose.slides.ink/ink/custom_data/) | Renvoie les données personnalisées de la forme.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fr/aspose.slides.ink/ink/raw_frame/) | Renvoie ou définit les propriétés du cadre brut de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fr/aspose.slides.ink/ink/frame/) | Renvoie ou définit les propriétés du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fr/aspose.slides.ink/ink/line_format/) | Renvoie l'objet LineFormat contenant les propriétés de formatage de ligne pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés de ligne.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fr/aspose.slides.ink/ink/three_d_format/) | Renvoie l'objet ThreeDFormat contenant les propriétés d'effet 3D pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés 3D.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides.ink/ink/effect_format/) | Renvoie l'objet EffectFormat qui contient les effets pixel appliqués à une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés d'effet.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides.ink/ink/fill_format/) | Renvoie l'objet FillFormat contenant les propriétés de formatage de remplissage pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés de remplissage.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides.ink/ink/hyperlink_click/) | Renvoie ou définit le lien hypertexte défini pour le clic de souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides.ink/ink/hyperlink_mouse_over/) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides.ink/ink/hyperlink_manager/) | Renvoie le gestionnaire de liens hypertexte.<br/>            Lecture seule [`IHyperlinkManager`](/slides/python-net/fr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fr/aspose.slides.ink/ink/hidden/) | Détermine si la forme est masquée.<br/>            Lecture/écriture **bool**. |
| [`z_order_position`](/slides/python-net/fr/aspose.slides.ink/ink/z_order_position/) | Renvoie la position d'une forme dans l'ordre Z.<br/>            Shapes[0] renvoie la forme à l'arrière de l'ordre Z,<br/>            et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre Z.<br/>            Lecture seule **int**. |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides.ink/ink/connection_site_count/) | Renvoie le nombre de points de connexion sur la forme.<br/>            Lecture seule **int**. |
| [`rotation`](/slides/python-net/fr/aspose.slides.ink/ink/rotation/) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour<br/>            de l'axe Z. Une valeur positive indique une rotation horaire ; une valeur négative<br/>            indique une rotation antihoraire.<br/>            Lecture/écriture **float**. |
| [`x`](/slides/python-net/fr/aspose.slides.ink/ink/x/) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides.ink/ink/y/) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides.ink/ink/width/) | Obtient ou définit la largeur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides.ink/ink/height/) | Obtient ou définit la hauteur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides.ink/ink/black_white_mode/) | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc.<br/>            Lecture/écriture [`BlackWhiteMode`](/slides/python-net/fr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fr/aspose.slides.ink/ink/unique_id/) | Renvoie un identifiant interne, limité à la présentation, destiné à être utilisé par les extensions ou autre code.<br/>            Parce que cette valeur peut être réassignée par l'utilisateur ou programmatiquement, elle ne doit pas être traitée<br/>            comme une clé unique persistante.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.office_interop_shape_id`](/slides/python-net/fr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides.ink/ink/office_interop_shape_id/) | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et<br/>            permet à PowerPoint ou au code d'interopérabilité de référencer de manière fiable la forme depuis n'importe où dans le document.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.unique_id`](/slides/python-net/fr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fr/aspose.slides.ink/ink/alternative_text/) | Renvoie ou définit le texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides.ink/ink/alternative_text_title/) | Renvoie ou définit le titre du texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`name`](/slides/python-net/fr/aspose.slides.ink/ink/name/) | Renvoie ou définit le nom d'une forme.<br/>            Ne doit pas être None. Utilisez une chaîne vide si nécessaire.<br/>            Lecture/écriture **str**. |
| [`is_decorative`](/slides/python-net/fr/aspose.slides.ink/ink/is_decorative/) | Obtient ou définit l'option « Marquer comme décoratif »<br/>            Lecture/écriture **bool**. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides.ink/ink/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fr/aspose.slides.ink/ink/is_grouped/) | Détermine si la forme est groupée.<br/>            Lecture seule **bool**. |
| [`parent_group`](/slides/python-net/fr/aspose.slides.ink/ink/parent_group/) | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon, renvoie None.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fr/aspose.slides.ink/ink/slide/) | Renvoie la diapositive parent d'une forme.<br/>            Lecture seule [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fr/aspose.slides.ink/ink/presentation/) | Renvoie la présentation parent d'une diapositive.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fr/aspose.slides.ink/ink/graphical_object_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/fr/aspose.slides.ink/ink/traces/) | Obtient toutes les traces contenues dans l'élément IInk [`IInkTrace`](/slides/python-net/fr/aspose.slides.ink/iinktrace).<br/>            Lecture seule. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides.ink/ink/get_image/#) | Renvoie la vignette de la forme.<br/>            Le type ShapeThumbnailBounds.Shape est utilisé par défaut pour les limites de vignette de forme. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | Renvoie la vignette de la forme. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | Enregistre le contenu de la forme au format SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de la forme au format SVG. |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides.ink/ink/remove_placeholder/#) | Définit que cette forme n'est pas un espace réservé. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | Ajoute un nouvel espace réservé s'il n'en existe pas et définit les propriétés de l'espace réservé sur celui spécifié. |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides.ink/ink/get_base_placeholder/#) | Renvoie une forme d'espace réservé de base (forme provenant de la disposition et/ou de la diapositive maîtresse dont la forme actuelle hérite).<br/>            None est renvoyé si la forme actuelle n'est pas héritée. |
| [`get_visual_bounds(self)`](/slides/python-net/fr/aspose.slides.ink/ink/get_visual_bounds/#) | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/fr/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | Enregistre une image dans la collection d'images personnalisées utilisées pour simuler les effets visuels des pinceaux d'encre.<br/>            Ces images sont utilisées lors du rendu de l'encre avec des valeurs [`InkEffectType`](/slides/python-net/fr/aspose.slides.ink/inkeffecttype) spécifiques,<br/>            telles que Galaxy, Rainbow, etc. En fournissant vos propres images, vous pouvez contrôler l'apparence de chaque effet d'encre. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/fr/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | Désenregistre une image de la collection d'images personnalisées utilisées pour simuler les effets visuels des pinceaux d'encre<br/>            précédemment enregistrées via **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide**. |

### Voir aussi
* classe [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject)
* classe [`Ink`](/slides/python-net/fr/aspose.slides.ink/ink)
* classe [`Shape`](/slides/python-net/fr/aspose.slides/shape)
* module [`aspose.slides.ink`](/slides/python-net/fr/aspose.slides.ink)
* bibliothèque [`Aspose.Slides`](/slides/python-net)