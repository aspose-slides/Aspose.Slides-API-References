---
title: LegacyDiagram class
second_title: Aspose.Slides a Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/legacydiagram/
---
## LegacyDiagram osztály

Egy régi diagram objektumot képvisel.

**Öröklés:**[`LegacyDiagram`](/slides/python-net/hu/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

A LegacyDiagram típus a következő tagokat tartalmazza:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/legacydiagram/is_text_holder/) | Meghatározza, hogy az alakzat TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/legacydiagram/placeholder/) | Visszaadja az alakzat helyfoglalóját. None értéket ad vissza, ha az alakzatnak nincs helyfoglalója.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/legacydiagram/custom_data/) | Visszaadja az alakzat egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/legacydiagram/raw_frame/) | Visszaadja vagy beállítja a nyers alakzat keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/legacydiagram/frame/) | Visszaadja vagy beállítja az alakzat keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/legacydiagram/line_format/) | Visszaadja a LineFormat objektumot, amely az alakzat vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs vonal tulajdonsága, None értéket adhat vissza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/legacydiagram/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely az alakzat 3D hatás tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs 3D tulajdonsága, None értéket adhat vissza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/legacydiagram/effect_format/) | Visszaadja az EffectFormat objektumot, amely az alakzatra alkalmazott pixel effektusokat tartalmazza.<br/>            Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs effektus tulajdonsága, None értéket adhat vissza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/legacydiagram/fill_format/) | Visszaadja a FillFormat objektumot, amely az alakzat kitöltési formázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs kitöltési tulajdonsága, None értéket adhat vissza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/legacydiagram/hyperlink_click/) | Visszaadja vagy beállítja a egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/legacydiagram/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egérmutatásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/legacydiagram/hyperlink_manager/) | Visszaadja a hiperhivatkozás-kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/legacydiagram/hidden/) | Meghatározza, hogy az alakzat rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/legacydiagram/z_order_position/) | Visszaadja egy alakzat z-sorrendben elfoglalt pozícióját.<br/>            A Shapes[0] a z-sorrend hátulján lévő alakzatot adja vissza,<br/>            a Shapes[Shapes.Count - 1] pedig a frontján lévő alakzatot.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/legacydiagram/connection_site_count/) | Visszaadja az alakzaton lévő csatlakozási pontok számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/legacydiagram/rotation/) | Visszaadja vagy beállítja a megadott alakzat z-tengely körüli forgatási fokszámát.<br/>            A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték<br/>            az óramutató járásával ellentétes forgást.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/legacydiagram/x/) | Visszaadja vagy beállítja az alakzat bal felső sarkának x-koordinátáját, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/legacydiagram/y/) | Visszaadja vagy beállítja az alakzat bal felső sarkának y-koordinátáját, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/legacydiagram/width/) | Visszaadja vagy beállítja az alakzat szélességét, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/legacydiagram/height/) | Visszaadja vagy beállítja az alakzat magasságát, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/legacydiagram/black_white_mode/) | A tulajdonság meghatározza, hogyan jelenik meg az alakzat fekete-fehér megjelenítési módban..<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/legacydiagram/unique_id/) | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat.<br/>            Mivel ezt az értéket a felhasználó vagy programozottan át lehet rendelni, nem szabad állandó egyedi kulcsként kezelni.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/legacydiagram/office_interop_shape_id/) | Visszaad egy diahatókörű egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéből.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/legacydiagram/alternative_text/) | Visszaadja vagy beállítja az alakzathoz társított alternatív szöveget.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/legacydiagram/alternative_text_title/) | Visszaadja vagy beállítja az alakzathoz társított alternatív szöveg címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/legacydiagram/name/) | Visszaadja vagy beállítja egy alakzat nevét.<br/>            Nem lehet None. Szükség esetén használjon üres karakterláncot.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/legacydiagram/is_decorative/) | Visszaadja vagy beállítja a „Megjelölés díszítőként” opciót<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/legacydiagram/shape_lock/) | Visszaadja az alakzat zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/legacydiagram/is_grouped/) | Meghatározza, hogy az alakzat csoportosítva van-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/legacydiagram/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosítva van. Egyébként None-t ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/legacydiagram/slide/) | Visszaadja egy alakzat szülő diát.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/legacydiagram/presentation/) | Visszaadja egy dia szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hu/aspose.slides/legacydiagram/graphical_object_lock/) | Visszaadja az alakzat zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/legacydiagram/get_image/#) | Visszaadja az alakzat bélyegképét.<br/>            Alapértelmezés szerint a ShapeThumbnailBounds.Shape alakzat bélyegkép határ típusa van használva. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | Visszaadja az alakzat bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | Mentés a Shape tartalmát SVG fájlként. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Mentés a Shape tartalmát SVG fájlként. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/legacydiagram/remove_placeholder/#) | Meghatározza, hogy ez az alakzat nem helyfoglaló. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | Új helyfoglalót ad hozzá, ha nincs, és a helyfoglaló tulajdonságait egy megadottra állítja. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/legacydiagram/get_base_placeholder/#) | Visszaad egy alap helyfoglaló alakzatot (az elrendezésből és/vagy fő diából származó alakzatot, amelyből a jelenlegi alakzat származik).<br/>            Ha a jelenlegi alakzat nem örökölt, None-t ad vissza. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/legacydiagram/get_visual_bounds/#) | Visszaadja az alakzat vizuális határait, amelyeket a megjelenített tartalma alapján számít. |
| [`convert_to_smart_art(self)`](/slides/python-net/hu/aspose.slides/legacydiagram/convert_to_smart_art/#) | Átalakítja a régi diagramot szerkeszthető SmartArt objektummá. <br/>            A létrehozott SmartArt objektumot a szülő csoport alakzathoz adja ugyanazon a pozíción. |
| [`convert_to_group_shape(self)`](/slides/python-net/hu/aspose.slides/legacydiagram/convert_to_group_shape/#) | Átalakítja a régi diagramot szerkeszthető csoport alakzattá. <br/>            A létrehozott GroupShape objektumot a szülő csoport alakzathoz adja ugyanazon a pozíción. |

### Lásd még
* osztály [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* osztály [`LegacyDiagram`](/slides/python-net/hu/aspose.slides/legacydiagram)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)