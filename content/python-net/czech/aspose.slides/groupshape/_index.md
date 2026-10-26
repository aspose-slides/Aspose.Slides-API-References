---
title: GroupShape class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/groupshape/
---
## GroupShape třída

Represents a group of shapes on a slide.

**Dědičnost:**[`GroupShape`](/slides/python-net/cs/aspose.slides/groupshape) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

Typ GroupShape vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/groupshape/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Jen ke čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/groupshape/placeholder/) | Vrací zástupný prvek pro tvar. Vrací None, pokud tvar nemá zástupný prvek.<br/>            Jen ke čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/groupshape/custom_data/) | Vrací vlastní data tvaru.<br/>            Jen ke čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/groupshape/raw_frame/) | Vrací nebo nastavuje vlastnosti surového rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/groupshape/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/groupshape/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Poznámka: Vrací None pro objekty GroupShape, protože nemají vlastnosti čáry.<br/>            Jen ke čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/groupshape/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje vlastnosti 3D efektů pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají 3D vlastnosti.<br/>            Jen ke čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/groupshape/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti efektu.<br/>            Jen ke čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/groupshape/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti výplně.<br/>            Jen ke čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/groupshape/hyperlink_click/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/groupshape/hyperlink_mouse_over/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/groupshape/hyperlink_manager/) | Vrací správce hypertextových odkazů.<br/>            Jen ke čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides/groupshape/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/Zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/groupshape/z_order_position/) | Vrací pozici tvaru ve z-řadě.<br/>            Shapes[0] vrací tvar na zadní pozici z-řady,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na přední pozici z-řady.<br/>            Jen ke čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/groupshape/connection_site_count/) | Vrací počet připojovacích míst na tvaru.<br/>            Jen ke čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/groupshape/rotation/) | Vrací nebo nastavuje počet stupňů, o který je specifikovaný tvar otočen kolem osy z.<br/>            Klady hodnota naznačuje otočení po směru hodinových ručiček; záporná hodnota naznačuje otočení proti směru hodinových ručiček.<br/>            Čtení/Zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/groupshape/x/) | Získává nebo nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/groupshape/y/) | Získává nebo nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/groupshape/width/) | Získává nebo nastavuje šířku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/groupshape/height/) | Získává nebo nastavuje výšku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/groupshape/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení..<br/>            Čtení/Zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/groupshape/unique_id/) | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována za trvalý jedinečný klíč.<br/>            Jen ke čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/groupshape/office_interop_shape_id/) | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Jen ke čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/groupshape/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Čtení/Zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/groupshape/alternative_text_title/) | Vrací nebo nastavuje nadpis alternativního textu spojeného s tvarem.<br/>            Čtení/Zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/groupshape/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nesmí být None. V případě potřeby použijte prázdný řetězec.<br/>            Čtení/Zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/groupshape/is_decorative/) | Získává nebo nastavuje možnost 'Označit jako dekorativní'<br/>            Čtení/Zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/groupshape/shape_lock/) | Vrací zámky tvaru.<br/>            Jen ke čtení [`IGroupShapeLock`](/slides/python-net/cs/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/groupshape/is_grouped/) | Určuje, zda je tvar seskupený.<br/>            Jen ke čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides/groupshape/parent_group/) | Vrací nadřazený objekt GroupShape, pokud je tvar seskupen. V opačném případě vrací None.<br/>            Jen ke čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/groupshape/slide/) | Vrací nadřazený snímek tvaru.<br/>            Jen ke čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/groupshape/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Jen ke čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/cs/aspose.slides/groupshape/group_shape_lock/) | Vrací zámky tvaru.<br/>            Jen ke čtení [`IGroupShapeLock`](/slides/python-net/cs/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/cs/aspose.slides/groupshape/shapes/) | Vrací kolekci tvarů uvnitř skupiny.<br/>            Jen ke čtení [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/groupshape/get_image/#) | Vrací miniaturu tvaru.<br/>            Typ ShapeThumbnailBounds.Shape se používá jako výchozí pro ohraničení miniatury tvaru. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/groupshape/write_as_svg/#iorawiobase) | Ukládá obsah tvaru jako soubor SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Ukládá obsah tvaru jako soubor SVG. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/groupshape/remove_placeholder/#) | Definuje, že tento tvar není zástupným prvkem. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/groupshape/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud žádný není, a nastaví vlastnosti zástupného prvku na zadaný. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/groupshape/get_base_placeholder/#) | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn).<br/>            Vrací None, pokud aktuální tvar není zděděn. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides/groupshape/get_visual_bounds/#) | Získává vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu. |

### Viz také
* třída [`GroupShape`](/slides/python-net/cs/aspose.slides/groupshape)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)