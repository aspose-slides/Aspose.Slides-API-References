---
title: AudioFrame class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/audioframe/
---
## AudioFrame klass

Representerar ett ljudklipp på en bild.

**Inheritance:**[`AudioFrame`](/slides/python-net/sv/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/sv/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/sv/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

AudioFrame-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/audioframe/is_text_holder/) | Avgör om formen är TextHolder_PPT.<br/>            Skrivskyddad **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides/audioframe/placeholder/) | Returnerar platshållaren för en form. Returnerar None om formen inte har någon platshållare.<br/>            Skrivskyddad [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides/audioframe/custom_data/) | Returnerar formens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/audioframe/raw_frame/) | Returnerar eller anger de råa egenskaperna för formens ram.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides/audioframe/frame/) | Returnerar eller anger ramens egenskaper för formen.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides/audioframe/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsattribut för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har linjeattribut.<br/>            Skrivskyddad [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/audioframe/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3D-effektattribut för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har 3D-attribut.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides/audioframe/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixel-effekter som tillämpas på en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har effektattribut.<br/>            Skrivskyddad [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides/audioframe/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsattribut för en form.<br/>            Obs: kan returnera None för vissa typer av former som inte har fyllningsattribut.<br/>            Skrivskyddad [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/audioframe/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för mus-klick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/audioframe/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för mus-över.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/audioframe/hyperlink_manager/) | Returnerar hyperlänks-hanteraren.<br/>            Skrivskyddad [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides/audioframe/hidden/) | Avgör om formen är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/audioframe/z_order_position/) | Returnerar positionen för en form i z-ordningen.<br/>            Shapes[0] returnerar formen längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen.<br/>            Skrivskyddad **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/audioframe/connection_site_count/) | Returnerar antalet anslutningsställen på formen.<br/>            Skrivskyddad **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides/audioframe/rotation/) | Returnerar eller anger antalet grader som den angivna formen roteras kring<br/>            z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde<br/>            indikerar moturs rotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides/audioframe/x/) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides/audioframe/y/) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides/audioframe/width/) | Hämtar eller anger bredden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides/audioframe/height/) | Hämtar eller anger höjden på formen, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/audioframe/black_white_mode/) | Egenskapen anger hur en form renderas i svart-vitt visningsläge..<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides/audioframe/unique_id/) | Returnerar en intern, presentations-avgränsad identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omassigneras av användaren eller programmässigt, får det inte behandlas<br/>            som en beständig unik nyckel.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/audioframe/office_interop_shape_id/) | Returnerar en bild-avgränsad unik identifierare som förblir konstant under formens livstid och<br/>            låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till formen från vilken plats som helst i dokumentet.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/audioframe/alternative_text/) | Returnerar eller anger alternativ text som är knuten till en form.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/audioframe/alternative_text_title/) | Returnerar eller anger titeln för den alternativa texten som är knuten till en form.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides/audioframe/name/) | Returnerar eller anger namnet på en form.<br/>            Får inte vara None. Använd tom sträng vid behov.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/audioframe/is_decorative/) | Hämtar eller anger alternativet 'Markera som dekorativ'<br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/audioframe/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IPictureFrameLock`](/slides/python-net/sv/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/audioframe/is_grouped/) | Avgör om formen är grupperad.<br/>            Skrivskyddad **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides/audioframe/parent_group/) | Returnerar överordnat GroupShape-objekt om formen är grupperad. Annars returneras None.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides/audioframe/slide/) | Returnerar föräldrabilden för en form.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides/audioframe/presentation/) | Returnerar föräldrapresentationen för en bild.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/sv/aspose.slides/audioframe/shape_style/) | Returnerar formens stilobjekt.<br/>            Skrivskyddad [`IShapeStyle`](/slides/python-net/sv/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/sv/aspose.slides/audioframe/shape_type/) | Returnerar eller anger AutoShape-typen för en PictureFrame.<br/>            Det finns tillåtna alla objekt i mängden [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype), <br/>            förutom alla typer av linjer:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Läs/skriv [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/sv/aspose.slides/audioframe/adjustments/) | Returnerar en samling av formens justeringsvärden.<br/>            Skrivskyddad [`IAdjustValueCollection`](/slides/python-net/sv/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/sv/aspose.slides/audioframe/picture_frame_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IPictureFrameLock`](/slides/python-net/sv/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/sv/aspose.slides/audioframe/picture_format/) | Returnerar PictureFillFormat-objektet för en bildram.<br/>            Skrivskyddad [`IPictureFillFormat`](/slides/python-net/sv/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/sv/aspose.slides/audioframe/relative_scale_height/) | Returnerar eller anger skalan för höjden (relativt originalbildens storlek) på bildramen. Värde 1.0 motsvarar 100 %.<br/>            Läs/skriv **float**. |
| [`relative_scale_width`](/slides/python-net/sv/aspose.slides/audioframe/relative_scale_width/) | Returnerar eller anger skalan för bredden (relativt originalbildens storlek) på bildramen. Värde 1.0 motsvarar 100 %.<br/>            Läs/skriv **float**. |
| [`is_cameo`](/slides/python-net/sv/aspose.slides/audioframe/is_cameo/) | Avgör om PictureFrame är ett Cameo-objekt eller inte.<br/>            Skrivskyddad **bool**. |
| [`audio_cd_start_track`](/slides/python-net/sv/aspose.slides/audioframe/audio_cd_start_track/) | Returnerar eller anger ett startspår-index.<br/>            Läs/skriv **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/sv/aspose.slides/audioframe/audio_cd_start_track_time/) | Returnerar eller anger en startspår-tid.<br/>            Läs/skriv **int**. |
| [`audio_cd_end_track`](/slides/python-net/sv/aspose.slides/audioframe/audio_cd_end_track/) | Returnerar eller anger ett sista spår-index<br/>            Läs/skriv **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/sv/aspose.slides/audioframe/audio_cd_end_track_time/) | Returnerar eller anger en sista spår-tid.<br/>            Läs/skriv **int**. |
| [`volume`](/slides/python-net/sv/aspose.slides/audioframe/volume/) | Returnerar eller anger ljudvolymen.<br/>            Läs/skriv [`AudioVolumeMode`](/slides/python-net/sv/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/sv/aspose.slides/audioframe/play_mode/) | Returnerar eller anger ljuduppspelningsläge.<br/>            Läs/skriv [`AudioPlayModePreset`](/slides/python-net/sv/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/sv/aspose.slides/audioframe/hide_at_showing/) | Avgör om ett AudioFrame är dolt.<br/>            Läs/skriv **bool**. |
| [`play_loop_mode`](/slides/python-net/sv/aspose.slides/audioframe/play_loop_mode/) | Avgör om ett ljud är i slinga.<br/>            Läs/skriv **bool**. |
| [`play_across_slides`](/slides/python-net/sv/aspose.slides/audioframe/play_across_slides/) | Avgör om ljudet spelas över flera bilder.<br/>            Läs/skriv **bool**. |
| [`rewind_audio`](/slides/python-net/sv/aspose.slides/audioframe/rewind_audio/) | Avgör om ljudet automatiskt spolas tillbaka till början efter uppspelning.<br/>            Läs/skriv **bool**. |
| [`embedded`](/slides/python-net/sv/aspose.slides/audioframe/embedded/) | Avgör om ett ljud är inbäddat i en presentation.<br/>            Skrivskyddad **bool**. |
| [`link_path_long`](/slides/python-net/sv/aspose.slides/audioframe/link_path_long/) | Returnerar eller anger namn på en ljudfil som är länkat till ett AudioFrame.<br/>            Läs/skriv **str**. |
| [`embedded_audio`](/slides/python-net/sv/aspose.slides/audioframe/embedded_audio/) | Returnerar eller anger inbäddat ljudobjekt.<br/>            Läs/skriv [`IAudio`](/slides/python-net/sv/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/sv/aspose.slides/audioframe/fade_in_duration/) | Anger tidslängden för den initiala tonings-in (fade-in) av mediet i millisekunder.<br/>            Läs/skriv **float**. |
| [`fade_out_duration`](/slides/python-net/sv/aspose.slides/audioframe/fade_out_duration/) | Anger tidslängden för den avslutande tonings-ut (fade-out) av mediet i millisekunder.<br/>            Läs/skriv **float**. |
| [`volume_value`](/slides/python-net/sv/aspose.slides/audioframe/volume_value/) | Returnerar eller anger ljudvolymen i procent.<br/>            Läs/skriv **float**. |
| [`trim_from_start`](/slides/python-net/sv/aspose.slides/audioframe/trim_from_start/) | Anger tidslängden som ska tas bort från början av mediet under uppspelning, i millisekunder.<br/>            Läs/skriv **float**. |
| [`trim_from_end`](/slides/python-net/sv/aspose.slides/audioframe/trim_from_end/) | Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder.<br/>            Läs/skriv **float**. |
| [`caption_tracks`](/slides/python-net/sv/aspose.slides/audioframe/caption_tracks/) | Hämtar samlingen av stängda undertexter som är kopplade till ljudramen.<br/>            Denna egenskap är skrivskyddad och returnerar ett [`ICaptionsCollection`](/slides/python-net/sv/aspose.slides/icaptionscollection) som innehåller alla undertextspår. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/audioframe/get_image/#) | Returnerar formens miniatyrbild.<br/>            ShapeThumbnailBounds.Shape används som standard för miniaturområdstyp. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Returnerar formens miniatuurbild. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Sparar formens innehåll som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar formens innehåll som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/audioframe/remove_placeholder/#) | Definierar att denna form inte är en platshållare. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Lägger till en ny platshållare om ingen finns och anger platshållaregenskaper till en angiven. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/audioframe/get_base_placeholder/#) | Returnerar en grundläggande platshållarform (form från layouten och/eller mästarbilder som den aktuella formen ärvs från).<br/>            En None returneras om den aktuella formen inte ärvs. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides/audioframe/get_visual_bounds/#) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |
| [`get_geometry_paths(self)`](/slides/python-net/sv/aspose.slides/audioframe/get_geometry_paths/#) | Returnerar en kopia av sökvägen för geometriformen. Koordinaterna är relativa till formens övre vänstra hörn. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/sv/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | Uppdaterar formens geometri från [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)-objektet. Koordinaterna måste vara relativa till formens<br/>            övre vänstra hörn.<br/>            Ändrar formens typ ([`GeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/geometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/sv/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | Uppdaterar formens geometri från en array av [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath). Koordinaterna måste vara relativa till formens<br/>            övre vänstra hörn.<br/>            Ändrar formens typ ([`GeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/geometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/sv/aspose.slides/audioframe/create_shape_elements/#) | Skapar och returnerar en array av formens element. |

### Se även
* klass [`AudioFrame`](/slides/python-net/sv/aspose.slides/audioframe)
* klass [`GeometryShape`](/slides/python-net/sv/aspose.slides/geometryshape)
* klass [`PictureFrame`](/slides/python-net/sv/aspose.slides/pictureframe)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)