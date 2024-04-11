---
title: Table
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/table/
---


Table class

Represents a table on a slide.

**Inheritance:**[`Table`](/slides/python-net/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/aspose.slides/shape)

The Table type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [is_text_holder](/slides/python-net/aspose.slides/table/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only .NET type System.Boolean. |
| [placeholder](/slides/python-net/aspose.slides/table/placeholder/) | Returns the placeholder for a shape. Returns null if the shape has no placeholder.<br/>            Read-only [`IPlaceholder`](/slides/python-net/aspose.slides/iplaceholder). |
| [custom_data](/slides/python-net/aspose.slides/table/custom_data/) | Returns the shape's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [raw_frame](/slides/python-net/aspose.slides/table/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [frame](/slides/python-net/aspose.slides/table/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [line_format](/slides/python-net/aspose.slides/table/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have line properties.<br/>            Read-only [`ILineFormat`](/slides/python-net/aspose.slides/ilineformat). |
| [three_d_format](/slides/python-net/aspose.slides/table/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have 3d properties.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/aspose.slides/ithreedformat). |
| [effect_format](/slides/python-net/aspose.slides/table/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return null for certain types of shapes which don't have effect properties.<br/>            Read-only [`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat). |
| [fill_format](/slides/python-net/aspose.slides/table/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have fill properties.<br/>            Read-only [`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [hyperlink_click](/slides/python-net/aspose.slides/table/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides/table/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [hyperlink_manager](/slides/python-net/aspose.slides/table/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/aspose.slides/ihyperlinkmanager). |
| [hidden](/slides/python-net/aspose.slides/table/hidden/) | Determines whether the shape is hidden.<br/>            Read/write .NET type System.Boolean. |
| [z_order_position](/slides/python-net/aspose.slides/table/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only .NET type System.Int32. |
| [connection_site_count](/slides/python-net/aspose.slides/table/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only .NET type System.Int32. |
| [rotation](/slides/python-net/aspose.slides/table/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write .NET type System.Single. |
| [x](/slides/python-net/aspose.slides/table/x/) | Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write .NET type System.Single. |
| [y](/slides/python-net/aspose.slides/table/y/) | Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write .NET type System.Single. |
| [width](/slides/python-net/aspose.slides/table/width/) | Returns or sets the width of the shape.<br/>            Read/write .NET type System.Single. |
| [height](/slides/python-net/aspose.slides/table/height/) | Returns or sets the height of the shape.<br/>            Read/write .NET type System.Single. |
| [black_white_mode](/slides/python-net/aspose.slides/table/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/aspose.slides/blackwhitemode). |
| [unique_id](/slides/python-net/aspose.slides/table/unique_id/) | Gets unique shape identifier in presentation scope.<br/>            Read-only .NET type System.UInt32.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/aspose.slides/shape#office_interop_shape_id) for getting unique shape identifier in slide scope. |
| [office_interop_shape_id](/slides/python-net/aspose.slides/table/office_interop_shape_id/) | Gets unique shape identifier in slide scope.<br/>            Read-only .NET type System.UInt32.<br/>            See also [`Shape.unique_id`](/slides/python-net/aspose.slides/shape#unique_id) for getting unique shape identifier in presentation scope. |
| [alternative_text](/slides/python-net/aspose.slides/table/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write .NET type System.String. |
| [alternative_text_title](/slides/python-net/aspose.slides/table/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write .NET type System.String. |
| [name](/slides/python-net/aspose.slides/table/name/) | Returns or sets the name of a shape.<br/>            Must be not null. Use empty string value if needed.<br/>            Read/write .NET type System.String. |
| [is_decorative](/slides/python-net/aspose.slides/table/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write .NET type System.Boolean. |
| [shape_lock](/slides/python-net/aspose.slides/table/shape_lock/) | Returns shape's locks.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/aspose.slides/igraphicalobjectlock). |
| [is_grouped](/slides/python-net/aspose.slides/table/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only .NET type System.Boolean. |
| [parent_group](/slides/python-net/aspose.slides/table/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape). |
| [slide](/slides/python-net/aspose.slides/table/slide/) | Returns the parent slide of a shape.<br/>            Read-only [`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide). |
| [presentation](/slides/python-net/aspose.slides/table/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only [`IPresentation`](/slides/python-net/aspose.slides/ipresentation). |
| [graphical_object_lock](/slides/python-net/aspose.slides/table/graphical_object_lock/) | Returns shape's locks.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/aspose.slides/igraphicalobjectlock). |
| [rows](/slides/python-net/aspose.slides/table/rows/) | Returns the collectoin of rows.<br/>            Read-only [`IRowCollection`](/slides/python-net/aspose.slides/irowcollection). |
| [columns](/slides/python-net/aspose.slides/table/columns/) | Returns the collectoin of columns.<br/>            Read-only [`IColumnCollection`](/slides/python-net/aspose.slides/icolumncollection). |
| [table_format](/slides/python-net/aspose.slides/table/table_format/) | Returns the TableFormat object that contains formatting properties for this table.<br/>            Read-only [`ITableFormat`](/slides/python-net/aspose.slides/itableformat). |
| [style_preset](/slides/python-net/aspose.slides/table/style_preset/) | Gets or sets builtin table style.<br/>            Read/write [`TableStylePreset`](/slides/python-net/aspose.slides/tablestylepreset). |
| [right_to_left](/slides/python-net/aspose.slides/table/right_to_left/) | Determines whether the table has right to left reading order.<br/>            Read-write .NET type System.Boolean. |
| [first_row](/slides/python-net/aspose.slides/table/first_row/) | Determines whether the first row of a table has to be drawn with a special formatting.<br/>            Read/write .NET type System.Boolean. |
| [first_col](/slides/python-net/aspose.slides/table/first_col/) | Determines whether the first column of a table has to be drawn with a special formatting.<br/>            Read/write .NET type System.Boolean. |
| [last_row](/slides/python-net/aspose.slides/table/last_row/) | Determines whether the last row of a table has to be drawn with a special formatting.<br/>            Read/write .NET type System.Boolean. |
| [last_col](/slides/python-net/aspose.slides/table/last_col/) | Determines whether the last column of a table has to be drawn with a special formatting.<br/>            Read/write .NET type System.Boolean. |
| [horizontal_banding](/slides/python-net/aspose.slides/table/horizontal_banding/) | Determines whether the even rows has to be drawn with a different formatting.<br/>            Read/write .NET type System.Boolean. |
| [vertical_banding](/slides/python-net/aspose.slides/table/vertical_banding/) | Determines whether the even columns has to be drawn with a different formatting.<br/>            Read/write .NET type System.Boolean. |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides/table/as_i_hyperlink_container/) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides/table/as_i_slide_component/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/table/as_i_presentation_component/) |  |
| [as_i_shape](/slides/python-net/aspose.slides/table/as_i_shape/) |  |
| [as_i_graphical_object](/slides/python-net/aspose.slides/table/as_i_graphical_object/) |  |
| [as_i_bulk_text_formattable](/slides/python-net/aspose.slides/table/as_i_bulk_text_formattable/) |  |

## Methods

| Method | Description |
| :- | :- |
| [get_thumbnail](/slides/python-net/aspose.slides/table/get_thumbnail/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [get_thumbnail](/slides/python-net/aspose.slides/table/get_thumbnail/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [write_as_svg](/slides/python-net/aspose.slides/table/write_as_svg/#systemiostream) | Saves content of Shape as SVG file. |
| [write_as_svg](/slides/python-net/aspose.slides/table/write_as_svg/#systemiostream-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [set_text_format](/slides/python-net/aspose.slides/table/set_text_format/#iportionformat) | Sets defined portion format properties to all table cells' portions. |
| [set_text_format](/slides/python-net/aspose.slides/table/set_text_format/#iparagraphformat) | Sets defined paragraph format properties to all table cells' paragraphs. |
| [set_text_format](/slides/python-net/aspose.slides/table/set_text_format/#itextframeformat) | Sets defined text frame format properties to all table cells' text frames. |
| [remove_placeholder](/slides/python-net/aspose.slides/table/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [add_placeholder](/slides/python-net/aspose.slides/table/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [get_base_placeholder](/slides/python-net/aspose.slides/table/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A null is returned if the current shape is not inherited. |
| [merge_cells](/slides/python-net/aspose.slides/table/merge_cells/#icell-icell-bool) | Merges neighbour cells. |

