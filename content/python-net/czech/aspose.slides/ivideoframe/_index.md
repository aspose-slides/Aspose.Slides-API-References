---
title: IVideoFrame class
second_title: Aspose.Slides pro Python přes .NET referenční příručku API
description: 
type: docs
url: /cs/aspose.slides/ivideoframe/
---
## IVideoFrame třída

Představuje video klip na snímku.

Typ IVideoFrame poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`rewind_video`](/slides/python-net/cs/aspose.slides/ivideoframe/rewind_video/) | Určuje, zda se video automaticky přehraje od začátku<br/>            jakmile film skončí.<br/>            Read/write **bool**. |
| [`play_loop_mode`](/slides/python-net/cs/aspose.slides/ivideoframe/play_loop_mode/) | Určuje, zda je video opakováno v smyčce.<br/>            Read/write **bool**. |
| [`hide_at_showing`](/slides/python-net/cs/aspose.slides/ivideoframe/hide_at_showing/) | Určuje, zda je VideoFrame skrytý.<br/>            Read/write **bool**. |
| [`volume`](/slides/python-net/cs/aspose.slides/ivideoframe/volume/) | Vrací nebo nastavuje hlasitost zvuku.<br/>            Read/write [`AudioVolumeMode`](/slides/python-net/cs/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/cs/aspose.slides/ivideoframe/volume_value/) | Vrací nebo nastavuje přesnou hlasitost videa jako procento.<br/>            Hodnota je vyjádřena jako procento od 0 do 100. Použijte tuto vlastnost<br/>            pro čtení nebo nastavení hodnot hlasitosti, které jsou přesnější než předdefinované<br/>            úrovně dostupné prostřednictvím vlastnosti [`IVideoFrame.volume`](/slides/python-net/cs/aspose.slides/ivideoframe/volume).<br/>            Read/write **float**. |
| [`play_mode`](/slides/python-net/cs/aspose.slides/ivideoframe/play_mode/) | Vrací nebo nastavuje režim přehrávání videa.<br/>            Read/write [`VideoPlayModePreset`](/slides/python-net/cs/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/cs/aspose.slides/ivideoframe/full_screen_mode/) | Určuje, zda je video zobrazováno v režimu celé obrazovky.<br/>            Read/write **bool**. |
| [`link_path_long`](/slides/python-net/cs/aspose.slides/ivideoframe/link_path_long/) | Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame.<br/>            Read/write **str**. |
| [`embedded_video`](/slides/python-net/cs/aspose.slides/ivideoframe/embedded_video/) | Vrací nebo nastavuje vložený video objekt.<br/>            Read/write [`IVideo`](/slides/python-net/cs/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/cs/aspose.slides/ivideoframe/trim_from_start/) | Oříznout začátek [ms] |
| [`trim_from_end`](/slides/python-net/cs/aspose.slides/ivideoframe/trim_from_end/) | Oříznout konec [ms] |
| [`caption_tracks`](/slides/python-net/cs/aspose.slides/ivideoframe/caption_tracks/) | Získává kolekci uzavřených titulků spojených s audio rámcem.<br/>            Tento atribut je jen pro čtení a vrací [`ICaptionsCollection`](/slides/python-net/cs/aspose.slides/icaptionscollection) obsahující všechny stopy titulků. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/ivideoframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/cs/aspose.slides/ivideoframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/cs/aspose.slides/ivideoframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/cs/aspose.slides/ivideoframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/cs/aspose.slides/ivideoframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/cs/aspose.slides/ivideoframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/cs/aspose.slides/ivideoframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/cs/aspose.slides/ivideoframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/ivideoframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/cs/aspose.slides/ivideoframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/cs/aspose.slides/ivideoframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/ivideoframe/raw_frame/) |  |
| [`frame`](/slides/python-net/cs/aspose.slides/ivideoframe/frame/) |  |
| [`line_format`](/slides/python-net/cs/aspose.slides/ivideoframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/ivideoframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/cs/aspose.slides/ivideoframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/cs/aspose.slides/ivideoframe/fill_format/) |  |
| [`hidden`](/slides/python-net/cs/aspose.slides/ivideoframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/ivideoframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/ivideoframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/cs/aspose.slides/ivideoframe/rotation/) |  |
| [`x`](/slides/python-net/cs/aspose.slides/ivideoframe/x/) |  |
| [`y`](/slides/python-net/cs/aspose.slides/ivideoframe/y/) |  |
| [`width`](/slides/python-net/cs/aspose.slides/ivideoframe/width/) |  |
| [`height`](/slides/python-net/cs/aspose.slides/ivideoframe/height/) |  |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/ivideoframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/ivideoframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/cs/aspose.slides/ivideoframe/name/) |  |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/ivideoframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/cs/aspose.slides/ivideoframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/ivideoframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/ivideoframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/ivideoframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/cs/aspose.slides/ivideoframe/parent_group/) |  |
| [`slide`](/slides/python-net/cs/aspose.slides/ivideoframe/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/ivideoframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/ivideoframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/ivideoframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/ivideoframe/hyperlink_manager/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/ivideoframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/ivideoframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/ivideoframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/ivideoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/cs/aspose.slides/ivideoframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/cs/aspose.slides/ivideoframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/cs/aspose.slides/ivideoframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/cs/aspose.slides/ivideoframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/ivideoframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/ivideoframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/ivideoframe/get_base_placeholder/#) |  |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)