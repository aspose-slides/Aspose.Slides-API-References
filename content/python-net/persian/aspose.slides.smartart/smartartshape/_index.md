---
title: SmartArtShape class
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.smartart/smartartshape/
---
## SmartArtShape کلاس

Represents SmartArt shape

**Inheritance:**[`SmartArtShape`](/slides/python-net/fa/aspose.slides.smartart/smartartshape) → [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

The SmartArtShape type exposes the following members:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            فقط-خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            فقط-خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/custom_data/) | Returns the shape's custom data.<br/>            فقط-خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/frame/) | Returns or sets the shape frame's properties.<br/>            قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            توجه: can return None for certain types of shapes which don't have line properties.<br/>            فقط-خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            توجه: can return None for certain types of shapes which don't have 3d properties.<br/>            فقط-خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            توجه: can return None for certain types of shapes which don't have effect properties.<br/>            فقط-خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            توجه: can return None for certain types of shapes which don't have fill properties.<br/>            فقط-خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/hyperlink_manager/) | Returns the hyperlink manager.<br/>            فقط-خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/hidden/) | Determines whether the shape is hidden.<br/>            قابل‌خواندن/قابل‌نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            فقط-خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            فقط-خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            قابل‌خواندن/قابل‌نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            قابل‌خواندن/قابل‌نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            قابل‌خواندن/قابل‌نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/width/) | Gets or sets the width of the shape, measured in points.<br/>            قابل‌خواندن/قابل‌نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/height/) | Gets or sets the height of the shape, measured in points.<br/>            قابل‌خواندن/قابل‌نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            قابل‌خواندن/قابل‌نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            فقط-خواندنی **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            فقط-خواندنی **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            قابل‌خواندن/قابل‌نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            قابل‌خواندن/قابل‌نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            قابل‌خواندن/قابل‌نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/shape_lock/) | Returns shape's locks.<br/>            فقط-خواندنی [`IBaseShapeLock`](/slides/python-net/fa/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/is_grouped/) | Determines whether the shape is grouped.<br/>            فقط-خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            فقط-خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/slide/) | Returns the parent slide of a shape.<br/>            فقط-خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/presentation/) | Returns the parent presentation of a slide.<br/>            فقط-خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/shape_style/) | Returns shape's style object.<br/>            فقط-خواندنی [`IShapeStyle`](/slides/python-net/fa/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/shape_type/) | Returns or sets the geometry preset type.<br/>            توجه: on value changing all adjustment values will reset to their default values.<br/>            قابل‌خواندن/قابل‌نوشتن [`ShapeType`](/slides/python-net/fa/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/adjustments/) | Returns a collection of shape's adjustment values.<br/>            فقط-خواندنی [`IAdjustValueCollection`](/slides/python-net/fa/aspose.slides/iadjustvaluecollection). |
| [`text_frame`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/text_frame/) | Returns text of the SmartArt shape.<br/>            فقط-خواندنی [`ITextFrame`](/slides/python-net/fa/aspose.slides/itextframe). |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |
| [`get_geometry_paths(self)`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/set_geometry_path/#igeometrypath) | Updates shape geometry from [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/set_geometry_paths/#listigeometrypath) | Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath). Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/fa/aspose.slides.smartart/smartartshape/create_shape_elements/#) | Creates and returns array of shape's elements. |

### همچنین ببینید
* کلاس [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* کلاس [`SmartArtShape`](/slides/python-net/fa/aspose.slides.smartart/smartartshape)
* ماژول [`aspose.slides.smartart`](/slides/python-net/fa/aspose.slides.smartart)
* کتابخانه [`Aspose.Slides`](/slides/python-net)