---
title: GraphicalObject class
second_title: Aspose.Slides a Pythonhoz a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/graphicalobject/
---
## GraphicalObject osztály

Az absztrakt grafikus objektumot képviseli.

**Inheritance:**[`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

A GraphicalObject típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/graphicalobject/is_text_holder/) | Meghatározza, hogy a forma TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/graphicalobject/placeholder/) | Visszaadja a forma helyőrzőjét. None értéket ad, ha a formának nincs helyőrzője.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/graphicalobject/custom_data/) | Visszaadja a forma egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/graphicalobject/raw_frame/) | Visszaadja vagy beállítja a nyers forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/graphicalobject/frame/) | Visszaadja vagy beállítja a forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/graphicalobject/line_format/) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formák esetén None értéket adhat, amelyeknek nincs vonal tulajdonsága.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/graphicalobject/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a forma 3D hatás tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formák esetén None értéket adhat, amelyeknek nincs 3D tulajdonsága.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/graphicalobject/effect_format/) | Visszaadja az EffectFormat objektumot, amely a forma pixel effektusait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formák esetén None értéket adhat, amelyeknek nincs effektus tulajdonsága.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/graphicalobject/fill_format/) | Visszaadja a FillFormat objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formák esetén None értéket adhat, amelyeknek nincs kitöltés tulajdonsága.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/graphicalobject/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/graphicalobject/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egér fölé mozgatásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/graphicalobject/hyperlink_manager/) | Visszaadja a hiperhivatkozás-kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/graphicalobject/hidden/) | Meghatározza, hogy a forma rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/graphicalobject/z_order_position/) | Visszaadja a forma pozícióját a z-sorrendben.<br/>            Shapes[0] visszaadja a z-sorrend hátul lévő formáját,<br/>            a Shapes[Shapes.Count - 1] visszaadja a z-sorrend elején lévő formát.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/graphicalobject/connection_site_count/) | Visszaadja a forma csatlakozási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/graphicalobject/rotation/) | Visszaadja vagy beállítja a megadott forma Z-tengely körüli forgatási fokszámát.<br/>            A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkező irányú forgást.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/graphicalobject/x/) | Visszaadja vagy beállítja a forma bal felső sarkának x-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/graphicalobject/y/) | Visszaadja vagy beállítja a forma bal felső sarkának y-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/graphicalobject/width/) | Visszaadja vagy beállítja a forma szélességét pontban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/graphicalobject/height/) | Visszaadja vagy beállítja a forma magasságát pontban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/graphicalobject/black_white_mode/) | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/graphicalobject/unique_id/) | Visszaad egy belső, prezentációra korlátozódó azonosítót, amelyet kiegészítők vagy egyéb kódok használhatnak.<br/>            Mivel ezt az értéket a felhasználó vagy programozottan újra lehet osztani, nem szabad úgy kezelni, mint egy állandó egyedi kulcsot.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/graphicalobject/office_interop_shape_id/) | Visszaad egy diára korlátozódó egyedi azonosítót, amely a forma élettartama alatt változatlan marad, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy a dokumentum bármely pontjáról megbízhatóan hivatkozzon a formára.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/graphicalobject/alternative_text/) | Visszaadja vagy beállítja a formához kapcsolódó alternatív szöveget.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/graphicalobject/alternative_text_title/) | Visszaadja vagy beállítja a formához kapcsolódó alternatív szöveg címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/graphicalobject/name/) | Visszaadja vagy beállítja a forma nevét.<br/>            Nem lehet None. Szükség esetén használjon üres karakterláncot.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/graphicalobject/is_decorative/) | Visszaadja vagy beállítja a „Megjelölés díszítő elemként” beállítást.<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/graphicalobject/shape_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/graphicalobject/is_grouped/) | Meghatározza, hogy a forma csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/graphicalobject/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Egyébként None értéket ad.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/graphicalobject/slide/) | Visszaadja a forma szülő diáját.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/graphicalobject/presentation/) | Visszaadja a dia szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hu/aspose.slides/graphicalobject/graphical_object_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/graphicalobject/get_image/#) | Visszaadja a forma bélyegképét.<br/>            A ShapeThumbnailBounds.Shape forma bélyegkép határoló típusa alapértelmezés szerint használatos. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | Visszaadja a forma bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | A Shape tartalmát SVG fájlként menti. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | A Shape tartalmát SVG fájlként menti. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/graphicalobject/remove_placeholder/#) | Meghatározza, hogy ez a forma nem helyőrző. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | Új helyőrzőt ad hozzá, ha nincs, és a megadott helyőrző tulajdonságait beállítja. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/graphicalobject/get_base_placeholder/#) | Visszaad egy alap helyőrző formát (a layout és/vagy mester diáról származó formát, amelyből a jelenlegi forma örökölt).<br/>            None értéket ad, ha a jelenlegi forma nem örökölt. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/graphicalobject/get_visual_bounds/#) | A forme vizuális határolóit adja vissza, amely a renderelt tartalomból számítódik. |

### Lásd még
* osztály [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)