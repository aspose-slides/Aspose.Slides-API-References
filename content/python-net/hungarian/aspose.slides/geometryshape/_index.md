---
title: GeometryShape class
second_title: Aspose.Slides a Pythonhoz a .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/geometryshape/
---
## GeometryShape osztály

Az összes geometriai alakzat szülőosztályát képviseli.

**Öröklődés:**[`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

A GeometryShape típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/geometryshape/is_text_holder/) | Meghatározza, hogy az alakzat TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/geometryshape/placeholder/) | Visszaadja az alakzat helyfoglalóját. Ha az alakzatnak nincs helyfoglalója, akkor None-t ad vissza.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/geometryshape/custom_data/) | Visszaadja az alakzat egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/geometryshape/raw_frame/) | Visszaadja vagy beállítja a nyers alakzatforma tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/geometryshape/frame/) | Visszaadja vagy beállítja az alakzatforma tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/geometryshape/line_format/) | Visszaadja a LineFormat objektumot, amely az alakzatra vonatkozó vonalformázási tulajdonságokat tartalmazza.<br/>            Megjegyzés: bizonyos olyan alakzatok esetén, amelyeknek nincs vonaltulajdonságuk, None-t adhat vissza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/geometryshape/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely egy alakzatra vonatkozó 3D effektus tulajdonságokat tartalmaz.<br/>            Megjegyzés: bizonyos olyan alakzatok esetén, amelyeknek nincs 3D tulajdonságuk, None-t adhat vissza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/geometryshape/effect_format/) | Visszaadja az EffectFormat objektumot, amely az alakzatra alkalmazott pixel effektusokat tartalmazza.<br/>            Megjegyzés: bizonyos olyan alakzatok esetén, amelyeknek nincs effektustulajdonságuk, None-t adhat vissza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/geometryshape/fill_format/) | Visszaadja a FillFormat objektumot, amely az alakzatra vonatkozó kitöltésformázási tulajdonságokat tartalmazza.<br/>            Megjegyzés: bizonyos olyan alakzatok esetén, amelyeknek nincs kitöltéstulajdonságuk, None-t adhat vissza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/geometryshape/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/geometryshape/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egérmutatásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/geometryshape/hyperlink_manager/) | Visszaadja a hiperhivatkozás-kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/geometryshape/hidden/) | Meghatározza, hogy az alakzat rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/geometryshape/z_order_position/) | Visszaadja az alakzat pozícióját a z-sorrendben.<br/>            A Shapes[0] a z-sorrend hátulját adja vissza,<br/>            a Shapes[Shapes.Count - 1] pedig a z-sorrend elejét.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/geometryshape/connection_site_count/) | Visszaadja az alakzat kapcsolódási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/geometryshape/rotation/) | Visszaadja vagy beállítja a megadott alakzat z-tengely körüli elforgatásának fokszámát.<br/>            A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték<br/>            az óramutatóval ellentétes forgást.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/geometryshape/x/) | Visszaadja vagy beállítja az alakzat bal felső sarkának X koordinátáját pontokban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/geometryshape/y/) | Visszaadja vagy beállítja az alakzat bal felső sarkának Y koordinátáját pontokban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/geometryshape/width/) | Visszaadja vagy beállítja az alakzat szélességét pontokban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/geometryshape/height/) | Visszaadja vagy beállítja az alakzat magasságát pontokban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/geometryshape/black_white_mode/) | A tulajdonság meghatározza, hogyan jelenik meg az alakzat fekete-fehér megjelenítési módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/geometryshape/unique_id/) | Visszaad egy belső, a prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat.<br/>            Mivel ezt az értéket felhasználó vagy programozott módon át lehet rendelni, nem tekinthető<br/>            állandó egyedi kulcsnak.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/geometryshape/office_interop_shape_id/) | Visszaad egy diára korlátozott egyedi azonosítót, amely a shape élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy a dokumentum bármely pontjáról megbízhatóan hivatkozzon rá.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/geometryshape/alternative_text/) | Visszaadja vagy beállítja az alakzathoz tartozó alternatív szöveget.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/geometryshape/alternative_text_title/) | Visszaadja vagy beállítja az alakzathoz tartozó alternatív szöveg címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/geometryshape/name/) | Visszaadja vagy beállítja egy alakzat nevét.<br/>            Nem lehet None. Szükség esetén használjon üres karakterláncot.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/geometryshape/is_decorative/) | Visszaadja vagy beállítja a 'Dekorációként jelölés' beállítást<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/geometryshape/shape_lock/) | Visszaadja az alakzat zárolásait.<br/>            Csak olvasható [`IBaseShapeLock`](/slides/python-net/hu/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/geometryshape/is_grouped/) | Meghatározza, hogy az alakzat csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/geometryshape/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosított. Egyébként None-t ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/geometryshape/slide/) | Visszaadja az alakzat szülő diáját.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/geometryshape/presentation/) | Visszaadja a dia szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/hu/aspose.slides/geometryshape/shape_style/) | Visszaadja az alakzat stílusobjektumát.<br/>            Csak olvasható [`IShapeStyle`](/slides/python-net/hu/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type/) | Visszaadja vagy beállítja a geometria előre beállított típusát.<br/>            Megjegyzés: az érték változtatásakor az összes igazítási érték visszaáll az alapértelmezett értékekre.<br/>            Olvasás/írás [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/hu/aspose.slides/geometryshape/adjustments/) | Visszaadja az alakzat igazítási értékeinek gyűjteményét.<br/>            Csak olvasható [`IAdjustValueCollection`](/slides/python-net/hu/aspose.slides/iadjustvaluecollection). |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/geometryshape/get_image/#) | Visszaadja az alakzat bélyegképét.<br/>            Alapértelmezés szerint a ShapeThumbnailBounds.Shape bélyegkép határoló típust használja. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | Visszaadja az alakzat bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | A Shape tartalmát SVG fájlként menti. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | A Shape tartalmát SVG fájlként menti. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/geometryshape/remove_placeholder/#) | Meghatározza, hogy ez az alakzat nem helyfoglaló. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | Új helyfoglalót ad hozzá, ha nincs, és beállítja a helyfoglaló tulajdonságait egy megadottra. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/geometryshape/get_base_placeholder/#) | Visszaad egy alap helyfoglaló alakzatot (a layout és/vagy mester dia alakzatát, amelyből a jelenlegi alakzat örökölt).<br/>            Ha a jelenlegi alakzat nem örökölt, None-t ad vissza. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/geometryshape/get_visual_bounds/#) | Visszaadja az alakzat vizuális határait, amelyeket a megjelenített tartalma alapján számítanak. |
| [`get_geometry_paths(self)`](/slides/python-net/hu/aspose.slides/geometryshape/get_geometry_paths/#) | Visszaadja a geometriai alakzat útvonalának másolatát. A koordináták az alakzat bal felső sarkához képest relatívak. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hu/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | Frissíti az alakzat geometriát a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) objektumból. A koordinátáknak a bal felső sarokhoz képest relatívnak kell lenniük.<br/>             Megváltoztatja az alakzat típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM)-re. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hu/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | Frissíti az alakzat geometriát [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) tömbből. A koordinátáknak a bal felső sarokhoz képest relatívnak kell lenniük.<br/>             Megváltoztatja az alakzat típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM)-re. |
| [`create_shape_elements(self)`](/slides/python-net/hu/aspose.slides/geometryshape/create_shape_elements/#) | Létrehozza és visszaadja az alakzat elemeinek tömbjét. |

### Lásd még
* osztály [`GeometryShape`](/slides/python-net/hu/aspose.slides/geometryshape)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)