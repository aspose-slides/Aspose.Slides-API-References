---
title: IShape class
second_title: Aspose.Slides Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/ishape/
---
## IShape osztály

Egy formát ábrázol egy dián.

Az IShape típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/ishape/is_text_holder/) | Meghatározza, hogy a forma TextHolder-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/ishape/placeholder/) | Visszaadja a forma helykitöltőjét.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/ishape/custom_data/) | Visszaadja a forma egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/ishape/raw_frame/) | Visszaadja vagy beállítja a nyers forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/ishape/frame/) | Visszaadja vagy beállítja a forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/ishape/line_format/) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/ishape/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a forma háromdimenziós formázási tulajdonságait tartalmazza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/ishape/effect_format/) | Visszaadja az EffectFormat objektumot, amely a forma alkalmazott pixel effektusait tartalmazza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/ishape/fill_format/) | Visszaadja a FillFormat objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/hu/aspose.slides/ishape/hidden/) | Meghatározza, hogy a forma rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/ishape/z_order_position/) | Visszaadja a forma pozícióját a z-sorrendben.<br/>            A Shapes[0] a z-sorrend hátuljában lévő formát adja vissza,<br/>            a Shapes[Shapes.Count - 1] pedig az előre lévő formát.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/ishape/connection_site_count/) | Visszaadja a forma csatlakozási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/ishape/rotation/) | Visszaadja vagy beállítja a megadott forma z-tengely körüli forgatásának fokszámát.<br/>            A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték<br/>            az óramutatóval ellentétes forgást.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/ishape/x/) | Beállítja vagy lekéri a forma bal felső sarkának x-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/ishape/y/) | Beállítja vagy lekéri a forma bal felső sarkának y-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/ishape/width/) | Beállítja vagy lekéri a forma szélességét pontban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/ishape/height/) | Beállítja vagy lekéri a forma magasságát pontban mérve.<br/>            Olvasás/írás **float**. |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/ishape/alternative_text/) | Visszaadja vagy beállítja a forma alternatív szövegét.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/ishape/alternative_text_title/) | Visszaadja vagy beállítja a forma alternatív szövegének címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/ishape/name/) | Visszaadja vagy beállítja a forma nevét.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/ishape/is_decorative/) | Beállítja vagy lekéri a 'Mark as decorative' opciót<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/ishape/shape_lock/) | Visszaadja a forma zárait.<br/>            Csak olvasható [`IBaseShapeLock`](/slides/python-net/hu/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/ishape/unique_id/) | Visszaad egy belső, bemutató-körű azonosítót, amelyet kiegészítők vagy más kód használhat.<br/>            Mivel ezt az értéket a felhasználó vagy programozottan újra lehet rendelni, nem szabad úgy kezelni,<br/>            mint egy állandó egyedi kulcsot.<br/>            Csak olvasható **int**.<br/>            Lásd még [`IShape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/ishape/office_interop_shape_id/) | Visszaad egy dián belüli egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéről.<br/>            Csak olvasható **int**.<br/>            Lásd még [`IShape.unique_id`](/slides/python-net/hu/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/ishape/is_grouped/) | Meghatározza, hogy a forma csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/ishape/black_white_mode/) | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/hu/aspose.slides/ishape/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Egyébként None-t ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/ishape/hyperlink_manager/) |  |

## Metódusok

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/ishape/get_image/#) | Visszaadja a forma bélyegképét.<br/>            Alapértelmezésként a ShapeThumbnailBounds.Shape forma bélyegkép-korlát típusa kerül használatra. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Visszaadja a forma bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/ishape/write_as_svg/#iorawiobase) | A forma tartalmát SVG fájlként menti. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | A forma tartalmát SVG fájlként menti. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/ishape/add_placeholder/#iplaceholder) | Új helykitöltőt ad hozzá, ha nincs, és beállítja a helykitöltő tulajdonságait egy megadottra. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/ishape/remove_placeholder/#) | Meghatározza, hogy ez a forma nem helykitöltő. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/ishape/get_base_placeholder/#) | Visszaad egy alap helykitöltő formát (a elrendezésből és/vagy a mester diáról származó formát, amelyből az aktuális forma örökölt).<br/>            Ha az aktuális forma nem örökölt, None-t ad vissza. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)