---
title: SummaryZoomSection class
second_title: Aspose.Slides for Python via .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection osztály

Egy Summary Zoom szekció objektumot képvisel egy Summary Zoom keretben.

**Inheritance:**[`SummaryZoomSection`](/slides/python-net/hu/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/hu/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/hu/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

A SummaryZoomSection típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/summaryzoomsection/is_text_holder/) | Megállapítja, hogy a forma TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/summaryzoomsection/placeholder/) | Visszaadja a forma helyettesítőjét. Ha a formának nincs helyettesítője, akkor None-ot ad vissza.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/summaryzoomsection/custom_data/) | Visszaadja a forma egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/summaryzoomsection/raw_frame/) | Visszaadja vagy beállítja a nyers forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/summaryzoomsection/frame/) | Visszaadja vagy beállítja a forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/summaryzoomsection/line_format/) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos olyan formák esetén, amelyeknek nincs vonal tulajdonsága, None-ot adhat vissza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/summaryzoomsection/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a forma 3D effektus tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos formák esetén, amelyeknek nincs 3D tulajdonsága, None-ot adhat vissza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/summaryzoomsection/effect_format/) | Visszaadja az EffectFormat objektumot, amely a forma alkalmazott pixel effektjeit tartalmazza.<br/>            Megjegyzés: bizonyos olyan formák esetén, amelyeknek nincs effektus tulajdonsága, None-ot adhat vissza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/summaryzoomsection/fill_format/) | Visszaadja a FillFormat objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos formák esetén, amelyeknek nincs kitöltési tulajdonsága, None-ot adhat vissza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/summaryzoomsection/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egérmutató feletti hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/summaryzoomsection/hyperlink_manager/) | Visszaadja a hiperhivatkozás-kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/summaryzoomsection/hidden/) | Megállapítja, hogy a forma rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/summaryzoomsection/z_order_position/) | Visszaadja egy forma helyzetét a z-sorrendben.<br/>            A Shapes[0] a z-sorrend hátsó végén lévő formát adja vissza,<br/>            a Shapes[Shapes.Count - 1] pedig a z-sorrend elején lévőt.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/summaryzoomsection/connection_site_count/) | Visszaadja a forma csatlakozási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/summaryzoomsection/rotation/) | Visszaadja vagy beállítja a megadott forma z-tengely körüli elforgatási fokszámát.<br/>            A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték<br/>            az óramutató járásával ellentétes forgást.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/summaryzoomsection/x/) | Visszaadja vagy beállítja a forma bal-felső sarkának x-koordinátáját, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/summaryzoomsection/y/) | Visszaadja vagy beállítja a forma bal-felső sarkának y-koordinátáját, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/summaryzoomsection/width/) | Visszaadja vagy beállítja a forma szélességét, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/summaryzoomsection/height/) | Visszaadja vagy beállítja a forma magasságát, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/summaryzoomsection/black_white_mode/) | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/summaryzoomsection/unique_id/) | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat.<br/>            Mivel ezt az értéket a felhasználó vagy a program módosíthatja, nem szabad állandó egyedi kulcsként kezelni.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/summaryzoomsection/office_interop_shape_id/) | Visszaad egy diára korlátozott egyedi azonosítót, amely a forma életciklusa alatt állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy a dokumentum bármely pontjáról megbízhatóan hivatkozzon a formára.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/summaryzoomsection/alternative_text/) | Visszaadja vagy beállítja egy forma alternatív szövegét.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/summaryzoomsection/alternative_text_title/) | Visszaadja vagy beállítja a forma alternatív szövegének címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/summaryzoomsection/name/) | Visszaadja vagy beállítja egy forma nevét.<br/>            Nem lehet None. Szükség esetén használjon üres karakterláncot.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/summaryzoomsection/is_decorative/) | Visszaadja vagy beállítja a 'Megjelölés dekoratívként' lehetőséget<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/summaryzoomsection/shape_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/summaryzoomsection/is_grouped/) | Megállapítja, hogy a forma csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/summaryzoomsection/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Egyébként None-ot ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/summaryzoomsection/slide/) | Visszaadja a forma szülő diaját.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/summaryzoomsection/presentation/) | Visszaadja a dia szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hu/aspose.slides/summaryzoomsection/graphical_object_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/hu/aspose.slides/summaryzoomsection/image_type/) | Visszaadja vagy beállítja egy zoom objektum kép típusát.<br/>            Olvasás/írás [`ZoomImageType`](/slides/python-net/hu/aspose.slides/zoomimagetype).<br/>            Alapértelmezett érték: Preview |
| [`return_to_parent`](/slides/python-net/hu/aspose.slides/summaryzoomsection/return_to_parent/) | Visszaadja vagy beállítja a navigáció viselkedését a diavetítésben.<br/>            Olvasás/írás **bool**.<br/>            Alapértelmezett érték: false |
| [`show_background`](/slides/python-net/hu/aspose.slides/summaryzoomsection/show_background/) | Visszaadja vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom a cél dia háttérét használja-e.<br/>            Olvasás/írás **bool**.<br/>            Alapértelmezett érték: true |
| [`zoom_image`](/slides/python-net/hu/aspose.slides/summaryzoomsection/zoom_image/) | Visszaadja vagy beállítja a zoom objektum képét.<br/>            Olvasás/írás [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/hu/aspose.slides/summaryzoomsection/transition_duration/) | Visszaadja vagy beállítja a Zoom és a dia közötti átmenet időtartamát.<br/>            Olvasás/írás **float**.<br/>            Alapértelmezett érték: 1.0f |
| [`target_section`](/slides/python-net/hu/aspose.slides/summaryzoomsection/target_section/) | Visszaadja vagy beállítja azt a szakaszobjektumot, amelyhez a Section Zoom objektum kapcsolódik.<br/>            Olvasás/írás [`ISection`](/slides/python-net/hu/aspose.slides/isection). |
| [`title`](/slides/python-net/hu/aspose.slides/summaryzoomsection/title/) | Visszaadja a Summary Zoom Section objektum szöveges címét. |
| [`description`](/slides/python-net/hu/aspose.slides/summaryzoomsection/description/) | Visszaadja a Summary Zoom Section objektum szöveges leírását. |

## Módszerek

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/summaryzoomsection/get_image/#) | Visszaadja a forma bélyegképét.<br/>            Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma bélyegkép keret típust használja. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/summaryzoomsection/get_image/#shapethumbnailbounds-float-float) | Visszaadja a forma bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase) | A Shape tartalmát SVG fájlként menti. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | A Shape tartalmát SVG fájlként menti. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/summaryzoomsection/remove_placeholder/#) | Meghatározza, hogy ez a forma nem helyettesítő. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | Új helyettesítőt ad hozzá, ha nincs, és beállítja a helyettesítő tulajdonságait egy megadottra. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/summaryzoomsection/get_base_placeholder/#) | Visszaad egy alap helyettesítő formát (a layoutból és/vagy a mester diából származó formát, amelyből a jelenlegi forma örököl).<br/>            Ha a jelenlegi forma nem örököl, akkor None-ot ad vissza. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/summaryzoomsection/get_visual_bounds/#) | Visszaadja a forma vizuális határait, amelyet a megjelenített tartalom alapján számol. |

### Lásd még
* osztály [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* osztály [`SectionZoomFrame`](/slides/python-net/hu/aspose.slides/sectionzoomframe)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* osztály [`SummaryZoomSection`](/slides/python-net/hu/aspose.slides/summaryzoomsection)
* osztály [`ZoomObject`](/slides/python-net/hu/aspose.slides/zoomobject)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)