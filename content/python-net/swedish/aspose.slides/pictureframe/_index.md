---
title: PictureFrame class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/pictureframe/
---
## PictureFrame klass

Representerar en ram med en bild inuti.

**Arv:**[`PictureFrame`](/slides/python-net/sv/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/sv/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

PictureFrame-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/pictureframe/is_text_holder/) | Avgör om formen är TextHolder_PPT.<br/>            Skrivskyddad **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/pictureframe/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Skrivskyddad [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/pictureframe/custom_data/) | Returnerar formens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/pictureframe/raw_frame/) | Returnerar eller anger de råa egenskaperna för formens ram.<br/>            Skriv/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/pictureframe/frame/) | Returnerar eller anger egenskaperna för formens ram.<br/>            Skriv/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/pictureframe/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har linjeegenskaper.<br/>            Skrivskyddad [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/pictureframe/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har 3D-egenskaper.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/pictureframe/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har effekt-egenskaper.<br/>            Skrivskyddad [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/pictureframe/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har fyllningsegenskaper.<br/>            Skrivskyddad [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/pictureframe/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för musklick.<br/>            Skriv/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/pictureframe/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för mus-över.<br/>            Skriv/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/pictureframe/hyperlink_manager/) | Returnerar hyperlinkhanteraren.<br/>            Skrivskyddad [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/pictureframe/hidden/) | Avgör om formen är dold.<br/>            Skriv/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/pictureframe/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Skrivskyddad **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/pictureframe/connection_site_count/) | Returnerar antalet anslutningsställen på formen.<br/>            Skrivskyddad **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/pictureframe/rotation/) | Returnerar eller anger antalet grader som den specificerade formen roteras kring<br/>            z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde<br/>            indikerar moturs rotation.<br/>            Skriv/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/pictureframe/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Skriv/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/pictureframe/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Skriv/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/pictureframe/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Skriv/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/pictureframe/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Skriv/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/pictureframe/black_white_mode/) | Egendomen specificerar hur en form renderas i svartvit displayläge.<br/>            Skriv/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/pictureframe/unique_id/) | Returnerar en intern, presentationsomfattande identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omassigneras av användaren eller programatiskt, får det inte behandlas<br/>            som en bestående unik nyckel.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/pictureframe/office_interop_shape_id/) | Returnerar en bildspelsomfattande unik identifierare som förblir konstant under formens livstid och<br/>            låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen varifrån i dokumentet.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/pictureframe/alternative_text/) | Returnerar eller anger alternativ text som är associerad med en form.<br/>            Skriv/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/pictureframe/alternative_text_title/) | Returnerar eller anger titeln för alternativ text som är associerad med en form.<br/>            Skriv/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/pictureframe/name/) | Returnerar eller anger namnet på en form.<br/>            Måste vara annat än None. Använd tom sträng om så behövs.<br/>            Skriv/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/pictureframe/is_decorative/) | Hämtar eller anger alternativet 'Mark as decorative'<br/>            Skriv/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/pictureframe/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IPictureFrameLock`](/slides/python-net/sv/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/pictureframe/is_grouped/) | Avgör om formen är grupperad.<br/>            Skrivskyddad **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/pictureframe/parent_group/) | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras None.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/pictureframe/slide/) | Returnerar den föräldra-bildspels-objektet för en form.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/pictureframe/presentation/) | Returnerar den föräldra-presentationen för ett bildspel.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/sv/aspose.slides/pictureframe/shape_style/) | Returnerar formens stilobjekt.<br/>            Skrivskyddad [`IShapeStyle`](/slides/python-net/sv/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/sv/aspose.slides/pictureframe/shape_type/) | Returnerar eller anger AutoShape-typen för en PictureFrame.<br/>            Alla objekt i uppsättningen [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) är tillåtna, förutom alla varianter av linjer:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Skriv/skriv [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/sv/aspose.slides/pictureframe/adjustments/) | Returnerar en samling av formens justeringsvärden.<br/>            Skrivskyddad [`IAdjustValueCollection`](/slides/python-net/sv/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/sv/aspose.slides/pictureframe/picture_frame_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IPictureFrameLock`](/slides/python-net/sv/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/sv/aspose.slides/pictureframe/picture_format/) | Returnerar PictureFillFormat-objektet för en bildram.<br/>            Skrivskyddad [`IPictureFillFormat`](/slides/python-net/sv/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/sv/aspose.slides/pictureframe/relative_scale_height/) | Returnerar eller anger skalan för höjden (i förhållande till originalbildens storlek) på bildramen. Värde 1.0 motsvarar 100 %.<br/>            Skriv/skriv **float**. |
| [`relative_scale_width`](/slides/python-net/sv/aspose.slides/pictureframe/relative_scale_width/) | Returnerar eller anger skalan för bredden (i förhållande till originalbildens storlek) på bildramen. Värde 1.0 motsvarar 100 %.<br/>            Skriv/skriv **float**. |
| [`is_cameo`](/slides/python-net/sv/aspose.slides/pictureframe/is_cameo/) | Avgör om PictureFrame är ett Cameo-objekt eller inte.<br/>            Skrivskyddad **bool**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/pictureframe/get_image/#) | Returnerar shape-miniatyrbild.<br/>            ShapeThumbnailBounds.Shape används som standard för miniatyrbildsgränstyp. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Returnerar shape-miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Sparar innehållet i Shape som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i Shape som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/pictureframe/remove_placeholder/#) | Anger att den här formen inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och anger platshållarens egenskaper till en specificerad. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/pictureframe/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbildspels-sliden som den aktuella formen ärvs från).<br/>            En None returneras om den aktuella formen inte är ärvd. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/pictureframe/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |
| [`get_geometry_paths(self)`](/slides/python-net/sv/aspose.slides/pictureframe/get_geometry_paths/#) | Returnerar en kopia av geometriformens bana. Koordinaterna är relativa till formens övre vänstra hörn. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/sv/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Uppdaterar formens geometri från [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)-objektet. Koordinaterna måste vara relativa till formens övre vänstra hörn.<br/>            Ändrar formens typ ([`GeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/geometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/sv/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Uppdaterar formens geometri från en array av [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath). Koordinaterna måste vara relativa till formens övre vänstra hörn.<br/>            Ändrar formens typ ([`GeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/geometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/sv/aspose.slides/pictureframe/create_shape_elements/#) | Skapar och returnerar en array av formens element. |

### Se även
* klass [`GeometryShape`](/slides/python-net/sv/aspose.slides/geometryshape)
* klass [`PictureFrame`](/slides/python-net/sv/aspose.slides/pictureframe)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)