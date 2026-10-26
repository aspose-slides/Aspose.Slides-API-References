---
title: SectionZoomFrame class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame classe

Represents a Section Zoom object in a slide.

**Inheritance:**[`SectionZoomFrame`](/slides/python-net/pt/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/pt/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/pt/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pt/aspose.slides/shape)

The SectionZoomFrame type exposes the following members:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides/sectionzoomframe/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Somente leitura **bool**. |
| [`placeholder`](/slides/python-net/pt/aspose.slides/sectionzoomframe/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Somente leitura [`IPlaceholder`](/slides/python-net/pt/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pt/aspose.slides/sectionzoomframe/custom_data/) | Returns the shape's custom data.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pt/aspose.slides/sectionzoomframe/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Leitura/Gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pt/aspose.slides/sectionzoomframe/frame/) | Returns or sets the shape frame's properties.<br/>            Leitura/Gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pt/aspose.slides/sectionzoomframe/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de linha.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/sectionzoomframe/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades 3d.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides/sectionzoomframe/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de efeito.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides/sectionzoomframe/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de preenchimento.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/sectionzoomframe/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Leitura/Gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/sectionzoomframe/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Leitura/Gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/sectionzoomframe/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Somente leitura [`IHyperlinkManager`](/slides/python-net/pt/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pt/aspose.slides/sectionzoomframe/hidden/) | Determines whether the shape is hidden.<br/>            Leitura/Gravação **bool**. |
| [`z_order_position`](/slides/python-net/pt/aspose.slides/sectionzoomframe/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Somente leitura **int**. |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides/sectionzoomframe/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Somente leitura **int**. |
| [`rotation`](/slides/python-net/pt/aspose.slides/sectionzoomframe/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Leitura/Gravação **float**. |
| [`x`](/slides/python-net/pt/aspose.slides/sectionzoomframe/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Leitura/Gravação **float**. |
| [`y`](/slides/python-net/pt/aspose.slides/sectionzoomframe/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Leitura/Gravação **float**. |
| [`width`](/slides/python-net/pt/aspose.slides/sectionzoomframe/width/) | Gets or sets the width of the shape, measured in points.<br/>            Leitura/Gravação **float**. |
| [`height`](/slides/python-net/pt/aspose.slides/sectionzoomframe/height/) | Gets or sets the height of the shape, measured in points.<br/>            Leitura/Gravação **float**. |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides/sectionzoomframe/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Leitura/Gravação [`BlackWhiteMode`](/slides/python-net/pt/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pt/aspose.slides/sectionzoomframe/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Somente leitura **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/pt/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides/sectionzoomframe/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Somente leitura **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/pt/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pt/aspose.slides/sectionzoomframe/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Leitura/Gravação **str**. |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides/sectionzoomframe/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Leitura/Gravação **str**. |
| [`name`](/slides/python-net/pt/aspose.slides/sectionzoomframe/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Leitura/Gravação **str**. |
| [`is_decorative`](/slides/python-net/pt/aspose.slides/sectionzoomframe/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Leitura/Gravação **bool**. |
| [`shape_lock`](/slides/python-net/pt/aspose.slides/sectionzoomframe/shape_lock/) | Returns shape's locks.<br/>            Somente leitura [`IGraphicalObjectLock`](/slides/python-net/pt/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pt/aspose.slides/sectionzoomframe/is_grouped/) | Determines whether the shape is grouped.<br/>            Somente leitura **bool**. |
| [`parent_group`](/slides/python-net/pt/aspose.slides/sectionzoomframe/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pt/aspose.slides/sectionzoomframe/slide/) | Returns the parent slide of a shape.<br/>            Somente leitura [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pt/aspose.slides/sectionzoomframe/presentation/) | Returns the parent presentation of a slide.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pt/aspose.slides/sectionzoomframe/graphical_object_lock/) | Returns shape's locks.<br/>            Somente leitura [`IGraphicalObjectLock`](/slides/python-net/pt/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/pt/aspose.slides/sectionzoomframe/image_type/) | Gets or sets the image type of a zoom object.<br/>            Leitura/Gravação [`ZoomImageType`](/slides/python-net/pt/aspose.slides/zoomimagetype).<br/>            Default value: Preview |
| [`return_to_parent`](/slides/python-net/pt/aspose.slides/sectionzoomframe/return_to_parent/) | Gets or sets the navigation behavior in slideshow.<br/>            Leitura/Gravação **bool**.<br/>            Default value: false |
| [`show_background`](/slides/python-net/pt/aspose.slides/sectionzoomframe/show_background/) | Gets or sets value that specifies whether the Zoom will use the background of the destination slide.<br/>            Leitura/Gravação **bool**.<br/>            Default value: true |
| [`zoom_image`](/slides/python-net/pt/aspose.slides/sectionzoomframe/zoom_image/) | Gets or sets image for zoom object.<br/>            Leitura/Gravação [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/pt/aspose.slides/sectionzoomframe/transition_duration/) | Gets or sets the duration of the transition between Zoom and slide.<br/>            Leitura/Gravação **float**.<br/>            Default value: 1.0f |
| [`target_section`](/slides/python-net/pt/aspose.slides/sectionzoomframe/target_section/) | Gets or sets the section object that the Section Zoom object links to.<br/>            Leitura/Gravação [`ISection`](/slides/python-net/pt/aspose.slides/isection). |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/sectionzoomframe/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/sectionzoomframe/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides/sectionzoomframe/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides/sectionzoomframe/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides/sectionzoomframe/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/pt/aspose.slides/sectionzoomframe/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |

### Veja Também
* classe [`GraphicalObject`](/slides/python-net/pt/aspose.slides/graphicalobject)
* classe [`SectionZoomFrame`](/slides/python-net/pt/aspose.slides/sectionzoomframe)
* classe [`Shape`](/slides/python-net/pt/aspose.slides/shape)
* classe [`ZoomObject`](/slides/python-net/pt/aspose.slides/zoomobject)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)