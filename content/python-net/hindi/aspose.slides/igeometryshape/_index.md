---
title: IGeometryShape class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/igeometryshape/
---
## IGeometryShape क्लास

सभी ज्यामितीय आकारों के लिए पैरेंट क्लास का प्रतिनिधित्व करता है।

IGeometryShape प्रकार निम्नलिखित सदस्य उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`shape_style`](/slides/python-net/hi/aspose.slides/igeometryshape/shape_style/) | आकार की शैली ऑब्जेक्ट को लौटाता है।<br/>            केवल-पढ़ने योग्य [`IShapeStyle`](/slides/python-net/hi/aspose.slides/ishapestyle)। |
| [`shape_type`](/slides/python-net/hi/aspose.slides/igeometryshape/shape_type/) | ज्यामिति प्रीसेट प्रकार को लौटाता है या सेट करता है।<br/>            नोट: मान बदलने पर सभी समायोजन मान उनके डिफ़ॉल्ट मानों पर रीसेट हो जाएँगे।<br/>            पढ़ें/लिखें [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| [`adjustments`](/slides/python-net/hi/aspose.slides/igeometryshape/adjustments/) | आकार के समायोजन मानों का संग्रह लौटाता है।<br/>            केवल-पढ़ने योग्य [`IAdjustValueCollection`](/slides/python-net/hi/aspose.slides/iadjustvaluecollection)। |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/hi/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/hi/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/hi/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/hi/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/hi/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/hi/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/hi/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/hi/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/hi/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/hi/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/hi/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/hi/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/hi/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/hi/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/hi/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/hi/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/hi/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/hi/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/hi/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/hi/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/hi/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/hi/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/hi/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## विधियाँ

| मेथड | विवरण |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/hi/aspose.slides/igeometryshape/get_geometry_paths/#) | ज्यामिति आकार के पथ की कॉपी लौटाता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होते हैं। |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hi/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) ऑब्जेक्ट से आकार की ज्यामिति को अपडेट करता है। निर्देशांक बाएँ<br/>             शीर्ष कोने के सापेक्ष होने चाहिए।<br/>             आकार के प्रकार ([`IGeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/igeometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hi/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) के एरे से आकार की ज्यामिति को अपडेट करता है। निर्देशांक बाएँ<br/>             शीर्ष कोने के सापेक्ष होने चाहिए।<br/>             आकार के प्रकार ([`IGeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/igeometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है। |
| [`create_shape_elements(self)`](/slides/python-net/hi/aspose.slides/igeometryshape/create_shape_elements/#) | आकार के तत्वों का एरे बनाता है और लौटाता है। |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)