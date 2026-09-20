---
title: VideoFrame class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/videoframe/
---
## VideoFrame klass

Representerar ett videoklipp på en bild.

**Arv:**[`VideoFrame`](/slides/python-net/sv/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/sv/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/sv/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

VideoFrame-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/videoframe/is_text_holder/) | Bestämmer om formen är TextHolder_PPT.<br/>            Skrivskyddad **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/videoframe/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Skrivskyddad [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/videoframe/custom_data/) | Returnerar formens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/videoframe/raw_frame/) | Hämtar eller anger de råa egenskaperna för formramen.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/videoframe/frame/) | Hämtar eller anger formramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/videoframe/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har linjeegenskaper.<br/>            Skrivskyddad [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/videoframe/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har 3D-egenskaper.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/videoframe/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixeleffekter som appliceras på en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har effektegränssnitt.<br/>            Skrivskyddad [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/videoframe/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformattingsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har fyllningsegenskaper.<br/>            Skrivskyddad [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/videoframe/hyperlink_click/) | Hämtar eller anger hyperlänken som definierats för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/videoframe/hyperlink_mouse_over/) | Hämtar eller anger hyperlänken som definierats för musöver.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/videoframe/hyperlink_manager/) | Returnerar hyperlänks-hanteraren.<br/>            Skrivskyddad [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/videoframe/hidden/) | Bestämmer om formen är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/videoframe/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Skrivskyddad **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/videoframe/connection_site_count/) | Returnerar antalet anslutningspunkter på formen.<br/>            Skrivskyddad **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/videoframe/rotation/) | Hämtar eller anger antal grader som den angivna formen roteras runt<br/>            z-axeln. Ett positivt värde indikerar medursrotation; ett negativt värde<br/>            indikerar motursrotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/videoframe/x/) | Hämtar eller anger x-koordinaten för formens övre-vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/videoframe/y/) | Hämtar eller anger y-koordinaten för formens övre-vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/videoframe/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/videoframe/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/videoframe/black_white_mode/) | Egendomen specificerar hur en form renderas i svart-vit visningsläge.<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/videoframe/unique_id/) | Returnerar en intern, presentations-scoped identifier avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan tilldelas om av användaren eller programmässigt, får det inte behandlas<br/>            som en bestående unik nyckel.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/videoframe/office_interop_shape_id/) | Returnerar en bild-scoped unik identifierare som förblir konstant under formens livstid och<br/>            låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till formen från var som helst i dokumentet.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/videoframe/alternative_text/) | Hämtar eller anger alternativ text för en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/videoframe/alternative_text_title/) | Hämtar eller anger titeln för alternativ text för en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/videoframe/name/) | Hämtar eller anger namnet på en form.<br/>            Måste vara icke-None. Använd tom sträng om nödvändigt.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/videoframe/is_decorative/) | Hämtar eller anger 'Mark as decorative'-alternativet<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/videoframe/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IPictureFrameLock`](/slides/python-net/sv/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/videoframe/is_grouped/) | Bestämmer om formen är grupperad.<br/>            Skrivskyddad **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/videoframe/parent_group/) | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras None.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/videoframe/slide/) | Returnerar föräldra-bilden för en form.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/videoframe/presentation/) | Returnerar föräldra-presentationen för en bild.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/sv/aspose.slides/videoframe/shape_style/) | Returnerar formens stil-objekt.<br/>            Skrivskyddad [`IShapeStyle`](/slides/python-net/sv/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/sv/aspose.slides/videoframe/shape_type/) | Hämtar eller anger AutoShape-typen för en PictureFrame.<br/>            Alla element i mängden [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) är tillåtna, förutom alla sorters linjer:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Läs/skriv [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/sv/aspose.slides/videoframe/adjustments/) | Returnerar en samling av formens justeringsvärden.<br/>            Skrivskyddad [`IAdjustValueCollection`](/slides/python-net/sv/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/sv/aspose.slides/videoframe/picture_frame_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IPictureFrameLock`](/slides/python-net/sv/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/sv/aspose.slides/videoframe/picture_format/) | Returnerar PictureFillFormat-objektet för en bildram.<br/>            Skrivskyddad [`IPictureFillFormat`](/slides/python-net/sv/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/sv/aspose.slides/videoframe/relative_scale_height/) | Hämtar eller anger skalan på höjden (relativt originalbildens storlek) för bildramen. Värde 1,0 motsvarar 100 %.<br/>            Läs/skriv **float**. |
| [`relative_scale_width`](/slides/python-net/sv/aspose.slides/videoframe/relative_scale_width/) | Hämtar eller anger skalan på bredden (relativt originalbildens storlek) för bildramen. Värde 1,0 motsvarar 100 %.<br/>            Läs/skriv **float**. |
| [`is_cameo`](/slides/python-net/sv/aspose.slides/videoframe/is_cameo/) | Bestämmer om PictureFrame är ett Cameo-objekt eller inte.<br/>            Skrivskyddad **bool**. |
| [`rewind_video`](/slides/python-net/sv/aspose.slides/videoframe/rewind_video/) | Bestämmer om en video automatiskt spolas tillbaka till början<br/>            så snart filmen har spelats färdigt.<br/>            Läs/skriv **bool**. |
| [`play_loop_mode`](/slides/python-net/sv/aspose.slides/videoframe/play_loop_mode/) | Bestämmer om en video loopas.<br/>            Läs/skriv **bool**. |
| [`hide_at_showing`](/slides/python-net/sv/aspose.slides/videoframe/hide_at_showing/) | Bestämmer om ett VideoFrame är dolt.<br/>            Läs/skriv **bool**. |
| [`volume`](/slides/python-net/sv/aspose.slides/videoframe/volume/) | Hämtar eller anger ljudvolymen.<br/>            Läs/skriv [`AudioVolumeMode`](/slides/python-net/sv/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/sv/aspose.slides/videoframe/play_mode/) | Hämtar eller anger videouppspelningsläget.<br/>            Läs/skriv [`VideoPlayModePreset`](/slides/python-net/sv/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/sv/aspose.slides/videoframe/full_screen_mode/) | Bestämmer om en video visas i helskärmsläge.<br/>            Läs/skriv **bool**. |
| [`link_path_long`](/slides/python-net/sv/aspose.slides/videoframe/link_path_long/) | Hämtar eller anger namnet på en videofil som är länkad till ett VideoFrame.<br/>            Läs/skriv **str**. |
| [`embedded_video`](/slides/python-net/sv/aspose.slides/videoframe/embedded_video/) | Hämtar eller anger inbäddat videoobjekt.<br/>            Läs/skriv [`IVideo`](/slides/python-net/sv/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/sv/aspose.slides/videoframe/trim_from_start/) | Beskär start [ms] |
| [`trim_from_end`](/slides/python-net/sv/aspose.slides/videoframe/trim_from_end/) | Beskär slut [ms] |
| [`caption_tracks`](/slides/python-net/sv/aspose.slides/videoframe/caption_tracks/) | Hämtar samlingen av stängda undertexter som är associerade med video-ramen.<br/>            Denna egenskap är skrivskyddad och returnerar ett [`ICaptionsCollection`](/slides/python-net/sv/aspose.slides/icaptionscollection) som innehåller alla undertextspår. |

## Metoder

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/videoframe/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyrbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Sparar innehållet i Shape som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i Shape som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/videoframe/remove_placeholder/#) | Definierar att denna forma inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en angiven. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/videoframe/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen är ärvd från).<br/>            Ett None returneras om den aktuella formen inte är ärvd. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/videoframe/get_visual_bounds/#) | Hämtar den visuella gränsen för formen beräknad från dess renderade innehåll. |
| [`get_geometry_paths(self)`](/slides/python-net/sv/aspose.slides/videoframe/get_geometry_paths/#) | Returnerar en kopia av banan för geometriformen. Koordinaterna är relativa till formens övre vänstra hörn. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/sv/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Uppdaterar formens geometri från [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)-objektet. Koordinaterna måste vara relativa till formens övre vänstra hörn.<br/>             Ändrar formens typ ([`GeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/geometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/sv/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Uppdaterar formens geometri från en array av [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath). Koordinaterna måste vara relativa till formens övre vänstra hörn.<br/>             Ändrar formens typ ([`GeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/geometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/sv/aspose.slides/videoframe/create_shape_elements/#) | Skapar och returnerar en array av formens element. |

### Se även
* klass [`GeometryShape`](/slides/python-net/sv/aspose.slides/geometryshape)
* klass [`PictureFrame`](/slides/python-net/sv/aspose.slides/pictureframe)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* klass [`VideoFrame`](/slides/python-net/sv/aspose.slides/videoframe)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)