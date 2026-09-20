---
title: Shape class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shape/
---
## Shape klass

Representerar en form på en bildruta.

Typen Shape exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/shape/is_text_holder/) | Avgör om formen är TextHolder_PPT.<br/>            Skrivskyddad **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/shape/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Skrivskyddad [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/shape/custom_data/) | Returnerar formens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/shape/raw_frame/) | Returnerar eller anger råa formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/shape/frame/) | Returnerar eller anger formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/shape/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har linjeegenskaper.<br/>            Skrivskyddad [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/shape/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har 3D-egenskaper.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/shape/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixeleffekter som appliceras på en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har effektegenskaper.<br/>            Skrivskyddad [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/shape/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har fyllningsegenskaper.<br/>            Skrivskyddad [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/shape/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/shape/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för musöver.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/shape/hyperlink_manager/) | Returnerar hyperlink-hanteraren.<br/>            Skrivskyddad [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/shape/hidden/) | Avgör om formen är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/shape/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Skrivskyddad **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/shape/connection_site_count/) | Returnerar antalet anslutningspunkter på formen.<br/>            Skrivskyddad **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/shape/rotation/) | Returnerar eller anger antalet grader som den angivna formen roteras kring z-axeln. Ett positivt värde indikerar medursrotation; ett negativt värde indikerar motursrotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/shape/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/shape/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/shape/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/shape/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/shape/black_white_mode/) | Egenskapen anger hur en form kommer att renderas i svart-vit displayläge.<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id/) | Returnerar en intern, presentation-omfattande identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omassigneras av användaren eller programmässigt, får det inte behandlas som en bestående unik nyckel.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id/) | Returnerar en bildomfattande unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till formen från vilken plats i dokumentet som helst.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/shape/alternative_text/) | Returnerar eller anger alternativ text kopplad till en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/shape/alternative_text_title/) | Returnerar eller anger titeln på den alternativa texten som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/shape/name/) | Returnerar eller anger namnet på en form.<br/>            Måste vara icke-None. Använd tom sträng om behövs.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/shape/is_decorative/) | Hämtar eller anger alternativet 'Mark as decorative' option<br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/shape/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IBaseShapeLock`](/slides/python-net/sv/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/shape/is_grouped/) | Avgör om formen är grupperad.<br/>            Skrivskyddad **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/shape/parent_group/) | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras None.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/shape/slide/) | Returnerar den överordnade bilden för en form.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/shape/presentation/) | Returnerar den överordnade presentationen för en bild.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/shape/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/shape/write_as_svg/#iorawiobase) | Sparar innehållet i Shape som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i Shape som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/shape/remove_placeholder/#) | Anger att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/shape/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och anger platshållaregenskaper till en specificerad. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/shape/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen ärvd från).<br/>            None returneras om den aktuella formen inte ärvs. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/shape/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)