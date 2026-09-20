---
title: ZoomObject class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/zoomobject/
---
## ZoomObject-klass

Representerar ett Zoom-objekt i en bild.

**Inheritance:**[`ZoomObject`](/slides/python-net/sv/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

ZoomObject-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/zoomobject/is_text_holder/) | Bestämmer om formen är TextHolder_PPT.<br/>            Skrivskyddad **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/zoomobject/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Skrivskyddad [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/zoomobject/custom_data/) | Returnerar formens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/zoomobject/raw_frame/) | Returnerar eller anger de råa egenskaperna för formens ram.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/zoomobject/frame/) | Returnerar eller anger formens ramegenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/zoomobject/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som saknar linjeegenskaper.<br/>            Skrivskyddad [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/zoomobject/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som saknar 3D-egenskaper.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/zoomobject/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixel-effekter som tillämpas på en form.<br/>            Obs: kan returnera None för vissa typer av former som saknar effektegenskaper.<br/>            Skrivskyddad [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/zoomobject/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som saknar fyllningsegenskaper.<br/>            Skrivskyddad [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/zoomobject/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/zoomobject/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för musöver.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/zoomobject/hyperlink_manager/) | Returnerar hyperlänkshanteraren.<br/>            Skrivskyddad [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/zoomobject/hidden/) | Bestämmer om formen är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/zoomobject/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Skrivskyddad **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/zoomobject/connection_site_count/) | Returnerar antalet anslutningsställen på formen.<br/>            Skrivskyddad **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/zoomobject/rotation/) | Returnerar eller anger antalet grader som den specificerade formen roteras kring<br/>            z-axeln. Ett positivt värde indikerar medursrotation; ett negativt värde<br/>            indikerar motursrotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/zoomobject/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/zoomobject/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/zoomobject/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/zoomobject/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/zoomobject/black_white_mode/) | Egenskapen anger hur en form renderas i svartvit display-läge.<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/zoomobject/unique_id/) | Returnerar en intern, presentation-omfattande identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omassigneras av användaren eller programmässigt, får det inte behandlas<br/>            som en bestående unik nyckel.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/zoomobject/office_interop_shape_id/) | Returnerar en bild-omfattande unik identifierare som förblir konstant under formens livstid och<br/>            låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till formen från var som helst i dokumentet.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/zoomobject/alternative_text/) | Returnerar eller anger den alternativa texten som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/zoomobject/alternative_text_title/) | Returnerar eller anger titeln för den alternativa texten som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/zoomobject/name/) | Returnerar eller anger namnet på en form.<br/>            Får inte vara None. Använd tom sträng om nödvändigt.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/zoomobject/is_decorative/) | Hämtar eller anger alternativet 'Mark as decorative'<br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/zoomobject/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/zoomobject/is_grouped/) | Bestämmer om formen är grupperad.<br/>            Skrivskyddad **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/zoomobject/parent_group/) | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras None.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/zoomobject/slide/) | Returnerar föräldrabilden för en form.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/zoomobject/presentation/) | Returnerar föräldrapresentationen för en bild.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/sv/aspose.slides/zoomobject/graphical_object_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/sv/aspose.slides/zoomobject/image_type/) | Hämtar eller anger bildtypen för ett zoom-objekt.<br/>            Läs/skriv [`ZoomImageType`](/slides/python-net/sv/aspose.slides/zoomimagetype).<br/>            Standardvärde: Preview |
| [`return_to_parent`](/slides/python-net/sv/aspose.slides/zoomobject/return_to_parent/) | Hämtar eller anger navigeringsbeteendet i bildspel.<br/>            Läs/skriv **bool**.<br/>            Standardvärde: false |
| [`show_background`](/slides/python-net/sv/aspose.slides/zoomobject/show_background/) | Hämtar eller anger värdet som specificerar om Zoom kommer att använda bakgrunden på destinationsbilden.<br/>            Läs/skriv **bool**.<br/>            Standardvärde: true |
| [`zoom_image`](/slides/python-net/sv/aspose.slides/zoomobject/zoom_image/) | Hämtar eller anger bild för zoom-objektet.<br/>            Läs/skriv [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/sv/aspose.slides/zoomobject/transition_duration/) | Hämtar eller anger varaktigheten för övergången mellan Zoom och bild.<br/>            Läs/skriv **float**.<br/>            Standardvärde: 1.0f |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/zoomobject/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape används som standard för miniatyrbildens gränsvärden. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | Sparar Shape:s innehåll som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar Shape:s innehåll som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/zoomobject/remove_placeholder/#) | Anger att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållaregenskaperna till en specificerad. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/zoomobject/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudsidan som den aktuella formen ärvs från).<br/>            None returneras om den aktuella formen inte ärvs. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/zoomobject/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |

### Se även
* klass [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* klass [`ZoomObject`](/slides/python-net/sv/aspose.slides/zoomobject)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)