---
title: LegacyDiagram class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/legacydiagram/
---
## LegacyDiagram-klass

Representerar ett föråldrat diagramobjekt.

**Inheritance:**[`LegacyDiagram`](/slides/python-net/sv/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

LegacyDiagram-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/legacydiagram/is_text_holder/) | Bestämmer om formen är TextHolder_PPT.<br/>            Endast läsning **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/legacydiagram/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Endast läsning [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/legacydiagram/custom_data/) | Returnerar formens anpassade data.<br/>            Endast läsning [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/legacydiagram/raw_frame/) | Returnerar eller anger råa formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/legacydiagram/frame/) | Returnerar eller anger formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/legacydiagram/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har linjeegenskaper.<br/>            Endast läsning [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/legacydiagram/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har 3D-egenskaper.<br/>            Endast läsning [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/legacydiagram/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixel-effekter som tillämpas på en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har effekt-egenskaper.<br/>            Endast läsning [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/legacydiagram/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har fyllningsegenskaper.<br/>            Endast läsning [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/legacydiagram/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/legacydiagram/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för musöver.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/legacydiagram/hyperlink_manager/) | Returnerar hyperlänkhanteraren.<br/>            Endast läsning [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/legacydiagram/hidden/) | Bestämmer om formen är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/legacydiagram/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Endast läsning **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/legacydiagram/connection_site_count/) | Returnerar antalet anslutningsställen på formen.<br/>            Endast läsning **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/legacydiagram/rotation/) | Returnerar eller anger antalet grader som den angivna formen är roterad runt z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/legacydiagram/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/legacydiagram/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/legacydiagram/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/legacydiagram/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/legacydiagram/black_white_mode/) | Egendom specificerar hur en form renderas i svartvita visningsläget..<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/legacydiagram/unique_id/) | Returnerar en intern, presentation-omfattande identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omassigneras av användaren eller programmässigt får det inte behandlas som en bestående unik nyckel.<br/>            Endast läsning **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/legacydiagram/office_interop_shape_id/) | Returnerar en bildomfattande unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från vilken plats i dokumentet som helst.<br/>            Endast läsning **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/legacydiagram/alternative_text/) | Returnerar eller anger alternativ text som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/legacydiagram/alternative_text_title/) | Returnerar eller anger titeln för den alternativa texten som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/legacydiagram/name/) | Returnerar eller anger namnet på en form.<br/>            Måste vara icke-None. Använd tom sträng om det behövs.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/legacydiagram/is_decorative/) | Hämtar eller anger alternativet 'Mark as decorative'<br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/legacydiagram/shape_lock/) | Returnerar formens lås.<br/>            Endast läsning [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/legacydiagram/is_grouped/) | Bestämmer om formen är grupperad.<br/>            Endast läsning **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/legacydiagram/parent_group/) | Returnerar parent GroupShape-objektet om formen är grupperad. Annars returneras None.<br/>            Endast läsning [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/legacydiagram/slide/) | Returnerar den överordnade bilden för en form.<br/>            Endast läsning [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/legacydiagram/presentation/) | Returnerar den överordnade presentationen för en bild.<br/>            Endast läsning [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/sv/aspose.slides/legacydiagram/graphical_object_lock/) | Returnerar formens lås.<br/>            Endast läsning [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/legacydiagram/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | Sparar Shape:s innehåll som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar Shape:s innehåll som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/legacydiagram/remove_placeholder/#) | Anger att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en specificerad. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/legacydiagram/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller mastern som den aktuella formen ärvs från).<br/>            En None returneras om den aktuella formen inte ärvs. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/legacydiagram/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |
| [`convert_to_smart_art(self)`](/slides/python-net/sv/aspose.slides/legacydiagram/convert_to_smart_art/#) | Omvandlar föråldrat diagram till redigerbart SmartArt-objekt. <br/>            Skapat SmartArt-objekt läggs till i den överordnade gruppformen på samma position. |
| [`convert_to_group_shape(self)`](/slides/python-net/sv/aspose.slides/legacydiagram/convert_to_group_shape/#) | Omvandlar föråldrat diagram till redigerbar gruppform. <br/>            Skapat GroupShape-objekt läggs till i den överordnade gruppformen på samma position. |

### Se även
* klass [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject)
* klass [`LegacyDiagram`](/slides/python-net/sv/aspose.slides/legacydiagram)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)