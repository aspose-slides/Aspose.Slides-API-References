---
title: VideoFrame class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/videoframe/
---
## VideoFrame klass

Representerar ett videoklipp på en bild.

**Inheritance:**[`VideoFrame`](/slides/python-net/sv/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/sv/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/sv/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

VideoFrame-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/videoframe/is_text_holder/) | Avgör om formen är TextHolder_PPT.<br/>            Skrivskyddad **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/videoframe/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Skrivskyddad [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/videoframe/custom_data/) | Returnerar formens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/videoframe/raw_frame/) | Hämtar eller anger de råa egenskaperna för formens ram.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/videoframe/frame/) | Hämtar eller anger egenskaperna för formens ram.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/videoframe/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har linjeegenskaper.<br/>            Skrivskyddad [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/videoframe/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har 3D-egenskaper.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/videoframe/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixeleffekter som appliceras på en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har effektegenskaper.<br/>            Skrivskyddad [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/videoframe/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har fyllningsegenskaper.<br/>            Skrivskyddad [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/videoframe/hyperlink_click/) | Hämtar eller anger hyperlänken som definierats för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/videoframe/hyperlink_mouse_over/) | Hämtar eller anger hyperlänken som definierats för musöverläggning.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/videoframe/hyperlink_manager/) | Returnerar hyperlänkhantevern.<br/>            Skrivskyddad [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/videoframe/hidden/) | Avgör om formen är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/videoframe/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Skrivskyddad **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/videoframe/connection_site_count/) | Returnerar antalet anslutningsställen på formen.<br/>            Skrivskyddad **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/videoframe/rotation/) | Returnerar eller anger antalet grader som den angivna formen roteras kring<br/>            z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde<br/>            indikerar moturs rotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/videoframe/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/videoframe/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/videoframe/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/videoframe/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/videoframe/black_white_mode/) | Egenskapen specificerar hur en form renderas i svartvitt läge..<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/videoframe/unique_id/) | Returnerar en intern, presentationsavgränsad identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omassigneras av användaren eller programmässigt, får det inte behandlas<br/>            som en bestående unik nyckel.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/videoframe/office_interop_shape_id/) | Returnerar en bildavgränsad unik identifierare som förblir konstant under formens livstid och<br/>            låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till formen från vilken del av dokumentet som helst.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/videoframe/alternative_text/) | Returnerar eller anger alternativ text som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/videoframe/alternative_text_title/) | Returnerar eller anger titeln för den alternativa texten som är associerad med en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/videoframe/name/) | Returnerar eller anger namnet på en form.<br/>            Måste vara icke-None. Använd tom sträng vid behov.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/videoframe/is_decorative/) | Hämtar eller anger alternativet 'Mark as decorative'<br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/videoframe/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IPictureFrameLock`](/slides/python-net/sv/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/videoframe/is_grouped/) | Avgör om formen är grupperad.<br/>            Skrivskyddad **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/videoframe/parent_group/) | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras None.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/videoframe/slide/) | Returnerar föräldrabilden för en form.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/videoframe/presentation/) | Returnerar föräldrapresentationen för en bild.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/sv/aspose.slides/videoframe/shape_style/) | Returnerar formens stilobjekt.<br/>            Skrivskyddad [`IShapeStyle`](/slides/python-net/sv/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/sv/aspose.slides/videoframe/shape_type/) | Returnerar eller anger AutoShape-typen för en PictureFrame.<br/>            Alla element i mängden [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) är tillåtna, <br/>            förutom alla typer av linjer:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Läs/skriv [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/sv/aspose.slides/videoframe/adjustments/) | Returnerar en samling av formens justeringsvärden.<br/>            Skrivskyddad [`IAdjustValueCollection`](/slides/python-net/sv/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/sv/aspose.slides/videoframe/picture_frame_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IPictureFrameLock`](/slides/python-net/sv/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/sv/aspose.slides/videoframe/picture_format/) | Returnerar PictureFillFormat-objektet för en bildram.<br/>            Skrivskyddad [`IPictureFillFormat`](/slides/python-net/sv/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/sv/aspose.slides/videoframe/relative_scale_height/) | Returnerar eller anger skalan för höjden (i förhållande till originalbildens storlek) på bildramen. Värde 1.0 motsvarar 100%.<br/>            Läs/skriv **float**. |
| [`relative_scale_width`](/slides/python-net/sv/aspose.slides/videoframe/relative_scale_width/) | Returnerar eller anger skalan för bredden (i förhållande till originalbildens storlek) på bildramen. Värde 1.0 motsvarar 100%.<br/>            Läs/skriv **float**. |
| [`is_cameo`](/slides/python-net/sv/aspose.slides/videoframe/is_cameo/) | Avgör om PictureFrame är ett Cameo-objekt eller inte.<br/>            Skrivskyddad **bool**. |
| [`rewind_video`](/slides/python-net/sv/aspose.slides/videoframe/rewind_video/) | Avgör om en video automatiskt spolas tillbaka till början<br/>            så snart filmen har spelat klart.<br/>            Läs/skriv **bool**. |
| [`play_loop_mode`](/slides/python-net/sv/aspose.slides/videoframe/play_loop_mode/) | Avgör om en video loopas.<br/>            Läs/skriv **bool**. |
| [`hide_at_showing`](/slides/python-net/sv/aspose.slides/videoframe/hide_at_showing/) | Avgör om en VideoFrame är dold.<br/>            Läs/skriv **bool**. |
| [`volume`](/slides/python-net/sv/aspose.slides/videoframe/volume/) | Returnerar eller anger ljudvolymen.<br/>            Läs/skriv [`AudioVolumeMode`](/slides/python-net/sv/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/sv/aspose.slides/videoframe/volume_value/) | Returnerar eller anger exakt videovolym som en procentandel.<br/>             Värdet uttrycks som en procent från 0 till 100. Använd denna egenskap<br/>             för att läsa eller ange volymvärden som är mer precisa än de fördefinierade<br/>             nivåerna som finns via [`VideoFrame.volume`](/slides/python-net/sv/aspose.slides/videoframe/volume)-egenskapen.<br/>             Läs/skriv **float**. |
| [`play_mode`](/slides/python-net/sv/aspose.slides/videoframe/play_mode/) | Returnerar eller anger videouppspelningsläget.<br/>            Läs/skriv [`VideoPlayModePreset`](/slides/python-net/sv/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/sv/aspose.slides/videoframe/full_screen_mode/) | Avgör om en video visas i helskärmsläge.<br/>            Läs/skriv **bool**. |
| [`link_path_long`](/slides/python-net/sv/aspose.slides/videoframe/link_path_long/) | Returnerar eller anger namnet på en videofil som är länkad till en VideoFrame.<br/>            Läs/skriv **str**. |
| [`embedded_video`](/slides/python-net/sv/aspose.slides/videoframe/embedded_video/) | Returnerar eller anger inbäddat videoobjekt.<br/>            Läs/skriv [`IVideo`](/slides/python-net/sv/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/sv/aspose.slides/videoframe/trim_from_start/) | Trimma start [ms] |
| [`trim_from_end`](/slides/python-net/sv/aspose.slides/videoframe/trim_from_end/) | Trimma slut [ms] |
| [`caption_tracks`](/slides/python-net/sv/aspose.slides/videoframe/caption_tracks/) | Hämtar samlingen av stängda undertexter som är associerade med videoramen.<br/>             Denna egenskap är skrivskyddad och returnerar ett [`ICaptionsCollection`](/slides/python-net/sv/aspose.slides/icaptionscollection) som innehåller alla undertextspår. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/videoframe/get_image/#) | Returnerar formens miniatyr.<br/>            ShapeThumbnailBounds.Shape miniatyrgränstyper används som standard. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatyr. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Sparar innehållet i Shape som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i Shape som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/videoframe/remove_placeholder/#) | Anger att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och anger platshållaregenskaper till en specifik. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/videoframe/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen ärvs från).<br/>            En None returneras om den aktuella formen inte ärvs. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/videoframe/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |
| [`get_geometry_paths(self)`](/slides/python-net/sv/aspose.slides/videoframe/get_geometry_paths/#) | Returnerar en kopia av sökvägen för geometriformen. Koordinaterna är relativa till formens övre vänstra hörn. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/sv/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Uppdaterar formens geometri från [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)-objektet. Koordinaterna måste vara relativa till formens övre<br/>             vänstra hörn.<br/>             Ändrar formens typ ([`GeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/geometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/sv/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Uppdaterar formens geometri från en array av [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath). Koordinaterna måste vara relativa till formens övre<br/>             vänstra hörn.<br/>             Ändrar formens typ ([`GeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/geometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/sv/aspose.slides/videoframe/create_shape_elements/#) | Skapar och returnerar en array av formens element. |

### Se även
* klass [`GeometryShape`](/slides/python-net/sv/aspose.slides/geometryshape)
* klass [`PictureFrame`](/slides/python-net/sv/aspose.slides/pictureframe)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* klass [`VideoFrame`](/slides/python-net/sv/aspose.slides/videoframe)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)