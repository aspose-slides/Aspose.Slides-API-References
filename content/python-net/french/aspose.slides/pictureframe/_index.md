---
title: PictureFrame class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/pictureframe/
---
## Classe PictureFrame

Représente un cadre contenant une image.

**Héritage:**[`PictureFrame`](/slides/python-net/fr/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/fr/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/fr/aspose.slides/shape)

Le type PictureFrame expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/pictureframe/is_text_holder/) | Détermine si la forme est TextHolder_PPT.<br/>            Lecture seule **bool**. |
| [`placeholder`](/slides/python-net/fr/aspose.slides/pictureframe/placeholder/) | Renvoie l'espace réservé d'une forme. Renvoie None si la forme n'a pas d'espace réservé.<br/>            Lecture seule [`IPlaceholder`](/slides/python-net/fr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fr/aspose.slides/pictureframe/custom_data/) | Renvoie les données personnalisées de la forme.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/pictureframe/raw_frame/) | Renvoie ou définit les propriétés brutes du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fr/aspose.slides/pictureframe/frame/) | Renvoie ou définit les propriétés du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fr/aspose.slides/pictureframe/line_format/) | Renvoie l'objet LineFormat qui contient les propriétés de mise en forme des lignes pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés de ligne.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/pictureframe/three_d_format/) | Renvoie l'objet ThreeDFormat qui contient les propriétés d'effet 3D d'une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés 3D.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides/pictureframe/effect_format/) | Renvoie l'objet EffectFormat qui contient les effets pixel appliqués à une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés d'effet.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides/pictureframe/fill_format/) | Renvoie l'objet FillFormat qui contient les propriétés de remplissage pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés de remplissage.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/pictureframe/hyperlink_click/) | Renvoie ou définit le lien hypertexte défini pour le clic de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/pictureframe/hyperlink_mouse_over/) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/pictureframe/hyperlink_manager/) | Renvoie le gestionnaire de liens hypertexte.<br/>            Lecture seule [`IHyperlinkManager`](/slides/python-net/fr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fr/aspose.slides/pictureframe/hidden/) | Détermine si la forme est masquée.<br/>            Lecture/écriture **bool**. |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/pictureframe/z_order_position/) | Renvoie la position d'une forme dans l'ordre Z.<br/>            Shapes[0] renvoie la forme située à l'arrière de l'ordre Z,<br/>            et Shapes[Shapes.Count - 1] renvoie la forme située à l'avant de l'ordre Z.<br/>            Lecture seule **int**. |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/pictureframe/connection_site_count/) | Renvoie le nombre de sites de connexion sur la forme.<br/>            Lecture seule **int**. |
| [`rotation`](/slides/python-net/fr/aspose.slides/pictureframe/rotation/) | Renvoie ou définit le nombre de degrés de rotation de la forme autour de l'axe Z.<br/>            Une valeur positive indique une rotation dans le sens horaire ; une valeur négative indique une rotation dans le sens antihoraire.<br/>            Lecture/écriture **float**. |
| [`x`](/slides/python-net/fr/aspose.slides/pictureframe/x/) | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides/pictureframe/y/) | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides/pictureframe/width/) | Renvoie ou définit la largeur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides/pictureframe/height/) | Renvoie ou définit la hauteur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/pictureframe/black_white_mode/) | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc.<br/>            Lecture/écriture [`BlackWhiteMode`](/slides/python-net/fr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fr/aspose.slides/pictureframe/unique_id/) | Renvoie un identifiant interne, limité à la présentation, destiné à être utilisé par des modules complémentaires ou autre code.<br/>            Parce que cette valeur peut être réassignée par l'utilisateur ou programmaticalement, elle ne doit pas être traitée<br/>            comme une clé unique persistante.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.office_interop_shape_id`](/slides/python-net/fr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/pictureframe/office_interop_shape_id/) | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant toute la durée de vie de la forme et<br/>            permet à PowerPoint ou au code d'interopérabilité de référencer de façon fiable la forme depuis n'importe où dans le document.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.unique_id`](/slides/python-net/fr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/pictureframe/alternative_text/) | Renvoie ou définit le texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/pictureframe/alternative_text_title/) | Renvoie ou définit le titre du texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`name`](/slides/python-net/fr/aspose.slides/pictureframe/name/) | Renvoie ou définit le nom d'une forme.<br/>            Doit ne pas être None. Utilisez une chaîne vide si nécessaire.<br/>            Lecture/écriture **str**. |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/pictureframe/is_decorative/) | Renvoie ou définit l'option 'Mark as decorative'<br/>            Lecture/écriture **bool**. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/pictureframe/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IPictureFrameLock`](/slides/python-net/fr/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/pictureframe/is_grouped/) | Détermine si la forme est groupée.<br/>            Lecture seule **bool**. |
| [`parent_group`](/slides/python-net/fr/aspose.slides/pictureframe/parent_group/) | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon, renvoie None.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fr/aspose.slides/pictureframe/slide/) | Renvoie la diapositive parent d'une forme.<br/>            Lecture seule [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fr/aspose.slides/pictureframe/presentation/) | Renvoie la présentation parent d'une diapositive.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/fr/aspose.slides/pictureframe/shape_style/) | Renvoie l'objet style de la forme.<br/>            Lecture seule [`IShapeStyle`](/slides/python-net/fr/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/fr/aspose.slides/pictureframe/shape_type/) | Renvoie ou définit le type AutoShape pour un PictureFrame.<br/>            Tous les éléments du jeu [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) sont autorisés, <br/>            à l'exception de tous les types de lignes :<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Lecture/écriture [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/fr/aspose.slides/pictureframe/adjustments/) | Renvoie une collection des valeurs d'ajustement de la forme.<br/>            Lecture seule [`IAdjustValueCollection`](/slides/python-net/fr/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/fr/aspose.slides/pictureframe/picture_frame_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IPictureFrameLock`](/slides/python-net/fr/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/fr/aspose.slides/pictureframe/picture_format/) | Renvoie l'objet PictureFillFormat pour un cadre image.<br/>            Lecture seule [`IPictureFillFormat`](/slides/python-net/fr/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/fr/aspose.slides/pictureframe/relative_scale_height/) | Renvoie ou définit l'échelle de la hauteur (relative à la taille originale de l'image) du cadre image. La valeur 1,0 correspond à 100 %.<br/>            Lecture/écriture **float**. |
| [`relative_scale_width`](/slides/python-net/fr/aspose.slides/pictureframe/relative_scale_width/) | Renvoie ou définit l'échelle de la largeur (relative à la taille originale de l'image) du cadre image. La valeur 1,0 correspond à 100 %.<br/>            Lecture/écriture **float**. |
| [`is_cameo`](/slides/python-net/fr/aspose.slides/pictureframe/is_cameo/) | Détermine si le PictureFrame est un objet Cameo ou non.<br/>            Lecture seule **bool**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/pictureframe/get_image/#) | Renvoie la miniature de la forme.<br/>            Le type ShapeThumbnailBounds.Shape est utilisé par défaut. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Renvoie la miniature de la forme. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Enregistre le contenu de la forme au format SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de la forme au format SVG. |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/pictureframe/remove_placeholder/#) | Indique que cette forme n'est pas un espace réservé. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Ajoute un nouvel espace réservé s'il n'en existe pas et définit les propriétés de l'espace réservé sur celui spécifié. |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/pictureframe/get_base_placeholder/#) | Renvoie une forme d'espace réservé de base (forme provenant de la mise en page et/ou de la diapositive maîtresse dont la forme actuelle est héritée).<br/>            Un None est renvoyé si la forme actuelle n'est pas héritée. |
| [`get_visual_bounds(self)`](/slides/python-net/fr/aspose.slides/pictureframe/get_visual_bounds/#) | Renvoie les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [`get_geometry_paths(self)`](/slides/python-net/fr/aspose.slides/pictureframe/get_geometry_paths/#) | Renvoie une copie du chemin de la forme géométrique. Les coordonnées sont relatives au coin supérieur gauche de la forme. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fr/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Met à jour la géométrie de la forme à partir de l'objet [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme.<br/>            Modifie le type de la forme ([`GeometryShape.shape_type`](/slides/python-net/fr/aspose.slides/geometryshape/shape_type)) en [`ShapeType.CUSTOM`](/slides/python-net/fr/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fr/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Met à jour la géométrie de la forme à partir d'un tableau de [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme.<br/>            Modifie le type de la forme ([`GeometryShape.shape_type`](/slides/python-net/fr/aspose.slides/geometryshape/shape_type)) en [`ShapeType.CUSTOM`](/slides/python-net/fr/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/fr/aspose.slides/pictureframe/create_shape_elements/#) | Crée et renvoie un tableau des éléments de la forme. |

### Voir aussi
* classe [`GeometryShape`](/slides/python-net/fr/aspose.slides/geometryshape)
* classe [`PictureFrame`](/slides/python-net/fr/aspose.slides/pictureframe)
* classe [`Shape`](/slides/python-net/fr/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)