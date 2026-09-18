---
title: Table class
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/table/
---
## Klasa Table

Represents a table on a slide.

**Inheritance:**[`Table`](/slides/python-net/pl/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

The Table type exposes the following members:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/table/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/table/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/table/custom_data/) | Returns the shape's custom data.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/table/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Do odczytu i zapisu [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/table/frame/) | Returns or sets the shape frame's properties.<br/>            Do odczytu i zapisu [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/table/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/table/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/table/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/table/fill_format/) | Returns a TableFormat.FillFormat object containing the fill formatting for the Table.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/table/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Do odczytu i zapisu [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/table/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Do odczytu i zapisu [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/table/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides/table/hidden/) | Determines whether the shape is hidden.<br/>            Do odczytu i zapisu **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/table/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/table/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/table/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Do odczytu i zapisu **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/table/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Do odczytu i zapisu **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/table/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Do odczytu i zapisu **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/table/width/) | Gets or sets the width of the shape, measured in points.<br/>            Do odczytu i zapisu **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/table/height/) | Gets or sets the height of the shape, measured in points.<br/>            Do odczytu i zapisu **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/table/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Do odczytu i zapisu [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/table/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Tylko do odczytu **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/table/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Tylko do odczytu **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/table/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Do odczytu i zapisu **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/table/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Do odczytu i zapisu **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/table/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Do odczytu i zapisu **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/table/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Do odczytu i zapisu **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/table/shape_lock/) | Returns shape's locks.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/table/is_grouped/) | Determines whether the shape is grouped.<br/>            Tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides/table/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/table/slide/) | Returns the parent slide of a shape.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/table/presentation/) | Returns the parent presentation of a slide.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pl/aspose.slides/table/graphical_object_lock/) | Returns shape's locks.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/pl/aspose.slides/table/rows/) | Returns the collectoin of rows.<br/>            Tylko do odczytu [`IRowCollection`](/slides/python-net/pl/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/pl/aspose.slides/table/columns/) | Returns the collectoin of columns.<br/>            Tylko do odczytu [`IColumnCollection`](/slides/python-net/pl/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/pl/aspose.slides/table/table_format/) | Returns the TableFormat object that contains formatting properties for this table.<br/>            Tylko do odczytu [`ITableFormat`](/slides/python-net/pl/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/pl/aspose.slides/table/style_preset/) | Gets or sets builtin table style.<br/>            Do odczytu i zapisu [`TableStylePreset`](/slides/python-net/pl/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/pl/aspose.slides/table/right_to_left/) | Determines whether the table has right to left reading order.<br/>            Do odczytu i zapisu **bool**. |
| [`first_row`](/slides/python-net/pl/aspose.slides/table/first_row/) | Determines whether the first row of a table has to be drawn with a special formatting.<br/>            Do odczytu i zapisu **bool**. |
| [`first_col`](/slides/python-net/pl/aspose.slides/table/first_col/) | Determines whether the first column of a table has to be drawn with a special formatting.<br/>            Do odczytu i zapisu **bool**. |
| [`last_row`](/slides/python-net/pl/aspose.slides/table/last_row/) | Determines whether the last row of a table has to be drawn with a special formatting.<br/>            Do odczytu i zapisu **bool**. |
| [`last_col`](/slides/python-net/pl/aspose.slides/table/last_col/) | Determines whether the last column of a table has to be drawn with a special formatting.<br/>            Do odczytu i zapisu **bool**. |
| [`horizontal_banding`](/slides/python-net/pl/aspose.slides/table/horizontal_banding/) | Determines whether the even rows has to be drawn with a different formatting.<br/>            Do odczytu i zapisu **bool**. |
| [`vertical_banding`](/slides/python-net/pl/aspose.slides/table/vertical_banding/) | Determines whether the even columns has to be drawn with a different formatting.<br/>            Do odczytu i zapisu **bool**. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/table/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/table/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`set_text_format(self, source)`](/slides/python-net/pl/aspose.slides/table/set_text_format/#iportionformat) | Sets defined portion format properties to all table cells' portions. |
| [`set_text_format(self, source)`](/slides/python-net/pl/aspose.slides/table/set_text_format/#iparagraphformat) | Sets defined paragraph format properties to all table cells' paragraphs. |
| [`set_text_format(self, source)`](/slides/python-net/pl/aspose.slides/table/set_text_format/#itextframeformat) | Sets defined text frame format properties to all table cells' text frames. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/table/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/table/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/table/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides/table/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/pl/aspose.slides/table/merge_cells/#icell-icell-bool) | Merges neighbour cells. |

### Zobacz także
* klasa [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* klasa [`Table`](/slides/python-net/pl/aspose.slides/table)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)