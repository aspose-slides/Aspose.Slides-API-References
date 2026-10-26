---
title: Ink class
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.ink/ink/
---
## Ink osztály

Egy tintát (ink) objektumot képvisel a dián.

**Öröklés:**[`Ink`](/slides/python-net/hu/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

Az Ink típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides.ink/ink/is_text_holder/) | Meghatározza, hogy a forma TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides.ink/ink/placeholder/) | Visszaadja a forma helyfoglalóját. Ha a formának nincs helyfoglalója, akkor None-t ad vissza.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides.ink/ink/custom_data/) | Visszaadja a forma egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides.ink/ink/raw_frame/) | Visszaadja vagy beállítja a nyers forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides.ink/ink/frame/) | Visszaadja vagy beállítja a forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides.ink/ink/line_format/) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formáknál, amelyeknek nincs vonal tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides.ink/ink/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a forma 3D hatástulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formáknál, amelyeknek nincs 3D tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides.ink/ink/effect_format/) | Visszaadja az EffectFormat objektumot, amely a forma pixel hatásait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formáknál, amelyeknek nincs hatástulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides.ink/ink/fill_format/) | Visszaadja a FillFormat objektumot, amely a forma kitöltésformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formáknál, amelyeknek nincs kitöltés tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides.ink/ink/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides.ink/ink/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egérmutató fölé kerülő hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides.ink/ink/hyperlink_manager/) | Visszaadja a hiperhivatkozáskezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides.ink/ink/hidden/) | Meghatározza, hogy a forma rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides.ink/ink/z_order_position/) | Visszaadja a forma pozícióját a z-rendben.<br/>            A Shapes[0] a z-rend hátsó végén lévő formát adja vissza,<br/>            a Shapes[Shapes.Count - 1] pedig a z-rend előtti végén lévő formát.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides.ink/ink/connection_site_count/) | Visszaadja a forma csatlakozási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides.ink/ink/rotation/) | Visszaadja vagy beállítja a megadott forma z-tengely körüli elforgatási fokszámát.<br/>            A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték<br/>            az óramutató járásával ellentétes forgást.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides.ink/ink/x/) | Visszaadja vagy beállítja a forma bal felső sarkának x-koordinátáját, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides.ink/ink/y/) | Visszaadja vagy beállítja a forma bal felső sarkának y-koordinátáját, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides.ink/ink/width/) | Visszaadja vagy beállítja a forma szélességét, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides.ink/ink/height/) | Visszaadja vagy beállítja a forma magasságát, pontban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides.ink/ink/black_white_mode/) | Ez a tulajdonság meghatározza, hogy a forma hogyan jelenik meg fekete-fehér megjelenítési módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides.ink/ink/unique_id/) | Visszaad egy belső, prezentáción belüli azonosítót, amelyet kiegészítők vagy más kódok használhatnak.<br/>            Mivel ezt az értéket a felhasználó vagy program szintjén újra lehet rendelni, nem szabad állandó egyedi kulcsként kezelni.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides.ink/ink/office_interop_shape_id/) | Visszaad egy dián belüli egyedi azonosítót, amely a forma teljes élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéről.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides.ink/ink/alternative_text/) | Visszaadja vagy beállítja a forma alternatív szövegét.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides.ink/ink/alternative_text_title/) | Visszaadja vagy beállítja a forma alternatív szövegének címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides.ink/ink/name/) | Visszaadja vagy beállítja a forma nevét.<br/>            Nem lehet None. Ha szükséges, használjon üres karakterláncot.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides.ink/ink/is_decorative/) | Visszaadja vagy beállítja a „Mark as decorative” opciót<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides.ink/ink/shape_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides.ink/ink/is_grouped/) | Meghatározza, hogy a forma csoportosítva van-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides.ink/ink/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosítva van. Ellenkező esetben None-t ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides.ink/ink/slide/) | Visszaadja a forma szülő diáját.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides.ink/ink/presentation/) | Visszaadja a dia szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hu/aspose.slides.ink/ink/graphical_object_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/hu/aspose.slides.ink/ink/traces/) | Visszaadja az IInk elem [`IInkTrace`](/slides/python-net/hu/aspose.slides.ink/iinktrace)-ban található összes nyomot.<br/>            Csak olvasható. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides.ink/ink/get_image/#) | Visszaadja a forma bélyegképét.<br/>            Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma bélyegkép határoló típusa használatos. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | Visszaadja a forma bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | Mentse a Shape tartalmát SVG fájlként. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Mentse a Shape tartalmát SVG fájlként. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides.ink/ink/remove_placeholder/#) | Meghatározza, hogy ez a forma nem helyfoglaló. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | Új helyfoglalót ad hozzá, ha nincs, és beállítja a helyfoglaló tulajdonságait egy megadottra. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides.ink/ink/get_base_placeholder/#) | Visszaad egy alap helyfoglaló formát (a layoutból és/vagy a mester diáról származó formát, amelyből a jelenlegi forma örököl).<br/>            Ha a jelenlegi forma nem örökölt, None-t ad vissza. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides.ink/ink/get_visual_bounds/#) | Visszaadja a forma vizuális határait, amelyeket a megjelenített tartalma alapján számítanak. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/hu/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | Regisztrál egy képet a tinta ecsetek vizuális hatásainak szimulálására használt egyéni képek gyűjteményébe.<br/>            Ezek a képek akkor kerülnek felhasználásra, amikor tinta renderelésekor konkrét [`InkEffectType`](/slides/python-net/hu/aspose.slides.ink/inkeffecttype) értékek vannak, <br/>            például Galaxy, Rainbow stb. Saját képek megadásával szabályozhatja, hogy minden tinta hatás hogyan jelenik meg. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/hu/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | Eltávolít egy képet a tinta ecsetek vizuális hatásainak szimulálására használt egyéni képek gyűjteményéből, amelyet korábban a **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide** regisztrált. |

### Lásd még
* osztály [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* osztály [`Ink`](/slides/python-net/hu/aspose.slides.ink/ink)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* modul [`aspose.slides.ink`](/slides/python-net/hu/aspose.slides.ink)
* könyvtár [`Aspose.Slides`](/slides/python-net)