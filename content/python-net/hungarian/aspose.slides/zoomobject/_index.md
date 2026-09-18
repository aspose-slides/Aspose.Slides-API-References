---
title: ZoomObject class
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/zoomobject/
---
## ZoomObject osztály

Represents an Zoom object in a slide.

**Inheritance:**[`ZoomObject`](/slides/python-net/hu/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

The ZoomObject type exposes the following members:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/zoomobject/is_text_holder/) | Meghatározza, hogy az alakzat TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/zoomobject/placeholder/) | Visszaadja az alakzat helyőrzőjét. None-t ad vissza, ha az alakzatnak nincs helyőrzője.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/zoomobject/custom_data/) | Visszaadja az alakzat egyéni adatát.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/zoomobject/raw_frame/) | Visszaadja vagy beállítja a nyers alakzat keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/zoomobject/frame/) | Visszaadja vagy beállítja az alakzat keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/zoomobject/line_format/) | Visszaadja a LineFormat objektumot, amely vonalformázási tulajdonságokat tartalmaz egy alakzat számára.<br/>            Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs vonal tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/zoomobject/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely 3D hatástulajdonságokat tartalmaz egy alakzat számára.<br/>            Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs 3D tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/zoomobject/effect_format/) | Visszaadja az EffectFormat objektumot, amely pixel-effekteket alkalmaz egy alakzatra.<br/>            Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs effektus tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/zoomobject/fill_format/) | Visszaadja a FillFormat objektumot, amely kitöltésformázási tulajdonságokat tartalmaz egy alakzat számára.<br/>            Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs kitöltés tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/zoomobject/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/zoomobject/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egér fölé helyezésre definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/zoomobject/hyperlink_manager/) | Visszaadja a hiperhivatkozás-kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/zoomobject/hidden/) | Meghatározza, hogy az alakzat rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/zoomobject/z_order_position/) | Visszaadja egy alakzat pozícióját a z-sorrendben.<br/>            A Shapes[0] a z-sorrend hátulján lévő alakzatot adja vissza,<br/>            a Shapes[Shapes.Count - 1] a z-sorrend elején lévő alakzatot adja vissza.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/zoomobject/connection_site_count/) | Visszaadja a kapcsolati pontok számát az alakzaton.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/zoomobject/rotation/) | Visszaadja vagy beállítja a fokok számát, amellyel a megadott alakzat a z-tengely körül elfordul.<br/>            A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkező irányt.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/zoomobject/x/) | Visszaadja vagy beállítja az alakzat bal felső sarkának x-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/zoomobject/y/) | Visszaadja vagy beállítja az alakzat bal felső sarkának y-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/zoomobject/width/) | Visszaadja vagy beállítja az alakzat szélességét pontban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/zoomobject/height/) | Visszaadja vagy beállítja az alakzat magasságát pontban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/zoomobject/black_white_mode/) | Tulajdonság meghatározza, hogy az alakzat hogyan jelenik meg fekete-fehér megjelenítési módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/zoomobject/unique_id/) | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kódok használhatnak.<br/>            Mivel ezt az értéket a felhasználó vagy programkóddal felül lehet írni, nem szabad állandó egyedi kulcsként kezelni.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/zoomobject/office_interop_shape_id/) | Visszaad egy diára vonatkozó egyedi azonosítót, amely a forma életciklusa alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéről.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/zoomobject/alternative_text/) | Visszaadja vagy beállítja a forma alternatív szövegét.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/zoomobject/alternative_text_title/) | Visszaadja vagy beállítja a forma alternatív szövegének címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/zoomobject/name/) | Visszaadja vagy beállítja egy forma nevét.<br/>            Nem lehet None. Szükség esetén használjon üres karakterláncot.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/zoomobject/is_decorative/) | Visszaadja vagy beállítja a „Megjelölés dekoratívként” opciót<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/zoomobject/shape_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/zoomobject/is_grouped/) | Meghatározza, hogy az alakzat csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/zoomobject/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Egyébként None-t ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/zoomobject/slide/) | Visszaadja a forma szülő diát.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/zoomobject/presentation/) | Visszaadja a diák szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hu/aspose.slides/zoomobject/graphical_object_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/hu/aspose.slides/zoomobject/image_type/) | Visszaadja vagy beállítja egy zoom objektum kép típusát.<br/>            Olvasás/írás [`ZoomImageType`](/slides/python-net/hu/aspose.slides/zoomimagetype).<br/>            Alapértelmezett érték: Preview |
| [`return_to_parent`](/slides/python-net/hu/aspose.slides/zoomobject/return_to_parent/) | Visszaadja vagy beállítja a navigációs viselkedést a diavetítésben.<br/>            Olvasás/írás **bool**.<br/>            Alapértelmezett érték: false |
| [`show_background`](/slides/python-net/hu/aspose.slides/zoomobject/show_background/) | Visszaadja vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom a cél dia háttérét használja-e.<br/>            Olvasás/írás **bool**.<br/>            Alapértelmezett érték: true |
| [`zoom_image`](/slides/python-net/hu/aspose.slides/zoomobject/zoom_image/) | Visszaadja vagy beállítja a zoom objektum képét.<br/>            Olvasás/írás [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/hu/aspose.slides/zoomobject/transition_duration/) | Visszaadja vagy beállítja a Zoom és a dia közötti átmenet időtartamát.<br/>            Olvasás/írás **float**.<br/>            Alapértelmezett érték: 1.0f |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/zoomobject/get_image/#) | Visszaadja az alakzat bélyegképét.<br/>            A ShapeThumbnailBounds.Shape alakzat bélyegkép határ típusa van alapértelmezés szerint használva. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | Visszaadja az alakzat bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | Elmenti az alakzat tartalmát SVG fájlként. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Elmenti az alakzat tartalmát SVG fájlként. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/zoomobject/remove_placeholder/#) | Meghatározza, hogy ez az alakzat nem helyőrző. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait egy megadottra. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/zoomobject/get_base_placeholder/#) | Visszaad egy alapértelmezett helyőrző alakzatot (az elrendezésből és/vagy a mester diákról származó alakzatot, amelyből a jelenlegi alakzat örököl).<br/>            None-t ad vissza, ha a jelenlegi alakzat nem örökölt. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/zoomobject/get_visual_bounds/#) | Visszaadja az alakzat vizuális határait, amelyet a megjelenített tartalma alapján számítanak. |

### Lásd még
* osztály [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* osztály [`ZoomObject`](/slides/python-net/hu/aspose.slides/zoomobject)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)