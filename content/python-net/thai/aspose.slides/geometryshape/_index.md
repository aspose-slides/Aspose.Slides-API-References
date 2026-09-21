---
title: GeometryShape class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/geometryshape/
---
## คลาส GeometryShape

Represents the parent class for all geometric shapes.

**Inheritance:**[`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

The GeometryShape type exposes the following members:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/geometryshape/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            **อ่านอย่างเดียว** **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/geometryshape/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            **อ่านอย่างเดียว** [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/geometryshape/custom_data/) | Returns the shape's custom data.<br/>            **อ่านอย่างเดียว** [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/geometryshape/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            **อ่าน/เขียน** [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/geometryshape/frame/) | Returns or sets the shape frame's properties.<br/>            **อ่าน/เขียน** [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/geometryshape/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            **อ่านอย่างเดียว** [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/geometryshape/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            **อ่านอย่างเดียว** [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/geometryshape/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            **อ่านอย่างเดียว** [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/geometryshape/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            **อ่านอย่างเดียว** [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/geometryshape/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            **อ่าน/เขียน** [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/geometryshape/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            **อ่าน/เขียน** [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/geometryshape/hyperlink_manager/) | Returns the hyperlink manager.<br/>            **อ่านอย่างเดียว** [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/geometryshape/hidden/) | Determines whether the shape is hidden.<br/>            **อ่าน/เขียน** **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/geometryshape/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            **อ่านอย่างเดียว** **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/geometryshape/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            **อ่านอย่างเดียว** **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/geometryshape/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            **อ่าน/เขียน** **float**. |
| [`x`](/slides/python-net/th/aspose.slides/geometryshape/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            **อ่าน/เขียน** **float**. |
| [`y`](/slides/python-net/th/aspose.slides/geometryshape/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            **อ่าน/เขียน** **float**. |
| [`width`](/slides/python-net/th/aspose.slides/geometryshape/width/) | Gets or sets the width of the shape, measured in points.<br/>            **อ่าน/เขียน** **float**. |
| [`height`](/slides/python-net/th/aspose.slides/geometryshape/height/) | Gets or sets the height of the shape, measured in points.<br/>            **อ่าน/เขียน** **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/geometryshape/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            **อ่าน/เขียน** [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/geometryshape/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            **อ่านอย่างเดียว** **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/geometryshape/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            **อ่านอย่างเดียว** **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/geometryshape/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            **อ่าน/เขียน** **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/geometryshape/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            **อ่าน/เขียน** **str**. |
| [`name`](/slides/python-net/th/aspose.slides/geometryshape/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            **อ่าน/เขียน** **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/geometryshape/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            **อ่าน/เขียน** **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/geometryshape/shape_lock/) | Returns shape's locks.<br/>            **อ่านอย่างเดียว** [`IBaseShapeLock`](/slides/python-net/th/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/geometryshape/is_grouped/) | Determines whether the shape is grouped.<br/>            **อ่านอย่างเดียว** **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/geometryshape/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            **อ่านอย่างเดียว** [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/geometryshape/slide/) | Returns the parent slide of a shape.<br/>            **อ่านอย่างเดียว** [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/geometryshape/presentation/) | Returns the parent presentation of a slide.<br/>            **อ่านอย่างเดียว** [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/th/aspose.slides/geometryshape/shape_style/) | Returns shape's style object.<br/>            **อ่านอย่างเดียว** [`IShapeStyle`](/slides/python-net/th/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type/) | Returns or sets the geometry preset type.<br/>            Note: on value changing all adjustment values will reset to their default values.<br/>            **อ่าน/เขียน** [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/th/aspose.slides/geometryshape/adjustments/) | Returns a collection of shape's adjustment values.<br/>            **อ่านอย่างเดียว** [`IAdjustValueCollection`](/slides/python-net/th/aspose.slides/iadjustvaluecollection). |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/geometryshape/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/geometryshape/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/geometryshape/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/geometryshape/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |
| [`get_geometry_paths(self)`](/slides/python-net/th/aspose.slides/geometryshape/get_geometry_paths/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/th/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | Updates shape geometry from [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath) object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/th/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/th/aspose.slides/geometryshape/create_shape_elements/#) | Creates and returns array of shape's elements. |

### ดูเพิ่มเติม
* คลาส [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)