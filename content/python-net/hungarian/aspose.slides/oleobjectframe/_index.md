---
title: OleObjectFrame class
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/oleobjectframe/
---
## OleObjectFrame osztály

Egy OLE objektumot képvisel a dián.

**Inheritance:**[`OleObjectFrame`](/slides/python-net/hu/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

Az OleObjectFrame típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/oleobjectframe/is_text_holder/) | Meghatározza, hogy a forma TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/oleobjectframe/placeholder/) | Visszaadja a forma helyőrzőjét. Ha a formának nincs helyőrzője, None-t ad vissza.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/oleobjectframe/custom_data/) | Visszaadja a forma egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/oleobjectframe/raw_frame/) | Visszaadja vagy beállítja a nyers forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/oleobjectframe/frame/) | Visszaadja vagy beállítja a forma keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/oleobjectframe/line_format/) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formák esetén visszaadhat None-ot, amelyeknek nincs vonal tulajdonsága.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/oleobjectframe/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a forma 3D effektus tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formák esetén visszaadhat None-ot, amelyeknek nincs 3D tulajdonsága.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/oleobjectframe/effect_format/) | Visszaadja az EffectFormat objektumot, amely a forma pixel effektusait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formák esetén visszaadhat None-ot, amelyeknek nincs effektus tulajdonsága.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/oleobjectframe/fill_format/) | Visszaadja a FillFormat objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos típusú formák esetén visszaadhat None-ot, amelyeknek nincs kitöltési tulajdonsága.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/oleobjectframe/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egérmutató fölé húzásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/oleobjectframe/hyperlink_manager/) | Visszaadja a hiperhivatkozás-kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/oleobjectframe/hidden/) | Meghatározza, hogy a forma rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/oleobjectframe/z_order_position/) | Visszaadja egy forma z-sorrendben betöltött pozícióját.<br/>            Shapes[0] a z-sorrend hátsó részén lévő formát adja vissza,<br/>            a Shapes[Shapes.Count - 1] a z-sorrend első részén lévő formát adja vissza.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/oleobjectframe/connection_site_count/) | Visszaadja a forma csatlakozási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/oleobjectframe/rotation/) | Visszaadja vagy beállítja a megadott forma Z tengely körüli elforgatási fokszámát.<br/>            A pozitív érték óramutató járásával megegyező forgást jelez; a negatív érték<br/>            az óramutatóval ellentétes forgást.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/oleobjectframe/x/) | Lekérdezi vagy beállítja a forma bal felső sarkának x koordinátáját pontokban.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/oleobjectframe/y/) | Lekérdezi vagy beállítja a forma bal felső sarkának y koordinátáját pontokban.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/oleobjectframe/width/) | Lekérdezi vagy beállítja a forma szélességét pontokban.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/oleobjectframe/height/) | Lekérdezi vagy beállítja a forma magasságát pontokban.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/oleobjectframe/black_white_mode/) | Ez a tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/oleobjectframe/unique_id/) | Visszaad egy belső, prezentációra korlátozódó azonosítót, amelyet kiegészítők vagy egyéb kód használhat.<br/>            Mivel ezt az értéket a felhasználó vagy programozott módon is újra lehet osztani, nem szabad állandó egyedi kulcsként kezelni.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/oleobjectframe/office_interop_shape_id/) | Visszaad egy diára korlátozódó egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéből.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/oleobjectframe/alternative_text/) | Visszaadja vagy beállítja a forma alternatív szövegét.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/oleobjectframe/alternative_text_title/) | Visszaadja vagy beállítja a forma alternatív szövegének címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/oleobjectframe/name/) | Visszaadja vagy beállítja egy forma nevét.<br/>            Nem lehet None. Ha szükséges, használjon üres karakterláncot.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/oleobjectframe/is_decorative/) | Lekérdezi vagy beállítja a 'Megjelölés dekoratívként' opciót<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/oleobjectframe/shape_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/oleobjectframe/is_grouped/) | Meghatározza, hogy a forma csoportosítva van-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/oleobjectframe/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosítva van. Ellenkező esetben None-t ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/oleobjectframe/slide/) | Visszaadja a forma szülő diáit.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/oleobjectframe/presentation/) | Visszaadja a diák szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hu/aspose.slides/oleobjectframe/graphical_object_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/hu/aspose.slides/oleobjectframe/substitute_picture_format/) | Visszaadja az OleObject kép kitöltés tulajdonságok objektumát.<br/>            Csak olvasható [`IPictureFillFormat`](/slides/python-net/hu/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/hu/aspose.slides/oleobjectframe/substitute_picture_title/) | Visszaadja vagy beállítja az OleObject ikon címét.<br/>            Olvasás/írás **str**. |
| [`object_name`](/slides/python-net/hu/aspose.slides/oleobjectframe/object_name/) | Visszaadja vagy beállítja egy objektum nevét.<br/>            Olvasás/írás **str**. |
| [`object_prog_id`](/slides/python-net/hu/aspose.slides/oleobjectframe/object_prog_id/) | Visszaadja egy objektum ProgID-jét.<br/>            Csak olvasható **str**. |
| [`link_file_name`](/slides/python-net/hu/aspose.slides/oleobjectframe/link_file_name/) | Visszaadja a hivatkozott fájl teljes útvonalát. Rövid fájlnevet használ.<br/>            Csak olvasható **str**. |
| [`link_path_long`](/slides/python-net/hu/aspose.slides/oleobjectframe/link_path_long/) | Visszaadja a hivatkozott fájl teljes útvonalát. Hosszú fájlnevet használ.<br/>            Olvasás/írás **str**. |
| [`link_path_relative`](/slides/python-net/hu/aspose.slides/oleobjectframe/link_path_relative/) | Visszaadja a hivatkozott fájl relatív útvonalát, ha létezik, ellenkező esetben üres karakterláncot ad vissza.<br/>            Csak olvasható **str**. |
| [`embedded_file_label`](/slides/python-net/hu/aspose.slides/oleobjectframe/embedded_file_label/) | Visszaadja a beágyazott OLE objektum fájlnevét |
| [`embedded_file_name`](/slides/python-net/hu/aspose.slides/oleobjectframe/embedded_file_name/) | Visszaadja a beágyazott OLE objektum elérési útját |
| [`embedded_data`](/slides/python-net/hu/aspose.slides/oleobjectframe/embedded_data/) | Lekérdezi vagy beállítja az OLE beágyazott adatokra vonatkozó információkat.<br/>            Olvasás/írás [`IOleEmbeddedDataInfo`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/hu/aspose.slides/oleobjectframe/is_object_icon/) | Meghatározza, hogy egy objektum ikonként látható-e.<br/>            Olvasás/írás **bool**. |
| [`is_object_link`](/slides/python-net/hu/aspose.slides/oleobjectframe/is_object_link/) | Meghatározza, hogy egy objektum külső fájlra hivatkozik-e.<br/>            Csak olvasható **bool**. |
| [`update_automatic`](/slides/python-net/hu/aspose.slides/oleobjectframe/update_automatic/) | Meghatározza, hogy a csatolt beágyazott objektum automatikusan frissül-e, amikor a prezentáció megnyílik vagy nyomtatásra kerül.<br/>            Olvasás/írás **bool**. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/oleobjectframe/get_image/#) | Visszaadja a forma bélyegképét.<br/>            Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma bélyegkép határ típusa használatos. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Visszaadja a forma bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | A forma tartalmát SVG fájlként menti. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | A forma tartalmát SVG fájlként menti. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/oleobjectframe/remove_placeholder/#) | Meghatározza, hogy ez a forma nem helyőrző. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Új helyőrzőt ad hozzá, ha nincs, és a megadott helyőrző tulajdonságait beállítja. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/oleobjectframe/get_base_placeholder/#) | Visszaad egy alap helyőrző formát (a jelenlegi formát fölöttes elrendezésből és/vagy mester diákról örökölt formát).<br/>            Ha a jelenlegi forma nem örököl, None-t ad vissza. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/oleobjectframe/get_visual_bounds/#) | Lekéri a forma vizuális határait, amelyeket a megjelenített tartalom alapján számít. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/hu/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Beállítja az OLE beágyazott adatokra vonatkozó információkat.<br/>            <br/>            Ez a metódus módosítja az objektum tulajdonságait az új adatok tükrözésére és <br/>            az IsObjectLink zászlót false-ra állítja, jelezve, hogy az OLE objektum beágyazott. |

### Lásd még
* osztály [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* osztály [`OleObjectFrame`](/slides/python-net/hu/aspose.slides/oleobjectframe)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)