---
title: Connector class
second_title: Aspose.Slides a Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/connector/
---
## Connector osztály

A Connector egy csatlakozót reprezentál.

**Inheritance:**[`Connector`](/slides/python-net/hu/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

A Connector típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/connector/is_text_holder/) | Meghatározza, hogy a forma TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/connector/placeholder/) | Visszaadja a forma helyfoglalóját. Ha a formának nincs helyfoglalója, visszaadja a None értéket.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/connector/custom_data/) | Visszaadja a forma egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/connector/raw_frame/) | Visszaadja vagy állítja a nyers forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/connector/frame/) | Visszaadja vagy állítja a forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/connector/line_format/) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formák esetén, amelyeknek nincs vonal tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/connector/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a forma 3D hatástulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formák esetén, amelyeknek nincs 3D tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/connector/effect_format/) | Visszaadja az EffectFormat objektumot, amely a forma pixel effektusait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formák esetén, amelyeknek nincs effektus tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/connector/fill_format/) | Visszaadja a FillFormat objektumot, amely a forma kitöltésformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formák esetén, amelyeknek nincs kitöltés tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/connector/hyperlink_click/) | Visszaadja vagy állítja a kattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/connector/hyperlink_mouse_over/) | Visszaadja vagy állítja az egér fölé húzásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/connector/hyperlink_manager/) | Visszaadja a hiperhivatkozás-kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/connector/hidden/) | Meghatározza, hogy a forma rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/connector/z_order_position/) | Visszaadja a forma z-sorrendben elfoglalt pozícióját.<br/>            Shapes[0] a z-sorrend hátsó végén lévő formát adja vissza,<br/>            a Shapes[Shapes.Count - 1] a z-sorrend első végén lévő formát adja vissza.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/connector/connection_site_count/) | Visszaadja a forma csatlakozási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/connector/rotation/) | Visszaadja vagy állítja a forma a z-tengely körül forgatott szögét fokban.<br/>            A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellentétes irányt.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/connector/x/) | Visszaadja vagy állítja a forma bal felső sarkának x-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/connector/y/) | Visszaadja vagy állítja a forma bal felső sarkának y-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/connector/width/) | Visszaadja vagy állítja a forma szélességét pontban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/connector/height/) | Visszaadja vagy állítja a forma magasságát pontban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/connector/black_white_mode/) | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/connector/unique_id/) | Visszaad egy belső, prezentációra jellemző azonosítót, amelyet kiegészítők vagy más kódok használhatnak.<br/>            Mivel ezt az értéket a felhasználó vagy programkódból felül lehet írni, nem tekinthető állandó egyedi kulcsnak.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/connector/office_interop_shape_id/) | Visszaad egy dia-specifikus egyedi azonosítót, amely a forma életciklusa során változatlan marad, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéről.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/connector/alternative_text/) | Visszaadja vagy állítja a forma alternatív szövegét.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/connector/alternative_text_title/) | Visszaadja vagy állítja a forma alternatív szövegének címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/connector/name/) | Visszaadja vagy állítja a forma nevét.<br/>            Nem lehet None. Szükség esetén üres karakterláncot használjon.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/connector/is_decorative/) | 'Mark as decorative' opció beállítása.<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/connector/shape_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IConnectorLock`](/slides/python-net/hu/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/connector/is_grouped/) | Meghatározza, hogy a forma csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/connector/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Egyébként None-t ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/connector/slide/) | Visszaadja a forma szülő diát.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/connector/presentation/) | Visszaadja a dia szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/hu/aspose.slides/connector/shape_style/) | Visszaadja a forma stílusobjektumát.<br/>            Csak olvasható [`IShapeStyle`](/slides/python-net/hu/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/hu/aspose.slides/connector/shape_type/) | Visszaadja vagy állítja az AutoShape típusát.<br/>            Olvasás/írás [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/hu/aspose.slides/connector/adjustments/) | Visszaadja a forma állítóértékeinek gyűjteményét.<br/>            Csak olvasható [`IAdjustValueCollection`](/slides/python-net/hu/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/hu/aspose.slides/connector/connector_lock/) | Visszaadja a connector zárolásait.<br/>            Csak olvasható [`IConnectorLock`](/slides/python-net/hu/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/hu/aspose.slides/connector/start_shape_connected_to/) | Visszaadja vagy állítja azt a formát, amelyhez a connector kezdőpontját csatolja.<br/>            Olvasás/írás [`IShape`](/slides/python-net/hu/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/hu/aspose.slides/connector/end_shape_connected_to/) | Visszaadja vagy állítja azt a formát, amelyhez a connector végpontját csatolja.<br/>            Olvasás/írás [`IShape`](/slides/python-net/hu/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/hu/aspose.slides/connector/start_shape_connection_site_index/) | Visszaadja vagy állítja a kezdő forma csatlakozási pontjának indexét.<br/>            Olvasás/írás **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/hu/aspose.slides/connector/end_shape_connection_site_index/) | Visszaadja vagy állítja a vég forma csatlakozási pontjának indexét.<br/>            Olvasás/írás **int**. |

## Módszerek

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/connector/get_image/#) | Visszaadja a forma bélyegképét.<br/>            Alapértelmezésként a ShapeThumbnailBounds.Shape forma bélyegkép határok típusa használatos. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Visszaadja a forma bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/connector/write_as_svg/#iorawiobase) | A Shape tartalmát SVG fájlként menti. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | A Shape tartalmát SVG fájlként menti. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/connector/remove_placeholder/#) | Meghatározza, hogy ez a forma nem helyfoglaló. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/connector/add_placeholder/#iplaceholder) | Új helyfoglalót ad hozzá, ha nincs, és a helyfoglaló tulajdonságait egy megadottra állítja. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/connector/get_base_placeholder/#) | Visszaad egy alap helyfoglaló formát (a layout vagy mester dia formáját, amelyből a jelenlegi forma örököl).<br/>            Ha a jelenlegi forma nem örököl, None-t ad vissza. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/connector/get_visual_bounds/#) | Visszaadja a forma vizuális határait, amelyeket a megjelenített tartalma alapján számol. |
| [`get_geometry_paths(self)`](/slides/python-net/hu/aspose.slides/connector/get_geometry_paths/#) | Visszaadja a geometriai forma útvonalának másolatát. A koordináták a forma bal felső sarkához relatívak. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hu/aspose.slides/connector/set_geometry_path/#igeometrypath) | Frissíti a forma geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) objektumból. A koordinátáknak a forma bal felső sarkához relatívnak kell lenniük.<br/>             A forma típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM)-re változtatja. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hu/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Frissíti a forma geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) tömbből. A koordinátáknak a forma bal felső sarkához relatívnak kell lenniük.<br/>             A forma típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM)-re változtatja. |
| [`create_shape_elements(self)`](/slides/python-net/hu/aspose.slides/connector/create_shape_elements/#) | Létrehozza és visszaadja a forma elemeinek tömbjét. |
| [`reroute(self)`](/slides/python-net/hu/aspose.slides/connector/reroute/#) | Átirányítja a connectort, hogy a két összekapcsolt forma között a legrövidebb lehetséges útvonalat kövesse. |

### Lásd még
* class [`Connector`](/slides/python-net/hu/aspose.slides/connector)
* class [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape)
* class [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)