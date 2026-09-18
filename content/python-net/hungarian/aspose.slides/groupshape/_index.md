---
title: GroupShape class
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/groupshape/
---
## GroupShape osztály

Egy dián lévő alakzatok csoportját képviseli.

**Öröklés:**[`GroupShape`](/slides/python-net/hu/aspose.slides/groupshape) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

A GroupShape típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/groupshape/is_text_holder/) | Megállapítja, hogy az alakzat TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/groupshape/placeholder/) | Visszaadja az alakzat helyőrzőjét. None értéket ad vissza, ha az alakzatnak nincs helyőrzője.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/groupshape/custom_data/) | Visszaadja az alakzat egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/groupshape/raw_frame/) | Visszaadja vagy beállítja a nyers alakzatteret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/groupshape/frame/) | Visszaadja vagy beállítja az alakzatteret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/groupshape/line_format/) | Visszaadja a LineFormat objektumot, amely a vonalformázási tulajdonságokat tartalmazza egy alakzatra.<br/>            Megjegyzés: GroupShape objektumok esetén None értéket ad vissza, mivel nincs vonal tulajdonságuk.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/groupshape/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely egy alakzat 3D effektus tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú alakzatok esetén None értéket adhat vissza, amelyeknek nincs 3D tulajdonságuk.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/groupshape/effect_format/) | Visszaadja az EffectFormat objektumot, amely egy alakzatra alkalmazott pixelhatásokat tartalmaz.<br/>            Megjegyzés: bizonyos típusú alakzatok esetén None értéket adhat vissza, amelyeknek nincs effektus tulajdonságuk.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/groupshape/fill_format/) | Visszaadja a FillFormat objektumot, amely egy alakzat kitöltési formázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú alakzatok esetén None értéket adhat vissza, amelyeknek nincs kitöltési tulajdonságuk.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/groupshape/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/groupshape/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egérmutatásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/groupshape/hyperlink_manager/) | Visszaadja a hiperhivatkozás-kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/groupshape/hidden/) | Megállapítja, hogy az alakzat rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/groupshape/z_order_position/) | Visszaadja egy alakzat z-rendben betöltött pozícióját.<br/>            A Shapes[0] a z-rend hátsó alakzatát adja vissza,<br/>            a Shapes[Shapes.Count - 1] pedig a z-rend első alakzatát.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/groupshape/connection_site_count/) | Visszaadja az alakzaton lévő csatlakozási pontok számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/groupshape/rotation/) | Visszaadja vagy beállítja a megadott alakzat z-tengely körüli forgatásának fokszámát.<br/>            A pozitív érték óramutató-járású forgást jelent; a negatív érték<br/>            ellentétes óramutató-járású forgást jelöl.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/groupshape/x/) | Visszaadja vagy beállítja az alakzat bal-felső sarkának x-koordinátáját, pontokban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/groupshape/y/) | Visszaadja vagy beállítja az alakzat bal-felső sarkának y-koordinátáját, pontokban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/groupshape/width/) | Visszaadja vagy beállítja az alakzat szélességét, pontokban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/groupshape/height/) | Visszaadja vagy beállítja az alakzat magasságát, pontokban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/groupshape/black_white_mode/) | A tulajdonság meghatározza, hogy egy alakzat hogyan jelenik meg fekete-fehér megjelenítési módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/groupshape/unique_id/) | Visszaad egy belső, prezentáció-szintű azonosítót, amelyet kiegészítők vagy más kód használhat.<br/>            Mivel ezt az értéket a felhasználó vagy programozott módon is újra lehet rendelni, nem tekinthető<br/>            állandó egyedi kulcsnak.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/groupshape/office_interop_shape_id/) | Visszaad egy diára korlátozódó egyedi azonosítót, amely a forma élettartama alatt állandó, és<br/>            lehetővé teszi a PowerPoint vagy az interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/groupshape/alternative_text/) | Visszaadja vagy beállítja az alakzathoz kapcsolódó alternatív szöveget.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/groupshape/alternative_text_title/) | Visszaadja vagy beállítja az alakzathoz kapcsolódó alternatív szöveg címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/groupshape/name/) | Visszaadja vagy beállítja egy alakzat nevét.<br/>            Nem lehet None. Szükség esetén használjon üres karakterlánc értéket.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/groupshape/is_decorative/) | Visszaadja vagy beállítja a „Dekoratívként jelölés” beállítást<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/groupshape/shape_lock/) | Visszaadja az alakzat zárolásait.<br/>            Csak olvasható [`IGroupShapeLock`](/slides/python-net/hu/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/groupshape/is_grouped/) | Megállapítja, hogy az alakzat csoportosítva van-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/groupshape/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosított. Egyébként None-t ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/groupshape/slide/) | Visszaadja egy alakzat szülő diáját.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/groupshape/presentation/) | Visszaadja egy dia szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/hu/aspose.slides/groupshape/group_shape_lock/) | Visszaadja az alakzat zárolásait.<br/>            Csak olvasható [`IGroupShapeLock`](/slides/python-net/hu/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/hu/aspose.slides/groupshape/shapes/) | Visszaadja a csoporton belüli alakzatok gyűjteményét.<br/>            Csak olvasható [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection). |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/groupshape/get_image/#) | Visszaadja az alakzat bélyegképét.<br/>            Alapértelmezés szerint a ShapeThumbnailBounds.Shape alakzat bélyegkép-határoló típust használja. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | Visszaadja az alakzat bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/groupshape/write_as_svg/#iorawiobase) | Elmenti az alakzat tartalmát SVG fájlként. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Elmenti az alakzat tartalmát SVG fájlként. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/groupshape/remove_placeholder/#) | Meghatározza, hogy ez az alakzat nem helyőrző. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/groupshape/add_placeholder/#iplaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait egy megadottra. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/groupshape/get_base_placeholder/#) | Visszaad egy alap helyőrző alakzatot (a jelenlegi alakzat származási elrendezéséből és/vagy mesterdiájából).<br/>            None értéket ad vissza, ha a jelenlegi alakzat nem származik. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/groupshape/get_visual_bounds/#) | Visszaadja az alakzat megjelenített tartalom alapján számított vizuális határait. |

### Lásd még
* osztály [`GroupShape`](/slides/python-net/hu/aspose.slides/groupshape)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)