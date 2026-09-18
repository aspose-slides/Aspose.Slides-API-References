---
title: InkActions class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ink/inkactions/
---
## InkActions sınıfı

Represents the root of ink actions.

**Kalıtım:**[`InkActions`](/slides/python-net/tr/aspose.slides.ink/inkactions) → [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

The InkActions type exposes the following members:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides.ink/inkactions/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Yalnızca okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides.ink/inkactions/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Yalnızca okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides.ink/inkactions/custom_data/) | Returns the shape's custom data.<br/>            Yalnızca okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides.ink/inkactions/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Okunur/Yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides.ink/inkactions/frame/) | Returns or sets the shape frame's properties.<br/>            Okunur/Yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides.ink/inkactions/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            Yalnızca okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides.ink/inkactions/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            Yalnızca okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides.ink/inkactions/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            Yalnızca okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides.ink/inkactions/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            Yalnızca okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides.ink/inkactions/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Okunur/Yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides.ink/inkactions/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Okunur/Yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides.ink/inkactions/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Yalnızca okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides.ink/inkactions/hidden/) | Determines whether the shape is hidden.<br/>            Okunur/Yazılabilir **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides.ink/inkactions/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Yalnızca okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides.ink/inkactions/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Yalnızca okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides.ink/inkactions/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Okunur/Yazılabilir **float**. |
| [`x`](/slides/python-net/tr/aspose.slides.ink/inkactions/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Okunur/Yazılabilir **float**. |
| [`y`](/slides/python-net/tr/aspose.slides.ink/inkactions/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Okunur/Yazılabilir **float**. |
| [`width`](/slides/python-net/tr/aspose.slides.ink/inkactions/width/) | Gets or sets the width of the shape, measured in points.<br/>            Okunur/Yazılabilir **float**. |
| [`height`](/slides/python-net/tr/aspose.slides.ink/inkactions/height/) | Gets or sets the height of the shape, measured in points.<br/>            Okunur/Yazılabilir **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides.ink/inkactions/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Okunur/Yazılabilir [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides.ink/inkactions/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Yalnızca okunur **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides.ink/inkactions/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Yalnızca okunur **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides.ink/inkactions/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Okunur/Yazılabilir **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides.ink/inkactions/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Okunur/Yazılabilir **str**. |
| [`name`](/slides/python-net/tr/aspose.slides.ink/inkactions/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Okunur/Yazılabilir **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides.ink/inkactions/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides.ink/inkactions/shape_lock/) | Returns shape's locks.<br/>            Yalnızca okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides.ink/inkactions/is_grouped/) | Determines whether the shape is grouped.<br/>            Yalnızca okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides.ink/inkactions/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Yalnızca okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides.ink/inkactions/slide/) | Returns the parent slide of a shape.<br/>            Yalnızca okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides.ink/inkactions/presentation/) | Returns the parent presentation of a slide.<br/>            Yalnızca okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/tr/aspose.slides.ink/inkactions/graphical_object_lock/) | Returns shape's locks.<br/>            Yalnızca okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides.ink/inkactions/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides.ink/inkactions/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides.ink/inkactions/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides.ink/inkactions/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides.ink/inkactions/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides.ink/inkactions/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |

### Ayrıca Bakınız
* sınıf [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject)
* sınıf [`InkActions`](/slides/python-net/tr/aspose.slides.ink/inkactions)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* modül [`aspose.slides.ink`](/slides/python-net/tr/aspose.slides.ink)
* kütüphane [`Aspose.Slides`](/slides/python-net)