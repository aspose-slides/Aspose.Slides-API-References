---
title: IAutoShape class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iautoshape/
---
## IAutoShape sınıfı

Bir AutoShape'ı temsil eder.

IAutoShape türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/iautoshape/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Yalnızca okuma [`IAutoShapeLock`](/slides/python-net/tr/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/tr/aspose.slides/iautoshape/auto_shape_lock/) | AutoShape'ın kilitlerini döndürür.<br/>            Yalnızca okuma [`IAutoShapeLock`](/slides/python-net/tr/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/tr/aspose.slides/iautoshape/text_frame/) | AutoShape için TextFrame nesnesini döndürür.<br/>            Yalnızca okuma [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/tr/aspose.slides/iautoshape/use_background_fill/) | Bu autoshape'in stil veya dolgu biçimi yerine slaytın arka plan dolgusuyla doldurulup doldurulmayacağını belirler.<br/>            Okuma/Yazma **bool**. |
| [`is_text_box`](/slides/python-net/tr/aspose.slides/iautoshape/is_text_box/) | Şeklin bir metin kutusu olup olmadığını belirtir. |
| [`shape_style`](/slides/python-net/tr/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/tr/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/tr/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/tr/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/tr/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/tr/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/tr/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/tr/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/tr/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/tr/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/tr/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/tr/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/tr/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/tr/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/tr/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/tr/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/tr/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/tr/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/tr/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/tr/aspose.slides/iautoshape/add_text_frame/#str) | Bir şekle yeni bir TextFrame ekler.<br/>            Şekilde zaten bir TextFrame varsa yalnızca metnini değiştirir. |
| [`get_geometry_paths(self)`](/slides/python-net/tr/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/tr/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/tr/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/tr/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/iautoshape/get_base_placeholder/#) |  |

### Ayrıca
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)