---
title: AutoShape class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/autoshape/
---
## Classe AutoShape

Représente un AutoShape.

**Héritage:**[`AutoShape`](/slides/python-net/fr/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/fr/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/fr/aspose.slides/shape)

Le type AutoShape expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/autoshape/is_text_holder/) | Détermine si la forme est TextHolder_PPT.<br/>            Lecture seule **bool**. |
| [`placeholder`](/slides/python-net/fr/aspose.slides/autoshape/placeholder/) | Renvoie l'espace réservé d'une forme. Renvoie None si la forme n'a pas d'espace réservé.<br/>            Lecture seule [`IPlaceholder`](/slides/python-net/fr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fr/aspose.slides/autoshape/custom_data/) | Renvoie les données personnalisées de la forme.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/autoshape/raw_frame/) | Renvoie ou définit les propriétés du cadre brut de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fr/aspose.slides/autoshape/frame/) | Renvoie ou définit les propriétés du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fr/aspose.slides/autoshape/line_format/) | Renvoie l'objet LineFormat qui contient les propriétés de formatage de ligne pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés de ligne.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/autoshape/three_d_format/) | Renvoie l'objet ThreeDFormat qui contient les propriétés d'effets 3D pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés 3D.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides/autoshape/effect_format/) | Renvoie l'objet EffectFormat qui contient les effets pixel appliqués à une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés d'effet.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides/autoshape/fill_format/) | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés de remplissage.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/autoshape/hyperlink_click/) | Renvoie ou définit le lien hypertexte défini pour le clic de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/autoshape/hyperlink_mouse_over/) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/autoshape/hyperlink_manager/) | Renvoie le gestionnaire de liens hypertexte.<br/>            Lecture seule [`IHyperlinkManager`](/slides/python-net/fr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fr/aspose.slides/autoshape/hidden/) | Détermine si la forme est cachée.<br/>            Lecture/écriture **bool**. |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/autoshape/z_order_position/) | Renvoie la position d'une forme dans l'ordre Z.<br/>            Shapes[0] renvoie la forme à l'arrière de l'ordre Z,<br/>            et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre Z.<br/>            Lecture seule **int**. |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/autoshape/connection_site_count/) | Renvoie le nombre de points de connexion sur la forme.<br/>            Lecture seule **int**. |
| [`rotation`](/slides/python-net/fr/aspose.slides/autoshape/rotation/) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour<br/>            de l'axe Z. Une valeur positive indique une rotation dans le sens horaire ; une valeur négative<br/>            indique une rotation dans le sens anti-horaire.<br/>            Lecture/écriture **float**. |
| [`x`](/slides/python-net/fr/aspose.slides/autoshape/x/) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides/autoshape/y/) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides/autoshape/width/) | Obtient ou définit la largeur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides/autoshape/height/) | Obtient ou définit la hauteur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/autoshape/black_white_mode/) | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc..<br/>            Lecture/écriture [`BlackWhiteMode`](/slides/python-net/fr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fr/aspose.slides/autoshape/unique_id/) | Renvoie un identifiant interne, propre à la présentation, destiné à être utilisé par les add-ins ou autre code.<br/>            Parce que cette valeur peut être réassignée par l'utilisateur ou programmatiquement, elle ne doit pas être considérée<br/>            comme une clé unique persistante.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.office_interop_shape_id`](/slides/python-net/fr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/autoshape/office_interop_shape_id/) | Renvoie un identifiant unique propre à la diapositive qui reste constant pendant la durée de vie de la forme et<br/>            permet à PowerPoint ou au code d'interopérabilité de référencer de manière fiable la forme depuis n'importe où dans le document.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.unique_id`](/slides/python-net/fr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/autoshape/alternative_text/) | Renvoie ou définit le texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/autoshape/alternative_text_title/) | Renvoie ou définit le titre du texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`name`](/slides/python-net/fr/aspose.slides/autoshape/name/) | Renvoie ou définit le nom d'une forme.<br/>            Ne doit pas être None. Utilisez une chaîne vide si nécessaire.<br/>            Lecture/écriture **str**. |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/autoshape/is_decorative/) | Obtient ou définit l'option 'Mark as decorative'<br/>            Lecture/écriture **bool**. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/autoshape/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IAutoShapeLock`](/slides/python-net/fr/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/autoshape/is_grouped/) | Détermine si la forme est groupée.<br/>            Lecture seule **bool**. |
| [`parent_group`](/slides/python-net/fr/aspose.slides/autoshape/parent_group/) | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon, renvoie None.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fr/aspose.slides/autoshape/slide/) | Renvoie la diapositive parent d'une forme.<br/>            Lecture seule [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fr/aspose.slides/autoshape/presentation/) | Renvoie la présentation parent d'une diapositive.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/fr/aspose.slides/autoshape/shape_style/) | Renvoie l'objet style de la forme.<br/>            Lecture seule [`IShapeStyle`](/slides/python-net/fr/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/fr/aspose.slides/autoshape/shape_type/) | Renvoie ou définit le type de présélection de géométrie.<br/>            Remarque : lors d'un changement de valeur, toutes les valeurs d'ajustement seront réinitialisées à leurs valeurs par défaut.<br/>            Lecture/écriture [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/fr/aspose.slides/autoshape/adjustments/) | Renvoie une collection des valeurs d'ajustement de la forme.<br/>            Lecture seule [`IAdjustValueCollection`](/slides/python-net/fr/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/fr/aspose.slides/autoshape/auto_shape_lock/) | Renvoie les verrous de l'autoshape.<br/>            Lecture seule [`IAutoShapeLock`](/slides/python-net/fr/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/fr/aspose.slides/autoshape/text_frame/) | Renvoie l'objet TextFrame pour l'AutoShape.<br/>            Lecture seule [`ITextFrame`](/slides/python-net/fr/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/fr/aspose.slides/autoshape/use_background_fill/) | Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage.<br/>            Lecture/écriture **bool**. |
| [`is_text_box`](/slides/python-net/fr/aspose.slides/autoshape/is_text_box/) | Spécifie si la forme est une zone de texte. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/autoshape/get_image/#) | Renvoie la miniature de la forme.<br/>            Le type ShapeThumbnailBounds.Shape est utilisé par défaut pour les limites de la miniature de forme. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Renvoie la miniature de la forme. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Enregistre le contenu de Shape en tant que fichier SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de Shape en tant que fichier SVG. |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/autoshape/remove_placeholder/#) | Définit que cette forme n'est pas un espace réservé. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Ajoute un nouvel espace réservé s'il n'y en a pas et définit les propriétés de l'espace réservé à un spécifié. |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/autoshape/get_base_placeholder/#) | Renvoie une forme d'espace réservé de base (forme provenant de la disposition et/ou de la diapositive maîtresse dont la forme actuelle hérite).<br/>            None est renvoyé si la forme actuelle n'hérite pas. |
| [`get_visual_bounds(self)`](/slides/python-net/fr/aspose.slides/autoshape/get_visual_bounds/#) | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [`get_geometry_paths(self)`](/slides/python-net/fr/aspose.slides/autoshape/get_geometry_paths/#) | Renvoie une copie du chemin de la forme géométrique. Les coordonnées sont relatives au coin supérieur gauche de la forme. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fr/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Met à jour la géométrie de la forme à partir de l'objet [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme.<br/>            Change le type de la forme ([`GeometryShape.shape_type`](/slides/python-net/fr/aspose.slides/geometryshape/shape_type)) en [`ShapeType.CUSTOM`](/slides/python-net/fr/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fr/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Met à jour la géométrie de la forme à partir d'un tableau de [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme.<br/>            Change le type de la forme ([`GeometryShape.shape_type`](/slides/python-net/fr/aspose.slides/geometryshape/shape_type)) en [`ShapeType.CUSTOM`](/slides/python-net/fr/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/fr/aspose.slides/autoshape/create_shape_elements/#) | Crée et renvoie un tableau des éléments de la forme. |
| [`add_text_frame(self, text)`](/slides/python-net/fr/aspose.slides/autoshape/add_text_frame/#str) | Ajoute un nouveau TextFrame à une forme.<br/>            Si la forme possède déjà un TextFrame, il modifie simplement son texte. |

### Voir aussi
* classe [`AutoShape`](/slides/python-net/fr/aspose.slides/autoshape)
* classe [`GeometryShape`](/slides/python-net/fr/aspose.slides/geometryshape)
* classe [`Shape`](/slides/python-net/fr/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)