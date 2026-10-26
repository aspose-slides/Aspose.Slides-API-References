---
title: InkActions class
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.ink/inkactions/
---
## InkActions osztály

A tintaműveletek gyökérét képviseli.

**Öröklődés:**[`InkActions`](/slides/python-net/hu/aspose.slides.ink/inkactions) → [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

Az InkActions típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides.ink/inkactions/is_text_holder/) | Megállapítja, hogy a forma TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides.ink/inkactions/placeholder/) | Visszaadja a forma helyőrzőjét. None értéket ad vissza, ha a formának nincs helyőrzője.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides.ink/inkactions/custom_data/) | Visszaadja a forma egyedi adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides.ink/inkactions/raw_frame/) | Visszaadja vagy beállítja a nyers forma keret tulajdonságait.<br/>            Olvasható/írható [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides.ink/inkactions/frame/) | Visszaadja vagy beállítja a forma keret tulajdonságait.<br/>            Olvasható/írható [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides.ink/inkactions/line_format/) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos formatípusok esetén None értéket adhat, ha nincs vonal tulajdonságuk.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides.ink/inkactions/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a forma 3D hatástulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos formatípusok esetén None értéket adhat, ha nincs 3D tulajdonságuk.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides.ink/inkactions/effect_format/) | Visszaadja az EffectFormat objektumot, amely a forma pixel effektjeit tartalmazza.<br/>            Megjegyzés: bizonyos formatípusok esetén None értéket adhat, ha nincs effektus tulajdonságuk.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides.ink/inkactions/fill_format/) | Visszaadja a FillFormat objektumot, amely a forma kitöltésformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos formatípusok esetén None értéket adhat, ha nincs kitöltés tulajdonságuk.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides.ink/inkactions/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasható/írható [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides.ink/inkactions/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egér fölé húzásra definiált hiperhivatkozást.<br/>            Olvasható/írható [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides.ink/inkactions/hyperlink_manager/) | Visszaadja a hiperhivatkozás-kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides.ink/inkactions/hidden/) | Megállapítja, hogy a forma rejtett-e.<br/>            Olvasható/írható **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides.ink/inkactions/z_order_position/) | Visszaadja a forma z-sorrendben betöltött pozícióját.<br/>            A Shapes[0] a z-sorrend hátuljában lévő formát adja vissza,<br/>            a Shapes[Shapes.Count - 1] a z-sorrend elején lévő formát adja vissza.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides.ink/inkactions/connection_site_count/) | Visszaadja a forma csatlakozási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides.ink/inkactions/rotation/) | Visszaadja vagy beállítja a megadott forma z-tengely körüli forgatási fokszámát.<br/>            A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték<br/>            az óramutató járásával ellentétes forgást.<br/>            Olvasható/írható **float**. |
| [`x`](/slides/python-net/hu/aspose.slides.ink/inkactions/x/) | Visszaadja vagy beállítja a forma bal felső sarkának x-koordinátáját pontban mérve.<br/>            Olvasható/írható **float**. |
| [`y`](/slides/python-net/hu/aspose.slides.ink/inkactions/y/) | Visszaadja vagy beállítja a forma bal felső sarkának y-koordinátáját pontban mérve.<br/>            Olvasható/írható **float**. |
| [`width`](/slides/python-net/hu/aspose.slides.ink/inkactions/width/) | Visszaadja vagy beállítja a forma szélességét pontban mérve.<br/>            Olvasható/írható **float**. |
| [`height`](/slides/python-net/hu/aspose.slides.ink/inkactions/height/) | Visszaadja vagy beállítja a forma magasságát pontban mérve.<br/>            Olvasható/írható **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides.ink/inkactions/black_white_mode/) | A tulajdonság meghatározza, hogy a forma fekete-fehér megjelenítési módban hogyan lesz renderelve.<br/>            Olvasható/írható [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides.ink/inkactions/unique_id/) | Visszaad egy belső, prezentációkörű azonosítót, amelyet kiegészítők vagy más kód használhat.<br/>            Mivel ezt az értéket a felhasználó vagy programkóddal újra lehet rendelni, nem szabad állandó egyedi kulcsként kezelni.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides.ink/inkactions/office_interop_shape_id/) | Visszaad egy diakörű egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéről.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides.ink/inkactions/alternative_text/) | Visszaadja vagy beállítja a forma alternatív szövegét.<br/>            Olvasható/írható **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides.ink/inkactions/alternative_text_title/) | Visszaadja vagy beállítja a forma alternatív szövegének címét.<br/>            Olvasható/írható **str**. |
| [`name`](/slides/python-net/hu/aspose.slides.ink/inkactions/name/) | Visszaadja vagy beállítja a forma nevét.<br/>            Nem lehet None. Szükség esetén használjon üres karakterláncot.<br/>            Olvasható/írható **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides.ink/inkactions/is_decorative/) | Visszaadja vagy beállítja a 'Megjelölés dekoratívként' opciót<br/>            Olvasható/írható **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides.ink/inkactions/shape_lock/) | Visszaadja a forma zárjait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides.ink/inkactions/is_grouped/) | Megállapítja, hogy a forma csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides.ink/inkactions/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Ellenkező esetben None értéket ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides.ink/inkactions/slide/) | Visszaadja a forma szülő diaját.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides.ink/inkactions/presentation/) | Visszaadja a dia szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hu/aspose.slides.ink/inkactions/graphical_object_lock/) | Visszaadja a forma zárjait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides.ink/inkactions/get_image/#) | Visszaadja a forma bélyegképét.<br/>            Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma bélyegkép határ típusa van használva. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides.ink/inkactions/get_image/#shapethumbnailbounds-float-float) | Visszaadja a forma bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase) | Elmenti a Forma tartalmát SVG fájlként. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Elmenti a Forma tartalmát SVG fájlként. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides.ink/inkactions/remove_placeholder/#) | Meghatározza, hogy ez a forma nem helyőrző. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides.ink/inkactions/add_placeholder/#iplaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait egy megadottra. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides.ink/inkactions/get_base_placeholder/#) | Visszaad egy alap helyőrző formát (a layoutból és/vagy a mester diából származó formát, amelyből az aktuális forma örököl).<br/>            None értéket ad vissza, ha az aktuális forma nem öröklődik. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides.ink/inkactions/get_visual_bounds/#) | Visszaadja a forma megjelenített határait, amelyeket a renderelt tartalma alapján számol. |

### Lásd még
* osztály [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* osztály [`InkActions`](/slides/python-net/hu/aspose.slides.ink/inkactions)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* modul [`aspose.slides.ink`](/slides/python-net/hu/aspose.slides.ink)
* könyvtár [`Aspose.Slides`](/slides/python-net)