---
title: SummaryZoomSection class
second_title: Aspose.Slides dla Pythona poprzez .NET – odwołanie API
description: 
type: docs
url: /pl/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection klasa

Represents a Summary Zoom Section object in a Summary Zoom frame.

**Inheritance:**[`SummaryZoomSection`](/slides/python-net/pl/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/pl/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/pl/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pl/aspose.slides/shape)

The SummaryZoomSection type exposes the following members:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/summaryzoomsection/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Tylko do odczytu **bool**. |
| [`placeholder`](/slides/python-net/pl/aspose.slides/summaryzoomsection/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Tylko do odczytu [`IPlaceholder`](/slides/python-net/pl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/summaryzoomsection/custom_data/) | Returns the shape's custom data.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/summaryzoomsection/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pl/aspose.slides/summaryzoomsection/frame/) | Returns or sets the shape frame's properties.<br/>            Odczyt/zapis [`IShapeFrame`](/slides/python-net/pl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pl/aspose.slides/summaryzoomsection/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Uwaga: can return None for certain types of shapes which don't have line properties.<br/>            Tylko do odczytu [`ILineFormat`](/slides/python-net/pl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/summaryzoomsection/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Uwaga: can return None for certain types of shapes which don't have 3d properties.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pl/aspose.slides/summaryzoomsection/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Uwaga: can return None for certain types of shapes which don't have effect properties.<br/>            Tylko do odczytu [`IEffectFormat`](/slides/python-net/pl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pl/aspose.slides/summaryzoomsection/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Uwaga: can return None for certain types of shapes which don't have fill properties.<br/>            Tylko do odczytu [`IFillFormat`](/slides/python-net/pl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/summaryzoomsection/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Odczyt/zapis [`IHyperlink`](/slides/python-net/pl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/summaryzoomsection/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Tylko do odczytu [`IHyperlinkManager`](/slides/python-net/pl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pl/aspose.slides/summaryzoomsection/hidden/) | Determines whether the shape is hidden.<br/>            Odczyt/zapis **bool**. |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/summaryzoomsection/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Tylko do odczytu **int**. |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/summaryzoomsection/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Tylko do odczytu **int**. |
| [`rotation`](/slides/python-net/pl/aspose.slides/summaryzoomsection/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Odczyt/zapis **float**. |
| [`x`](/slides/python-net/pl/aspose.slides/summaryzoomsection/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Odczyt/zapis **float**. |
| [`y`](/slides/python-net/pl/aspose.slides/summaryzoomsection/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Odczyt/zapis **float**. |
| [`width`](/slides/python-net/pl/aspose.slides/summaryzoomsection/width/) | Gets or sets the width of the shape, measured in points.<br/>            Odczyt/zapis **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/summaryzoomsection/height/) | Gets or sets the height of the shape, measured in points.<br/>            Odczyt/zapis **float**. |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/summaryzoomsection/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Odczyt/zapis [`BlackWhiteMode`](/slides/python-net/pl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pl/aspose.slides/summaryzoomsection/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Tylko do odczytu **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/pl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/summaryzoomsection/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Tylko do odczytu **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/pl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/summaryzoomsection/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Odczyt/zapis **str**. |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/summaryzoomsection/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Odczyt/zapis **str**. |
| [`name`](/slides/python-net/pl/aspose.slides/summaryzoomsection/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Odczyt/zapis **str**. |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/summaryzoomsection/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Odczyt/zapis **bool**. |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/summaryzoomsection/shape_lock/) | Returns shape's locks.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/summaryzoomsection/is_grouped/) | Determines whether the shape is grouped.<br/>            Tylko do odczytu **bool**. |
| [`parent_group`](/slides/python-net/pl/aspose.slides/summaryzoomsection/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Tylko do odczytu [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pl/aspose.slides/summaryzoomsection/slide/) | Returns the parent slide of a shape.<br/>            Tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/summaryzoomsection/presentation/) | Returns the parent presentation of a slide.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pl/aspose.slides/summaryzoomsection/graphical_object_lock/) | Returns shape's locks.<br/>            Tylko do odczytu [`IGraphicalObjectLock`](/slides/python-net/pl/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/pl/aspose.slides/summaryzoomsection/image_type/) | Gets or sets the image type of a zoom object.<br/>            Odczyt/zapis [`ZoomImageType`](/slides/python-net/pl/aspose.slides/zoomimagetype).<br/>            Default value: Preview |
| [`return_to_parent`](/slides/python-net/pl/aspose.slides/summaryzoomsection/return_to_parent/) | Gets or sets the navigation behavior in slideshow.<br/>            Odczyt/zapis **bool**.<br/>            Default value: false |
| [`show_background`](/slides/python-net/pl/aspose.slides/summaryzoomsection/show_background/) | Gets or sets value that specifies whether the Zoom will use the background of the destination slide.<br/>            Odczyt/zapis **bool**.<br/>            Default value: true |
| [`zoom_image`](/slides/python-net/pl/aspose.slides/summaryzoomsection/zoom_image/) | Gets or sets image for zoom object.<br/>            Odczyt/zapis [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/pl/aspose.slides/summaryzoomsection/transition_duration/) | Gets or sets the duration of the transition between Zoom and slide.<br/>            Odczyt/zapis **float**.<br/>            Default value: 1.0f |
| [`target_section`](/slides/python-net/pl/aspose.slides/summaryzoomsection/target_section/) | Gets or sets the section object that the Section Zoom object links to.<br/>            Odczyt/zapis [`ISection`](/slides/python-net/pl/aspose.slides/isection). |
| [`title`](/slides/python-net/pl/aspose.slides/summaryzoomsection/title/) | Returns the text title of the Summary Zoom Section object. |
| [`description`](/slides/python-net/pl/aspose.slides/summaryzoomsection/description/) | Returns the text description of the Summary Zoom Section object. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/summaryzoomsection/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/summaryzoomsection/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/summaryzoomsection/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/summaryzoomsection/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/pl/aspose.slides/summaryzoomsection/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |


### Zobacz także
* klasa [`GraphicalObject`](/slides/python-net/pl/aspose.slides/graphicalobject)
* klasa [`SectionZoomFrame`](/slides/python-net/pl/aspose.slides/sectionzoomframe)
* klasa [`Shape`](/slides/python-net/pl/aspose.slides/shape)
* klasa [`SummaryZoomSection`](/slides/python-net/pl/aspose.slides/summaryzoomsection)
* klasa [`ZoomObject`](/slides/python-net/pl/aspose.slides/zoomobject)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)