---
title: PictureFrame class
second_title: Aspose.Slides Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/pictureframe/
---
## PictureFrame osztály

Képkeretet ábrázol, amelyen belül kép található.

**Öröklődés:**[`PictureFrame`](/slides/python-net/hu/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

A PictureFrame típus a következő tagokat biztosítja:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/pictureframe/is_text_holder/) | Megállapítja, hogy a forma TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/pictureframe/placeholder/) | Visszaadja a forma helykitöltőjét. Ha a formának nincs helykitöltője, akkor None értéket ad vissza.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/pictureframe/custom_data/) | Visszaadja a forma egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/pictureframe/raw_frame/) | Visszaadja vagy beállítja a nyers forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/pictureframe/frame/) | Visszaadja vagy beállítja a forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/pictureframe/line_format/) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, vonal tulajdonságokkal nem rendelkező formák esetén None értéket adhat vissza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/pictureframe/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a forma 3D hatás tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, 3D tulajdonságokkal nem rendelkező formák esetén None értéket adhat vissza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/pictureframe/effect_format/) | Visszaadja az EffectFormat objektumot, amely a forma pixel effektusait tartalmazza.<br/>            Megjegyzés: bizonyos, effekt tulajdonságokkal nem rendelkező formák esetén None értéket adhat vissza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/pictureframe/fill_format/) | Visszaadja a FillFormat objektumot, amely a forma kitöltésformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, kitöltési tulajdonságokkal nem rendelkező formák esetén None értéket adhat vissza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/pictureframe/hyperlink_click/) | Visszaadja vagy állítja be az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/pictureframe/hyperlink_mouse_over/) | Visszaadja vagy állítja be az egérmutatásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/pictureframe/hyperlink_manager/) | Visszaadja a hiperhivatkozáskezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/pictureframe/hidden/) | Megállapítja, hogy a forma rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/pictureframe/z_order_position/) | Visszaadja a forma pozícióját a Z-sorrendben.<br/>            A Shapes[0] a Z-sorrend hátsó végén lévő formát adja vissza,<br/>            és a Shapes[Shapes.Count - 1] a Z-sorrend első végén lévő formát adja vissza.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/pictureframe/connection_site_count/) | Visszaadja a forma csatlakozási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/pictureframe/rotation/) | Visszaadja vagy állítja be a megadott forma Z-tengely körüli elforgatási szögét fokban. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkező irányt.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/pictureframe/x/) | Lekéri vagy beállítja a forma bal felső sarkának x-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/pictureframe/y/) | Lekéri vagy beállítja a forma bal felső sarkának y-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/pictureframe/width/) | Lekéri vagy beállítja a forma szélességét pontban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/pictureframe/height/) | Lekéri vagy beállítja a forma magasságát pontban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/pictureframe/black_white_mode/) | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/pictureframe/unique_id/) | Visszaad egy belső, prezentációkörnyezetre vonatkozó azonosítót, amelyet kiegészítők vagy más kód használhat.<br/>            Mivel ezt az értéket a felhasználó vagy programkódból át lehet írni, nem szabad állandó egyedi kulcsként kezelni.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/pictureframe/office_interop_shape_id/) | Visszaad egy dia-környezetre vonatkozó egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy a dokumentum bármely pontjáról megbízhatóan hivatkozzon a formára.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/pictureframe/alternative_text/) | Visszaadja vagy állítja be a forma alternatív szövegét.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/pictureframe/alternative_text_title/) | Visszaadja vagy állítja be a forma alternatív szövegének címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/pictureframe/name/) | Visszaadja vagy állítja be egy forma nevét.<br/>            Nem lehet None. Szükség esetén használjon üres karakterláncot.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/pictureframe/is_decorative/) | Lekéri vagy állítja be a „Dekorációnak jelölés” opciót<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/pictureframe/shape_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IPictureFrameLock`](/slides/python-net/hu/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/pictureframe/is_grouped/) | Megállapítja, hogy a forma csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/pictureframe/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Egyébként None értéket ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/pictureframe/slide/) | Visszaadja a forma szülő diáját.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/pictureframe/presentation/) | Visszaadja a dia szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/hu/aspose.slides/pictureframe/shape_style/) | Visszaadja a forma stílusobjektumát.<br/>            Csak olvasható [`IShapeStyle`](/slides/python-net/hu/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/hu/aspose.slides/pictureframe/shape_type/) | Visszaadja vagy állítja be a PictureFrame AutoShape típusát.<br/>            A [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) halmaz minden eleme engedélyezett, kivéve a különböző vonalakat:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Olvasás/írás [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/hu/aspose.slides/pictureframe/adjustments/) | Visszaadja a forma beállítási értékeinek gyűjteményét.<br/>            Csak olvasható [`IAdjustValueCollection`](/slides/python-net/hu/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/hu/aspose.slides/pictureframe/picture_frame_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IPictureFrameLock`](/slides/python-net/hu/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/hu/aspose.slides/pictureframe/picture_format/) | Visszaadja a PictureFillFormat objektumot egy képkerethez.<br/>            Csak olvasható [`IPictureFillFormat`](/slides/python-net/hu/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/hu/aspose.slides/pictureframe/relative_scale_height/) | Visszaadja vagy állítja be a képkeret magasságának (az eredeti képmérettel összehasonlítva) skáláját. Az 1,0 érték 100%-nak felel meg.<br/>            Olvasás/írás **float**. |
| [`relative_scale_width`](/slides/python-net/hu/aspose.slides/pictureframe/relative_scale_width/) | Visszaadja vagy állítja be a képkeret szélességének (az eredeti képmérettel összehasonlítva) skáláját. Az 1,0 érték 100%-nak felel meg.<br/>            Olvasás/írás **float**. |
| [`is_cameo`](/slides/python-net/hu/aspose.slides/pictureframe/is_cameo/) | Megállapítja, hogy a PictureFrame Cameo objektum-e vagy sem.<br/>            Csak olvasható **bool**. |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/pictureframe/get_image/#) | Visszaadja a forma bélyegképét.<br/>            Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma bélyegkép határ típust használja. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Visszaadja a forma bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Elmenti a Forma tartalmát SVG fájlként. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Elmenti a Forma tartalmát SVG fájlként. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/pictureframe/remove_placeholder/#) | Meghatározza, hogy ez a forma nem helykitöltő. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Új helykitöltőt ad hozzá, ha nincs, és beállítja a helykitöltő tulajdonságait a megadottra. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/pictureframe/get_base_placeholder/#) | Visszaad egy alap helykitöltő formát (a elrendezésből és/vagy mester diákról származó formát, amelyből a jelenlegi forma örököl).<br/>            Ha a jelenlegi forma nem öröklődik, akkor None értéket ad vissza. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/pictureframe/get_visual_bounds/#) | Lekéri a forma megjelenített határait, amely a renderelt tartalom alapján kerül kiszámításra. |
| [`get_geometry_paths(self)`](/slides/python-net/hu/aspose.slides/pictureframe/get_geometry_paths/#) | Visszaadja a geometriai forma útvonalának másolatát. A koordináták a forma bal felső sarkához képest relatívak. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hu/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Frissíti a forma geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) objektumból. A koordinátáknak a forma bal felső sarkához képest relatívnek kell lenniük.<br/>             Megváltoztatja a forma típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM) értékre. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hu/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Frissíti a forma geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) tömbből. A koordinátáknak a forma bal felső sarkához képest relatívnek kell lenniük.<br/>             Megváltoztatja a forma típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) a [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM) értékre. |
| [`create_shape_elements(self)`](/slides/python-net/hu/aspose.slides/pictureframe/create_shape_elements/#) | Létrehozza és visszaadja a forma elemeinek tömbjét. |

### Lásd még
* osztály [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape)
* osztály [`PictureFrame`](/slides/python-net/hu/aspose.slides/pictureframe)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)