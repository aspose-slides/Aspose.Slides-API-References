---
title: InkActions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ink/inkactions/
---
## InkActions クラス

Represents the root of ink actions.

**Inheritance:**[`InkActions`](/slides/python-net/ja/aspose.slides.ink/inkactions) → [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

The InkActions type exposes the following members:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides.ink/inkactions/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/ja/aspose.slides.ink/inkactions/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Read-only [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ja/aspose.slides.ink/inkactions/custom_data/) | Returns the shape's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ja/aspose.slides.ink/inkactions/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ja/aspose.slides.ink/inkactions/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ja/aspose.slides.ink/inkactions/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            Read-only [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ja/aspose.slides.ink/inkactions/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ja/aspose.slides.ink/inkactions/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            Read-only [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ja/aspose.slides.ink/inkactions/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            Read-only [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides.ink/inkactions/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides.ink/inkactions/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides.ink/inkactions/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ja/aspose.slides.ink/inkactions/hidden/) | Determines whether the shape is hidden.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/ja/aspose.slides.ink/inkactions/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides.ink/inkactions/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/ja/aspose.slides.ink/inkactions/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/ja/aspose.slides.ink/inkactions/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/ja/aspose.slides.ink/inkactions/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/ja/aspose.slides.ink/inkactions/width/) | Gets or sets the width of the shape, measured in points.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/ja/aspose.slides.ink/inkactions/height/) | Gets or sets the height of the shape, measured in points.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides.ink/inkactions/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ja/aspose.slides.ink/inkactions/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Read-only **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides.ink/inkactions/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Read-only **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ja/aspose.slides.ink/inkactions/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides.ink/inkactions/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/ja/aspose.slides.ink/inkactions/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/ja/aspose.slides.ink/inkactions/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/ja/aspose.slides.ink/inkactions/shape_lock/) | Returns shape's locks.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ja/aspose.slides.ink/inkactions/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/ja/aspose.slides.ink/inkactions/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Read-only [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ja/aspose.slides.ink/inkactions/slide/) | Returns the parent slide of a shape.<br/>            Read-only [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ja/aspose.slides.ink/inkactions/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ja/aspose.slides.ink/inkactions/graphical_object_lock/) | Returns shape's locks.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock). |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides.ink/inkactions/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides.ink/inkactions/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides.ink/inkactions/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides.ink/inkactions/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides.ink/inkactions/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides.ink/inkactions/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |

### 参照
* クラス [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* クラス [`InkActions`](/slides/python-net/ja/aspose.slides.ink/inkactions)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* モジュール [`aspose.slides.ink`](/slides/python-net/ja/aspose.slides.ink)
* ライブラリ [`Aspose.Slides`](/slides/python-net)