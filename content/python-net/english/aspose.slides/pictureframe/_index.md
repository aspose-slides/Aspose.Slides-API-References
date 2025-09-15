---
title: PictureFrame class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/pictureframe/
---


## PictureFrame class

Represents a frame with a picture inside.

**Inheritance:**[`PictureFrame`](/slides/python-net/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/aspose.slides/shape)

The PictureFrame type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/aspose.slides/pictureframe/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/aspose.slides/pictureframe/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Read-only [`IPlaceholder`](/slides/python-net/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/aspose.slides/pictureframe/custom_data/) | Returns the shape's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/aspose.slides/pictureframe/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/aspose.slides/pictureframe/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/aspose.slides/pictureframe/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            Read-only [`ILineFormat`](/slides/python-net/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/aspose.slides/pictureframe/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/aspose.slides/pictureframe/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            Read-only [`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/aspose.slides/pictureframe/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            Read-only [`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/aspose.slides/pictureframe/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/aspose.slides/pictureframe/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/aspose.slides/pictureframe/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/aspose.slides/pictureframe/hidden/) | Determines whether the shape is hidden.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/aspose.slides/pictureframe/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/aspose.slides/pictureframe/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/aspose.slides/pictureframe/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/aspose.slides/pictureframe/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/aspose.slides/pictureframe/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/aspose.slides/pictureframe/width/) | Gets or sets the width of the shape, measured in points.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/aspose.slides/pictureframe/height/) | Gets or sets the height of the shape, measured in points.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/aspose.slides/pictureframe/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/aspose.slides/pictureframe/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Read-only **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/aspose.slides/pictureframe/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Read-only **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/aspose.slides/pictureframe/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/aspose.slides/pictureframe/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/aspose.slides/pictureframe/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/aspose.slides/pictureframe/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/aspose.slides/pictureframe/shape_lock/) | Returns shape's locks.<br/>            Read-only [`IPictureFrameLock`](/slides/python-net/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/aspose.slides/pictureframe/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/aspose.slides/pictureframe/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Read-only [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/aspose.slides/pictureframe/slide/) | Returns the parent slide of a shape.<br/>            Read-only [`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/aspose.slides/pictureframe/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only [`IPresentation`](/slides/python-net/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/aspose.slides/pictureframe/shape_style/) | Returns shape's style object.<br/>            Read-only [`IShapeStyle`](/slides/python-net/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/aspose.slides/pictureframe/shape_type/) | Returns or sets the AutoShape type for a PictureFrame.<br/>            There are allowable all items of the set [`ShapeType`](/slides/python-net/aspose.slides/shapetype), <br/>            except all sorts of lines:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Read/write [`ShapeType`](/slides/python-net/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/aspose.slides/pictureframe/adjustments/) | Returns a collection of shape's adjustment values.<br/>            Read-only [`IAdjustValueCollection`](/slides/python-net/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/aspose.slides/pictureframe/picture_frame_lock/) | Returns shape's locks.<br/>            Read-only [`IPictureFrameLock`](/slides/python-net/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/aspose.slides/pictureframe/picture_format/) | Returns the PictureFillFormat object for a picture frame.<br/>            Read-only [`IPictureFillFormat`](/slides/python-net/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/aspose.slides/pictureframe/relative_scale_height/) | Returns or sets the scale of height(relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%.<br/>            Read/write **float**. |
| [`relative_scale_width`](/slides/python-net/aspose.slides/pictureframe/relative_scale_width/) | Returns or sets the scale of width (relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%.<br/>            Read/write **float**. |
| [`is_cameo`](/slides/python-net/aspose.slides/pictureframe/is_cameo/) | Determines whether the PictureFrame is Cameo object or not.<br/>            Read only **bool**. |

## Methods

| Method | Description |
| :- | :- |
| [`get_thumbnail`](/slides/python-net/aspose.slides/pictureframe/get_thumbnail/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_thumbnail`](/slides/python-net/aspose.slides/pictureframe/get_thumbnail/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`get_image`](/slides/python-net/aspose.slides/pictureframe/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image`](/slides/python-net/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg`](/slides/python-net/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg`](/slides/python-net/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder`](/slides/python-net/aspose.slides/pictureframe/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder`](/slides/python-net/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder`](/slides/python-net/aspose.slides/pictureframe/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>A None is returned if the current shape is not inherited. |
| [`get_geometry_paths`](/slides/python-net/aspose.slides/pictureframe/get_geometry_paths/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [`set_geometry_path`](/slides/python-net/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Updates shape geometry from [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath) object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths`](/slides/python-net/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath). Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements`](/slides/python-net/aspose.slides/pictureframe/create_shape_elements/#) | Creates and returns array of shape's elements. |


### Examples

The following examples shows how to change Audio Frame Thumbnail.


### See Also
* class [`GeometryShape`](/slides/python-net/aspose.slides/geometryshape)
* class [`PictureFrame`](/slides/python-net/aspose.slides/pictureframe)
* class [`Shape`](/slides/python-net/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

