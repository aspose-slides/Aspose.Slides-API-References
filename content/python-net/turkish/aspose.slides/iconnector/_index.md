---
title: IConnector class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iconnector/
---
## IConnector sınıfı

Bir bağlayıcıyı temsil eder.

IConnector türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/iconnector/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Yalnızca okunabilir [`IConnectorLock`](/slides/python-net/tr/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/tr/aspose.slides/iconnector/connector_lock/) | Bağlayıcının kilitlerini döndürür.<br/>            Yalnızca okunabilir [`IConnectorLock`](/slides/python-net/tr/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/tr/aspose.slides/iconnector/start_shape_connected_to/) | Bağlayıcının başlangıcının bağlanacağı şekli döndürür veya ayarlar.<br/>            Okunabilir/Yazılabilir [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/tr/aspose.slides/iconnector/end_shape_connected_to/) | Bağlayıcının sonunun bağlanacağı şekli döndürür veya ayarlar.<br/>            Okunabilir/Yazılabilir [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/tr/aspose.slides/iconnector/start_shape_connection_site_index/) | Başlangıç şekli için bağlantı noktasının dizinini döndürür veya ayarlar.<br/>            Okunabilir/Yazılabilir **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/tr/aspose.slides/iconnector/end_shape_connection_site_index/) | Son şekil için bağlantı noktasının dizinini döndürür veya ayarlar.<br/>            Okunabilir/Yazılabilir **int**. |
| [`shape_style`](/slides/python-net/tr/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/tr/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/tr/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/tr/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/tr/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/tr/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/tr/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/tr/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/tr/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/tr/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/tr/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/tr/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/tr/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/tr/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/tr/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/tr/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/tr/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/tr/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/tr/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/iconnector/hyperlink_manager/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/tr/aspose.slides/iconnector/reroute/#) | Bağlayıcıyı, bağladığı şekiller arasında mümkün olan en kısa yolu alacak şekilde yeniden yönlendirir. |
| [`get_geometry_paths(self)`](/slides/python-net/tr/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/tr/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/tr/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/tr/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/iconnector/get_base_placeholder/#) |  |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)