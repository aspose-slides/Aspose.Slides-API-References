---
title: SmartArt class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.smartart/smartart/
---
## classe SmartArt

Représente un diagramme SmartArt

**Héritage:**[`SmartArt`](/slides/python-net/fr/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fr/aspose.slides/shape)

Le type SmartArt expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides.smartart/smartart/is_text_holder/) | Détermine si la forme est TextHolder_PPT.<br/>            Lecture seule **bool**. |
| [`placeholder`](/slides/python-net/fr/aspose.slides.smartart/smartart/placeholder/) | Renvoie l'espace réservé pour une forme. Renvoie None si la forme n'a pas d'espace réservé.<br/>            Lecture seule [`IPlaceholder`](/slides/python-net/fr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fr/aspose.slides.smartart/smartart/custom_data/) | Renvoie les données personnalisées de la forme.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fr/aspose.slides.smartart/smartart/raw_frame/) | Renvoie ou définit les propriétés du cadre brut de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fr/aspose.slides.smartart/smartart/frame/) | Renvoie ou définit les propriétés du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fr/aspose.slides.smartart/smartart/line_format/) | Renvoie l'objet LineFormat qui contient les propriétés de formatage de ligne pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés de ligne.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fr/aspose.slides.smartart/smartart/three_d_format/) | Renvoie l'objet ThreeDFormat qui contient les propriétés d'effet 3D pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés 3D.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides.smartart/smartart/effect_format/) | Renvoie l'objet EffectFormat qui contient les effets pixellisés appliqués à une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés d'effet.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides.smartart/smartart/fill_format/) | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés de remplissage.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides.smartart/smartart/hyperlink_click/) | Renvoie ou définit le lien hypertexte défini pour le clic de souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides.smartart/smartart/hyperlink_manager/) | Renvoie le gestionnaire de liens hypertexte.<br/>            Lecture seule [`IHyperlinkManager`](/slides/python-net/fr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fr/aspose.slides.smartart/smartart/hidden/) | Détermine si la forme est masquée.<br/>            Lecture/écriture **bool**. |
| [`z_order_position`](/slides/python-net/fr/aspose.slides.smartart/smartart/z_order_position/) | Renvoie la position d'une forme dans l'ordre Z.<br/>            Shapes[0] renvoie la forme à l'arrière de l'ordre Z,<br/>            et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre Z.<br/>            Lecture seule **int**. |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides.smartart/smartart/connection_site_count/) | Renvoie le nombre de points de connexion sur la forme.<br/>            Lecture seule **int**. |
| [`rotation`](/slides/python-net/fr/aspose.slides.smartart/smartart/rotation/) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation anti-horaire.<br/>            Lecture/écriture **float**. |
| [`x`](/slides/python-net/fr/aspose.slides.smartart/smartart/x/) | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides.smartart/smartart/y/) | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides.smartart/smartart/width/) | Renvoie ou définit la largeur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides.smartart/smartart/height/) | Renvoie ou définit la hauteur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides.smartart/smartart/black_white_mode/) | La propriété spécifie comment une forme sera rendue en mode d'affichage noir-et-blanc.<br/>            Lecture/écriture [`BlackWhiteMode`](/slides/python-net/fr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fr/aspose.slides.smartart/smartart/unique_id/) | Renvoie un identifiant interne, limité à la présentation, destiné à être utilisé par des add-ins ou autre code.<br/>            Étant donné que cette valeur peut être réassignée par l'utilisateur ou programmé, elle ne doit pas être considérée<br/>            comme une clé unique persistante.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.office_interop_shape_id`](/slides/python-net/fr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides.smartart/smartart/office_interop_shape_id/) | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code interop de référencer la forme de manière fiable depuis n'importe où dans le document.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.unique_id`](/slides/python-net/fr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fr/aspose.slides.smartart/smartart/alternative_text/) | Renvoie ou définit le texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides.smartart/smartart/alternative_text_title/) | Renvoie ou définit le titre du texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`name`](/slides/python-net/fr/aspose.slides.smartart/smartart/name/) | Renvoie ou définit le nom d'une forme.<br/>            Ne doit pas être None. Utilisez la chaîne vide si nécessaire.<br/>            Lecture/écriture **str**. |
| [`is_decorative`](/slides/python-net/fr/aspose.slides.smartart/smartart/is_decorative/) | Renvoie ou définit l'option 'Marquer comme décoratif'<br/>            Lecture/écriture **bool**. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides.smartart/smartart/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fr/aspose.slides.smartart/smartart/is_grouped/) | Détermine si la forme est groupée.<br/>            Lecture seule **bool**. |
| [`parent_group`](/slides/python-net/fr/aspose.slides.smartart/smartart/parent_group/) | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon renvoie None.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fr/aspose.slides.smartart/smartart/slide/) | Renvoie la diapositive parent d'une forme.<br/>            Lecture seule [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fr/aspose.slides.smartart/smartart/presentation/) | Renvoie la présentation parent d'une diapositive.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fr/aspose.slides.smartart/smartart/graphical_object_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/fr/aspose.slides.smartart/smartart/all_nodes/) | Renvoie les collections de tous les nœuds dans l'objet SmartArt.<br/>            Lecture seule [`ISmartArtNodeCollection`](/slides/python-net/fr/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/fr/aspose.slides.smartart/smartart/nodes/) | Renvoie les collections de nœuds racine dans l'objet SmartArt.<br/>            Lecture seule [`ISmartArtNodeCollection`](/slides/python-net/fr/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/fr/aspose.slides.smartart/smartart/layout/) | Renvoie ou définit la disposition de l'objet SmartArt.<br/>            Lecture/écriture [`SmartArtLayoutType`](/slides/python-net/fr/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/fr/aspose.slides.smartart/smartart/quick_style/) | Renvoie ou définit le style rapide de l'objet SmartArt.<br/>            Lecture/écriture [`SmartArtQuickStyleType`](/slides/python-net/fr/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/fr/aspose.slides.smartart/smartart/color_style/) | Renvoie ou définit le style de couleur de l'objet SmartArt.<br/>            Lecture/écriture [`SmartArtColorType`](/slides/python-net/fr/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/fr/aspose.slides.smartart/smartart/is_reversed/) | Renvoie ou définit l'état du diagramme SmartArt concernant LTR (de gauche à droite) ou RTL (de droite à gauche), si le diagramme prend en charge l'inversion.<br/>            Lecture/écriture **bool**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides.smartart/smartart/get_image/#) | Renvoie la miniature de la forme.<br/>            Le type ShapeThumbnailBounds.Shape est utilisé par défaut pour les limites de la miniature. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | Renvoie la miniature de la forme. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | Enregistre le contenu de la forme au format SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de la forme au format SVG. |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides.smartart/smartart/remove_placeholder/#) | Indique que cette forme n'est pas un espace réservé. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | Ajoute un nouvel espace réservé s'il n'y en a pas et définit les propriétés de l'espace réservé à un spécifié. |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides.smartart/smartart/get_base_placeholder/#) | Renvoie une forme d'espace réservé basique (forme provenant de la mise en page et/ou de la diapositive maîtresse dont la forme actuelle hérite).<br/>            Renvoie None si la forme actuelle n'hérite d'aucune. |
| [`get_visual_bounds(self)`](/slides/python-net/fr/aspose.slides.smartart/smartart/get_visual_bounds/#) | Renvoie les limites visuelles de la forme calculées à partir de son contenu rendu. |

### Voir aussi
* classe [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject)
* classe [`Shape`](/slides/python-net/fr/aspose.slides/shape)
* classe [`SmartArt`](/slides/python-net/fr/aspose.slides.smartart/smartart)
* module [`aspose.slides.smartart`](/slides/python-net/fr/aspose.slides.smartart)
* bibliothèque [`Aspose.Slides`](/slides/python-net)