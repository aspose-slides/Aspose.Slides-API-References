---
title: AudioFrame class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/audioframe/
---
## AudioFrame classe

Représente un clip audio sur une diapositive.

**Héritage:**[`AudioFrame`](/slides/python-net/fr/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/fr/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/fr/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/fr/aspose.slides/shape)

Le type AudioFrame expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/audioframe/is_text_holder/) | Détermine si la forme est TextHolder_PPT.<br/>            Lecture seule **bool**. |
| [`placeholder`](/slides/python-net/fr/aspose.slides/audioframe/placeholder/) | Renvoie l'espace réservé d'une forme. Renvoie None si la forme n'a aucun espace réservé.<br/>            Lecture seule [`IPlaceholder`](/slides/python-net/fr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fr/aspose.slides/audioframe/custom_data/) | Renvoie les données personnalisées de la forme.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/audioframe/raw_frame/) | Renvoie ou définit les propriétés du cadre de forme brut.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fr/aspose.slides/audioframe/frame/) | Renvoie ou définit les propriétés du cadre de forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fr/aspose.slides/audioframe/line_format/) | Renvoie l'objet LineFormat qui contient les propriétés de mise en forme des lignes pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés de ligne.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/audioframe/three_d_format/) | Renvoie l'objet ThreeDFormat qui contient les propriétés d'effet 3D pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés 3D.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides/audioframe/effect_format/) | Renvoie l'objet EffectFormat qui contient les effets pixélisés appliqués à une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés d'effet.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides/audioframe/fill_format/) | Renvoie l'objet FillFormat qui contient les propriétés de mise en forme du remplissage pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés de remplissage.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/audioframe/hyperlink_click/) | Renvoie ou définit le lien hypertexte défini pour le clic de souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/audioframe/hyperlink_mouse_over/) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/audioframe/hyperlink_manager/) | Renvoie le gestionnaire de liens hypertexte.<br/>            Lecture seule [`IHyperlinkManager`](/slides/python-net/fr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fr/aspose.slides/audioframe/hidden/) | Détermine si la forme est masquée.<br/>            Lecture/écriture **bool**. |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/audioframe/z_order_position/) | Renvoie la position d'une forme dans l'ordre Z.<br/>            Shapes[0] renvoie la forme à l'arrière de l'ordre Z,<br/>            et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre Z.<br/>            Lecture seule **int**. |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/audioframe/connection_site_count/) | Renvoie le nombre de points de connexion sur la forme.<br/>            Lecture seule **int**. |
| [`rotation`](/slides/python-net/fr/aspose.slides/audioframe/rotation/) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe Z<br/>            Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative<br/>            indique une rotation dans le sens inverse des aiguilles.<br/>            Lecture/écriture **float**. |
| [`x`](/slides/python-net/fr/aspose.slides/audioframe/x/) | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides/audioframe/y/) | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides/audioframe/width/) | Renvoie ou définit la largeur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides/audioframe/height/) | Renvoie ou définit la hauteur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/audioframe/black_white_mode/) | Cette propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc.<br/>            Lecture/écriture [`BlackWhiteMode`](/slides/python-net/fr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fr/aspose.slides/audioframe/unique_id/) | Renvoie un identifiant interne, limité à la présentation, destiné à être utilisé par les compléments ou autre code.<br/>            Puisque cette valeur peut être réassignée par l'utilisateur ou programmatique, elle ne doit pas être traitée<br/>            comme une clé unique persistante.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.office_interop_shape_id`](/slides/python-net/fr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/audioframe/office_interop_shape_id/) | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et<br/>            permet à PowerPoint ou au code interop de référencer de manière fiable la forme depuis n'importe où dans le document.<br/>            Lecture seule **int**.<br/>            Voir aussi [`Shape.unique_id`](/slides/python-net/fr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/audioframe/alternative_text/) | Renvoie ou définit le texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/audioframe/alternative_text_title/) | Renvoie ou définit le titre du texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`name`](/slides/python-net/fr/aspose.slides/audioframe/name/) | Renvoie ou définit le nom d'une forme.<br/>            Doit ne pas être None. Utilisez une chaîne vide si nécessaire.<br/>            Lecture/écriture **str**. |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/audioframe/is_decorative/) | Obtient ou définit l'option 'Marquer comme décoratif'<br/>            Lecture/écriture **bool**. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/audioframe/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IPictureFrameLock`](/slides/python-net/fr/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/audioframe/is_grouped/) | Détermine si la forme est groupée.<br/>            Lecture seule **bool**. |
| [`parent_group`](/slides/python-net/fr/aspose.slides/audioframe/parent_group/) | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon renvoie None.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fr/aspose.slides/audioframe/slide/) | Renvoie la diapositive parent d'une forme.<br/>            Lecture seule [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fr/aspose.slides/audioframe/presentation/) | Renvoie la présentation parent d'une diapositive.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/fr/aspose.slides/audioframe/shape_style/) | Renvoie l'objet style de la forme.<br/>            Lecture seule [`IShapeStyle`](/slides/python-net/fr/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/fr/aspose.slides/audioframe/shape_type/) | Renvoie ou définit le type AutoShape pour un PictureFrame.<br/>            Tous les éléments autorisés de l'ensemble [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) sont acceptés,<br/>            à l'exception de tous les types de lignes :<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Lecture/écriture [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/fr/aspose.slides/audioframe/adjustments/) | Renvoie une collection des valeurs de réglage de la forme.<br/>            Lecture seule [`IAdjustValueCollection`](/slides/python-net/fr/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/fr/aspose.slides/audioframe/picture_frame_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IPictureFrameLock`](/slides/python-net/fr/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/fr/aspose.slides/audioframe/picture_format/) | Renvoie l'objet PictureFillFormat pour un cadre d'image.<br/>            Lecture seule [`IPictureFillFormat`](/slides/python-net/fr/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/fr/aspose.slides/audioframe/relative_scale_height/) | Renvoie ou définit l'échelle de hauteur (relative à la taille originale de l'image) du cadre d'image. La valeur 1,0 correspond à 100 %.<br/>            Lecture/écriture **float**. |
| [`relative_scale_width`](/slides/python-net/fr/aspose.slides/audioframe/relative_scale_width/) | Renvoie ou définit l'échelle de largeur (relative à la taille originale de l'image) du cadre d'image. La valeur 1,0 correspond à 100 %.<br/>            Lecture/écriture **float**. |
| [`is_cameo`](/slides/python-net/fr/aspose.slides/audioframe/is_cameo/) | Détermine si le PictureFrame est un objet Cameo ou non.<br/>            Lecture seule **bool**. |
| [`audio_cd_start_track`](/slides/python-net/fr/aspose.slides/audioframe/audio_cd_start_track/) | Renvoie ou définit un indice de piste de démarrage.<br/>            Lecture/écriture **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/fr/aspose.slides/audioframe/audio_cd_start_track_time/) | Renvoie ou définit un temps de piste de démarrage.<br/>            Lecture/écriture **int**. |
| [`audio_cd_end_track`](/slides/python-net/fr/aspose.slides/audioframe/audio_cd_end_track/) | Renvoie ou définit un indice de dernière piste<br/>            Lecture/écriture **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/fr/aspose.slides/audioframe/audio_cd_end_track_time/) | Renvoie ou définit un temps de dernière piste.<br/>            Lecture/écriture **int**. |
| [`volume`](/slides/python-net/fr/aspose.slides/audioframe/volume/) | Renvoie ou définit le volume audio.<br/>            Lecture/écriture [`AudioVolumeMode`](/slides/python-net/fr/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/fr/aspose.slides/audioframe/play_mode/) | Renvoie ou définit le mode de lecture audio.<br/>            Lecture/écriture [`AudioPlayModePreset`](/slides/python-net/fr/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/fr/aspose.slides/audioframe/hide_at_showing/) | Détermine si un AudioFrame est masqué.<br/>            Lecture/écriture **bool**. |
| [`play_loop_mode`](/slides/python-net/fr/aspose.slides/audioframe/play_loop_mode/) | Détermine si un audio est en boucle.<br/>            Lecture/écriture **bool**. |
| [`play_across_slides`](/slides/python-net/fr/aspose.slides/audioframe/play_across_slides/) | Détermine si l'audio joue à travers les diapositives.<br/>             Lecture/écriture **bool**. |
| [`rewind_audio`](/slides/python-net/fr/aspose.slides/audioframe/rewind_audio/) | Détermine si l'audio est automatiquement rembobiné au début après la lecture.<br/>             Lecture/écriture **bool**. |
| [`embedded`](/slides/python-net/fr/aspose.slides/audioframe/embedded/) | Détermine si un son est intégré à une présentation.<br/>            Lecture seule **bool**. |
| [`link_path_long`](/slides/python-net/fr/aspose.slides/audioframe/link_path_long/) | Renvoie ou définit le nom d'un fichier audio lié à un AudioFrame.<br/>            Lecture/écriture **str**. |
| [`embedded_audio`](/slides/python-net/fr/aspose.slides/audioframe/embedded_audio/) | Renvoie ou définit l'objet audio intégré.<br/>            Lecture/écriture [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/fr/aspose.slides/audioframe/fade_in_duration/) | Spécifie la durée en millisecondes du fondu d'entrée initial du média.<br/>             Lecture/écriture **float**. |
| [`fade_out_duration`](/slides/python-net/fr/aspose.slides/audioframe/fade_out_duration/) | Spécifie la durée en millisecondes du fondu de sortie final du média.<br/>             Lecture/écriture **float**. |
| [`volume_value`](/slides/python-net/fr/aspose.slides/audioframe/volume_value/) | Renvoie ou définit le volume audio en pourcentage.<br/>             Lecture/écriture **float**. |
| [`trim_from_start`](/slides/python-net/fr/aspose.slides/audioframe/trim_from_start/) | Spécifie la durée à retirer du début du média pendant la lecture, en millisecondes.<br/>            Lecture/écriture **float**. |
| [`trim_from_end`](/slides/python-net/fr/aspose.slides/audioframe/trim_from_end/) | Spécifie la durée à retirer de la fin du média pendant la lecture, en millisecondes.<br/>            Lecture/écriture **float**. |
| [`caption_tracks`](/slides/python-net/fr/aspose.slides/audioframe/caption_tracks/) | Obtient la collection des sous-titres fermés associés au cadre audio.<br/>            Cette propriété est en lecture seule et renvoie un [`ICaptionsCollection`](/slides/python-net/fr/aspose.slides/icaptionscollection) contenant toutes les pistes de sous-titres. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/audioframe/get_image/#) | Renvoie la miniature de la forme.<br/>            Le type ShapeThumbnailBounds.Shape des limites de la miniature de forme est utilisé par défaut. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Renvoie la miniature de la forme. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Enregistre le contenu de Shape au format SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de Shape au format SVG. |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/audioframe/remove_placeholder/#) | Définit que cette forme n'est pas un espace réservé. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Ajoute un nouvel espace réservé s'il n'existe pas et définit les propriétés de l'espace réservé à un spécifié. |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/audioframe/get_base_placeholder/#) | Renvoie une forme d'espace réservé de base (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle hérite).<br/>            Un None est renvoyé si la forme actuelle n'hérite pas. |
| [`get_visual_bounds(self)`](/slides/python-net/fr/aspose.slides/audioframe/get_visual_bounds/#) | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [`get_geometry_paths(self)`](/slides/python-net/fr/aspose.slides/audioframe/get_geometry_paths/#) | Renvoie la copie du chemin de la forme géométrique. Les coordonnées sont relatives au coin supérieur gauche de la forme. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fr/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | Met à jour la géométrie de la forme à partir de l'objet [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme.<br/>             Change le type de la forme ([`GeometryShape.shape_type`](/slides/python-net/fr/aspose.slides/geometryshape/shape_type)) en [`ShapeType.CUSTOM`](/slides/python-net/fr/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fr/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | Met à jour la géométrie de la forme à partir d'un tableau de [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme.<br/>             Change le type de la forme ([`GeometryShape.shape_type`](/slides/python-net/fr/aspose.slides/geometryshape/shape_type)) en [`ShapeType.CUSTOM`](/slides/python-net/fr/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/fr/aspose.slides/audioframe/create_shape_elements/#) | Crée et renvoie un tableau des éléments de la forme. |

### Voir aussi
* classe [`AudioFrame`](/slides/python-net/fr/aspose.slides/audioframe)
* classe [`GeometryShape`](/slides/python-net/fr/aspose.slides/geometryshape)
* classe [`PictureFrame`](/slides/python-net/fr/aspose.slides/pictureframe)
* classe [`Shape`](/slides/python-net/fr/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)