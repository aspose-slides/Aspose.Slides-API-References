---
title: Chart class
second_title: Aspose.Slides a Python-hoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chart/
---
## Chart osztály

Egy grafikus diagramot jelenít meg egy dián.

**Inheritance:**[`Chart`](/slides/python-net/hu/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/hu/aspose.slides/shape)

A Chart típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides.charts/chart/is_text_holder/) | Meghatározza, hogy a shape TextHolder_PPT-e.<br/>            Csak olvasható **bool**. |
| [`placeholder`](/slides/python-net/hu/aspose.slides.charts/chart/placeholder/) | Visszaadja a shape helyőrzőjét. None-t ad vissza, ha a shape-nek nincs helyőrzője.<br/>            Csak olvasható [`IPlaceholder`](/slides/python-net/hu/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/hu/aspose.slides.charts/chart/custom_data/) | Visszaadja a shape egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/hu/aspose.slides.charts/chart/raw_frame/) | Visszaadja vagy beállítja a nyers shape keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/hu/aspose.slides.charts/chart/frame/) | Visszaadja vagy beállítja a shape keret tulajdonságait.<br/>            Olvasás/írás [`IShapeFrame`](/slides/python-net/hu/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/hu/aspose.slides.charts/chart/line_format/) | Visszaadja a LineFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, vonal tulajdonságokkal nem rendelkező shape-ek esetén None-t adhat vissza.<br/>            Csak olvasható [`ILineFormat`](/slides/python-net/hu/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/hu/aspose.slides.charts/chart/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a shape 3D hatásának tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, 3D tulajdonságokkal nem rendelkező shape-ek esetén None-t adhat vissza.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/hu/aspose.slides.charts/chart/effect_format/) | Visszaadja az EffectFormat objektumot, amely a shape-re alkalmazott pixelhatásokat tartalmazza.<br/>            Megjegyzés: bizonyos, effekt tulajdonságokkal nem rendelkező shape-ek esetén None-t adhat vissza.<br/>            Csak olvasható [`IEffectFormat`](/slides/python-net/hu/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/hu/aspose.slides.charts/chart/fill_format/) | Visszaadja a FillFormat objektumot, amely a shape kitöltésének formázási tulajdonságait tartalmazza.<br/>            Megjegyzés: bizonyos, kitöltési tulajdonságokkal nem rendelkező shape-ek esetén None-t adhat vissza.<br/>            Csak olvasható [`IFillFormat`](/slides/python-net/hu/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides.charts/chart/hyperlink_click/) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides.charts/chart/hyperlink_mouse_over/) | Visszaadja vagy beállítja az egérmutatásra definiált hiperhivatkozást.<br/>            Olvasás/írás [`IHyperlink`](/slides/python-net/hu/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides.charts/chart/hyperlink_manager/) | Visszaadja a hiperhivatkozás kezelőt.<br/>            Csak olvasható [`IHyperlinkManager`](/slides/python-net/hu/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/hu/aspose.slides.charts/chart/hidden/) | Meghatározza, hogy a shape rejtett-e.<br/>            Olvasás/írás **bool**. |
| [`z_order_position`](/slides/python-net/hu/aspose.slides.charts/chart/z_order_position/) | Visszaadja a shape pozícióját a z-sorrendben.<br/>            A Shapes[0] a z-sorrend hátuljában lévő shape-et adja vissza,<br/>            és a Shapes[Shapes.Count - 1] a z-sorrend elöl lévő shape-et adja vissza.<br/>            Csak olvasható **int**. |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides.charts/chart/connection_site_count/) | Visszaadja a shape csatlakozási pontjainak számát.<br/>            Csak olvasható **int**. |
| [`rotation`](/slides/python-net/hu/aspose.slides.charts/chart/rotation/) | Visszaadja vagy beállítja a megadott shape z-tengely körüli forgatásának fokszámát.<br/>            A pozitív érték az óramutató járásával megegyező forgatást jelzi; a negatív érték az ellenkező irányt.<br/>            Olvasás/írás **float**. |
| [`x`](/slides/python-net/hu/aspose.slides.charts/chart/x/) | Visszaadja vagy beállítja a shape bal felső sarkának x-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides.charts/chart/y/) | Visszaadja vagy beállítja a shape bal felső sarkának y-koordinátáját pontban mérve.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides.charts/chart/width/) | Visszaadja vagy beállítja a shape szélességét pontban mérve.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides.charts/chart/height/) | Visszaadja vagy beállítja a shape magasságát pontban mérve.<br/>            Olvasás/írás **float**. |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides.charts/chart/black_white_mode/) | A property meghatározza, hogyan jelenik meg a shape fekete-fehér megjelenítési módban.<br/>            Olvasás/írás [`BlackWhiteMode`](/slides/python-net/hu/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/hu/aspose.slides.charts/chart/unique_id/) | Visszaad egy belső, prezentációkörű azonosítót, amelyet kiegészítők vagy más kód használhat.<br/>            Mivel ezt az értéket a felhasználó vagy programozottan is újra lehet rendelni, nem tekinthető állandó egyedi kulcsnak.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.office_interop_shape_id`](/slides/python-net/hu/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides.charts/chart/office_interop_shape_id/) | Visszaad egy diakörű egyedi azonosítót, amely a shape élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy interop kód megbízhatóan hivatkozzon rá a dokumentum bármely részéről.<br/>            Csak olvasható **int**.<br/>            Lásd még [`Shape.unique_id`](/slides/python-net/hu/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/hu/aspose.slides.charts/chart/alternative_text/) | Visszaadja vagy beállítja a shape-hez tartozó alternatív szöveget.<br/>            Olvasás/írás **str**. |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides.charts/chart/alternative_text_title/) | Visszaadja vagy beállítja a shape-hez tartozó alternatív szöveg címét.<br/>            Olvasás/írás **str**. |
| [`name`](/slides/python-net/hu/aspose.slides.charts/chart/name/) | Visszaadja vagy beállítja a shape nevét.<br/>            Nem lehet None. Szükség esetén használjon üres karakterláncot.<br/>            Olvasás/írás **str**. |
| [`is_decorative`](/slides/python-net/hu/aspose.slides.charts/chart/is_decorative/) | Beállítja a „Mark as decorative” (díszítőként jelöl) opciót<br/>            Olvasás/írás **bool**. |
| [`shape_lock`](/slides/python-net/hu/aspose.slides.charts/chart/shape_lock/) | Visszaadja a shape zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/hu/aspose.slides.charts/chart/is_grouped/) | Meghatározza, hogy a shape csoportosított-e.<br/>            Csak olvasható **bool**. |
| [`parent_group`](/slides/python-net/hu/aspose.slides.charts/chart/parent_group/) | Visszaadja a szülő GroupShape objektumot, ha a shape csoportosított. Egyébként None-t ad vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/hu/aspose.slides.charts/chart/slide/) | Visszaadja a shape szülő diát.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides.charts/chart/presentation/) | Visszaadja a slide szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/hu/aspose.slides.charts/chart/graphical_object_lock/) | Visszaadja a shape zárolásait.<br/>            Csak olvasható [`IGraphicalObjectLock`](/slides/python-net/hu/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/hu/aspose.slides.charts/chart/plot_visible_cells_only/) | Meghatározza, hogy csak a látható cellák legyenek ábrázolva. Hamis érték esetén a látható és a rejtett cellák egyaránt megjelennek.<br/>            Olvasás/írás **bool**. |
| [`display_blanks_as`](/slides/python-net/hu/aspose.slides.charts/chart/display_blanks_as/) | Visszaadja vagy beállítja a diagram üres celláinak ábrázolási módját.<br/>            Olvasás/írás [`DisplayBlanksAsType`](/slides/python-net/hu/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/hu/aspose.slides.charts/chart/chart_data/) | Visszaad információt a diagramhoz kapcsolódó linkelt vagy beágyazott adatról.<br/>            Csak olvasható [`IChartData`](/slides/python-net/hu/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/hu/aspose.slides.charts/chart/has_title/) | Meghatározza, hogy a diagramnak legyen látható címe.<br/>            Olvasás/írás **bool**. |
| [`chart_title`](/slides/python-net/hu/aspose.slides.charts/chart/chart_title/) | Visszaadja vagy beállítja a diagram címét.<br/>            Csak olvasható [`IChartTitle`](/slides/python-net/hu/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/hu/aspose.slides.charts/chart/has_data_table/) | Meghatározza, hogy a diagramnak legyen adat táblája.<br/>            Olvasás/írás **bool**. |
| [`has_legend`](/slides/python-net/hu/aspose.slides.charts/chart/has_legend/) | Meghatározza, hogy a diagramnak legyen jelmagyarázata.<br/>            Olvasás/írás **bool**. |
| [`legend`](/slides/python-net/hu/aspose.slides.charts/chart/legend/) | Visszaadja vagy beállítja a diagram jelmagyarázatát.<br/>            Csak olvasható [`ILegend`](/slides/python-net/hu/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/hu/aspose.slides.charts/chart/chart_data_table/) | Visszaadja a diagram adat tábláját.<br/>            Csak olvasható [`IDataTable`](/slides/python-net/hu/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/hu/aspose.slides.charts/chart/style/) | Visszaadja vagy beállítja a diagram stílusát.<br/>            Olvasás/írás [`StyleType`](/slides/python-net/hu/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/hu/aspose.slides.charts/chart/type/) | Visszaadja vagy beállítja a diagram típusát.<br/>            Olvasás/írás [`ChartType`](/slides/python-net/hu/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/hu/aspose.slides.charts/chart/plot_area/) | A diagram ábrázoló területét reprezentálja.<br/>            Csak olvasható [`IChartPlotArea`](/slides/python-net/hu/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/hu/aspose.slides.charts/chart/rotation_3d/) | Visszaad egy 3D forgatást a diagramhoz.<br/>            Csak olvasható [`IRotation3D`](/slides/python-net/hu/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/hu/aspose.slides.charts/chart/back_wall/) | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram háttérfalának formázását.<br/>            Csak olvasható [`IChartWall`](/slides/python-net/hu/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/hu/aspose.slides.charts/chart/side_wall/) | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram oldalfalának formázását.<br/>            Csak olvasható [`IChartWall`](/slides/python-net/hu/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/hu/aspose.slides.charts/chart/floor/) | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram padlójának formázását.<br/>            Csak olvasható [`IChartWall`](/slides/python-net/hu/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/hu/aspose.slides.charts/chart/text_format/) | Visszaadja a diagram szövegformátumát.<br/>            A property nem alkalmazható a következő típusokra: [`ChartType.TREEMAP`](/slides/python-net/hu/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/hu/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/hu/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/hu/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/hu/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/hu/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Csak olvasható [`IChartTextFormat`](/slides/python-net/hu/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/hu/aspose.slides.charts/chart/theme_manager/) | Visszaadja a témakezelőt.<br/>            Csak olvasható [`IOverrideThemeManager`](/slides/python-net/hu/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/hu/aspose.slides.charts/chart/user_shapes/) | Megadja a diagramra rajzolt shape-eket.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/hu/aspose.slides.charts/chart/axes/) | Hozzáférést biztosít a diagram tengelyeihez.<br/>            Csak olvasható [`IAxesManager`](/slides/python-net/hu/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/hu/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Meghatározza, hogy a diagramon a legnagyobb adatcímkék megjelenjenek-e.<br/>            Olvasás/írás **bool**. |
| [`has_rounded_corners`](/slides/python-net/hu/aspose.slides.charts/chart/has_rounded_corners/) | Meghatározza, hogy a diagram területe legyen-e lekerekített sarkú.<br/>            Olvasás/írás **bool**. |
| [`chart`](/slides/python-net/hu/aspose.slides.charts/chart/chart/) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides.charts/chart/get_image/#) | Visszaadja a shape bélyegképét.<br/>            A ShapeThumbnailBounds.Shape shape bélyegkép határ típusa alapértelmezés szerint használható. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Visszaadja a shape bélyegképét. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | A Shape tartalmát SVG fájlként menti. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | A Shape tartalmát SVG fájlként menti. |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides.charts/chart/remove_placeholder/#) | Meghatározza, hogy ez a shape nem helyőrző. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait egy megadottra. |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides.charts/chart/get_base_placeholder/#) | Visszaad egy alap helyőrző shape-et (a layoutból és/vagy a fő diáról származó shape, amelyből a jelenlegi shape öröklődik).<br/>            None-t ad vissza, ha a jelenlegi shape nem öröklődik. |
| [`get_visual_bounds(self)`](/slides/python-net/hu/aspose.slides.charts/chart/get_visual_bounds/#) | Lekéri a shape vizuális határait, amely a megjelenített tartalomból számított. |
| [`validate_chart_layout(self)`](/slides/python-net/hu/aspose.slides.charts/chart/validate_chart_layout/#) | Kiszámítja a diagram elemeinek tényleges értékeit. A tényleges értékek tartalmazzák az IActualLayout interfészt megvalósító elemek pozícióját (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) és a tényleges tengelyértékeket (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [`create_theme_effective(self)`](/slides/python-net/hu/aspose.slides.charts/chart/create_theme_effective/#) | Visszaad egy hatékony témát ehhez a diagramhoz. |

### Lásd még
* osztály [`Chart`](/slides/python-net/hu/aspose.slides.charts/chart)
* osztály [`GraphicalObject`](/slides/python-net/hu/aspose.slides/graphicalobject)
* osztály [`Shape`](/slides/python-net/hu/aspose.slides/shape)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)