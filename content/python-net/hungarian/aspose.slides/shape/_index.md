---
title: Shape class
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/shape/
---
## Shape osztály

A dián lévő formát képviseli.

A Shape típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/shape/is_text_holder/) | Megállapítja, hogy a forma TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/shape/placeholder/) | Visszaadja a forma helyőrzőjét. None-t ad vissza, ha a formának nincs helyőrzője.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/shape/custom_data/) | Visszaadja a forma egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/shape/raw_frame/) | Visszaadja vagy beállítja a nyers forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/shape/frame/) | Visszaadja vagy beállítja a forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/shape/line_format/) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, vonallal nem rendelkező formák esetén None-t adhat vissza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/shape/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a forma 3D-effektus tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, 3D-tulajdonsággal nem rendelkező formák esetén None-t adhat vissza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/shape/effect_format/) | Visszaadja az EffectFormat objektumot, amely a forma pixel-effektusait tartalmazza.<br/>            Megjegyzés: bizonyos, hatással nem rendelkező formák esetén None-t adhat vissza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/shape/fill_format/) | Visszaadja a FillFormat objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, kitöltéssel nem rendelkező formák esetén None-t adhat vissza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/shape/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/shape/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egérmutatásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/shape/hyperlink_manager/) | Visszaadja a hiperhivatkozás-kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/shape/hidden/) | Megállapítja, hogy a forma rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/shape/z_order_position/) | Visszaadja a forma pozícióját a z-sorrendben.<br/>            Shapes[0] a z-sorrend hátulját, a Shapes[Shapes.Count - 1] az előtétjét adja vissza.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/shape/connection_site_count/) | Visszaadja a forma csatlakozási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/shape/rotation/) | Visszaadja vagy beállítja a forma z-tengely körül forgatásának fokszámát.<br/>            A pozitív érték óramutató járásával megegyező forgást, a negatív érték az ellenkezőjét jelzi.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/shape/x/) | Visszaadja vagy beállítja a forma bal-felső sarkának x-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/shape/y/) | Visszaadja vagy beállítja a forma bal-felső sarkának y-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/shape/width/) | Visszaadja vagy beállítja a forma szélességét pontban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/shape/height/) | Visszaadja vagy beállítja a forma magasságát pontban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/shape/black_white_mode/) | Tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítő módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id/) | Visszaad egy belső, prezentáció-szintű azonosítót, amelyet kiegészítők vagy egyéb kód használhat.<br/>            Mivel ezt az értéket a felhasználó vagy a program felülírhatja, nem tekinthető állandó egyedi kulcsnak.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id/) | Visszaad egy diára korlátozódó egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy a dokumentum bármely pontjáról megbízhatóan hivatkozzon a formára.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/shape/alternative_text/) | Visszaadja vagy beállítja a forma alternatív szövegét.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/shape/alternative_text_title/) | Visszaadja vagy beállítja a forma alternatív szövegének címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/shape/name/) | Visszaadja vagy beállítja a forma nevét.<br/>            Nem lehet None. Szükség esetén használjon üres karakterláncot.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/shape/is_decorative/) | Beállítja vagy lekéri a „Megjelölés díszítőelemként” opciót.<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/shape/shape_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IBaseShapeLock`](/slides/python-net/hu/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/shape/is_grouped/) | Megállapítja, hogy a forma csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/shape/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Egyébként None-t ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/shape/slide/) | Visszaadja a forma szülő diáját.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/shape/presentation/) | Visszaadja a dia szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |

## Módszerek

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/shape/get_image/#) | Visszaadja a forma bélyegképét.<br/>            Alapértelmezés szerint a ShapeThumbnailBounds.Shape típusú forma bélyegkép-határokat használja. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | Visszaadja a forma bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/shape/write_as_svg/#iorawiobase) | Elmenti a Shape tartalmát SVG fájlként. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Elmenti a Shape tartalmát SVG fájlként. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/shape/remove_placeholder/#) | Meghatározza, hogy ez a forma nem helyőrző. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/shape/add_placeholder/#iplaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait a megadottra. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/shape/get_base_placeholder/#) | Visszaad egy alap helyőrző formát (a jelenlegi formától örökölt forma a elrendezésből és/vagy a mester diából).<br/>            None-t ad vissza, ha a jelenlegi forma nem öröklődik. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/shape/get_visual_bounds/#) | Lekéri a forma vizuális határait, melyek a megjelenített tartalom alapján számolódnak. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)