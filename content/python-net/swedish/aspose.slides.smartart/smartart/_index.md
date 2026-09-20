---
title: SmartArt class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.smartart/smartart/
---
## SmartArt klass

Representerar ett SmartArt-diagram

**Arv:**[`SmartArt`](/slides/python-net/sv/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

SmartArt-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides.smartart/smartart/is_text_holder/) | Bestämmer om formen är TextHolder_PPT.<br/>            Skrivskyddad **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides.smartart/smartart/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Skrivskyddad [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides.smartart/smartart/custom_data/) | Returnerar formens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides.smartart/smartart/raw_frame/) | Returnerar eller anger de råa egenskaperna för formens ram.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides.smartart/smartart/frame/) | Returnerar eller anger egenskaperna för formens ram.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides.smartart/smartart/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformat egenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har linjeegenskaper.<br/>            Skrivskyddad [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides.smartart/smartart/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3d-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har 3d-egenskaper.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides.smartart/smartart/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixel-effekter som applicerats på en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har effekt-egenskaper.<br/>            Skrivskyddad [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides.smartart/smartart/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformat egenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har fyllningsegenskaper.<br/>            Skrivskyddad [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides.smartart/smartart/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för muspekning.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides.smartart/smartart/hyperlink_manager/) | Returnerar hyperlänkhanteraren.<br/>            Skrivskyddad [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides.smartart/smartart/hidden/) | Bestämmer om formen är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides.smartart/smartart/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Skrivskyddad **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides.smartart/smartart/connection_site_count/) | Returnerar antalet anslutningsställen på formen.<br/>            Skrivskyddad **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides.smartart/smartart/rotation/) | Returnerar eller anger antalet grader som den angivna formen roteras kring<br/>            z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde<br/>            indikerar moturs rotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides.smartart/smartart/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides.smartart/smartart/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides.smartart/smartart/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides.smartart/smartart/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides.smartart/smartart/black_white_mode/) | Egenskapen anger hur en form kommer att renderas i svart-vit visningsläge..<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides.smartart/smartart/unique_id/) | Returnerar en intern, presentationsavgränsad identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omtilldelas av användaren eller programmässigt, får det inte behandlas<br/>            som en beständig unik nyckel.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides.smartart/smartart/office_interop_shape_id/) | Returnerar en bild-avgränsad unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från var som helst i dokumentet.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides.smartart/smartart/alternative_text/) | Returnerar eller anger alternativ text som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides.smartart/smartart/alternative_text_title/) | Returnerar eller anger titeln för den alternativa texten som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides.smartart/smartart/name/) | Returnerar eller anger namnet på en form.<br/>            Måste vara icke-None. Använd en tom sträng om det behövs.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides.smartart/smartart/is_decorative/) | Hämtar eller anger alternativet 'Markera som dekorativ' <br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides.smartart/smartart/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides.smartart/smartart/is_grouped/) | Bestämmer om formen är grupperad.<br/>            Skrivskyddad **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides.smartart/smartart/parent_group/) | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras None.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides.smartart/smartart/slide/) | Returnerar föräldra-bilden för en form.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides.smartart/smartart/presentation/) | Returnerar föräldrapresentationen för en bild.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/sv/aspose.slides.smartart/smartart/graphical_object_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/sv/aspose.slides.smartart/smartart/all_nodes/) | Returnerar samlingar av alla noder i SmartArt-objektet.<br/>            Skrivskyddad [`ISmartArtNodeCollection`](/slides/python-net/sv/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/sv/aspose.slides.smartart/smartart/nodes/) | Returnerar samlingar av rot-noder i SmartArt-objektet.<br/>            Skrivskyddad [`ISmartArtNodeCollection`](/slides/python-net/sv/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/sv/aspose.slides.smartart/smartart/layout/) | Returnerar eller anger layouten för SmartArt-objektet.<br/>            Läs/skriv [`SmartArtLayoutType`](/slides/python-net/sv/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/sv/aspose.slides.smartart/smartart/quick_style/) | Returnerar eller anger snabbstil för SmartArt-objektet.<br/>            Läs/skriv [`SmartArtQuickStyleType`](/slides/python-net/sv/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/sv/aspose.slides.smartart/smartart/color_style/) | Returnerar eller anger färgstilen för SmartArt-objektet.<br/>            Läs/skriv [`SmartArtColorType`](/slides/python-net/sv/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/sv/aspose.slides.smartart/smartart/is_reversed/) | Returnera eller ange tillståndet för SmartArt-diagrammet avseende (vänster-till-höger) LTR eller (höger-till-vänster) RTL, om diagrammet stöder omvändning.<br/>            Läs/skriv **bool**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides.smartart/smartart/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type används som standard. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | Sparar innehållet i Shape som en SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i Shape som en SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides.smartart/smartart/remove_placeholder/#) | Definierar att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållaregenskaper till en specificerad. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides.smartart/smartart/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen ärvs från).<br/>            None returneras om den aktuella formen inte ärvs. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides.smartart/smartart/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |

### Se även
* klass [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* klass [`SmartArt`](/slides/python-net/sv/aspose.slides.smartart/smartart)
* modul [`aspose.slides.smartart`](/slides/python-net/sv/aspose.slides.smartart)
* bibliotek [`Aspose.Slides`](/slides/python-net)