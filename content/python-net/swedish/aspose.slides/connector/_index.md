---
title: Connector class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/connector/
---
## Connector-klass

Representerar en anslutning.

**Arv:**[`Connector`](/slides/python-net/sv/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/sv/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

Connector-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/connector/is_text_holder/) | Bestämmer om formen är TextHolder_PPT.<br/>            Skrivskyddad **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/connector/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Skrivskyddad [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/connector/custom_data/) | Returnerar formens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/connector/raw_frame/) | Returnerar eller anger de råa formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/connector/frame/) | Returnerar eller anger formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/connector/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som saknar linjeegenskaper.<br/>            Skrivskyddad [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/connector/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som saknar 3D-egenskaper.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/connector/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en form.<br/>            Obs: kan returnera None för vissa typer av former som saknar effektegenskaper.<br/>            Skrivskyddad [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/connector/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som saknar fyllningsegenskaper.<br/>            Skrivskyddad [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/connector/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för ett musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/connector/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för muspekning.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/connector/hyperlink_manager/) | Returnerar hyperlänkshanteraren.<br/>            Skrivskyddad [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/connector/hidden/) | Bestämmer om formen är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/connector/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Skrivskyddad **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/connector/connection_site_count/) | Returnerar antalet anslutningsställen på formen.<br/>            Skrivskyddad **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/connector/rotation/) | Returnerar eller anger antalet grader som den angivna formen roteras kring<br/>            z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde<br/>            indikerar moturs rotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/connector/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/connector/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/connector/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/connector/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/connector/black_white_mode/) | Egenskapen anger hur en form renderas i svart-vit visningsläge..<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/connector/unique_id/) | Returnerar en intern, presentation-avgränsad identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omassigneras av användaren eller programmässigt, får det inte behandlas<br/>            som en bestående unik nyckel.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/connector/office_interop_shape_id/) | Returnerar en bild-avgränsad unik identifierare som förblir konstant under formens livstid och<br/>            låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från var som helst i dokumentet.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/connector/alternative_text/) | Returnerar eller anger alternativ text som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/connector/alternative_text_title/) | Returnerar eller anger titeln för den alternativa texten som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/connector/name/) | Returnerar eller anger namnet på en form.<br/>            Får inte vara None. Använd en tom sträng om nödvändigt.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/connector/is_decorative/) | Hämtar eller anger alternativet 'Mark as decorative'<br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/connector/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IConnectorLock`](/slides/python-net/sv/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/connector/is_grouped/) | Bestämmer om formen är grupperad.<br/>            Skrivskyddad **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/connector/parent_group/) | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras None.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/connector/slide/) | Returnerar bilden som förälder till en form.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/connector/presentation/) | Returnerar presentationens förälder till en bild.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/sv/aspose.slides/connector/shape_style/) | Returnerar formens stilobjekt.<br/>            Skrivskyddad [`IShapeStyle`](/slides/python-net/sv/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/sv/aspose.slides/connector/shape_type/) | Returnerar eller anger AutoShape-typen.<br/>            Läs/skriv [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/sv/aspose.slides/connector/adjustments/) | Returnerar en samling av formens justeringsvärden.<br/>            Skrivskyddad [`IAdjustValueCollection`](/slides/python-net/sv/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/sv/aspose.slides/connector/connector_lock/) | Returnerar kopplingens lås.<br/>            Skrivskyddad [`IConnectorLock`](/slides/python-net/sv/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/sv/aspose.slides/connector/start_shape_connected_to/) | Returnerar eller anger formen som början av kopplingen ska fästas vid.<br/>            Läs/skriv [`IShape`](/slides/python-net/sv/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/sv/aspose.slides/connector/end_shape_connected_to/) | Returnerar eller anger formen som änden av kopplingen ska fästas vid.<br/>            Läs/skriv [`IShape`](/slides/python-net/sv/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/sv/aspose.slides/connector/start_shape_connection_site_index/) | Returnerar eller anger indexet för anslutningsstället för startformen.<br/>            Läs/skriv **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/sv/aspose.slides/connector/end_shape_connection_site_index/) | Returnerar eller anger indexet för anslutningsstället för slutformen.<br/>            Läs/skriv **int**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/connector/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape miniatyrbildens gränstyp används som standard. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/connector/write_as_svg/#iorawiobase) | Sparar innehållet i Shape som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i Shape som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/connector/remove_placeholder/#) | Definierar att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/connector/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om det inte finns någon och sätter platshållarens egenskaper till en angiven. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/connector/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen ärvs från).<br/>            None returneras om den aktuella formen inte ärvs. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/connector/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |
| [`get_geometry_paths(self)`](/slides/python-net/sv/aspose.slides/connector/get_geometry_paths/#) | Returnerar en kopia av geometriformens bana. Koordinaterna är relativa till formens vänstra övre hörn. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/sv/aspose.slides/connector/set_geometry_path/#igeometrypath) | Uppdaterar formens geometri från [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)-objektet. Koordinater måste vara relativa till formens vänstra<br/>            övre hörn.<br/>            Ändrar formens typ ([`GeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/geometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/sv/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Uppdaterar formens geometri från en array av [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath). Koordinater måste vara relativa till formens vänstra<br/>            övre hörn.<br/>            Ändrar formens typ ([`GeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/geometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/sv/aspose.slides/connector/create_shape_elements/#) | Skapar och returnerar en array av formens element. |
| [`reroute(self)`](/slides/python-net/sv/aspose.slides/connector/reroute/#) | Omdirigerar kopplingen så att den tar den kortaste möjliga vägen mellan formerna den ansluter. |

### Se även
* klass [`Connector`](/slides/python-net/sv/aspose.slides/connector)
* klass [`GeometryShape`](/slides/python-net/sv/aspose.slides/geometryshape)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)