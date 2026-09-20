---
title: SectionZoomFrame class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame klass

Representerar ett Section Zoom-objekt i en bild.

**Arv:**[`SectionZoomFrame`](/slides/python-net/sv/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/sv/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

SectionZoomFrame-typen exponeras följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/sectionzoomframe/is_text_holder/) | Avgör om formen är TextHolder_PPT.<br/>            Skrivskyddad **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/sectionzoomframe/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Skrivskyddad [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/sectionzoomframe/custom_data/) | Returnerar formens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/sectionzoomframe/raw_frame/) | Returnerar eller anger de råa formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/sectionzoomframe/frame/) | Returnerar eller anger formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/sectionzoomframe/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har linjeegenskaper.<br/>            Skrivskyddad [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/sectionzoomframe/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har 3D-egenskaper.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/sectionzoomframe/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixel-effekter som tillämpas på en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har effektegenskaper.<br/>            Skrivskyddad [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/sectionzoomframe/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har fyllningsegenskaper.<br/>            Skrivskyddad [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/sectionzoomframe/hyperlink_click/) | Returnerar eller anger hyperlänken som definieras för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/sectionzoomframe/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definieras för muspekning.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/sectionzoomframe/hyperlink_manager/) | Returnerar hyperlänkshanteraren.<br/>            Skrivskyddad [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/sectionzoomframe/hidden/) | Avgör om formen är gömd.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/sectionzoomframe/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Skrivskyddad **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/sectionzoomframe/connection_site_count/) | Returnerar antalet anslutningspunkter på formen.<br/>            Skrivskyddad **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/sectionzoomframe/rotation/) | Returnerar eller anger antalet grader som den angivna formen roteras kring<br/>            z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde<br/>            indikerar moturs rotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/sectionzoomframe/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/sectionzoomframe/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/sectionzoomframe/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/sectionzoomframe/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/sectionzoomframe/black_white_mode/) | Egenskapen specificerar hur en form renderas i svart-vitt läge..<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/sectionzoomframe/unique_id/) | Returnerar en intern, presentations-avgränsad identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omassigneras av användaren eller programatiskt, får det inte behandlas<br/>            som en beständig unik nyckel.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/sectionzoomframe/office_interop_shape_id/) | Returnerar en slide-avgränsad unik identifierare som förblir konstant under formens livstid och<br/>            låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till formen från var som helst i dokumentet.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/sectionzoomframe/alternative_text/) | Returnerar eller anger alternativ text kopplad till en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/sectionzoomframe/alternative_text_title/) | Returnerar eller anger titeln för alternativ text kopplad till en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/sectionzoomframe/name/) | Returnerar eller anger namnet på en form.<br/>            Måste vara icke-None. Använd tom sträng om så behövs.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/sectionzoomframe/is_decorative/) | Hämtar eller anger alternativet 'Mark as decorative'<br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/sectionzoomframe/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/sectionzoomframe/is_grouped/) | Avgör om formen är grupperad.<br/>            Skrivskyddad **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/sectionzoomframe/parent_group/) | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras None.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/sectionzoomframe/slide/) | Returnerar föräldra-bilden för en form.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/sectionzoomframe/presentation/) | Returnerar föräldrapresentationen för en bild.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/sv/aspose.slides/sectionzoomframe/graphical_object_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/sv/aspose.slides/sectionzoomframe/image_type/) | Hämtar eller anger bildtypen för ett zoom-objekt.<br/>            Läs/skriv [`ZoomImageType`](/slides/python-net/sv/aspose.slides/zoomimagetype).<br/>            Standardvärde: Preview |
| [`return_to_parent`](/slides/python-net/sv/aspose.slides/sectionzoomframe/return_to_parent/) | Hämtar eller anger navigeringsbeteendet i bildspel.<br/>            Läs/skriv **bool**.<br/>            Standardvärde: false |
| [`show_background`](/slides/python-net/sv/aspose.slides/sectionzoomframe/show_background/) | Hämtar eller anger värdet som specificerar om Zoom kommer att använda bakgrunden på destinationsbilden.<br/>            Läs/skriv **bool**.<br/>            Standardvärde: true |
| [`zoom_image`](/slides/python-net/sv/aspose.slides/sectionzoomframe/zoom_image/) | Hämtar eller anger bild för zoom-objekt.<br/>            Läs/skriv [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/sv/aspose.slides/sectionzoomframe/transition_duration/) | Hämtar eller anger varaktigheten för övergången mellan Zoom och bild.<br/>            Läs/skriv **float**.<br/>            Standardvärde: 1.0f |
| [`target_section`](/slides/python-net/sv/aspose.slides/sectionzoomframe/target_section/) | Hämtar eller anger sektion-objektet som Section Zoom-objektet länkar till.<br/>            Läs/skriv [`ISection`](/slides/python-net/sv/aspose.slides/isection). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/sectionzoomframe/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape formens miniatyrgränser typ används som standard. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/sectionzoomframe/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase) | Sparar innehållet i Shape som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i Shape som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/sectionzoomframe/remove_placeholder/#) | Anger att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/sectionzoomframe/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en specificerad. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/sectionzoomframe/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen är ärvd från).<br/>            None returneras om den aktuella formen inte är ärvd. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/sectionzoomframe/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |

### Se även
* klass [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject)
* klass [`SectionZoomFrame`](/slides/python-net/sv/aspose.slides/sectionzoomframe)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* klass [`ZoomObject`](/slides/python-net/sv/aspose.slides/zoomobject)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)