---
title: AutoShape class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/autoshape/
---


## AutoShape class

Represents an AutoShape.

**Inheritance:**[`AutoShape`](/slides/python-net/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/aspose.slides/shape)

The AutoShape type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/aspose.slides/autoshape/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/aspose.slides/autoshape/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Read-only [`IPlaceholder`](/slides/python-net/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/aspose.slides/autoshape/custom_data/) | Returns the shape's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/aspose.slides/autoshape/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/aspose.slides/autoshape/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/aspose.slides/autoshape/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            Read-only [`ILineFormat`](/slides/python-net/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/aspose.slides/autoshape/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/aspose.slides/autoshape/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            Read-only [`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/aspose.slides/autoshape/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            Read-only [`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/aspose.slides/autoshape/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/aspose.slides/autoshape/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/aspose.slides/autoshape/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/aspose.slides/autoshape/hidden/) | Determines whether the shape is hidden.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/aspose.slides/autoshape/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/aspose.slides/autoshape/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/aspose.slides/autoshape/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/aspose.slides/autoshape/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/aspose.slides/autoshape/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/aspose.slides/autoshape/width/) | Gets or sets the width of the shape, measured in points.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/aspose.slides/autoshape/height/) | Gets or sets the height of the shape, measured in points.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/aspose.slides/autoshape/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/aspose.slides/autoshape/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Read-only **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/aspose.slides/autoshape/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Read-only **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/aspose.slides/autoshape/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/aspose.slides/autoshape/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/aspose.slides/autoshape/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/aspose.slides/autoshape/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/aspose.slides/autoshape/shape_lock/) | Returns shape's locks.<br/>            Read-only [`IAutoShapeLock`](/slides/python-net/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/aspose.slides/autoshape/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/aspose.slides/autoshape/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Read-only [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/aspose.slides/autoshape/slide/) | Returns the parent slide of a shape.<br/>            Read-only [`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/aspose.slides/autoshape/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only [`IPresentation`](/slides/python-net/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/aspose.slides/autoshape/shape_style/) | Returns shape's style object.<br/>            Read-only [`IShapeStyle`](/slides/python-net/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/aspose.slides/autoshape/shape_type/) | Returns or sets the geometry preset type.<br/>            Note: on value changing all adjustment values will reset to their default values.<br/>            Read/write [`ShapeType`](/slides/python-net/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/aspose.slides/autoshape/adjustments/) | Returns a collection of shape's adjustment values.<br/>            Read-only [`IAdjustValueCollection`](/slides/python-net/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/aspose.slides/autoshape/auto_shape_lock/) | Returns autoshape's locks.<br/>            Read-only [`IAutoShapeLock`](/slides/python-net/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/aspose.slides/autoshape/text_frame/) | Returns TextFrame object for the AutoShape.<br/>            Read-only [`ITextFrame`](/slides/python-net/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/aspose.slides/autoshape/use_background_fill/) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format.<br/>            Read/write **bool**. |
| [`is_text_box`](/slides/python-net/aspose.slides/autoshape/is_text_box/) | Specifies if the shape is a text box. |

## Methods

| Method | Description |
| :- | :- |
| [`get_image`](/slides/python-net/aspose.slides/autoshape/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image`](/slides/python-net/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg`](/slides/python-net/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg`](/slides/python-net/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder`](/slides/python-net/aspose.slides/autoshape/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder`](/slides/python-net/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder`](/slides/python-net/aspose.slides/autoshape/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_geometry_paths`](/slides/python-net/aspose.slides/autoshape/get_geometry_paths/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [`set_geometry_path`](/slides/python-net/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Updates shape geometry from [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath) object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths`](/slides/python-net/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath). Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements`](/slides/python-net/aspose.slides/autoshape/create_shape_elements/#) | Creates and returns array of shape's elements. |
| [`add_text_frame`](/slides/python-net/aspose.slides/autoshape/add_text_frame/#str) | Adds a new TextFrame to a shape.<br/>            If shape already has TextFrame then simply changes its text. |


### See Also
* class [`AutoShape`](/slides/python-net/aspose.slides/autoshape)
* class [`GeometryShape`](/slides/python-net/aspose.slides/geometryshape)
* class [`Shape`](/slides/python-net/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

