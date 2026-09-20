---
title: InkActions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.ink/inkactions/
---
## InkActions klass

Represents the root of ink actions.

**Inheritance:**[`InkActions`](/slides/python-net/sv/aspose.slides.ink/inkactions) → [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

The InkActions type exposes the following members:

## Egenskaper

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides.ink/inkactions/is_text_holder/) | Bestämmer om formen är TextHolder_PPT.<br/>            Endast läsning **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides.ink/inkactions/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen saknar platshållare.<br/>            Endast läsning [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides.ink/inkactions/custom_data/) | Returnerar formens anpassade data.<br/>            Endast läsning [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides.ink/inkactions/raw_frame/) | Returnerar eller anger de råa egenskaperna för formens ram.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides.ink/inkactions/frame/) | Returnerar eller anger ramens egenskaper för formen.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides.ink/inkactions/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som saknar linjeegenskaper.<br/>            Endast läsning [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides.ink/inkactions/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3d-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som saknar 3d-egenskaper.<br/>            Endast läsning [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides.ink/inkactions/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixel-effekter som tillämpas på en form.<br/>            Obs: kan returnera None för vissa typer av former som saknar effekt-egenskaper.<br/>            Endas läsning [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides.ink/inkactions/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som saknar fyllningsegenskaper.<br/>            Endast läsning [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides.ink/inkactions/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides.ink/inkactions/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för musöver.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides.ink/inkactions/hyperlink_manager/) | Returnerar hyperlänkshanteraren.<br/>            Endast läsning [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides.ink/inkactions/hidden/) | Bestämmer om formen är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides.ink/inkactions/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Endast läsning **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides.ink/inkactions/connection_site_count/) | Returnerar antalet anslutningspunkter på formen.<br/>            Endast läsning **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides.ink/inkactions/rotation/) | Returnerar eller anger antalet grader som den angivna formen roteras kring<br/>            z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde<br/>            indikerar moturs rotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides.ink/inkactions/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides.ink/inkactions/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides.ink/inkactions/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides.ink/inkactions/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides.ink/inkactions/black_white_mode/) | Egenskapen anger hur en form kommer att renderas i svartvitt läge.<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides.ink/inkactions/unique_id/) | Returnerar en intern, presentationsavgränsad identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omassigneras av användaren eller programmässigt, får det inte behandlas<br/>            som en bestående unik nyckel.<br/>            Endast läsning **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides.ink/inkactions/office_interop_shape_id/) | Returnerar en bildavgränsad unik identifierare som förblir konstant under formens livstid och<br/>            låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från var som helst i dokumentet.<br/>            Endast läsning **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides.ink/inkactions/alternative_text/) | Returnerar eller anger alternativ text som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides.ink/inkactions/alternative_text_title/) | Returnerar eller anger titeln för den alternativa texten som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides.ink/inkactions/name/) | Returnerar eller anger namnet på en form.<br/>            Måste vara icke-None. Använd en tom sträng vid behov.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides.ink/inkactions/is_decorative/) | Hämtar eller anger alternativet 'Mark as decorative'<br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides.ink/inkactions/shape_lock/) | Returnerar formens lås.<br/>            Endast läsning [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides.ink/inkactions/is_grouped/) | Bestämmer om formen är grupperad.<br/>            Endast läsning **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides.ink/inkactions/parent_group/) | Returnerar överordnat GroupShape-objekt om formen är grupperad. Annars returneras None.<br/>            Endast läsning [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides.ink/inkactions/slide/) | Returnerar den överordnade bilden för en form.<br/>            Endast läsning [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides.ink/inkactions/presentation/) | Returnerar den överordnade presentationen för en bild.<br/>            Endast läsning [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/sv/aspose.slides.ink/inkactions/graphical_object_lock/) | Returnerar formens lås.<br/>            Endast läsning [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |

## Metoder

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides.ink/inkactions/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape används som standard för miniatyrbildens gränstyp. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides.ink/inkactions/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase) | Sparar innehållet i Shape som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i Shape som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides.ink/inkactions/remove_placeholder/#) | Definierar att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides.ink/inkactions/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållaregenskaperna till en specificerad. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides.ink/inkactions/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen ärvs från).<br/>            None returneras om den aktuella formen inte ärvs. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides.ink/inkactions/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |

### Se också
* klass [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject)
* klass [`InkActions`](/slides/python-net/sv/aspose.slides.ink/inkactions)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* modul [`aspose.slides.ink`](/slides/python-net/sv/aspose.slides.ink)
* bibliotek [`Aspose.Slides`](/slides/python-net)