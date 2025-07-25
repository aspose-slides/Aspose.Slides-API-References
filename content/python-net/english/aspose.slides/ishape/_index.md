﻿---
title: IShape class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishape/
---


## IShape class

Represents a shape on a slide.

The IShape type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/aspose.slides/ishape/is_text_holder/) | Determines whether the shape is TextHolder.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/aspose.slides/ishape/placeholder/) | Returns the placeholder for a shape.<br/>            Read-only [`IPlaceholder`](/slides/python-net/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/aspose.slides/ishape/custom_data/) | Returns the shape's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/aspose.slides/ishape/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/aspose.slides/ishape/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/aspose.slides/ishape/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Read-only [`ILineFormat`](/slides/python-net/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/aspose.slides/ishape/three_d_format/) | Returns the ThreeDFormat object that contains line formatting properties for a shape.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/aspose.slides/ishape/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Read-only [`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/aspose.slides/ishape/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Read-only [`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/aspose.slides/ishape/hidden/) | Determines whether the shape is hidden.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/aspose.slides/ishape/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/aspose.slides/ishape/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/aspose.slides/ishape/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/aspose.slides/ishape/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/aspose.slides/ishape/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/aspose.slides/ishape/width/) | Gets or sets the width of the shape, measured in points.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/aspose.slides/ishape/height/) | Gets or sets the height of the shape, measured in points.<br/>            Read/write **float**. |
| [`alternative_text`](/slides/python-net/aspose.slides/ishape/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/aspose.slides/ishape/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/aspose.slides/ishape/name/) | Returns or sets the name of a shape.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/aspose.slides/ishape/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/aspose.slides/ishape/shape_lock/) | Returns shape's locks.<br/>            Read-only [`IBaseShapeLock`](/slides/python-net/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/aspose.slides/ishape/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Read-only **int**.<br/>            See also [`IShape.office_interop_shape_id`](/slides/python-net/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/aspose.slides/ishape/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Read-only **int**.<br/>            See also [`IShape.unique_id`](/slides/python-net/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/aspose.slides/ishape/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only **bool**. |
| [`black_white_mode`](/slides/python-net/aspose.slides/ishape/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/aspose.slides/ishape/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Read-only [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/aspose.slides/ishape/hyperlink_manager/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`get_thumbnail`](/slides/python-net/aspose.slides/ishape/get_thumbnail/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_thumbnail`](/slides/python-net/aspose.slides/ishape/get_thumbnail/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`get_image`](/slides/python-net/aspose.slides/ishape/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image`](/slides/python-net/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg`](/slides/python-net/aspose.slides/ishape/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg`](/slides/python-net/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`add_placeholder`](/slides/python-net/aspose.slides/ishape/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`remove_placeholder`](/slides/python-net/aspose.slides/ishape/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`get_base_placeholder`](/slides/python-net/aspose.slides/ishape/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>A None is returned if the current shape is not inherited. |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

