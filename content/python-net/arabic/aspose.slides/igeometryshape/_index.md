---
title: IGeometryShape class
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/igeometryshape/
---
## IGeometryShape فئة

يمثل الفئة الأصلية لجميع الأشكال الهندسية.

يعرض نوع IGeometryShape الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`shape_style`](/slides/python-net/ar/aspose.slides/igeometryshape/shape_style/) | يعيد كائن نمط الشكل.<br/>            Read-only [`IShapeStyle`](/slides/python-net/ar/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ar/aspose.slides/igeometryshape/shape_type/) | يعيد أو يعيّن نوع الإعداد الهندسي.<br/>            ملاحظة: عند تغيير القيمة ستعاد جميع قيم التعديل إلى القيم الافتراضية.<br/>            Read/write [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ar/aspose.slides/igeometryshape/adjustments/) | يعيد مجموعة من قيم تعديل الشكل.<br/>            Read-only [`IAdjustValueCollection`](/slides/python-net/ar/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ar/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/ar/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/ar/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/ar/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ar/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/ar/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/ar/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ar/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/ar/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/ar/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/ar/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/ar/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/ar/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/ar/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ar/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/ar/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## الأساليب

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/ar/aspose.slides/igeometryshape/get_geometry_paths/#) | يعيد نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ar/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | يقوم بتحديث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى اليسار<br/>             أعلى زاوية الشكل.<br/>             يغير نوع الشكل ([`IGeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/igeometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ar/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | يقوم بتحديث هندسة الشكل من مصفوفة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى اليسار<br/>             أعلى زاوية الشكل.<br/>             يغير نوع الشكل ([`IGeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/igeometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ar/aspose.slides/igeometryshape/create_shape_elements/#) | إنشاء وإرجاع مصفوفة من عناصر الشكل. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)