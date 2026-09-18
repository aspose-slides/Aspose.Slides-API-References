---
title: AutoShape class
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/autoshape/
---
## AutoShape osztály

Az AutoShape-t ábrázolja.

**Inheritance:**[`AutoShape`](/slides/python-net/hu/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

Az AutoShape típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/autoshape/is_text_holder/) | Meghatározza, hogy a forma TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/autoshape/placeholder/) | Visszaadja a forma helyfoglalóját. None értéket ad vissza, ha a formának nincs helyfoglalója.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/autoshape/custom_data/) | Visszaadja a forma egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/autoshape/raw_frame/) | Visszaadja vagy beállítja a nyers forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/autoshape/frame/) | Visszaadja vagy beállítja a forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/autoshape/line_format/) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, vonal tulajdonságokkal nem rendelkező formák esetén None értéket adhat vissza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/autoshape/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a forma 3D hatás tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, 3D tulajdonságokkal nem rendelkező formák esetén None értéket adhat vissza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/autoshape/effect_format/) | Visszaadja az EffectFormat objektumot, amely a forma alkalmazott pixel effektjeit tartalmazza.<br/>            Megjegyzés: bizonyos, effekt tulajdonságokkal nem rendelkező formák esetén None értéket adhat vissza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/autoshape/fill_format/) | Visszaadja a FillFormat objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, kitöltési tulajdonságokkal nem rendelkező formák esetén None értéket adhat vissza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/autoshape/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/autoshape/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egérmutató fölé mozgatásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/autoshape/hyperlink_manager/) | Visszaadja a hiperhivatkozás kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/autoshape/hidden/) | Meghatározza, hogy a forma rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/autoshape/z_order_position/) | Visszaadja a forma pozícióját a z-sorrendben,<br/>            a Shapes[0] a z-sorrend hátulján lévő formát adja vissza,<br/>            a Shapes[Shapes.Count - 1] pedig az előtted lévő formát.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/autoshape/connection_site_count/) | Visszaadja a forma csatlakozási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/autoshape/rotation/) | Visszaadja vagy beállítja a megadott forma z-tengely körüli elforgatási szögét fokokban.<br/>            A pozitív érték óramutató járásával megegyező forgást jelez; a negatív érték<br/>            az óramutatóval ellentétes forgást.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/autoshape/x/) | Visszaadja vagy beállítja a forma bal felső sarkának x-koordinátáját pontokban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/autoshape/y/) | Visszaadja vagy beállítja a forma bal felső sarkának y-koordinátáját pontokban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/autoshape/width/) | Visszaadja vagy beállítja a forma szélességét pontokban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/autoshape/height/) | Visszaadja vagy beállítja a forma magasságát pontokban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/autoshape/black_white_mode/) | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/autoshape/unique_id/) | Visszaad egy belső, a prezentációra korlátozott azonosítót, amelyet bővítmények vagy más kód használhat.<br/>            Mivel ez az érték felhasználó vagy program által felülírható, nem szabad állandó egyedi kulcsként kezelni.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/autoshape/office_interop_shape_id/) | Visszaad egy diára korlátozott egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéről.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/autoshape/alternative_text/) | Visszaadja vagy beállítja a forma alternatív szövegét.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/autoshape/alternative_text_title/) | Visszaadja vagy beállítja a forma alternatív szövegének címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/autoshape/name/) | Visszaadja vagy beállítja a forma nevét.<br/>            Nem lehet None. Szükség esetén használjon üres karakterláncot.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/autoshape/is_decorative/) | Visszaadja vagy beállítja a 'Mark as decorative' (díszítőnek jelölés) opciót.<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/autoshape/shape_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IAutoShapeLock`](/slides/python-net/hu/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/autoshape/is_grouped/) | Meghatározza, hogy a forma csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/autoshape/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Ellenkező esetben None-t ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/autoshape/slide/) | Visszaadja a forma szülő diáját.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/autoshape/presentation/) | Visszaadja a dia szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/hu/aspose.slides/autoshape/shape_style/) | Visszaadja a forma stílus objektumát.<br/>            Csak olvasható [`IShapeStyle`](/slides/python-net/hu/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/hu/aspose.slides/autoshape/shape_type/) | Visszaadja vagy beállítja a geometria előre beállított típusát.<br/>            Megjegyzés: az érték megváltoztatásakor minden igazítási érték visszaáll az alapértelmezett értékére.<br/>            Olvasás/írás [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/hu/aspose.slides/autoshape/adjustments/) | Visszaad egy gyűjteményt a forma igazítási értékeiről.<br/>            Csak olvasható [`IAdjustValueCollection`](/slides/python-net/hu/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/hu/aspose.slides/autoshape/auto_shape_lock/) | Visszaadja az automatikus forma zárolásait.<br/>            Csak olvasható [`IAutoShapeLock`](/slides/python-net/hu/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/hu/aspose.slides/autoshape/text_frame/) | Visszaadja az AutoShape TextFrame objektumát.<br/>            Csak olvasható [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/hu/aspose.slides/autoshape/use_background_fill/) | Meghatározza, hogy ez az automatikus forma a dia háttérkitöltésével legyen-e kitöltve a stílus vagy kitöltési formátum helyett.<br/>            Olvasás/írás **bool**. |
| [`is_text_box`](/slides/python-net/hu/aspose.slides/autoshape/is_text_box/) | Megadja, hogy a forma szövegdoboz-e. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/autoshape/get_image/#) | Visszaadja a forma bélyegképét.<br/>            Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma bélyegkép határoló típusa használatos. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Visszaadja a forma bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/autoshape/write_as_svg/#iorawiobase) | A Shape tartalmát SVG fájlként menti. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | A Shape tartalmát SVG fájlként menti. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/autoshape/remove_placeholder/#) | Meghatározza, hogy ez a forma nem helyfoglaló. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Új helyfoglalót ad hozzá, ha nincs, és a helyfoglaló tulajdonságait a megadottra állítja. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/autoshape/get_base_placeholder/#) | Visszaad egy alap helyfoglaló formát (a layoutból és/vagy a mesterdiáról származó formát, amelyből a jelenlegi forma örököl).<br/>            Ha a jelenlegi forma nem örököl, None-t ad vissza. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/autoshape/get_visual_bounds/#) | Lekéri a forma vizuális határait, amelyeket a megjelenített tartalma alapján számol. |
| [`get_geometry_paths(self)`](/slides/python-net/hu/aspose.slides/autoshape/get_geometry_paths/#) | Visszaadja a geometriai forma útvonalának másolatát. A koordináták a forma bal felső sarkához relatívak. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hu/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Frissíti a forma geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) objektumtól. A koordinátáknak a forma bal felső sarkához relatívnak kell lenniük.<br/>             Megváltoztatja a forma típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) erre: [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hu/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Frissíti a forma geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) tömbből. A koordinátáknak a forma bal felső sarkához relatívnak kell lenniük.<br/>             Megváltoztatja a forma típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) erre: [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/hu/aspose.slides/autoshape/create_shape_elements/#) | Létrehozza és visszaadja a forma elemeinek tömbjét. |
| [`add_text_frame(self, text)`](/slides/python-net/hu/aspose.slides/autoshape/add_text_frame/#str) | Új TextFrame-et ad a formához.<br/>            Ha a formának már van TextFrame-je, akkor csak a szöveget módosítja. |

### Lásd még
* osztály [`AutoShape`](/slides/python-net/hu/aspose.slides/autoshape)
* osztály [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)