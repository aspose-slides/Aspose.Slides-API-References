---
title: ZoomFrame class
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/zoomframe/
---
## ZoomFrame osztály

Egy dián lévő Slide Zoom objektumot képvisel.

**Inheritance:**[`ZoomFrame`](/slides/python-net/hu/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/hu/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

A ZoomFrame típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/zoomframe/is_text_holder/) | Megállapítja, hogy a forma TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides/zoomframe/placeholder/) | Visszaadja a forma helyfoglalóját. Ha a formának nincs helyfoglalója, None-t ad vissza.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/zoomframe/custom_data/) | Visszaadja a forma egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/zoomframe/raw_frame/) | Visszaadja vagy beállítja a nyers forma keret tulajdonságait.<br/>            Olvasható/írható [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides/zoomframe/frame/) | Visszaadja vagy beállítja a forma keret tulajdonságait.<br/>            Olvasható/írható [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides/zoomframe/line_format/) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos olyan formák esetén, amelyeknek nincs vonal tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/zoomframe/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a forma 3D hatás tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos olyan formák esetén, amelyeknek nincs 3D tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/zoomframe/effect_format/) | Visszaadja az EffectFormat objektumot, amely a formára alkalmazott pixel-effekteket tartalmazza.<br/>            Megjegyzés: bizonyos olyan formák esetén, amelyeknek nincs effekt tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/zoomframe/fill_format/) | Visszaadja a FillFormat objektumot, amely a forma kitöltésformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos olyan formák esetén, amelyeknek nincs kitöltési tulajdonsága, None-t adhat vissza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/zoomframe/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasható/írható [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/zoomframe/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egérmutató felett definiált hiperhivatkozást.<br/>            Olvasható/írható [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/zoomframe/hyperlink_manager/) | Visszaadja a hiperhivatkozás-kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides/zoomframe/hidden/) | Megállapítja, hogy a forma rejtett-e.<br/>            Olvasható/írható **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/zoomframe/z_order_position/) | Visszaadja a forma z-sorrendben elfoglalt pozícióját.<br/>            A Shapes[0] a z-sorrend hátsó végén lévő formát adja vissza,<br/>            a Shapes[Shapes.Count - 1] pedig az elülső végén lévőt.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/zoomframe/connection_site_count/) | Visszaadja a forma csatlakozási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides/zoomframe/rotation/) | Visszaadja vagy beállítja, hogy a megadott forma hány fokkal van elfordítva a z-tengely körül. A pozitív érték óramutató-járású forgást jelent, a negatív érték pedig az ellenkező irányt.<br/>            Olvasható/írható **float**. |
| [`x`](/slides/python-net/hu/aspose.slides/zoomframe/x/) | Visszaadja vagy beállítja a forma bal-felső sarkának x-koordinátáját pontban mérve.<br/>            Olvasható/írható **float**. |
| [`y`](/slides/python-net/hu/aspose.slides/zoomframe/y/) | Visszaadja vagy beállítja a forma bal-felső sarkának y-koordinátáját pontban mérve.<br/>            Olvasható/írható **float**. |
| [`width`](/slides/python-net/hu/aspose.slides/zoomframe/width/) | Visszaadja vagy beállítja a forma szélességét pontban mérve.<br/>            Olvasható/írható **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/zoomframe/height/) | Visszaadja vagy beállítja a forma magasságát pontban mérve.<br/>            Olvasható/írható **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/zoomframe/black_white_mode/) | A tulajdonság meghatározza, hogy a forma hogyan jelenik meg fekete-fehér megjelenítési módban.<br/>            Olvasható/írható [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides/zoomframe/unique_id/) | Visszaad egy belső, a bemutatóra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat.<br/>            Mivel a felhasználó vagy a program módosíthatja ezt az értéket, nem tekinthető tartós egyedi kulcsnak.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/zoomframe/office_interop_shape_id/) | Visszaad egy diára korlátozott egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéről.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/zoomframe/alternative_text/) | Visszaadja vagy beállítja a forma alternatív szövegét.<br/>            Olvasható/írható **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/zoomframe/alternative_text_title/) | Visszaadja vagy beállítja a forma alternatív szövegének címét.<br/>            Olvasható/írható **str**. |
| [`name`](/slides/python-net/hu/aspose.slides/zoomframe/name/) | Visszaadja vagy beállítja a forma nevét.<br/>            Nem lehet None. Szükség esetén üres karakterlánc használható.<br/>            Olvasható/írható **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/zoomframe/is_decorative/) | Beállítja a „Megjelölés dekoratívként” opciót<br/>            Olvasható/írható **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/zoomframe/shape_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/zoomframe/is_grouped/) | Megállapítja, hogy a forma csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides/zoomframe/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Egyébként None-t ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides/zoomframe/slide/) | Visszaadja a forma szülő diát.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/zoomframe/presentation/) | Visszaadja a dia szülő bemutatóját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hu/aspose.slides/zoomframe/graphical_object_lock/) | Visszaadja a forma zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/hu/aspose.slides/zoomframe/image_type/) | Beállítja a zoom objektum képtípusát.<br/>            Olvasható/írható [`ZoomImageType`](/slides/python-net/hu/aspose.slides/zoomimagetype).<br/>            Alapértelmezett: Preview |
| [`return_to_parent`](/slides/python-net/hu/aspose.slides/zoomframe/return_to_parent/) | Beállítja a diavetítésben a navigáció viselkedését.<br/>            Olvasható/írható **bool**.<br/>            Alapértelmezett: false |
| [`show_background`](/slides/python-net/hu/aspose.slides/zoomframe/show_background/) | Beállítja, hogy a Zoom a cél dia hátterét használja-e.<br/>            Olvasható/írható **bool**.<br/>            Alapértelmezett: true |
| [`zoom_image`](/slides/python-net/hu/aspose.slides/zoomframe/zoom_image/) | Beállítja a zoom objektum képét.<br/>            Olvasható/írható [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/hu/aspose.slides/zoomframe/transition_duration/) | Beállítja a Zoom és a dia közötti átmenet időtartamát.<br/>            Olvasható/írható **float**.<br/>            Alapértelmezett: 1.0f |
| [`target_slide`](/slides/python-net/hu/aspose.slides/zoomframe/target_slide/) | Beállítja azt a diaobjektumot, amelyre a Slide Zoom objektum hivatkozik.<br/>            Olvasható/írható [`ISlide`](/slides/python-net/hu/aspose.slides/islide). |

## Metódusok

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/zoomframe/get_image/#) | Visszaadja a forma miniatűrjét.<br/>            Alapértelmezésben a ShapeThumbnailBounds.Shape forma miniatűr keret típust használja. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | Visszaadja a forma miniatűrjét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | Elmenti a Shape tartalmát SVG fájlként. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Elmenti a Shape tartalmát SVG fájlként. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/zoomframe/remove_placeholder/#) | Meghatározza, hogy ez a forma nem helyfoglaló. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | Új helyfoglalót ad hozzá, ha nincs, és a megadott helyfoglaló tulajdonságait állítja be. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/zoomframe/get_base_placeholder/#) | Visszaad egy alaphelyfoglaló formát (a layoutból és/vagy a fődiáról származó formát, amelyből a jelenlegi forma örököl).<br/>            Ha a jelenlegi forma nem örökölt, None-t ad vissza. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides/zoomframe/get_visual_bounds/#) | A forma megjelenített tartalma alapján számított vizuális keretet adja vissza. |

### Lásd még
* class [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* class [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* class [`ZoomFrame`](/slides/python-net/hu/aspose.slides/zoomframe)
* class [`ZoomObject`](/slides/python-net/hu/aspose.slides/zoomobject)
* module [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)