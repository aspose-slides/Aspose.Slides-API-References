---
title: Ink class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.ink/ink/
---
## Ink क्लास

Represents an ink object on a slide.

**Inheritance:**[`Ink`](/slides/python-net/hi/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hi/aspose.slides/shape)

The Ink type exposes the following members:

## प्रॉपर्टीज़

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hi/aspose.slides.ink/ink/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            केवल पढ़ने योग्य **bool**. |
| [`placeholder`](/slides/python-net/hi/aspose.slides.ink/ink/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            केवल पढ़ने योग्य [`IPlaceholder`](/slides/python-net/hi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hi/aspose.slides.ink/ink/custom_data/) | Returns the shape's custom data.<br/>            केवल पढ़ने योग्य [`ICustomData`](/slides/python-net/hi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hi/aspose.slides.ink/ink/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            पढ़ने और लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hi/aspose.slides.ink/ink/frame/) | Returns or sets the shape frame's properties.<br/>            पढ़ने और लिखने योग्य [`IShapeFrame`](/slides/python-net/hi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hi/aspose.slides.ink/ink/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            नोट: can return None for certain types of shapes which don't have line properties.<br/>            केवल पढ़ने योग्य [`ILineFormat`](/slides/python-net/hi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hi/aspose.slides.ink/ink/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            नोट: can return None for certain types of shapes which don't have 3d properties.<br/>            केवल पढ़ने योग्य [`IThreeDFormat`](/slides/python-net/hi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hi/aspose.slides.ink/ink/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            नोट: can return None for certain types of shapes which don't have effect properties.<br/>            केवल पढ़ने योग्य [`IEffectFormat`](/slides/python-net/hi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hi/aspose.slides.ink/ink/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            नोट: can return None for certain types of shapes which don't have fill properties.<br/>            केवल पढ़ने योग्य [`IFillFormat`](/slides/python-net/hi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hi/aspose.slides.ink/ink/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            पढ़ने और लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hi/aspose.slides.ink/ink/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            पढ़ने और लिखने योग्य [`IHyperlink`](/slides/python-net/hi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hi/aspose.slides.ink/ink/hyperlink_manager/) | Returns the hyperlink manager.<br/>            केवल पढ़ने योग्य [`IHyperlinkManager`](/slides/python-net/hi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hi/aspose.slides.ink/ink/hidden/) | Determines whether the shape is hidden.<br/>            पढ़ने और लिखने योग्य **bool**. |
| [`z_order_position`](/slides/python-net/hi/aspose.slides.ink/ink/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            केवल पढ़ने योग्य **int**. |
| [`connection_site_count`](/slides/python-net/hi/aspose.slides.ink/ink/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            केवल पढ़ने योग्य **int**. |
| [`rotation`](/slides/python-net/hi/aspose.slides.ink/ink/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            पढ़ने और लिखने योग्य **float**. |
| [`x`](/slides/python-net/hi/aspose.slides.ink/ink/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            पढ़ने और लिखने योग्य **float**. |
| [`y`](/slides/python-net/hi/aspose.slides.ink/ink/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            पढ़ने और लिखने योग्य **float**. |
| [`width`](/slides/python-net/hi/aspose.slides.ink/ink/width/) | Gets or sets the width of the shape, measured in points.<br/>            पढ़ने और लिखने योग्य **float**. |
| [`height`](/slides/python-net/hi/aspose.slides.ink/ink/height/) | Gets or sets the height of the shape, measured in points.<br/>            पढ़ने और लिखने योग्य **float**. |
| [`black_white_mode`](/slides/python-net/hi/aspose.slides.ink/ink/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            पढ़ने और लिखने योग्य [`BlackWhiteMode`](/slides/python-net/hi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hi/aspose.slides.ink/ink/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            केवल पढ़ने योग्य **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/hi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hi/aspose.slides.ink/ink/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            केवल पढ़ने योग्य **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/hi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hi/aspose.slides.ink/ink/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            पढ़ने और लिखने योग्य **str**. |
| [`alternative_text_title`](/slides/python-net/hi/aspose.slides.ink/ink/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            पढ़ने और लिखने योग्य **str**. |
| [`name`](/slides/python-net/hi/aspose.slides.ink/ink/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            पढ़ने और लिखने योग्य **str**. |
| [`is_decorative`](/slides/python-net/hi/aspose.slides.ink/ink/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            पढ़ने और लिखने योग्य **bool**. |
| [`shape_lock`](/slides/python-net/hi/aspose.slides.ink/ink/shape_lock/) | Returns shape's locks.<br/>            केवल पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hi/aspose.slides.ink/ink/is_grouped/) | Determines whether the shape is grouped.<br/>            केवल पढ़ने योग्य **bool**. |
| [`parent_group`](/slides/python-net/hi/aspose.slides.ink/ink/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            केवल पढ़ने योग्य [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hi/aspose.slides.ink/ink/slide/) | Returns the parent slide of a shape.<br/>            केवल पढ़ने योग्य [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hi/aspose.slides.ink/ink/presentation/) | Returns the parent presentation of a slide.<br/>            केवल पढ़ने योग्य [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hi/aspose.slides.ink/ink/graphical_object_lock/) | Returns shape's locks.<br/>            केवल पढ़ने योग्य [`IGraphicalObjectLock`](/slides/python-net/hi/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/hi/aspose.slides.ink/ink/traces/) | Gets all traces containing in the IInk element [`IInkTrace`](/slides/python-net/hi/aspose.slides.ink/iinktrace).<br/>            केवल पढ़ने योग्य. |

## मेथड्स

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hi/aspose.slides.ink/ink/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hi/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`write_as_svg(self, stream)`](/slides/python-net/hi/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hi/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`remove_placeholder(self)`](/slides/python-net/hi/aspose.slides.ink/ink/remove_placeholder/#) | Defines that this shape isn't a placeholder.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hi/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_base_placeholder(self)`](/slides/python-net/hi/aspose.slides.ink/ink/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_visual_bounds(self)`](/slides/python-net/hi/aspose.slides.ink/ink/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/hi/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | Registers an image to collection of custom images used to simulate visual effects for ink brushes.<br/>            These images are used when rendering ink with specific [`InkEffectType`](/slides/python-net/hi/aspose.slides.ink/inkeffecttype) values,<br/>            such as Galaxy, Rainbow, etc. By providing your own images, you can control how each ink effect appears.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/hi/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | Unregisters an image from collection of custom images used to simulate visual effects for ink brushes<br/>            previously registered images via **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide**.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |

### देखें भी
* क्लास [`GraphicalObject`](/slides/python-net/hi/aspose.slides/graphicalobject)
* क्लास [`Ink`](/slides/python-net/hi/aspose.slides.ink/ink)
* क्लास [`Shape`](/slides/python-net/hi/aspose.slides/shape)
* मॉड्यूल [`aspose.slides.ink`](/slides/python-net/hi/aspose.slides.ink)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)