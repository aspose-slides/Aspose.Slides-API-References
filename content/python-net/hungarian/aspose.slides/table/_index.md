---
title: Table class
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozásában
description: 
type: docs
url: /hu/aspose.slides/table/
---
## Table osztály

Egy dián lévő táblát reprezentál.

**Inheritance:**[`Table`](/slides/python-net/hu/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

A Table típus a következő tagokat tesz közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/table/is_text_holder/) | Megállapítja, hogy a forma TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/table/placeholder/) | Visszaadja a forma helyőrzőjét. None-t ad vissza, ha a formának nincs helyőrzője.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/table/custom_data/) | Visszaadja a forma egyedi adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/table/raw_frame/) | Visszaadja vagy beállítja a nyers forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/table/frame/) | Visszaadja vagy beállítja a forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/table/line_format/) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos olyan formák esetén, amelyeknek nincs vonal tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/table/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a forma 3D effektus tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos olyan formák esetén, amelyeknek nincs 3D tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/table/effect_format/) | Visszaadja az EffectFormat objektumot, amely a forma alkalmazott pixel effektjeit tartalmazza.<br/>            Megjegyzés: bizonyos olyan formák esetén, amelyeknek nincs effektus tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/table/fill_format/) | Visszaad egy TableFormat.FillFormat objektumot, amely a Table kitöltési formázását tartalmazza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/table/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/table/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egér fölé helyezésre definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/table/hyperlink_manager/) | Visszaadja a hiperhivatkozás-kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/table/hidden/) | Megállapítja, hogy a forma rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/table/z_order_position/) | Visszaadja egy forma z-sorrendben elfoglalt pozícióját.<br/>            A Shapes[0] a z-sorrend hátsó formáját adja vissza,<br/>            a Shapes[Shapes.Count - 1] pedig a z-sorrend első formáját adja vissza.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/table/connection_site_count/) | Visszaadja a forma csatlakozási helyeinek számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/table/rotation/) | Visszaadja vagy beállítja a megadott forma z-tengely körüli forgatási fokok számát. A pozitív érték az óramutató járásával megegyező forgatást jelzi; a negatív érték az óramutató járásával ellentétes forgatást.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/table/x/) | Visszaadja vagy beállítja a forma bal felső sarkának x koordinátáját, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/table/y/) | Visszaadja vagy beállítja a forma bal felső sarkának y koordinátáját, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/table/width/) | Visszaadja vagy beállítja a forma szélességét, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/table/height/) | Visszaadja vagy beállítja a forma magasságát, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/table/black_white_mode/) | A tulajdonság megadja, hogyan jelenik meg a forma fekete-fehér megjelenítési módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/table/unique_id/) | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat.<br/>            Mivel ezt az értéket a felhasználó vagy programozottan át lehet rendelni, nem szabad tartós egyedi kulcsként kezelni.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/table/office_interop_shape_id/) | Visszaad egy diára korlátozott egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/table/alternative_text/) | Visszaadja vagy beállítja a forma alternatív szövegét.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/table/alternative_text_title/) | Visszaadja vagy beállítja a forma alternatív szövegének címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/table/name/) | Visszaadja vagy beállítja egy forma nevét.<br/>            Nem lehet None. Szükség esetén használjon üres karakterláncot.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/table/is_decorative/) | Visszaadja vagy beállítja a 'Dekorációnak jelölés' opciót<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/table/shape_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/table/is_grouped/) | Megállapítja, hogy a forma csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/table/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Ellenkező esetben None-t ad.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/table/slide/) | Visszaadja a forma szülő diáját.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/table/presentation/) | Visszaadja a dia szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hu/aspose.slides/table/graphical_object_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/hu/aspose.slides/table/rows/) | Visszaadja a sorok gyűjteményét.<br/>            Csak olvasható [`IRowCollection`](/slides/python-net/hu/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/hu/aspose.slides/table/columns/) | Visszaadja az oszlopok gyűjteményét.<br/>            Csak olvasható [`IColumnCollection`](/slides/python-net/hu/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/hu/aspose.slides/table/table_format/) | Visszaadja a TableFormat objektumot, amely ennek a táblának a formázási tulajdonságait tartalmazza.<br/>            Csak olvasható [`ITableFormat`](/slides/python-net/hu/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/hu/aspose.slides/table/style_preset/) | Visszaadja vagy beállítja a beépített táblastílust.<br/>            Olvasás/írás [`TableStylePreset`](/slides/python-net/hu/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/hu/aspose.slides/table/right_to_left/) | Megállapítja, hogy a tábla jobbról balra olvasási sorrendet használ-e.<br/>            Olvasás/írás **bool**. |
| [`first_row`](/slides/python-net/hu/aspose.slides/table/first_row/) | Megállapítja, hogy a tábla első sorát speciális formázással kell-e megjeleníteni.<br/>            Olvasás/írás **bool**. |
| [`first_col`](/slides/python-net/hu/aspose.slides/table/first_col/) | Megállapítja, hogy a tábla első oszlopát speciális formázással kell-e megjeleníteni.<br/>            Olvasás/írás **bool**. |
| [`last_row`](/slides/python-net/hu/aspose.slides/table/last_row/) | Megállapítja, hogy a tábla utolsó sorát speciális formázással kell-e megjeleníteni.<br/>            Olvasás/írás **bool**. |
| [`last_col`](/slides/python-net/hu/aspose.slides/table/last_col/) | Megállapítja, hogy a tábla utolsó oszlopát speciális formázással kell-e megjeleníteni.<br/>            Olvasás/írás **bool**. |
| [`horizontal_banding`](/slides/python-net/hu/aspose.slides/table/horizontal_banding/) | Megállapítja, hogy a páros sorokat különböző formázással kell-e megjeleníteni.<br/>            Olvasás/írás **bool**. |
| [`vertical_banding`](/slides/python-net/hu/aspose.slides/table/vertical_banding/) | Megállapítja, hogy a páros oszlopokat különböző formázással kell-e megjeleníteni.<br/>            Olvasás/írás **bool**. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/table/get_image/#) | Visszaadja a forma bélyegképét.<br/>            Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma bélyegkép határoló típusa használatos. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Visszaadja a forma bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/table/write_as_svg/#iorawiobase) | A Shape tartalmát SVG fájlként menti. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | A Shape tartalmát SVG fájlként menti. |
| [`set_text_format(self, source)`](/slides/python-net/hu/aspose.slides/table/set_text_format/#iportionformat) | Beállítja a meghatározott portion formátum tulajdonságait az összes táblacellához tartozó részekre. |
| [`set_text_format(self, source)`](/slides/python-net/hu/aspose.slides/table/set_text_format/#iparagraphformat) | Beállítja a meghatározott bekezdésformátum tulajdonságait az összes táblacellához tartozó bekezdésekre. |
| [`set_text_format(self, source)`](/slides/python-net/hu/aspose.slides/table/set_text_format/#itextframeformat) | Beállítja a meghatározott szövegkeret formátum tulajdonságait az összes táblacellához tartozó szövegkeretekre. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/table/remove_placeholder/#) | Megadja, hogy ez a forma nem helyőrző. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/table/add_placeholder/#iplaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait egy megadottra. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/table/get_base_placeholder/#) | Visszaad egy alap helyőrző formát (a layoutból és/vagy mester diából származó formát, amelyből az aktuális forma örököl).<br/>            None-t ad vissza, ha az aktuális forma nem örökölt. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/table/get_visual_bounds/#) | Visszaadja a forma vizuális határait, amelyet a renderelt tartalma alapján számítanak. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/hu/aspose.slides/table/merge_cells/#icell-icell-bool) | Összevonja a szomszédos cellákat. |

### Lásd még
* osztály [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* osztály [`Table`](/slides/python-net/hu/aspose.slides/table)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)