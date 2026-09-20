---
title: OleObjectFrame class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/oleobjectframe/
---
## OleObjectFrame klass

Representerar ett OLE-objekt på en bild.

**Arv:**[`OleObjectFrame`](/slides/python-net/sv/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

OleObjectFrame-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/oleobjectframe/is_text_holder/) | Bestämmer om formen är TextHolder_PPT.<br/>            Skrivskyddad **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/oleobjectframe/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Skrivskyddad [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/oleobjectframe/custom_data/) | Returnerar formens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/oleobjectframe/raw_frame/) | Returnerar eller anger de råa formramsegenskaperna.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/oleobjectframe/frame/) | Returnerar eller anger formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/oleobjectframe/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har linjeegenskaper.<br/>            Skrivskyddad [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/oleobjectframe/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3d-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har 3d-egenskaper.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/oleobjectframe/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixel-effekter som tillämpas på en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har effektsegenskaper.<br/>            Skrivskyddad [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/oleobjectframe/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har fyllningsegenskaper.<br/>            Skrivskyddad [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/oleobjectframe/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för mus över.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/oleobjectframe/hyperlink_manager/) | Returnerar hyperlänksadministratören.<br/>            Skrivskyddad [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/oleobjectframe/hidden/) | Bestämmer om formen är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/oleobjectframe/z_order_position/) | Returnerar formens position i z-ordningen,<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Skrivskyddad **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/oleobjectframe/connection_site_count/) | Returnerar antalet anslutningsplatser på formen.<br/>            Skrivskyddad **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/oleobjectframe/rotation/) | Returnerar eller anger antalet grader som den angivna formen roteras kring<br/>            z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde<br/>            indikerar moturs rotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/oleobjectframe/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/oleobjectframe/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/oleobjectframe/width/) | Hämtar eller anger formens bredd, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/oleobjectframe/height/) | Hämtar eller anger formens höjd, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/oleobjectframe/black_white_mode/) | Egenskapen anger hur en form ska renderas i svartvit visningsläge.<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/oleobjectframe/unique_id/) | Returnerar en intern, presentationsspecifik identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan tilldelas om av användaren eller programmässigt, får det inte behandlas som en bestående unik nyckel.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/oleobjectframe/office_interop_shape_id/) | Returnerar en bildspecifik unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen var som helst i dokumentet.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/oleobjectframe/alternative_text/) | Returnerar eller anger alternativ text för en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/oleobjectframe/alternative_text_title/) | Returnerar eller anger titeln för alternativ text för en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/oleobjectframe/name/) | Returnerar eller anger namnet på en form.<br/>            Måste inte vara None. Använd tom sträng om så behövs.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/oleobjectframe/is_decorative/) | Hämtar eller anger alternativet 'Markera som dekorativ'.<br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/oleobjectframe/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/oleobjectframe/is_grouped/) | Bestämmer om formen är grupperad.<br/>            Skrivskyddad **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/oleobjectframe/parent_group/) | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras None.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/oleobjectframe/slide/) | Returnerar formens föräldra-bild.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/oleobjectframe/presentation/) | Returnerar bildspelets förälder (presentationen) för en bild.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/sv/aspose.slides/oleobjectframe/graphical_object_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/sv/aspose.slides/oleobjectframe/substitute_picture_format/) | Returnerar OleObject-bildfyllningsegenskapsobjektet.<br/>            Skrivskyddad [`IPictureFillFormat`](/slides/python-net/sv/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/sv/aspose.slides/oleobjectframe/substitute_picture_title/) | Returnerar eller anger titeln för OleObject-ikon.<br/>            Läs/skriv **str**. |
| [`object_name`](/slides/python-net/sv/aspose.slides/oleobjectframe/object_name/) | Returnerar eller anger namnet på ett objekt.<br/>            Läs/skriv **str**. |
| [`object_prog_id`](/slides/python-net/sv/aspose.slides/oleobjectframe/object_prog_id/) | Returnerar ProgID för ett objekt.<br/>            Skrivskyddad **str**. |
| [`link_file_name`](/slides/python-net/sv/aspose.slides/oleobjectframe/link_file_name/) | Returnerar den fullständiga sökvägen till en länkad fil. Kort filnamn används.<br/>            Skrivskyddad **str**. |
| [`link_path_long`](/slides/python-net/sv/aspose.slides/oleobjectframe/link_path_long/) | Returnerar den fullständiga sökvägen till en länkad fil. Långt filnamn används.<br/>            Läs/skriv **str**. |
| [`link_path_relative`](/slides/python-net/sv/aspose.slides/oleobjectframe/link_path_relative/) | Returnerar den relativa sökvägen till en länkad fil om den finns, annars returneras en tom sträng.<br/>            Skrivskyddad **str**. |
| [`embedded_file_label`](/slides/python-net/sv/aspose.slides/oleobjectframe/embedded_file_label/) | Returnerar filnamnet för inbäddat OLE-objekt |
| [`embedded_file_name`](/slides/python-net/sv/aspose.slides/oleobjectframe/embedded_file_name/) | Returnerar sökvägen för inbäddat OLE-objekt |
| [`embedded_data`](/slides/python-net/sv/aspose.slides/oleobjectframe/embedded_data/) | Hämtar eller anger information om OLE-inbäddad data.<br/>            Läs/skriv [`IOleEmbeddedDataInfo`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/sv/aspose.slides/oleobjectframe/is_object_icon/) | Bestämmer om ett objekt visas som ikon.<br/>            Läs/skriv **bool**. |
| [`is_object_link`](/slides/python-net/sv/aspose.slides/oleobjectframe/is_object_link/) | Bestämmer om ett objekt är länkat till en extern fil.<br/>            Skrivskyddad **bool**. |
| [`update_automatic`](/slides/python-net/sv/aspose.slides/oleobjectframe/update_automatic/) | Bestämmer om det länkade inbäddade objektet automatiskt uppdateras när presentationen öppnas eller skrivs ut.<br/>            Läs/skriv **bool**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/oleobjectframe/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape formens miniatyrbildsgränstyp används som standard. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Sparar innehållet i formen som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i formen som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/oleobjectframe/remove_placeholder/#) | Definierar att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om det inte finns någon och sätter platshållaregenskaper till en specificerad. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/oleobjectframe/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudsidan som den aktuella formen är ärvd från).<br/>            En None returneras om den aktuella formen inte är ärvd. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/oleobjectframe/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/sv/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Sätter information om OLE-inbäddad data.<br/>            <br/>            Denna metod ändrar objektets egenskaper för att återspegla den nya datan och sätter IsObjectLink-flaggan till false, vilket indikerar att OLE-objektet är inbäddat. |

### Se även
* klass [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject)
* klass [`OleObjectFrame`](/slides/python-net/sv/aspose.slides/oleobjectframe)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)