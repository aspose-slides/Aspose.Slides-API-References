---
title: AudioFrame class
second_title: Aspose.Slides a Python számára .NET API referenciája
description:
type: docs
url: /hu/aspose.slides/audioframe/
---
## AudioFrame osztály

Egy hangklipet ábrázol a dián.

**Öröklés:**[`AudioFrame`](/slides/python-net/hu/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/hu/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

Az AudioFrame típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/audioframe/is_text_holder/) | Meghatározza, hogy a forma TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/audioframe/placeholder/) | Visszaadja a forma helyőrzőjét. Ha a formának nincs helyőrzője, None-t ad vissza.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/audioframe/custom_data/) | Visszaadja a forma egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/audioframe/raw_frame/) | Visszaadja vagy beállítja a nyers forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/audioframe/frame/) | Visszaadja vagy beállítja a forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/audioframe/line_format/) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, vonal tulajdonságokkal nem rendelkező formák esetén None-t adhat vissza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/audioframe/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a forma 3D hatás tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, 3D tulajdonságokkal nem rendelkező formák esetén None-t adhat vissza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/audioframe/effect_format/) | Visszaadja az EffectFormat objektumot, amely a forma alkalmazott képponteffekteit tartalmazza.<br/>            Megjegyzés: bizonyos, effektus tulajdonságokkal nem rendelkező formák esetén None-t adhat vissza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/audioframe/fill_format/) | Visszaadja a FillFormat objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, kitöltési tulajdonságokkal nem rendelkező formák esetén None-t adhat vissza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/audioframe/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/audioframe/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egér fölé mozgatására definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/audioframe/hyperlink_manager/) | Visszaadja a hiperhivatkozás-kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/audioframe/hidden/) | Meghatározza, hogy a forma rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/audioframe/z_order_position/) | Visszaadja egy forma z-sorrendbeli pozícióját.<br/>            A Shapes[0] a sorrend hátuljában lévő formát adja vissza,<br/>            a Shapes[Shapes.Count - 1] pedig a sorrend elején lévő formát.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/audioframe/connection_site_count/) | Visszaadja a forma csatlakozási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/audioframe/rotation/) | Visszaadja vagy beállítja a megadott forma z-tengely körüli elforgatási fokszámát.<br/>            A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték<br/>            az óramutató járásával ellentétes forgást.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/audioframe/x/) | Visszaadja vagy beállítja a forma bal felső sarkának x-koordinátáját, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/audioframe/y/) | Visszaadja vagy beállítja a forma bal felső sarkának y-koordinátáját, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/audioframe/width/) | Visszaadja vagy beállítja a forma szélességét, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/audioframe/height/) | Visszaadja vagy beállítja a forma magasságát, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/audioframe/black_white_mode/) | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/audioframe/unique_id/) | Visszaad egy belső, a prezentációra korlátozódó azonosítót, amelyet kiegészítők vagy más kód használhat.<br/>            Mivel ezt az értéket a felhasználó vagy programkóddal újra lehet rendelni, nem szabad tartós egyedi kulcsként kezelni.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/audioframe/office_interop_shape_id/) | Visszaad egy diára korlátozódó egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéből.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/audioframe/alternative_text/) | Visszaadja vagy beállítja a forma alternatív szövegét.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/audioframe/alternative_text_title/) | Visszaadja vagy beállítja a forma alternatív szövegének címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/audioframe/name/) | Visszaadja vagy beállítja a forma nevét.<br/>            Nem lehet None. Szükség esetén üres karakterláncot használjon.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/audioframe/is_decorative/) | Visszaadja vagy beállítja a 'Mark as decorative' beállítást<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/audioframe/shape_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IPictureFrameLock`](/slides/python-net/hu/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/audioframe/is_grouped/) | Meghatározza, hogy a forma csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/audioframe/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Egyébként None-t ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/audioframe/slide/) | Visszaadja a forma szülő diáját.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/audioframe/presentation/) | Visszaadja a dia szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/hu/aspose.slides/audioframe/shape_style/) | Visszaadja a forma stílusobjektumát.<br/>            Csak olvasható [`IShapeStyle`](/slides/python-net/hu/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/hu/aspose.slides/audioframe/shape_type/) | Visszaadja vagy beállítja a PictureFrame AutoShape típusát.<br/>            Az [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) halmaz minden eleme megengedett, <br/>            kivéve mindenféle vonalat:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Olvasás/írás [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/hu/aspose.slides/audioframe/adjustments/) | Visszaadja a forma igazítási értékeinek gyűjteményét.<br/>            Csak olvasható [`IAdjustValueCollection`](/slides/python-net/hu/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/hu/aspose.slides/audioframe/picture_frame_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IPictureFrameLock`](/slides/python-net/hu/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/hu/aspose.slides/audioframe/picture_format/) | Visszaadja a képkeret PictureFillFormat objektumát.<br/>            Csak olvasható [`IPictureFillFormat`](/slides/python-net/hu/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/hu/aspose.slides/audioframe/relative_scale_height/) | Visszaadja vagy beállítja a képkeret magasságának méretezését (az eredeti képmérettel arányosan). Az 1.0 érték 100%-nak felel meg.<br/>            Olvasás/írás **float**. |
| [`relative_scale_width`](/slides/python-net/hu/aspose.slides/audioframe/relative_scale_width/) | Visszaadja vagy beállítja a képkeret szélességének méretezését (az eredeti képmérettel arányosan). Az 1.0 érték 100%-nak felel meg.<br/>            Olvasás/írás **float**. |
| [`is_cameo`](/slides/python-net/hu/aspose.slides/audioframe/is_cameo/) | Meghatározza, hogy a PictureFrame Cameo objektum-e vagy sem.<br/>            Csak olvasható **bool**. |
| [`audio_cd_start_track`](/slides/python-net/hu/aspose.slides/audioframe/audio_cd_start_track/) | Visszaadja vagy beállítja egy kezdő sáv indexét.<br/>            Olvasás/írás **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/hu/aspose.slides/audioframe/audio_cd_start_track_time/) | Visszaadja vagy beállítja egy kezdő sáv időpontját.<br/>            Olvasás/írás **int**. |
| [`audio_cd_end_track`](/slides/python-net/hu/aspose.slides/audioframe/audio_cd_end_track/) | Visszaadja vagy beállítja egy utolsó sáv indexét<br/>            Olvasás/írás **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/hu/aspose.slides/audioframe/audio_cd_end_track_time/) | Visszaadja vagy beállítja egy utolsó sáv időpontját.<br/>            Olvasás/írás **int**. |
| [`volume`](/slides/python-net/hu/aspose.slides/audioframe/volume/) | Visszaadja vagy beállítja a hangerőt.<br/>            Olvasás/írás [`AudioVolumeMode`](/slides/python-net/hu/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/hu/aspose.slides/audioframe/play_mode/) | Visszaadja vagy beállítja a hang lejátszási módját.<br/>            Olvasás/írás [`AudioPlayModePreset`](/slides/python-net/hu/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/hu/aspose.slides/audioframe/hide_at_showing/) | Meghatározza, hogy az AudioFrame rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`play_loop_mode`](/slides/python-net/hu/aspose.slides/audioframe/play_loop_mode/) | Meghatározza, hogy a hang ciklikusan ismétlődik-e.<br/>            Olvasás/írás **bool**. |
| [`play_across_slides`](/slides/python-net/hu/aspose.slides/audioframe/play_across_slides/) | Meghatározza, hogy a hang a diák között játszódik-e.<br/>            Olvasás/írás **bool**. |
| [`rewind_audio`](/slides/python-net/hu/aspose.slides/audioframe/rewind_audio/) | Meghatározza, hogy a hang lejátszás után automatikusan visszatekerődik-e a kezdetre.<br/>            Olvasás/írás **bool**. |
| [`embedded`](/slides/python-net/hu/aspose.slides/audioframe/embedded/) | Meghatározza, hogy a hang be van-e ágyazva a prezentációba.<br/>            Csak olvasható **bool**. |
| [`link_path_long`](/slides/python-net/hu/aspose.slides/audioframe/link_path_long/) | Visszaadja vagy beállítja egy audiofájl nevét, amely az AudioFrame-hez van linkelve.<br/>            Olvasás/írás **str**. |
| [`embedded_audio`](/slides/python-net/hu/aspose.slides/audioframe/embedded_audio/) | Visszaadja vagy beállítja a beágyazott audio objektumot.<br/>            Olvasás/írás [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/hu/aspose.slides/audioframe/fade_in_duration/) | Megadja a média kezdeti elhalványulásának időtartamát ezredmásodpercben.<br/>            Olvasás/írás **float**. |
| [`fade_out_duration`](/slides/python-net/hu/aspose.slides/audioframe/fade_out_duration/) | Megadja a média befejező elhalványulásának időtartamát ezredmásodpercben.<br/>            Olvasás/írás **float**. |
| [`volume_value`](/slides/python-net/hu/aspose.slides/audioframe/volume_value/) | Visszaadja vagy beállítja a hangerőt százalékban.<br/>            Olvasás/írás **float**. |
| [`trim_from_start`](/slides/python-net/hu/aspose.slides/audioframe/trim_from_start/) | Megadja a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben.<br/>            Olvasás/írás **float**. |
| [`trim_from_end`](/slides/python-net/hu/aspose.slides/audioframe/trim_from_end/) | Megadja a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben.<br/>            Olvasás/írás **float**. |
| [`caption_tracks`](/slides/python-net/hu/aspose.slides/audioframe/caption_tracks/) | Visszaadja a hangkerethez kapcsolódó feliratsorok gyűjteményét.<br/>            Ez a tulajdonság csak olvasható, és egy [`ICaptionsCollection`](/slides/python-net/hu/aspose.slides/icaptionscollection)-t ad vissza, amely az összes felirat sávot tartalmazza. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/audioframe/get_image/#) | Visszaadja a forma bélyegképét.<br/>            Alapértelmezés szerint a ShapeThumbnailBounds.Shape bélyegkép határ típusa használatos. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Visszaadja a forma bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/audioframe/write_as_svg/#iorawiobase) | A Shape tartalmát SVG fájlként menti. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | A Shape tartalmát SVG fájlként menti. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/audioframe/remove_placeholder/#) | Meghatározza, hogy ez a forma nem helyőrző. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Új helyőrzőt ad hozzá, ha nincs, és a megadott helyőrző tulajdonságait beállítja. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/audioframe/get_base_placeholder/#) | Visszaad egy alap helyőrző formát (a layoutból és/vagy a mesterdiáról származó formát, amelyből az aktuális forma örököl).<br/>            Ha az aktuális forma nem öröklődik, None-t ad vissza. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/audioframe/get_visual_bounds/#) | Visszaadja a forma vizuális határait, amelyet a renderelt tartalom alapján számít. |
| [`get_geometry_paths(self)`](/slides/python-net/hu/aspose.slides/audioframe/get_geometry_paths/#) | Visszaadja a geometriai forma útvonalának másolatát. A koordináták a forma bal felső sarkához képest relatívak. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hu/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | Frissíti a forma geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) objektumból. A koordinátáknak a forma bal<br/>             felső sarkához relatívnak kell lenniük.<br/>             A forma típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM)-ra módosítja. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hu/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | Frissíti a forma geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) tömbből. A koordinátáknak a forma bal<br/>             felső sarkához relatívnak kell lenniük.<br/>             A forma típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM)-ra módosítja. |
| [`create_shape_elements(self)`](/slides/python-net/hu/aspose.slides/audioframe/create_shape_elements/#) | Létrehozza és visszaadja a forma elemeinek tömbjét. |

### Lásd még
* osztály [`AudioFrame`](/slides/python-net/hu/aspose.slides/audioframe)
* osztály [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape)
* osztály [`PictureFrame`](/slides/python-net/hu/aspose.slides/pictureframe)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)