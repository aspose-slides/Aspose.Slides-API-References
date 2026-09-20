---
title: Chart class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chart/
---
## třída Chart

Představuje grafický diagram na snímku.

**Dědičnost:**[`Chart`](/slides/python-net/cs/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

Typ Chart poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides.charts/chart/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze pro čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides.charts/chart/placeholder/) | Vrací zástupný prvek pro tvar. Vrací None, pokud tvar žádný zástupný prvek nemá.<br/>            Pouze pro čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides.charts/chart/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides.charts/chart/raw_frame/) | Vrací nebo nastavuje vlastnosti surového rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides.charts/chart/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides.charts/chart/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti čáry.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides.charts/chart/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje 3D efektové vlastnosti pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají 3D vlastnosti.<br/>            Pouze pro čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides.charts/chart/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají efektové vlastnosti.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides.charts/chart/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají výplňové vlastnosti.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides.charts/chart/hyperlink_click/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides.charts/chart/hyperlink_mouse_over/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides.charts/chart/hyperlink_manager/) | Vrací správce hypertextových odkazů.<br/>            Pouze pro čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides.charts/chart/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/Zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides.charts/chart/z_order_position/) | Vrací pozici tvaru v z-řadě.<br/>            Shapes[0] vrací tvar na konci z-řady,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na začátku z-řady.<br/>            Pouze pro čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides.charts/chart/connection_site_count/) | Vrací počet připojovacích míst na tvaru.<br/>            Pouze pro čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides.charts/chart/rotation/) | Vrací nebo nastavuje počet stupňů, o který je daný tvar otočen kolem osy z.<br/>            Kladná hodnota označuje otáčení po směru hodinových ručiček; záporná hodnota<br/>            označuje otáčení proti směru hodinových ručiček.<br/>            Čtení/Zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides.charts/chart/x/) | Získává nebo nastavuje souřadnici x levého horního rohu tvaru, měřeno v bodech.<br/>            Čtení/Zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides.charts/chart/y/) | Získává nebo nastavuje souřadnici y levého horního rohu tvaru, měřeno v bodech.<br/>            Čtení/Zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides.charts/chart/width/) | Získává nebo nastavuje šířku tvaru, měřeno v bodech.<br/>            Čtení/Zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides.charts/chart/height/) | Získává nebo nastavuje výšku tvaru, měřeno v bodech.<br/>            Čtení/Zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides.charts/chart/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení.<br/>            Čtení/Zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides.charts/chart/unique_id/) | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována<br/>            za trvalý jedinečný klíč.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides.charts/chart/office_interop_shape_id/) | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a<br/>            umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides.charts/chart/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Čtení/Zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides.charts/chart/alternative_text_title/) | Vrací nebo nastavuje nadpis alternativního textu spojeného s tvarem.<br/>            Čtení/Zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides.charts/chart/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nesmí být None. Použijte prázdný řetězec, pokud je potřeba.<br/>            Čtení/Zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides.charts/chart/is_decorative/) | Získává nebo nastavuje volbu 'Označit jako dekorativní'<br/>            Čtení/Zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides.charts/chart/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides.charts/chart/is_grouped/) | Určuje, zda je tvar seskupen.<br/>            Pouze pro čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides.charts/chart/parent_group/) | Vrací objekt GroupShape rodiče, pokud je tvar seskupen. Jinak vrací None.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/chart/slide/) | Vrací nadřazený snímek tvaru.<br/>            Pouze pro čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/chart/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/cs/aspose.slides.charts/chart/graphical_object_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/cs/aspose.slides.charts/chart/plot_visible_cells_only/) | Určuje, zda jsou vykresleny pouze viditelné buňky. False pro vykreslení jak viditelných, tak skrytých buněk.<br/>            Čtení/Zápis **bool**. |
| [`display_blanks_as`](/slides/python-net/cs/aspose.slides.charts/chart/display_blanks_as/) | Vrací nebo nastavuje způsob vykreslení prázdných buněk v diagramu.<br/>            Čtení/Zápis [`DisplayBlanksAsType`](/slides/python-net/cs/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/cs/aspose.slides.charts/chart/chart_data/) | Vrací informace o propojených nebo vložených datech spojených s diagramem.<br/>            Pouze pro čtení [`IChartData`](/slides/python-net/cs/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/cs/aspose.slides.charts/chart/has_title/) | Určuje, zda má diagram viditelný nadpis.<br/>            Čtení/Zápis **bool**. |
| [`chart_title`](/slides/python-net/cs/aspose.slides.charts/chart/chart_title/) | Vrací nebo nastavuje nadpis diagramu.<br/>            Pouze pro čtení [`IChartTitle`](/slides/python-net/cs/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/cs/aspose.slides.charts/chart/has_data_table/) | Určuje, zda má diagram datovou tabulku.<br/>            Čtení/Zápis **bool**. |
| [`has_legend`](/slides/python-net/cs/aspose.slides.charts/chart/has_legend/) | Určuje, zda má diagram legendu.<br/>            Čtení/Zápis **bool**. |
| [`legend`](/slides/python-net/cs/aspose.slides.charts/chart/legend/) | Vrací nebo nastavuje legendu pro diagram.<br/>            Pouze pro čtení [`ILegend`](/slides/python-net/cs/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/cs/aspose.slides.charts/chart/chart_data_table/) | Vrací datovou tabulku diagramu.<br/>            Pouze pro čtení [`IDataTable`](/slides/python-net/cs/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/cs/aspose.slides.charts/chart/style/) | Vrací nebo nastavuje styl diagramu.<br/>            Čtení/Zápis [`StyleType`](/slides/python-net/cs/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/cs/aspose.slides.charts/chart/type/) | Vrací nebo nastavuje typ diagramu.<br/>            Čtení/Zápis [`ChartType`](/slides/python-net/cs/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/cs/aspose.slides.charts/chart/plot_area/) | Reprezentuje oblast vykreslování diagramu.<br/>            Pouze pro čtení [`IChartPlotArea`](/slides/python-net/cs/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/cs/aspose.slides.charts/chart/rotation_3d/) | Vrací 3D rotaci diagramu.<br/>            Pouze pro čtení [`IRotation3D`](/slides/python-net/cs/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/cs/aspose.slides.charts/chart/back_wall/) | Vrací objekt, který umožňuje změnit formát zadní stěny 3D diagramu.<br/>            Pouze pro čtení [`IChartWall`](/slides/python-net/cs/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/cs/aspose.slides.charts/chart/side_wall/) | Vrací objekt, který umožňuje změnit formát boční stěny 3D diagramu.<br/>            Pouze pro čtení [`IChartWall`](/slides/python-net/cs/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/cs/aspose.slides.charts/chart/floor/) | Vrací objekt, který umožňuje změnit formát podlahy 3D diagramu.<br/>            Pouze pro čtení [`IChartWall`](/slides/python-net/cs/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/cs/aspose.slides.charts/chart/text_format/) | Vrací formát textu diagramu.<br/>            Vlastnost není použita pro následující typy: [`ChartType.TREEMAP`](/slides/python-net/cs/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/cs/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/cs/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/cs/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/cs/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/cs/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Pouze pro čtení [`IChartTextFormat`](/slides/python-net/cs/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/cs/aspose.slides.charts/chart/theme_manager/) | Vrací správce motivu.<br/>            Pouze pro čtení [`IOverrideThemeManager`](/slides/python-net/cs/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/cs/aspose.slides.charts/chart/user_shapes/) | Určuje tvary kreslené nad diagramem.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/cs/aspose.slides.charts/chart/axes/) | Poskytuje přístup k osám diagramu.<br/>            Pouze pro čtení [`IAxesManager`](/slides/python-net/cs/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/cs/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Určuje, že datové popisky nad maximem diagramu mají být zobrazeny.<br/>            Čtení/Zápis **bool**. |
| [`has_rounded_corners`](/slides/python-net/cs/aspose.slides.charts/chart/has_rounded_corners/) | Určuje, že oblast diagramu má mít zaoblené rohy.<br/>            Čtení/Zápis **bool**. |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/chart/chart/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides.charts/chart/get_image/#) | Vrací miniaturu tvaru.<br/>            Typ ShapeThumbnailBounds.Shape je použit jako výchozí. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Ukládá obsah tvaru jako soubor SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Ukládá obsah tvaru jako soubor SVG. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides.charts/chart/remove_placeholder/#) | Definuje, že tento tvar není zástupný prvek. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na zadaný. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides.charts/chart/get_base_placeholder/#) | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavní snímky, ze kterého je aktuální tvar zděděn).<br/>            Je vráceno None, pokud aktuální tvar není zděděn. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides.charts/chart/get_visual_bounds/#) | Získává vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [`validate_chart_layout(self)`](/slides/python-net/cs/aspose.slides.charts/chart/validate_chart_layout/#) | Vypočítává skutečné hodnoty prvků diagramu. Skutečné hodnoty zahrnují pozice prvků, které implementují rozhraní IActualLayout <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            a skutečné hodnoty os (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [`create_theme_effective(self)`](/slides/python-net/cs/aspose.slides.charts/chart/create_theme_effective/#) | Vrací efektivní motiv pro tento diagram. |

### Viz také
* třída [`Chart`](/slides/python-net/cs/aspose.slides.charts/chart)
* třída [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)