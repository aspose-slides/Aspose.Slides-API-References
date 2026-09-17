---
title: IAudioFrame class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/iaudioframe/
---
## IAudioFrame classe

Représente un clip audio sur une diapositive.

Le type IAudioFrame expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`audio_cd_start_track`](/slides/python-net/fr/aspose.slides/iaudioframe/audio_cd_start_track/) | Renvoie ou définit un indice de piste de départ.<br/>            Lecture/écriture **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/fr/aspose.slides/iaudioframe/audio_cd_start_track_time/) | Renvoie ou définit le temps de la piste de départ.<br/>            Lecture/écriture **int**. |
| [`audio_cd_end_track`](/slides/python-net/fr/aspose.slides/iaudioframe/audio_cd_end_track/) | Renvoie ou définit un indice de dernière piste<br/>            Lecture/écriture **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/fr/aspose.slides/iaudioframe/audio_cd_end_track_time/) | Renvoie ou définit le temps de la dernière piste.<br/>            Lecture/écriture **int**. |
| [`volume`](/slides/python-net/fr/aspose.slides/iaudioframe/volume/) | Renvoie ou définit le volume audio.<br/>            Lecture/écriture [`AudioVolumeMode`](/slides/python-net/fr/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/fr/aspose.slides/iaudioframe/play_mode/) | Renvoie ou définit le mode de lecture audio.<br/>            Lecture/écriture [`AudioPlayModePreset`](/slides/python-net/fr/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/fr/aspose.slides/iaudioframe/hide_at_showing/) | Détermine si un AudioFrame est masqué.<br/>            Lecture/écriture **bool**. |
| [`play_loop_mode`](/slides/python-net/fr/aspose.slides/iaudioframe/play_loop_mode/) | Détermine si un audio est en boucle.<br/>            Lecture/écriture **bool**. |
| [`play_across_slides`](/slides/python-net/fr/aspose.slides/iaudioframe/play_across_slides/) | Détermine si un audio est lu de façon continue à travers les diapositives.<br/>             Lecture/écriture **bool**. |
| [`rewind_audio`](/slides/python-net/fr/aspose.slides/iaudioframe/rewind_audio/) | Détermine si un audio revient automatiquement au début après la lecture.<br/>             Lecture/écriture **bool**. |
| [`embedded`](/slides/python-net/fr/aspose.slides/iaudioframe/embedded/) | Détermine si un son est intégré à une présentation.<br/>            Lecture seule **bool**. |
| [`link_path_long`](/slides/python-net/fr/aspose.slides/iaudioframe/link_path_long/) | Renvoie ou définit le nom d'un fichier audio lié à un AudioFrame.<br/>            Lecture/écriture **str**. |
| [`embedded_audio`](/slides/python-net/fr/aspose.slides/iaudioframe/embedded_audio/) | Renvoie ou définit l'objet audio intégré.<br/>            Lecture/écriture [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/fr/aspose.slides/iaudioframe/fade_in_duration/) | Spécifie la durée du fondu d'entrée initial du média en millisecondes.<br/>             Lecture/écriture **float**. |
| [`fade_out_duration`](/slides/python-net/fr/aspose.slides/iaudioframe/fade_out_duration/) | Spécifie la durée du fondu de sortie final du média en millisecondes.<br/>             Lecture/écriture **float**. |
| [`volume_value`](/slides/python-net/fr/aspose.slides/iaudioframe/volume_value/) | Renvoie ou définit le volume audio en pourcentage.<br/>             Lecture/écriture **float**. |
| [`trim_from_start`](/slides/python-net/fr/aspose.slides/iaudioframe/trim_from_start/) | Spécifie la durée à supprimer du début du média pendant la lecture, en millisecondes.<br/>            Lecture/écriture **float**. |
| [`trim_from_end`](/slides/python-net/fr/aspose.slides/iaudioframe/trim_from_end/) | Spécifie la durée à supprimer de la fin du média pendant la lecture, en millisecondes.<br/>            Lecture/écriture **float**. |
| [`caption_tracks`](/slides/python-net/fr/aspose.slides/iaudioframe/caption_tracks/) | Obtient la collection de sous-titres fermés associés à la trame audio.<br/>            Cette propriété est en lecture seule et renvoie un [`ICaptionsCollection`](/slides/python-net/fr/aspose.slides/icaptionscollection) contenant toutes les pistes de sous-titres. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/iaudioframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/fr/aspose.slides/iaudioframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/fr/aspose.slides/iaudioframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/fr/aspose.slides/iaudioframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/fr/aspose.slides/iaudioframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/fr/aspose.slides/iaudioframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/fr/aspose.slides/iaudioframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/fr/aspose.slides/iaudioframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/iaudioframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/fr/aspose.slides/iaudioframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/fr/aspose.slides/iaudioframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/iaudioframe/raw_frame/) |  |
| [`frame`](/slides/python-net/fr/aspose.slides/iaudioframe/frame/) |  |
| [`line_format`](/slides/python-net/fr/aspose.slides/iaudioframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/iaudioframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/fr/aspose.slides/iaudioframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/fr/aspose.slides/iaudioframe/fill_format/) |  |
| [`hidden`](/slides/python-net/fr/aspose.slides/iaudioframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/iaudioframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/iaudioframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/fr/aspose.slides/iaudioframe/rotation/) |  |
| [`x`](/slides/python-net/fr/aspose.slides/iaudioframe/x/) |  |
| [`y`](/slides/python-net/fr/aspose.slides/iaudioframe/y/) |  |
| [`width`](/slides/python-net/fr/aspose.slides/iaudioframe/width/) |  |
| [`height`](/slides/python-net/fr/aspose.slides/iaudioframe/height/) |  |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/iaudioframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/iaudioframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/fr/aspose.slides/iaudioframe/name/) |  |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/iaudioframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/fr/aspose.slides/iaudioframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/iaudioframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/iaudioframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/iaudioframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/fr/aspose.slides/iaudioframe/parent_group/) |  |
| [`slide`](/slides/python-net/fr/aspose.slides/iaudioframe/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/iaudioframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/iaudioframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/iaudioframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/iaudioframe/hyperlink_manager/) |  |

## Méthodes

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/iaudioframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/iaudioframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/iaudioframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/iaudioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/fr/aspose.slides/iaudioframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fr/aspose.slides/iaudioframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fr/aspose.slides/iaudioframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/fr/aspose.slides/iaudioframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/iaudioframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/iaudioframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/iaudioframe/get_base_placeholder/#) |  |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)