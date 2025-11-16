---
title: Connector class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/connector/
---


## Connector class

Represents a connector.

**Inheritance:**[`Connector`](/slides/python-net/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/aspose.slides/shape)

The Connector type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/aspose.slides/connector/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/aspose.slides/connector/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Read-only [`IPlaceholder`](/slides/python-net/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/aspose.slides/connector/custom_data/) | Returns the shape's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/aspose.slides/connector/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/aspose.slides/connector/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/aspose.slides/connector/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            Read-only [`ILineFormat`](/slides/python-net/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/aspose.slides/connector/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/aspose.slides/connector/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            Read-only [`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/aspose.slides/connector/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            Read-only [`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/aspose.slides/connector/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/aspose.slides/connector/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/aspose.slides/connector/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/aspose.slides/connector/hidden/) | Determines whether the shape is hidden.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/aspose.slides/connector/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/aspose.slides/connector/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/aspose.slides/connector/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/aspose.slides/connector/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/aspose.slides/connector/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/aspose.slides/connector/width/) | Gets or sets the width of the shape, measured in points.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/aspose.slides/connector/height/) | Gets or sets the height of the shape, measured in points.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/aspose.slides/connector/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/aspose.slides/connector/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Read-only **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/aspose.slides/connector/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Read-only **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/aspose.slides/connector/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/aspose.slides/connector/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/aspose.slides/connector/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/aspose.slides/connector/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/aspose.slides/connector/shape_lock/) | Returns shape's locks.<br/>            Read-only [`IConnectorLock`](/slides/python-net/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/aspose.slides/connector/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/aspose.slides/connector/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Read-only [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/aspose.slides/connector/slide/) | Returns the parent slide of a shape.<br/>            Read-only [`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/aspose.slides/connector/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only [`IPresentation`](/slides/python-net/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/aspose.slides/connector/shape_style/) | Returns shape's style object.<br/>            Read-only [`IShapeStyle`](/slides/python-net/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/aspose.slides/connector/shape_type/) | Returns or sets the AutoShape type.<br/>            Read/write [`ShapeType`](/slides/python-net/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/aspose.slides/connector/adjustments/) | Returns a collection of shape's adjustment values.<br/>            Read-only [`IAdjustValueCollection`](/slides/python-net/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/aspose.slides/connector/connector_lock/) | Returns connector's locks.<br/>            Read-only [`IConnectorLock`](/slides/python-net/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/aspose.slides/connector/start_shape_connected_to/) | Returns or sets the shape to attach the beginning of the connector to.<br/>            Read/write [`IShape`](/slides/python-net/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/aspose.slides/connector/end_shape_connected_to/) | Returns or sets the shape to attach the end of the connector to.<br/>            Read/write [`IShape`](/slides/python-net/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/aspose.slides/connector/start_shape_connection_site_index/) | Returns or sets the index of connection site for start shape.<br/>            Read/write **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/aspose.slides/connector/end_shape_connection_site_index/) | Returns or sets the index of connection site for end shape.<br/>            Read/write **int**. |

## Methods

| Method | Description |
| :- | :- |
| [`get_image`](/slides/python-net/aspose.slides/connector/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image`](/slides/python-net/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg`](/slides/python-net/aspose.slides/connector/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg`](/slides/python-net/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder`](/slides/python-net/aspose.slides/connector/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder`](/slides/python-net/aspose.slides/connector/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder`](/slides/python-net/aspose.slides/connector/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_geometry_paths`](/slides/python-net/aspose.slides/connector/get_geometry_paths/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [`set_geometry_path`](/slides/python-net/aspose.slides/connector/set_geometry_path/#igeometrypath) | Updates shape geometry from [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath) object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths`](/slides/python-net/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath). Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements`](/slides/python-net/aspose.slides/connector/create_shape_elements/#) | Creates and returns array of shape's elements. |
| [`reroute`](/slides/python-net/aspose.slides/connector/reroute/#) | Reroutes connector so that it take the shortest possible path between the shapes it connect. |


### See Also
* class [`Connector`](/slides/python-net/aspose.slides/connector)
* class [`GeometryShape`](/slides/python-net/aspose.slides/geometryshape)
* class [`Shape`](/slides/python-net/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

