---
title: ISmartArt class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.smartart/ismartart/
---
## ISmartArt sınıfı

Bir SmartArt diyagramını temsil eder.

ISmartArt türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`all_nodes`](/slides/python-net/tr/aspose.slides.smartart/ismartart/all_nodes/) | SmartArt nesnesindeki tüm düğümlerin koleksiyonlarını döndürür.<br/>            Salt-okunur [`ISmartArtNodeCollection`](/slides/python-net/tr/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/tr/aspose.slides.smartart/ismartart/nodes/) | SmartArt nesnesindeki kök düğümlerin koleksiyonlarını döndürür.<br/>            Salt-okunur [`ISmartArtNodeCollection`](/slides/python-net/tr/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/tr/aspose.slides.smartart/ismartart/layout/) | SmartArt nesnesinin düzenini alır veya ayarlar.<br/>            Okunur/Yazılabilir [`SmartArtLayoutType`](/slides/python-net/tr/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/tr/aspose.slides.smartart/ismartart/quick_style/) | SmartArt nesnesinin hızlı stilini alır veya ayarlar.<br/>            Okunur/Yazılabilir [`SmartArtQuickStyleType`](/slides/python-net/tr/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/tr/aspose.slides.smartart/ismartart/color_style/) | SmartArt nesnesinin renk stilini alır veya ayarlar.<br/>            Okunur/Yazılabilir [`SmartArtColorType`](/slides/python-net/tr/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/tr/aspose.slides.smartart/ismartart/is_reversed/) | SmartArt diyagramının (soldan sağa) LTR veya (sağdan sola) RTL yönündeki durumunu alır veya ayarlar, eğer diyagram ters çevirmeyi destekliyorsa.<br/>            Okunur/Yazılabilir **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides.smartart/ismartart/shape_lock/) |  |
| [`graphical_object_lock`](/slides/python-net/tr/aspose.slides.smartart/ismartart/graphical_object_lock/) |  |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides.smartart/ismartart/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/tr/aspose.slides.smartart/ismartart/placeholder/) |  |
| [`custom_data`](/slides/python-net/tr/aspose.slides.smartart/ismartart/custom_data/) |  |
| [`raw_frame`](/slides/python-net/tr/aspose.slides.smartart/ismartart/raw_frame/) |  |
| [`frame`](/slides/python-net/tr/aspose.slides.smartart/ismartart/frame/) |  |
| [`line_format`](/slides/python-net/tr/aspose.slides.smartart/ismartart/line_format/) |  |
| [`three_d_format`](/slides/python-net/tr/aspose.slides.smartart/ismartart/three_d_format/) |  |
| [`effect_format`](/slides/python-net/tr/aspose.slides.smartart/ismartart/effect_format/) |  |
| [`fill_format`](/slides/python-net/tr/aspose.slides.smartart/ismartart/fill_format/) |  |
| [`hidden`](/slides/python-net/tr/aspose.slides.smartart/ismartart/hidden/) |  |
| [`z_order_position`](/slides/python-net/tr/aspose.slides.smartart/ismartart/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides.smartart/ismartart/connection_site_count/) |  |
| [`rotation`](/slides/python-net/tr/aspose.slides.smartart/ismartart/rotation/) |  |
| [`x`](/slides/python-net/tr/aspose.slides.smartart/ismartart/x/) |  |
| [`y`](/slides/python-net/tr/aspose.slides.smartart/ismartart/y/) |  |
| [`width`](/slides/python-net/tr/aspose.slides.smartart/ismartart/width/) |  |
| [`height`](/slides/python-net/tr/aspose.slides.smartart/ismartart/height/) |  |
| [`alternative_text`](/slides/python-net/tr/aspose.slides.smartart/ismartart/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides.smartart/ismartart/alternative_text_title/) |  |
| [`name`](/slides/python-net/tr/aspose.slides.smartart/ismartart/name/) |  |
| [`is_decorative`](/slides/python-net/tr/aspose.slides.smartart/ismartart/is_decorative/) |  |
| [`unique_id`](/slides/python-net/tr/aspose.slides.smartart/ismartart/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides.smartart/ismartart/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/tr/aspose.slides.smartart/ismartart/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides.smartart/ismartart/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/tr/aspose.slides.smartart/ismartart/parent_group/) |  |
| [`slide`](/slides/python-net/tr/aspose.slides.smartart/ismartart/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides.smartart/ismartart/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides.smartart/ismartart/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides.smartart/ismartart/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides.smartart/ismartart/hyperlink_manager/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides.smartart/ismartart/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides.smartart/ismartart/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides.smartart/ismartart/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides.smartart/ismartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides.smartart/ismartart/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides.smartart/ismartart/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides.smartart/ismartart/get_base_placeholder/#) |  |

### Ayrıca Bakınız
* modül [`aspose.slides.smartart`](/slides/python-net/tr/aspose.slides.smartart)
* kütüphane [`Aspose.Slides`](/slides/python-net)