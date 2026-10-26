---
title: SmartArt class
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.smartart/smartart/
---
## SmartArt osztály

Represents a SmartArt diagram

**Inheritance:**[`SmartArt`](/slides/python-net/hu/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

The SmartArt type exposes the following members:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides.smartart/smartart/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides.smartart/smartart/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides.smartart/smartart/custom_data/) | Returns the shape's custom data.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides.smartart/smartart/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides.smartart/smartart/frame/) | Returns or sets the shape frame's properties.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides.smartart/smartart/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides.smartart/smartart/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides.smartart/smartart/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides.smartart/smartart/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides.smartart/smartart/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides.smartart/smartart/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides.smartart/smartart/hidden/) | Determines whether the shape is hidden.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides.smartart/smartart/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides.smartart/smartart/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides.smartart/smartart/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides.smartart/smartart/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides.smartart/smartart/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides.smartart/smartart/width/) | Gets or sets the width of the shape, measured in points.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides.smartart/smartart/height/) | Gets or sets the height of the shape, measured in points.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides.smartart/smartart/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides.smartart/smartart/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Csak olvasható **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides.smartart/smartart/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Csak olvasható **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides.smartart/smartart/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides.smartart/smartart/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides.smartart/smartart/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides.smartart/smartart/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides.smartart/smartart/shape_lock/) | Returns shape's locks.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides.smartart/smartart/is_grouped/) | Determines whether the shape is grouped.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides.smartart/smartart/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides.smartart/smartart/slide/) | Returns the parent slide of a shape.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides.smartart/smartart/presentation/) | Returns the parent presentation of a slide.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hu/aspose.slides.smartart/smartart/graphical_object_lock/) | Returns shape's locks.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/hu/aspose.slides.smartart/smartart/all_nodes/) | Returns collections of all nodes in the SmartArt object.<br/>            Csak olvasható [`ISmartArtNodeCollection`](/slides/python-net/hu/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/hu/aspose.slides.smartart/smartart/nodes/) | Returns collections of root nodes in SmartArt object.<br/>            Csak olvasható [`ISmartArtNodeCollection`](/slides/python-net/hu/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/hu/aspose.slides.smartart/smartart/layout/) | Returns or sets layout of the SmartArt object.<br/>            Olvasás/írás [`SmartArtLayoutType`](/slides/python-net/hu/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/hu/aspose.slides.smartart/smartart/quick_style/) | Returns or sets quick style of SmartArt object.<br/>            Olvasás/írás [`SmartArtQuickStyleType`](/slides/python-net/hu/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/hu/aspose.slides.smartart/smartart/color_style/) | Returns or sets color style of SmartArt object.<br/>            Olvasás/írás [`SmartArtColorType`](/slides/python-net/hu/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/hu/aspose.slides.smartart/smartart/is_reversed/) | Return or set the state of the SmartArt diagram with regard to (left-to-right) LTR or (right-to-left) RTL, if the diagram supports reversal.<br/>            Olvasás/írás **bool**. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides.smartart/smartart/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides.smartart/smartart/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides.smartart/smartart/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides.smartart/smartart/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |

### Lásd még
* osztály [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* osztály [`SmartArt`](/slides/python-net/hu/aspose.slides.smartart/smartart)
* modul [`aspose.slides.smartart`](/slides/python-net/hu/aspose.slides.smartart)
* könyvtár [`Aspose.Slides`](/slides/python-net)