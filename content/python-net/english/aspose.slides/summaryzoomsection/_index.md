---
title: SummaryZoomSection
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/summaryzoomsection/
---


SummaryZoomSection class

Represents a Summary Zoom Section object in a Summary Zoom frame.

**Inheritance:**[`SummaryZoomSection`](/slides/python-net/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/aspose.slides/shape)

The SummaryZoomSection type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [is_text_holder](/slides/python-net/aspose.slides/summaryzoomsection/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only .NET type System.Boolean. |
| [placeholder](/slides/python-net/aspose.slides/summaryzoomsection/placeholder/) | Returns the placeholder for a shape. Returns null if the shape has no placeholder.<br/>            Read-only [`IPlaceholder`](/slides/python-net/aspose.slides/iplaceholder). |
| [custom_data](/slides/python-net/aspose.slides/summaryzoomsection/custom_data/) | Returns the shape's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [raw_frame](/slides/python-net/aspose.slides/summaryzoomsection/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [frame](/slides/python-net/aspose.slides/summaryzoomsection/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [line_format](/slides/python-net/aspose.slides/summaryzoomsection/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have line properties.<br/>            Read-only [`ILineFormat`](/slides/python-net/aspose.slides/ilineformat). |
| [three_d_format](/slides/python-net/aspose.slides/summaryzoomsection/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have 3d properties.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/aspose.slides/ithreedformat). |
| [effect_format](/slides/python-net/aspose.slides/summaryzoomsection/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return null for certain types of shapes which don't have effect properties.<br/>            Read-only [`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat). |
| [fill_format](/slides/python-net/aspose.slides/summaryzoomsection/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have fill properties.<br/>            Read-only [`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [hyperlink_click](/slides/python-net/aspose.slides/summaryzoomsection/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [hyperlink_manager](/slides/python-net/aspose.slides/summaryzoomsection/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/aspose.slides/ihyperlinkmanager). |
| [hidden](/slides/python-net/aspose.slides/summaryzoomsection/hidden/) | Determines whether the shape is hidden.<br/>            Read/write .NET type System.Boolean. |
| [z_order_position](/slides/python-net/aspose.slides/summaryzoomsection/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only .NET type System.Int32. |
| [connection_site_count](/slides/python-net/aspose.slides/summaryzoomsection/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only .NET type System.Int32. |
| [rotation](/slides/python-net/aspose.slides/summaryzoomsection/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write .NET type System.Single. |
| [x](/slides/python-net/aspose.slides/summaryzoomsection/x/) | Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write .NET type System.Single. |
| [y](/slides/python-net/aspose.slides/summaryzoomsection/y/) | Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write .NET type System.Single. |
| [width](/slides/python-net/aspose.slides/summaryzoomsection/width/) | Returns or sets the width of the shape.<br/>            Read/write .NET type System.Single. |
| [height](/slides/python-net/aspose.slides/summaryzoomsection/height/) | Returns or sets the height of the shape.<br/>            Read/write .NET type System.Single. |
| [black_white_mode](/slides/python-net/aspose.slides/summaryzoomsection/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/aspose.slides/blackwhitemode). |
| [unique_id](/slides/python-net/aspose.slides/summaryzoomsection/unique_id/) | Gets unique shape identifier in presentation scope.<br/>            Read-only .NET type System.UInt32.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/aspose.slides/shape#office_interop_shape_id) for getting unique shape identifier in slide scope. |
| [office_interop_shape_id](/slides/python-net/aspose.slides/summaryzoomsection/office_interop_shape_id/) | Gets unique shape identifier in slide scope.<br/>            Read-only .NET type System.UInt32.<br/>            See also [`Shape.unique_id`](/slides/python-net/aspose.slides/shape#unique_id) for getting unique shape identifier in presentation scope. |
| [alternative_text](/slides/python-net/aspose.slides/summaryzoomsection/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write .NET type System.String. |
| [alternative_text_title](/slides/python-net/aspose.slides/summaryzoomsection/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write .NET type System.String. |
| [name](/slides/python-net/aspose.slides/summaryzoomsection/name/) | Returns or sets the name of a shape.<br/>            Must be not null. Use empty string value if needed.<br/>            Read/write .NET type System.String. |
| [is_decorative](/slides/python-net/aspose.slides/summaryzoomsection/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write .NET type System.Boolean. |
| [shape_lock](/slides/python-net/aspose.slides/summaryzoomsection/shape_lock/) | Returns shape's locks.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/aspose.slides/igraphicalobjectlock). |
| [is_grouped](/slides/python-net/aspose.slides/summaryzoomsection/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only .NET type System.Boolean. |
| [parent_group](/slides/python-net/aspose.slides/summaryzoomsection/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape). |
| [slide](/slides/python-net/aspose.slides/summaryzoomsection/slide/) | Returns the parent slide of a shape.<br/>            Read-only [`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide). |
| [presentation](/slides/python-net/aspose.slides/summaryzoomsection/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only [`IPresentation`](/slides/python-net/aspose.slides/ipresentation). |
| [graphical_object_lock](/slides/python-net/aspose.slides/summaryzoomsection/graphical_object_lock/) | Returns shape's locks.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/aspose.slides/igraphicalobjectlock). |
| [image_type](/slides/python-net/aspose.slides/summaryzoomsection/image_type/) | Gets or sets the image type of a zoom object.<br/>            Read/write [`ZoomImageType`](/slides/python-net/aspose.slides/zoomimagetype).<br/>            Default value: Preview |
| [return_to_parent](/slides/python-net/aspose.slides/summaryzoomsection/return_to_parent/) | Gets or sets the navigation behavior in slideshow.<br/>            Read/write .NET type System.Boolean.<br/>            Default value: false |
| [show_background](/slides/python-net/aspose.slides/summaryzoomsection/show_background/) | Gets or sets value that specifies whether the Zoom will use the background of the destination slide.<br/>            Read/write .NET type System.Boolean.<br/>            Default value: true |
| [image](/slides/python-net/aspose.slides/summaryzoomsection/image/) | Gets or sets image for zoom object.<br/>            Read/write [`IPPImage`](/slides/python-net/aspose.slides/ippimage). |
| [transition_duration](/slides/python-net/aspose.slides/summaryzoomsection/transition_duration/) | Gets or sets the duration of the transition between Zoom and slide.<br/>            Read/write .NET type System.Single.<br/>            Default value: 1.0f |
| [target_section](/slides/python-net/aspose.slides/summaryzoomsection/target_section/) | Gets or sets the section object that the Section Zoom object links to.<br/>            Read/write [`ISection`](/slides/python-net/aspose.slides/isection). |
| [title](/slides/python-net/aspose.slides/summaryzoomsection/title/) | Returns the text title of the Summary Zoom Section object. |
| [description](/slides/python-net/aspose.slides/summaryzoomsection/description/) | Returns the text description of the Summary Zoom Section object. |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides/summaryzoomsection/as_i_hyperlink_container/) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides/summaryzoomsection/as_i_slide_component/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/summaryzoomsection/as_i_presentation_component/) |  |
| [as_i_shape](/slides/python-net/aspose.slides/summaryzoomsection/as_i_shape/) |  |
| [as_i_graphical_object](/slides/python-net/aspose.slides/summaryzoomsection/as_i_graphical_object/) |  |
| [as_i_zoom_object](/slides/python-net/aspose.slides/summaryzoomsection/as_i_zoom_object/) |  |
| [as_i_section_zoom_frame](/slides/python-net/aspose.slides/summaryzoomsection/as_i_section_zoom_frame/) |  |

## Methods

| Method | Description |
| :- | :- |
| [get_thumbnail](/slides/python-net/aspose.slides/summaryzoomsection/get_thumbnail/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [get_thumbnail](/slides/python-net/aspose.slides/summaryzoomsection/get_thumbnail/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [write_as_svg](/slides/python-net/aspose.slides/summaryzoomsection/write_as_svg/#systemiostream) | Saves content of Shape as SVG file. |
| [write_as_svg](/slides/python-net/aspose.slides/summaryzoomsection/write_as_svg/#systemiostream-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [remove_placeholder](/slides/python-net/aspose.slides/summaryzoomsection/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [add_placeholder](/slides/python-net/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [get_base_placeholder](/slides/python-net/aspose.slides/summaryzoomsection/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A null is returned if the current shape is not inherited. |

