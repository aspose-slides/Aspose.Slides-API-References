---
title: GeometryShape class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/
---


## GeometryShape class

Represents the parent class for all geometric shapes.

**Inheritance:**[`GeometryShape`](/slides/python-net/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/aspose.slides/shape)

The GeometryShape type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [is_text_holder](/slides/python-net/aspose.slides/is_text_holder) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only :py:class:`bool`. |
| [placeholder](/slides/python-net/aspose.slides/placeholder) | Returns the placeholder for a shape. Returns null if the shape has no placeholder.<br/>            Read-only :py:class:`aspose.slides.IPlaceholder`. |
| [custom_data](/slides/python-net/aspose.slides/custom_data) | Returns the shape's custom data.<br/>            Read-only :py:class:`aspose.slides.ICustomData`. |
| [raw_frame](/slides/python-net/aspose.slides/raw_frame) | Returns or sets the raw shape frame's properties.<br/>            Read/write :py:class:`aspose.slides.IShapeFrame`. |
| [frame](/slides/python-net/aspose.slides/frame) | Returns or sets the shape frame's properties.<br/>            Read/write :py:class:`aspose.slides.IShapeFrame`. |
| [line_format](/slides/python-net/aspose.slides/line_format) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have line properties.<br/>            Read-only :py:class:`aspose.slides.ILineFormat`. |
| [three_d_format](/slides/python-net/aspose.slides/three_d_format) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have 3d properties.<br/>            Read-only :py:class:`aspose.slides.IThreeDFormat`. |
| [effect_format](/slides/python-net/aspose.slides/effect_format) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return null for certain types of shapes which don't have effect properties.<br/>            Read-only :py:class:`aspose.slides.IEffectFormat`. |
| [fill_format](/slides/python-net/aspose.slides/fill_format) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have fill properties.<br/>            Read-only :py:class:`aspose.slides.IFillFormat`. |
| [hyperlink_click](/slides/python-net/aspose.slides/hyperlink_click) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write :py:class:`aspose.slides.IHyperlink`. |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides/hyperlink_mouse_over) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write :py:class:`aspose.slides.IHyperlink`. |
| [hyperlink_manager](/slides/python-net/aspose.slides/hyperlink_manager) | Returns the hyperlink manager.<br/>            Read-only :py:class:`aspose.slides.IHyperlinkManager`. |
| [hidden](/slides/python-net/aspose.slides/hidden) | Determines whether the shape is hidden.<br/>            Read/write :py:class:`bool`. |
| [z_order_position](/slides/python-net/aspose.slides/z_order_position) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only :py:class:`int`. |
| [connection_site_count](/slides/python-net/aspose.slides/connection_site_count) | Returns the number of connection sites on the shape.<br/>            Read-only :py:class:`int`. |
| [rotation](/slides/python-net/aspose.slides/rotation) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write :py:class:`float`. |
| [x](/slides/python-net/aspose.slides/x) | Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write :py:class:`float`. |
| [y](/slides/python-net/aspose.slides/y) | Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write :py:class:`float`. |
| [width](/slides/python-net/aspose.slides/width) | Returns or sets the width of the shape.<br/>            Read/write :py:class:`float`. |
| [height](/slides/python-net/aspose.slides/height) | Returns or sets the height of the shape.<br/>            Read/write :py:class:`float`. |
| [black_white_mode](/slides/python-net/aspose.slides/black_white_mode) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write :py:enum:`aspose.slides.BlackWhiteMode`. |
| [unique_id](/slides/python-net/aspose.slides/unique_id) | Gets unique shape identifier in presentation scope.<br/>            Read-only :py:class:`int`.<br/>            See also :py:attr:`aspose.slides.Shape.office_interop_shape_id` for getting unique shape identifier in slide scope. |
| [office_interop_shape_id](/slides/python-net/aspose.slides/office_interop_shape_id) | Gets unique shape identifier in slide scope.<br/>            Read-only :py:class:`int`.<br/>            See also :py:attr:`aspose.slides.Shape.unique_id` for getting unique shape identifier in presentation scope. |
| [alternative_text](/slides/python-net/aspose.slides/alternative_text) | Returns or sets the alternative text associated with a shape.<br/>            Read/write :py:class:`System.String`. |
| [alternative_text_title](/slides/python-net/aspose.slides/alternative_text_title) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write :py:class:`System.String`. |
| [name](/slides/python-net/aspose.slides/name) | Returns or sets the name of a shape.<br/>            Must be not null. Use empty string value if needed.<br/>            Read/write :py:class:`System.String`. |
| [is_decorative](/slides/python-net/aspose.slides/is_decorative) | Gets or sets 'Mark as decorative' option<br/>            Reed/write :py:class:`bool`. |
| [shape_lock](/slides/python-net/aspose.slides/shape_lock) | Returns shape's locks.<br/>            Read-only :py:class:`aspose.slides.IBaseShapeLock`. |
| [is_grouped](/slides/python-net/aspose.slides/is_grouped) | Determines whether the shape is grouped.<br/>            Read-only :py:class:`bool`. |
| [parent_group](/slides/python-net/aspose.slides/parent_group) | Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only :py:class:`aspose.slides.IGroupShape`. |
| [slide](/slides/python-net/aspose.slides/slide) | Returns the parent slide of a shape.<br/>            Read-only :py:class:`aspose.slides.IBaseSlide`. |
| [presentation](/slides/python-net/aspose.slides/presentation) | Returns the parent presentation of a slide.<br/>            Read-only :py:class:`aspose.slides.IPresentation`. |
| [shape_style](/slides/python-net/aspose.slides/shape_style) | Returns shape's style object.<br/>            Read-only :py:class:`aspose.slides.IShapeStyle`. |
| [shape_type](/slides/python-net/aspose.slides/shape_type) | Returns or sets the geometry preset type.<br/>            Note: on value changing all adjustment values will reset to their default values.<br/>            Read/write :py:enum:`aspose.slides.ShapeType`. |
| [adjustments](/slides/python-net/aspose.slides/adjustments) | Returns a collection of shape's adjustment values.<br/>            Read-only :py:class:`aspose.slides.IAdjustValueCollection`. |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides/as_i_hyperlink_container) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides/as_i_slide_component) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/as_i_presentation_component) |  |
| [as_i_shape](/slides/python-net/aspose.slides/as_i_shape) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/geometryshape/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [__init__](/slides/python-net/aspose.slides/geometryshape/#ShapeThumbnailBounds-float-float) | Returns shape thumbnail. |
| [__init__](/slides/python-net/aspose.slides/geometryshape/#System.IO.Stream) | Saves content of Shape as SVG file. |
| [__init__](/slides/python-net/aspose.slides/geometryshape/#System.IO.Stream-aspose.slides.export.ISVGOptions) | Saves content of Shape as SVG file. |
| [__init__](/slides/python-net/aspose.slides/geometryshape/#) | Defines that this shape isn't a placeholder. |
| [__init__](/slides/python-net/aspose.slides/geometryshape/#IPlaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [__init__](/slides/python-net/aspose.slides/geometryshape/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). |
| [__init__](/slides/python-net/aspose.slides/geometryshape/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [__init__](/slides/python-net/aspose.slides/geometryshape/#IGeometryPath) | Updates shape geometry from :py:class:`aspose.slides.IGeometryPath` object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape (:py:attr:`aspose.slides.GeometryShape.shape_type`) to :py:attr:`aspose.slides.ShapeType.CUSTOM`. |
| [__init__](/slides/python-net/aspose.slides/geometryshape/#List[IGeometryPath]) | Updates shape geometry from array of :py:class:`aspose.slides.IGeometryPath`. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape (:py:attr:`aspose.slides.GeometryShape.shape_type`) to :py:attr:`aspose.slides.ShapeType.CUSTOM`. |
| [__init__](/slides/python-net/aspose.slides/geometryshape/#) | Creates and returns array of shape's elements. |

