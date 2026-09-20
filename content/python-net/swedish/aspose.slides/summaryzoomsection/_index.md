---
title: SummaryZoomSection class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection klass

Representerar ett Summary Zoom Section-objekt i en Summary Zoom-ram.

**Arv:**[`SummaryZoomSection`](/slides/python-net/sv/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/sv/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/sv/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

Typen SummaryZoomSection exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/summaryzoomsection/is_text_holder/) | Determinerar om formen är TextHolder_PPT.<br/>            Endast läsning **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/summaryzoomsection/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Endast läsning [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/summaryzoomsection/custom_data/) | Returnerar formens anpassade data.<br/>            Endast läsning [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/summaryzoomsection/raw_frame/) | Returnerar eller anger de råa formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/summaryzoomsection/frame/) | Returnerar eller anger formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/summaryzoomsection/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Observera: kan returnera None för vissa typer av former som saknar linjeegenskaper.<br/>            Endast läsning [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/summaryzoomsection/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form.<br/>            Observera: kan returnera None för vissa typer av former som saknar 3D-egenskaper.<br/>            Endast läsning [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/summaryzoomsection/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en form.<br/>            Observera: kan returnera None för vissa typer av former som saknar effektegenskaper.<br/>            Endast läsning [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/summaryzoomsection/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form.<br/>            Observera: kan returnera None för vissa typer av former som saknar fyllningsegenskaper.<br/>            Endast läsning [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/summaryzoomsection/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för musöver.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/summaryzoomsection/hyperlink_manager/) | Returnerar hyperlänkshanteraren.<br/>            Endast läsning [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/summaryzoomsection/hidden/) | Bestämmer om formen är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/summaryzoomsection/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Endast läsning **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/summaryzoomsection/connection_site_count/) | Returnerar antalet anslutningsställen på formen.<br/>            Endast läsning **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/summaryzoomsection/rotation/) | Returnerar eller anger antalet grader som den specificerade formen roterar kring<br/>            z-axeln. Ett positivt värde indikerar medursrotation; ett negativt värde<br/>            indikerar motursrotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/summaryzoomsection/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/summaryzoomsection/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/summaryzoomsection/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/summaryzoomsection/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/summaryzoomsection/black_white_mode/) | Egenskapen anger hur en form renderas i svart-vit visningsläge..<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/summaryzoomsection/unique_id/) | Returnerar en intern, presentationsavgränsad identifierare avsedd för bruk av tillägg eller annan kod.<br/>            Eftersom detta värde kan omplaceras av användaren eller programmässigt, får det inte behandlas<br/>            som en bestående unik nyckel.<br/>            Endast läsning **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/summaryzoomsection/office_interop_shape_id/) | Returnerar en bild-avgränsad unik identifierare som förblir konstant under formens livstid och<br/>            låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till formen från var som helst i dokumentet.<br/>            Endast läsning **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/summaryzoomsection/alternative_text/) | Returnerar eller anger alternativ text som är kopplad till en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/summaryzoomsection/alternative_text_title/) | Returnerar eller anger titeln för alternativ text som är kopplad till en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/summaryzoomsection/name/) | Returnerar eller anger namnet på en form.<br/>            Får inte vara None. Använd tom sträng vid behov.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/summaryzoomsection/is_decorative/) | Hämtar eller anger alternativet 'Mark as decorative'<br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/summaryzoomsection/shape_lock/) | Returnerar formens lås.<br/>            Endast läsning [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/summaryzoomsection/is_grouped/) | Bestämmer om formen är grupperad.<br/>            Endast läsning **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/summaryzoomsection/parent_group/) | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras None.<br/>            Endast läsning [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/summaryzoomsection/slide/) | Returnerar föräldrabilden för en form.<br/>            Endast läsning [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/summaryzoomsection/presentation/) | Returnerar föräldrapresentationen för en bild.<br/>            Endast läsning [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/sv/aspose.slides/summaryzoomsection/graphical_object_lock/) | Returnerar formens lås.<br/>            Endast läsning [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/sv/aspose.slides/summaryzoomsection/image_type/) | Hämtar eller anger bildtypen för ett zoom-objekt.<br/>            Läs/skriv [`ZoomImageType`](/slides/python-net/sv/aspose.slides/zoomimagetype).<br/>            Standardvärde: Preview |
| [`return_to_parent`](/slides/python-net/sv/aspose.slides/summaryzoomsection/return_to_parent/) | Hämtar eller anger navigeringsbeteendet i bildspelsläge.<br/>            Läs/skriv **bool**.<br/>            Standardvärde: false |
| [`show_background`](/slides/python-net/sv/aspose.slides/summaryzoomsection/show_background/) | Hämtar eller anger värdet som specificerar huruvida Zoom kommer att använda bakgrunden för destinationsbilden.<br/>            Läs/skriv **bool**.<br/>            Standardvärde: true |
| [`zoom_image`](/slides/python-net/sv/aspose.slides/summaryzoomsection/zoom_image/) | Hämtar eller anger bild för zoom-objektet.<br/>            Läs/skriv [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/sv/aspose.slides/summaryzoomsection/transition_duration/) | Hämtar eller anger varaktigheten för övergången mellan Zoom och bild.<br/>            Läs/skriv **float**.<br/>            Standardvärde: 1.0f |
| [`target_section`](/slides/python-net/sv/aspose.slides/summaryzoomsection/target_section/) | Hämtar eller anger sektion-objektet som Section Zoom-objektet länkar till.<br/>            Läs/skriv [`ISection`](/slides/python-net/sv/aspose.slides/isection). |
| [`title`](/slides/python-net/sv/aspose.slides/summaryzoomsection/title/) | Returnerar texttiteln för Summary Zoom Section-objektet. |
| [`description`](/slides/python-net/sv/aspose.slides/summaryzoomsection/description/) | Returnerar textbeskrivningen för Summary Zoom Section-objektet. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/summaryzoomsection/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape-typ för formens miniatyrbounds används som standard. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/summaryzoomsection/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase) | Sparar innehållet i Shape som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i Shape som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/summaryzoomsection/remove_placeholder/#) | Definierar att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och anger platshållaregenskaper till en specificerad. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/summaryzoomsection/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudinnehållsbilden som den aktuella formen är ärvd från).<br/>            En None returneras om den aktuella formen inte är ärvd. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/summaryzoomsection/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |

### Se även
* klass [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject)
* klass [`SectionZoomFrame`](/slides/python-net/sv/aspose.slides/sectionzoomframe)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* klass [`SummaryZoomSection`](/slides/python-net/sv/aspose.slides/summaryzoomsection)
* klass [`ZoomObject`](/slides/python-net/sv/aspose.slides/zoomobject)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)