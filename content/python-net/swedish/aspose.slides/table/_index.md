---
title: Table class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/table/
---
## Tabellklass

Representerar en tabell på en bild.

**Inheritance:**[`Table`](/slides/python-net/sv/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

Typen Table exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/table/is_text_holder/) | Bestämmer om formen är TextHolder_PPT.<br/>            Endast läsning **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/table/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Endast läsning [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/table/custom_data/) | Returnerar formens anpassade data.<br/>            Endast läsning [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/table/raw_frame/) | Returnerar eller anger de råa formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/table/frame/) | Returnerar eller anger formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/table/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har linjeegenskaper.<br/>            Endast läsning [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/table/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3d-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har 3d-egenskaper.<br/>            Endast läsning [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/table/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixel-effekter som appliceras på en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har effekt-egenskaper.<br/>            Endas läsning [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/table/fill_format/) | Returnerar ett TableFormat.FillFormat-objekt som innehåller fyllningsformatering för Tabellen.<br/>            Endast läsning [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/table/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/table/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för musöver.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/table/hyperlink_manager/) | Returnerar hyperlänkshanteraren.<br/>            Endast läsning [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/table/hidden/) | Bestämmer om formen är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/table/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Endast läsning **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/table/connection_site_count/) | Returnerar antalet anslutningsställen på formen.<br/>            Endast läsning **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/table/rotation/) | Returnerar eller anger antalet grader den angivna formen roteras kring<br/>            z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde<br/>            indikerar moturs rotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/table/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/table/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/table/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/table/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/table/black_white_mode/) | Egendomen specificerar hur en form renderas i svartvit visningsläge..<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/table/unique_id/) | Returnerar en intern, presentation-avgränsad identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omfördelas av användaren eller programmässigt, får det inte behandlas<br/>            som en beständig unik nyckel.<br/>            Endast läsning **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/table/office_interop_shape_id/) | Returnerar en bild-avgränsad unik identifierare som förblir konstant under formens livstid och<br/>            låter PowerPoint eller interop-kod pålitligt referera till formen från var som helst i dokumentet.<br/>            Endast läsning **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/table/alternative_text/) | Returnerar eller anger alternativ text kopplad till en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/table/alternative_text_title/) | Returnerar eller anger rubriken för den alternativa texten kopplad till en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/table/name/) | Returnerar eller anger namnet på en form.<br/>            Måste vara icke-None. Använd tom sträng om så behövs.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/table/is_decorative/) | Hämtar eller anger 'Markera som dekoration' alternativet<br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/table/shape_lock/) | Returnerar formens lås.<br/>            Endast läsning [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/table/is_grouped/) | Bestämmer om formen är grupperad.<br/>            Endast läsning **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/table/parent_group/) | Returnerar föräldern GroupShape-objektet om formen är grupperad. Annars returneras None.<br/>            Endast läsning [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/table/slide/) | Returnerar förälderns bild för en form.<br/>            Endast läsning [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/table/presentation/) | Returnerar föräldrapresentationen för en bild.<br/>            Endast läsning [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/sv/aspose.slides/table/graphical_object_lock/) | Returnerar formens lås.<br/>            Endast läsning [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/sv/aspose.slides/table/rows/) | Returnerar samlingen av rader.<br/>            Endast läsning [`IRowCollection`](/slides/python-net/sv/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/sv/aspose.slides/table/columns/) | Returnerar samlingen av kolumner.<br/>            Endast läsning [`IColumnCollection`](/slides/python-net/sv/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/sv/aspose.slides/table/table_format/) | Returnerar TableFormat-objektet som innehåller formateringsegenskaper för denna tabell.<br/>            Endast läsning [`ITableFormat`](/slides/python-net/sv/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/sv/aspose.slides/table/style_preset/) | Hämtar eller anger inbyggd tabellstil.<br/>            Läs/skriv [`TableStylePreset`](/slides/python-net/sv/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/sv/aspose.slides/table/right_to_left/) | Bestämmer om tabellen har läsordning från höger till vänster.<br/>            Läs/skriv **bool**. |
| [`first_row`](/slides/python-net/sv/aspose.slides/table/first_row/) | Bestämmer om den första raden i en tabell ska ritas med särskild formatering.<br/>            Läs/skriv **bool**. |
| [`first_col`](/slides/python-net/sv/aspose.slides/table/first_col/) | Bestämmer om den första kolumnen i en tabell ska ritas med särskild formatering.<br/>            Läs/skriv **bool**. |
| [`last_row`](/slides/python-net/sv/aspose.slides/table/last_row/) | Bestämmer om den sista raden i en tabell ska ritas med särskild formatering.<br/>            Läs/skriv **bool**. |
| [`last_col`](/slides/python-net/sv/aspose.slides/table/last_col/) | Bestämmer om den sista kolumnen i en tabell ska ritas med särskild formatering.<br/>            Läs/skriv **bool**. |
| [`horizontal_banding`](/slides/python-net/sv/aspose.slides/table/horizontal_banding/) | Bestämmer om jämna rader ska ritas med annan formatering.<br/>            Läs/skriv **bool**. |
| [`vertical_banding`](/slides/python-net/sv/aspose.slides/table/vertical_banding/) | Bestämmer om jämna kolumner ska ritas med annan formatering.<br/>            Läs/skriv **bool**. |

## Metoder

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/table/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape används som standard för miniatyrbildens bounds-typ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/table/write_as_svg/#iorawiobase) | Sparar innehållet i Shape som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i Shape som SVG-fil. |
| [`set_text_format(self, source)`](/slides/python-net/sv/aspose.slides/table/set_text_format/#iportionformat) | Ställer in definierade formategenskaper för delområden på alla tabellcellers delområden. |
| [`set_text_format(self, source)`](/slides/python-net/sv/aspose.slides/table/set_text_format/#iparagraphformat) | Ställer in definierade styckeformategenskaper på alla tabellcellers stycken. |
| [`set_text_format(self, source)`](/slides/python-net/sv/aspose.slides/table/set_text_format/#itextframeformat) | Ställer in definierade textramformategenskaper på alla tabellcellers textramar. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/table/remove_placeholder/#) | Definierar att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/table/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållaregenskaper till en angiven. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/table/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller mästarbilden som den aktuella formen ärver från).<br/>            En None returneras om den aktuella formen inte ärvs. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/table/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/sv/aspose.slides/table/merge_cells/#icell-icell-bool) | Slår ihop intilliggande celler. |

### Se även
* klass [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* klass [`Table`](/slides/python-net/sv/aspose.slides/table)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)