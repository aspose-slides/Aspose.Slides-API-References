---
title: Table class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/table/
---
## Table třída

Represents a table on a slide.

**Dědičnost:**[`Table`](/slides/python-net/cs/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

Typ Table vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/table/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze ke čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/table/placeholder/) | Vrací zástupný prvek pro tvar. Vrací None, pokud tvar nemá zástupný prvek.<br/>            Pouze ke čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/table/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze ke čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/table/raw_frame/) | Vrací nebo nastavuje vlastnosti surového rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/table/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/table/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti čáry.<br/>            Pouze ke čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/table/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje 3D efektní vlastnosti pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají 3D vlastnosti.<br/>            Pouze ke čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/table/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají efektní vlastnosti.<br/>            Pouze ke čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/table/fill_format/) | Vrací objekt TableFormat.FillFormat, který obsahuje výplňové formátování pro Table.<br/>            Pouze ke čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/table/hyperlink_click/) | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/table/hyperlink_mouse_over/) | Vrací nebo nastavuje hyperodkaz definovaný pro přejetí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/table/hyperlink_manager/) | Vrací správce hyperodkazů.<br/>            Pouze ke čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides/table/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/table/z_order_position/) | Vrací pozici tvaru v pořadí z.<br/>            Shapes[0] vrací tvar na zadní části pořadí z,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na přední části pořadí z.<br/>            Pouze ke čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/table/connection_site_count/) | Vrací počet připojovacích míst na tvaru.<br/>            Pouze ke čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/table/rotation/) | Vrací nebo nastavuje počet stupňů, o které je daný tvar otočen kolem osy z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček.<br/>            Čtení/zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/table/x/) | Získává nebo nastavuje souřadnici x levého horního rohu tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/table/y/) | Získává nebo nastavuje souřadnici y levého horního rohu tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/table/width/) | Získává nebo nastavuje šířku tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/table/height/) | Získává nebo nastavuje výšku tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/table/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení.<br/>            Čtení/zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/table/unique_id/) | Vrací interní, v rámci prezentace omezený identifikátor určený pro použití doplňky nebo jiným kódem.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována za trvalý jedinečný klíč.<br/>            Pouze ke čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/table/office_interop_shape_id/) | Vrací jedinečný identifikátor omezený na snímek, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze ke čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/table/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Čtení/zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/table/alternative_text_title/) | Vrací nebo nastavuje nadpis alternativního textu spojeného s tvarem.<br/>            Čtení/zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/table/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nesmí být None. Použijte prázdný řetězec, pokud je potřeba.<br/>            Čtení/zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/table/is_decorative/) | Získává nebo nastavuje možnost 'Označit jako dekorativní'<br/>            Čtení/zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/table/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze ke čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/table/is_grouped/) | Určuje, zda je tvar seskupen.<br/>            Pouze ke čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides/table/parent_group/) | Vrací nadřazený objekt GroupShape, pokud je tvar seskupen. Jinak vrací None.<br/>            Pouze ke čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/table/slide/) | Vrací nadřazený snímek tvaru.<br/>            Pouze ke čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/table/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Pouze ke čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/cs/aspose.slides/table/graphical_object_lock/) | Vrací zámky tvaru.<br/>            Pouze ke čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/cs/aspose.slides/table/rows/) | Vrací kolekci řádků.<br/>            Pouze ke čtení [`IRowCollection`](/slides/python-net/cs/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/cs/aspose.slides/table/columns/) | Vrací kolekci sloupců.<br/>            Pouze ke čtení [`IColumnCollection`](/slides/python-net/cs/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/cs/aspose.slides/table/table_format/) | Vrací objekt TableFormat, který obsahuje formátovací vlastnosti pro tuto tabulku.<br/>            Pouze ke čtení [`ITableFormat`](/slides/python-net/cs/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/cs/aspose.slides/table/style_preset/) | Získává nebo nastavuje vestavěný styl tabulky.<br/>            Čtení/zápis [`TableStylePreset`](/slides/python-net/cs/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/cs/aspose.slides/table/right_to_left/) | Určuje, zda má tabulka směr čtení zprava doleva.<br/>            Čtení/zápis **bool**. |
| [`first_row`](/slides/python-net/cs/aspose.slides/table/first_row/) | Určuje, zda má být první řádek tabulky vykreslen se speciálním formátováním.<br/>            Čtení/zápis **bool**. |
| [`first_col`](/slides/python-net/cs/aspose.slides/table/first_col/) | Určuje, zda má být první sloupec tabulky vykreslen se speciálním formátováním.<br/>            Čtení/zápis **bool**. |
| [`last_row`](/slides/python-net/cs/aspose.slides/table/last_row/) | Určuje, zda má být poslední řádek tabulky vykreslen se speciálním formátováním.<br/>            Čtení/zápis **bool**. |
| [`last_col`](/slides/python-net/cs/aspose.slides/table/last_col/) | Určuje, zda má být poslední sloupec tabulky vykreslen se speciálním formátováním.<br/>            Čtení/zápis **bool**. |
| [`horizontal_banding`](/slides/python-net/cs/aspose.slides/table/horizontal_banding/) | Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním.<br/>            Čtení/zápis **bool**. |
| [`vertical_banding`](/slides/python-net/cs/aspose.slides/table/vertical_banding/) | Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním.<br/>            Čtení/zápis **bool**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/table/get_image/#) | Vrací miniaturu tvaru.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/table/write_as_svg/#iorawiobase) | Uloží obsah Shape jako SVG soubor. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Uloží obsah Shape jako SVG soubor. |
| [`set_text_format(self, source)`](/slides/python-net/cs/aspose.slides/table/set_text_format/#iportionformat) | Nastaví definované vlastnosti formátu úseku pro všechny úseky buněk tabulky. |
| [`set_text_format(self, source)`](/slides/python-net/cs/aspose.slides/table/set_text_format/#iparagraphformat) | Nastaví definované vlastnosti formátu odstavce pro všechny odstavce buněk tabulky. |
| [`set_text_format(self, source)`](/slides/python-net/cs/aspose.slides/table/set_text_format/#itextframeformat) | Nastaví definované vlastnosti formátu textového rámce pro všechny textové rámečky buněk tabulky. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/table/remove_placeholder/#) | Definuje, že tento tvar není zástupný prvek. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/table/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud žádný není, a nastaví vlastnosti zástupného prvku na zadaný. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/table/get_base_placeholder/#) | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar odvozen).<br/>            Vrací None, pokud aktuální tvar není odvozen. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides/table/get_visual_bounds/#) | Získává vizuální hranice tvaru vypočtené z jeho vykresleného obsahu. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/cs/aspose.slides/table/merge_cells/#icell-icell-bool) | Spojuje sousední buňky. |

### Viz také
* třída [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* třída [`Table`](/slides/python-net/cs/aspose.slides/table)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)