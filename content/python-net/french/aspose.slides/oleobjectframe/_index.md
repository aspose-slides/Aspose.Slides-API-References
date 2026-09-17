---
title: OleObjectFrame class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/oleobjectframe/
---
## OleObjectFrame classe

Represents an OLE object on a slide.

**Inheritance:**[`OleObjectFrame`](/slides/python-net/fr/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fr/aspose.slides/shape)

The OleObjectFrame type exposes the following members:

## Propriétés

| Propriété | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/oleobjectframe/is_text_holder/) | Détermine si la forme est TextHolder_PPT.<br/>            Lecture seule **bool**. |
| [`placeholder`](/slides/python-net/fr/aspose.slides/oleobjectframe/placeholder/) | Renvoie l’espace réservé d’une forme. Renvoie None si la forme n’a aucun espace réservé.<br/>            Lecture seule [`IPlaceholder`](/slides/python-net/fr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fr/aspose.slides/oleobjectframe/custom_data/) | Renvoie les données personnalisées de la forme.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/oleobjectframe/raw_frame/) | Renvoie ou définit les propriétés du cadre brut de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fr/aspose.slides/oleobjectframe/frame/) | Renvoie ou définit les propriétés du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fr/aspose.slides/oleobjectframe/line_format/) | Renvoie l’objet LineFormat qui contient les propriétés de formatage de ligne pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés de ligne.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/oleobjectframe/three_d_format/) | Renvoie l’objet ThreeDFormat qui contient les propriétés d’effet 3D pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés 3D.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides/oleobjectframe/effect_format/) | Renvoie l’objet EffectFormat qui contient les effets pixel appliqués à une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés d’effet.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides/oleobjectframe/fill_format/) | Renvoie l’objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n’ont pas de propriétés de remplissage.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/oleobjectframe/hyperlink_click/) | Renvoie ou définit le lien hypertexte défini pour le clic de souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/oleobjectframe/hyperlink_manager/) | Renvoie le gestionnaire de liens hypertexte.<br/>            Lecture seule [`IHyperlinkManager`](/slides/python-net/fr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fr/aspose.slides/oleobjectframe/hidden/) | Détermine si la forme est masquée.<br/>            Lecture/écriture **bool**. |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/oleobjectframe/z_order_position/) | Renvoie la position d’une forme dans l’ordre z.<br/>            Shapes[0] renvoie la forme à l’arrière de l’ordre z,<br/>            et Shapes[Shapes.Count - 1] renvoie la forme à l’avant de l’ordre z.<br/>            Lecture seule **int**. |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/oleobjectframe/connection_site_count/) | Renvoie le nombre de points de connexion sur la forme.<br/>            Lecture seule **int**. |
| [`rotation`](/slides/python-net/fr/aspose.slides/oleobjectframe/rotation/) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l’axe z.<br/>            Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation anti-horaire.<br/>            Lecture/écriture **float**. |
| [`x`](/slides/python-net/fr/aspose.slides/oleobjectframe/x/) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides/oleobjectframe/y/) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides/oleobjectframe/width/) | Obtient ou définit la largeur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides/oleobjectframe/height/) | Obtient ou définit la hauteur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/oleobjectframe/black_white_mode/) | La propriété indique comment une forme sera rendue en mode d’affichage noir et blanc..<br/>            Lecture/écriture [`BlackWhiteMode`](/slides/python-net/fr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fr/aspose.slides/oleobjectframe/unique_id/) | Renvoie un identifiant interne, limité à la présentation, destiné à être utilisé par les modules complémentaires ou autre code.<br/>            Comme cette valeur peut être réassignée par l’utilisateur ou programmé, elle ne doit pas être traitée<br/>            comme une clé unique persistante.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.office_interop_shape_id`](/slides/python-net/fr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/oleobjectframe/office_interop_shape_id/) | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et<br/>            permet à PowerPoint ou au code interop de référencer la forme de manière fiable depuis n’importe où dans le document.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.unique_id`](/slides/python-net/fr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/oleobjectframe/alternative_text/) | Renvoie ou définit le texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/oleobjectframe/alternative_text_title/) | Renvoie ou définit le titre du texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`name`](/slides/python-net/fr/aspose.slides/oleobjectframe/name/) | Renvoie ou définit le nom d’une forme.<br/>            Doit ne pas être None. Utilisez une chaîne vide si nécessaire.<br/>            Lecture/écriture **str**. |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/oleobjectframe/is_decorative/) | Obtient ou définit l’option « Mark as decorative »<br/>            Lecture/écriture **bool**. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/oleobjectframe/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/oleobjectframe/is_grouped/) | Détermine si la forme est groupée.<br/>            Lecture seule **bool**. |
| [`parent_group`](/slides/python-net/fr/aspose.slides/oleobjectframe/parent_group/) | Renvoie l’objet GroupShape parent si la forme est groupée. Sinon renvoie None.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fr/aspose.slides/oleobjectframe/slide/) | Renvoie la diapositive parent d’une forme.<br/>            Lecture seule [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fr/aspose.slides/oleobjectframe/presentation/) | Renvoie la présentation parent d’une diapositive.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fr/aspose.slides/oleobjectframe/graphical_object_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/fr/aspose.slides/oleobjectframe/substitute_picture_format/) | Renvoie l’objet des propriétés de remplissage d’image OleObject.<br/>            Lecture seule [`IPictureFillFormat`](/slides/python-net/fr/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/fr/aspose.slides/oleobjectframe/substitute_picture_title/) | Renvoie ou définit le titre pour l’icône OleObject.<br/>            Lecture/écriture **str**. |
| [`object_name`](/slides/python-net/fr/aspose.slides/oleobjectframe/object_name/) | Renvoie ou définit le nom d’un objet.<br/>            Lecture/écriture **str**. |
| [`object_prog_id`](/slides/python-net/fr/aspose.slides/oleobjectframe/object_prog_id/) | Renvoie le ProgID d’un objet.<br/>            Lecture seule **str**. |
| [`link_file_name`](/slides/python-net/fr/aspose.slides/oleobjectframe/link_file_name/) | Renvoie le chemin complet vers un fichier lié. Le nom de fichier court sera utilisé.<br/>            Lecture seule **str**. |
| [`link_path_long`](/slides/python-net/fr/aspose.slides/oleobjectframe/link_path_long/) | Renvoie le chemin complet vers un fichier lié. Le nom de fichier long sera utilisé.<br/>            Lecture/écriture **str**. |
| [`link_path_relative`](/slides/python-net/fr/aspose.slides/oleobjectframe/link_path_relative/) | Renvoie le chemin relatif vers un fichier lié s’il est présent, sinon renvoie une chaîne vide.<br/>             Lecture seule **str**. |
| [`embedded_file_label`](/slides/python-net/fr/aspose.slides/oleobjectframe/embedded_file_label/) | Renvoie le nom de fichier de l’objet OLE incorporé |
| [`embedded_file_name`](/slides/python-net/fr/aspose.slides/oleobjectframe/embedded_file_name/) | Renvoie le chemin de l’objet OLE incorporé |
| [`embedded_data`](/slides/python-net/fr/aspose.slides/oleobjectframe/embedded_data/) | Obtient ou définit les informations concernant les données OLE incorporées.<br/>            Lecture/écriture [`IOleEmbeddedDataInfo`](/slides/python-net/fr/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/fr/aspose.slides/oleobjectframe/is_object_icon/) | Détermine si un objet est visible sous forme d’icône.<br/>            Lecture/écriture **bool**. |
| [`is_object_link`](/slides/python-net/fr/aspose.slides/oleobjectframe/is_object_link/) | Détermine si un objet est lié à un fichier externe.<br/>            Lecture seule **bool**. |
| [`update_automatic`](/slides/python-net/fr/aspose.slides/oleobjectframe/update_automatic/) | Détermine si l’objet incorporé lié est automatiquement mis à jour lorsque la présentation est ouverte ou imprimée.<br/>            Lecture/écriture **bool**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/oleobjectframe/get_image/#) | Renvoie la vignette de la forme.<br/>            Le type ShapeThumbnailBounds.Shape est utilisé par défaut pour les limites de la vignette. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Renvoie la vignette de la forme. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Enregistre le contenu de la forme sous forme de fichier SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de la forme sous forme de fichier SVG. |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/oleobjectframe/remove_placeholder/#) | Indique que cette forme n’est pas un espace réservé. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Ajoute un nouvel espace réservé s’il n’en existe pas et définit ses propriétés sur celui spécifié. |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/oleobjectframe/get_base_placeholder/#) | Renvoie une forme d’espace réservé de base (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle hérite).<br/>            Renvoie None si la forme actuelle n’est pas héritée. |
| [`get_visual_bounds(self)`](/slides/python-net/fr/aspose.slides/oleobjectframe/get_visual_bounds/#) | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/fr/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Définit les informations concernant les données OLE incorporées.<br/>            <br/>            Cette méthode modifie les propriétés de l’objet pour refléter les nouvelles données et <br/>            définit le drapeau IsObjectLink à false, indiquant que l’objet OLE est incorporé. |

### Voir aussi
* classe [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject)
* classe [`OleObjectFrame`](/slides/python-net/fr/aspose.slides/oleobjectframe)
* classe [`Shape`](/slides/python-net/fr/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)