---
title: SummaryZoomFrame class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame klass

Representerar ett Summary Zoom-objekt i en bild.

**Arv:**[`SummaryZoomFrame`](/slides/python-net/sv/aspose.slides/summaryzoomframe) → [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

Typen SummaryZoomFrame visar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/summaryzoomframe/is_text_holder/) | Avgör om formen är TextHolder_PPT.<br/>            Skrivskyddad **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/summaryzoomframe/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Skrivskyddad [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/summaryzoomframe/custom_data/) | Returnerar formens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/summaryzoomframe/raw_frame/) | Returnerar eller anger de råa egenskaperna för formramen.<br/>            Läsa/skriva [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/summaryzoomframe/frame/) | Returnerar eller anger egenskaperna för formramen.<br/>            Läsa/skriva [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/summaryzoomframe/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa former som saknar linjeegenskaper.<br/>            Skrivskyddad [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/summaryzoomframe/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa former som saknar 3D-egenskaper.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/summaryzoomframe/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en form.<br/>            Obs: kan returnera None för vissa former som saknar effektegenskaper.<br/>            Skrivskyddad [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/summaryzoomframe/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa former som saknar fyllningsegenskaper.<br/>            Skrivskyddad [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/summaryzoomframe/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för musklick.<br/>            Läsa/skriva [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/summaryzoomframe/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för musöver.<br/>            Läsa/skriva [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/summaryzoomframe/hyperlink_manager/) | Returnerar hyperlänks-hanteraren.<br/>            Skrivskyddad [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/summaryzoomframe/hidden/) | Avgör om formen är dold.<br/>            Läsa/skriva **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/summaryzoomframe/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Skrivskyddad **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/summaryzoomframe/connection_site_count/) | Returnerar antalet anslutningsställen på formen.<br/>            Skrivskyddad **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/summaryzoomframe/rotation/) | Returnerar eller anger antalet grader som den angivna formen roteras kring<br/>            z-axeln. Ett positivt värde indikerar medursrotation; ett negativt värde<br/>            indikerar motursrotation.<br/>            Läsa/skriva **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/summaryzoomframe/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läsa/skriva **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/summaryzoomframe/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läsa/skriva **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/summaryzoomframe/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läsa/skriva **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/summaryzoomframe/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läsa/skriva **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/summaryzoomframe/black_white_mode/) | Egenskapen anger hur en form renderas i svart-vitt läge.<br/>            Läsa/skriva [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/summaryzoomframe/unique_id/) | Returnerar en intern, presentations-omfattande identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omassigneras av användaren eller programmässigt, bör det inte behandlas<br/>            som en beständig unik nyckel.<br/>            Skrivskyddad **int**.<br/>            Se också [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/summaryzoomframe/office_interop_shape_id/) | Returnerar en bild-omfattande unik identifierare som förblir konstant under formens livslängd och<br/>            låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från vilken plats som helst i dokumentet.<br/>            Skrivskyddad **int**.<br/>            Se också [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/summaryzoomframe/alternative_text/) | Returnerar eller anger alternativ text som är associerad med en form.<br/>            Läsa/skriva **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/summaryzoomframe/alternative_text_title/) | Returnerar eller anger titeln för den alternativa texten som är associerad med en form.<br/>            Läsa/skriva **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/summaryzoomframe/name/) | Returnerar eller anger namnet på en form.<br/>            Måste vara icke-None. Använd tom sträng vid behov.<br/>            Läsa/skriva **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/summaryzoomframe/is_decorative/) | Hämtar eller anger alternativet 'Mark as decorative'.<br/>            Läsa/skriva **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/summaryzoomframe/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/summaryzoomframe/is_grouped/) | Avgör om formen är grupperad.<br/>            Skrivskyddad **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/summaryzoomframe/parent_group/) | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras None.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/summaryzoomframe/slide/) | Returnerar föräldrabilden för en form.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/summaryzoomframe/presentation/) | Returnerar föräldrapresentationen för en bild.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/sv/aspose.slides/summaryzoomframe/graphical_object_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`layout`](/slides/python-net/sv/aspose.slides/summaryzoomframe/layout/) | Hämtar layouten för Summary Zoom-sektioner i ramen.<br/>            Standardvärdet är GridLayout. |
| [`summary_zoom_collection`](/slides/python-net/sv/aspose.slides/summaryzoomframe/summary_zoom_collection/) | Hämtar [`ISummaryZoomSectionCollection`](/slides/python-net/sv/aspose.slides/isummaryzoomsectioncollection) för Summary Zoom-ram-objektet. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/summaryzoomframe/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape-formen för miniatyrbildsgränser används som standard. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/summaryzoomframe/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase) | Sparar innehållet i Shape som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i Shape som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/summaryzoomframe/remove_placeholder/#) | Anger att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/summaryzoomframe/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och anger platshållarens egenskaper till en specifik. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/summaryzoomframe/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudsidan som den aktuella formen ärvt från).<br/>            None returneras om den aktuella formen inte är ärvd. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/summaryzoomframe/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |

### Se även
* klass [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* klass [`SummaryZoomFrame`](/slides/python-net/sv/aspose.slides/summaryzoomframe)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)