---
title: GraphicalObject class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/graphicalobject/
---
## GraphicalObject klass

Representerar abstrakt grafiskt objekt.

**Arv:**[`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

Typen GraphicalObject exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/graphicalobject/is_text_holder/) | Avgör om formen är TextHolder_PPT.<br/>            Skrivskyddad **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/graphicalobject/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Skrivskyddad [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/graphicalobject/custom_data/) | Returnerar formens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/graphicalobject/raw_frame/) | Returnerar eller anger den råa formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/graphicalobject/frame/) | Returnerar eller anger formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/graphicalobject/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har linjeegenskaper.<br/>            Skrivskyddad [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/graphicalobject/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3d-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har 3d-egenskaper.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/graphicalobject/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixeleffekter som appliceras på en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har effekt-egenskaper.<br/>            Skrivskyddad [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/graphicalobject/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har fyllningsegenskaper.<br/>            Skrivskyddad [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/graphicalobject/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/graphicalobject/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för musöver.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/graphicalobject/hyperlink_manager/) | Returnerar hyperlänkshanteraren.<br/>            Skrivskyddad [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/graphicalobject/hidden/) | Avgör om formen är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/graphicalobject/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Skrivskyddad **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/graphicalobject/connection_site_count/) | Returnerar antalet anslutningsställen på formen.<br/>            Skrivskyddad **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/graphicalobject/rotation/) | Returnerar eller anger antalet grader som den angivna formen är roterad kring<br/>            z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde<br/>            indikerar moturs rotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/graphicalobject/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/graphicalobject/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/graphicalobject/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/graphicalobject/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/graphicalobject/black_white_mode/) | Egenskapen anger hur en form kommer att renderas i svartvit visningsläge..<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/graphicalobject/unique_id/) | Returnerar en intern, presentation-avgränsad identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omfördelas av användaren eller programmässigt, får det inte behandlas<br/>            som en beständig unik nyckel.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/graphicalobject/office_interop_shape_id/) | Returnerar en bild-avgränsad unik identifierare som förblir konstant under formens livstid och<br/>            låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till formen från vilken del av dokumentet som helst.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/graphicalobject/alternative_text/) | Returnerar eller anger alternativ text som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/graphicalobject/alternative_text_title/) | Returnerar eller anger titeln för alternativ text som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/graphicalobject/name/) | Returnerar eller anger namnet på en form.<br/>            Måste vara ej None. Använd tom strängvärde om nötig.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/graphicalobject/is_decorative/) | Hämtar eller anger alternativet 'Mark as decorative'<br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/graphicalobject/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/graphicalobject/is_grouped/) | Avgör om formen är grupperad.<br/>            Skrivskyddad **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/graphicalobject/parent_group/) | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Returnerar annars None.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/graphicalobject/slide/) | Returnerar bildens förälder till en form.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/graphicalobject/presentation/) | Returnerar presentationens förälder till en bild.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/sv/aspose.slides/graphicalobject/graphical_object_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/graphicalobject/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape miniatyrbildens gränstyper används som standard. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | Sparar innehållet i Shape som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i Shape som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/graphicalobject/remove_placeholder/#) | Definierar att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en specificerad. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/graphicalobject/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudd bilden som den nuvarande formen ärvs från).<br/>            En None returneras om den nuvarande formen inte ärvs. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/graphicalobject/get_visual_bounds/#) | Hämtar den visuella gränsen för formen beräknad från dess renderade innehåll. |

### Se även
* klass [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)