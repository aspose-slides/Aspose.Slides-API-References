---
title: IAudioFrame class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/iaudioframe/
---
## IAudioFrame třída

Reprezentuje zvukový klip na snímku.

Typ IAudioFrame vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`audio_cd_start_track`](/slides/python-net/cs/aspose.slides/iaudioframe/audio_cd_start_track/) | Vrací nebo nastavuje počáteční index stopy.<br/>            Čtení/Zápis **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/cs/aspose.slides/iaudioframe/audio_cd_start_track_time/) | Vrací nebo nastavuje počáteční čas stopy.<br/>            Čtení/Zápis **int**. |
| [`audio_cd_end_track`](/slides/python-net/cs/aspose.slides/iaudioframe/audio_cd_end_track/) | Vrací nebo nastavuje poslední index stopy<br/>            Čtení/Zápis **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/cs/aspose.slides/iaudioframe/audio_cd_end_track_time/) | Vrací nebo nastavuje poslední čas stopy.<br/>            Čtení/Zápis **int**. |
| [`volume`](/slides/python-net/cs/aspose.slides/iaudioframe/volume/) | Vrací nebo nastavuje hlasitost zvuku.<br/>            Čtení/Zápis [`AudioVolumeMode`](/slides/python-net/cs/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/cs/aspose.slides/iaudioframe/play_mode/) | Vrací nebo nastavuje režim přehrávání zvuku.<br/>            Čtení/Zápis [`AudioPlayModePreset`](/slides/python-net/cs/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/cs/aspose.slides/iaudioframe/hide_at_showing/) | Určuje, zda je AudioFrame skrytý.<br/>            Čtení/Zápis **bool**. |
| [`play_loop_mode`](/slides/python-net/cs/aspose.slides/iaudioframe/play_loop_mode/) | Určuje, zda se zvuk opakuje ve smyčce.<br/>            Čtení/Zápis **bool**. |
| [`play_across_slides`](/slides/python-net/cs/aspose.slides/iaudioframe/play_across_slides/) | Určuje, zda se zvuk přehrává napříč snímky.<br/>             Čtení/Zápis **bool**. |
| [`rewind_audio`](/slides/python-net/cs/aspose.slides/iaudioframe/rewind_audio/) | Určuje, zda se zvuk po přehrání automaticky přetočí na začátek.<br/>             Čtení/Zápis **bool**. |
| [`embedded`](/slides/python-net/cs/aspose.slides/iaudioframe/embedded/) | Určuje, zda je zvuk vložen do prezentace.<br/>            Pouze ke čtení **bool**. |
| [`link_path_long`](/slides/python-net/cs/aspose.slides/iaudioframe/link_path_long/) | Vrací nebo nastavuje název zvukového souboru, který je propojen s AudioFrame.<br/>            Čtení/Zápis **str**. |
| [`embedded_audio`](/slides/python-net/cs/aspose.slides/iaudioframe/embedded_audio/) | Vrací nebo nastavuje vložený zvukový objekt.<br/>            Čtení/Zápis [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/cs/aspose.slides/iaudioframe/fade_in_duration/) | Určuje časovou délku počátečního postupného zesílení média v milisekundách.<br/>             Čtení/Zápis **float**. |
| [`fade_out_duration`](/slides/python-net/cs/aspose.slides/iaudioframe/fade_out_duration/) | Určuje časovou délku koncového postupného zeslabení média v milisekundách.<br/>             Čtení/Zápis **float**. |
| [`volume_value`](/slides/python-net/cs/aspose.slides/iaudioframe/volume_value/) | Vrací nebo nastavuje hlasitost zvuku v procentech.<br/>             Čtení/Zápis **float**. |
| [`trim_from_start`](/slides/python-net/cs/aspose.slides/iaudioframe/trim_from_start/) | Určuje časovou délku, která se má během přehrávání odebrat od začátku média, v milisekundách.<br/>            Čtení/Zápis **float**. |
| [`trim_from_end`](/slides/python-net/cs/aspose.slides/iaudioframe/trim_from_end/) | Určuje časovou délku, která se má během přehrávání odebrat od konce média, v milisekundách.<br/>            Čtení/Zápis **float**. |
| [`caption_tracks`](/slides/python-net/cs/aspose.slides/iaudioframe/caption_tracks/) | Získá kolekci uzavřených titulků souvisejících s audio rámcem.<br/>            Tato vlastnost je pouze ke čtení a vrací [`ICaptionsCollection`](/slides/python-net/cs/aspose.slides/icaptionscollection) obsahující všechny stopy titulků. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/iaudioframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/cs/aspose.slides/iaudioframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/cs/aspose.slides/iaudioframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/cs/aspose.slides/iaudioframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/cs/aspose.slides/iaudioframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/cs/aspose.slides/iaudioframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/cs/aspose.slides/iaudioframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/cs/aspose.slides/iaudioframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/iaudioframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/cs/aspose.slides/iaudioframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/cs/aspose.slides/iaudioframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/iaudioframe/raw_frame/) |  |
| [`frame`](/slides/python-net/cs/aspose.slides/iaudioframe/frame/) |  |
| [`line_format`](/slides/python-net/cs/aspose.slides/iaudioframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/iaudioframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/cs/aspose.slides/iaudioframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/cs/aspose.slides/iaudioframe/fill_format/) |  |
| [`hidden`](/slides/python-net/cs/aspose.slides/iaudioframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/iaudioframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/iaudioframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/cs/aspose.slides/iaudioframe/rotation/) |  |
| [`x`](/slides/python-net/cs/aspose.slides/iaudioframe/x/) |  |
| [`y`](/slides/python-net/cs/aspose.slides/iaudioframe/y/) |  |
| [`width`](/slides/python-net/cs/aspose.slides/iaudioframe/width/) |  |
| [`height`](/slides/python-net/cs/aspose.slides/iaudioframe/height/) |  |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/iaudioframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/iaudioframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/cs/aspose.slides/iaudioframe/name/) |  |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/iaudioframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/cs/aspose.slides/iaudioframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/iaudioframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/iaudioframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/iaudioframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/cs/aspose.slides/iaudioframe/parent_group/) |  |
| [`slide`](/slides/python-net/cs/aspose.slides/iaudioframe/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/iaudioframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/iaudioframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/iaudioframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/iaudioframe/hyperlink_manager/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/iaudioframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/iaudioframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/iaudioframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/iaudioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/cs/aspose.slides/iaudioframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/cs/aspose.slides/iaudioframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/cs/aspose.slides/iaudioframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/cs/aspose.slides/iaudioframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/iaudioframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/iaudioframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/iaudioframe/get_base_placeholder/#) |  |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)