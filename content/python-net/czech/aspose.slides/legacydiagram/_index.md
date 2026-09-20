---
title: LegacyDiagram class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/legacydiagram/
---
## LegacyDiagram třída

Representuje objekt starého diagramu.

**Inheritance:**[`LegacyDiagram`](/slides/python-net/cs/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

Typ LegacyDiagram poskytuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/legacydiagram/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze ke čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/legacydiagram/placeholder/) | Vrací zástupný znak pro tvar. Vrací None, pokud tvar nemá zástupný znak.<br/>            Pouze ke čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/legacydiagram/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze ke čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/legacydiagram/raw_frame/) | Vrací nebo nastavuje vlastnosti surového rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/legacydiagram/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/legacydiagram/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čar pro tvar.<br/>            Poznámka: může vracet None u určitých typů tvarů, které nemají vlastnosti čar.<br/>            Pouze ke čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/legacydiagram/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje vlastnosti 3D efektů pro tvar.<br/>            Poznámka: může vracet None u určitých typů tvarů, které nemají 3D vlastnosti.<br/>            Pouze ke čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/legacydiagram/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vracet None u určitých typů tvarů, které nemají vlastnosti efektu.<br/>            Pouze ke čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/legacydiagram/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar.<br/>            Poznámka: může vracet None u určitých typů tvarů, které nemají vlastnosti výplně.<br/>            Pouze ke čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/legacydiagram/hyperlink_click/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/legacydiagram/hyperlink_mouse_over/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/legacydiagram/hyperlink_manager/) | Vrací správce hypertextových odkazů.<br/>            Pouze ke čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides/legacydiagram/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/Zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/legacydiagram/z_order_position/) | Vrací pozici tvaru v z-orderu.<br/>            Shapes[0] vrací tvar na pozadí z-orderu,<br/>            a Shapes[Shapes.Count - 1] vrací tvar v popředí z-orderu.<br/>            Pouze ke čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/legacydiagram/connection_site_count/) | Vrací počet připojovacích míst na tvaru.<br/>            Pouze ke čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/legacydiagram/rotation/) | Vrací nebo nastavuje počet stupňů, o které je určený tvar otočen kolem osy z.<br/>            Kladná hodnota značí otáčení po směru hodinových ručiček; záporná hodnota<br/>            značí otáčení proti směru hodinových ručiček.<br/>            Čtení/Zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/legacydiagram/x/) | Získá nebo nastaví souřadnici x levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/legacydiagram/y/) | Získá nebo nastaví souřadnici y levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/legacydiagram/width/) | Získá nebo nastaví šířku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/legacydiagram/height/) | Získá nebo nastaví výšku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/legacydiagram/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení..<br/>            Čtení/Zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/legacydiagram/unique_id/) | Vrací interní, prezentací omezený identifikátor určený pro použití doplňky nebo jiný kód.<br/>            Protože tato hodnota může být přidělena uživatelem nebo programově, nesmí být považována<br/>            za trvalý jedinečný klíč.<br/>            Pouze ke čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/legacydiagram/office_interop_shape_id/) | Vrací jedinečný identifikátor omezený na snímek, který zůstává konstantní po celou životnost tvaru a<br/>            umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze ke čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/legacydiagram/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Čtení/Zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/legacydiagram/alternative_text_title/) | Vrací nebo nastavuje název alternativního textu spojeného s tvarem.<br/>            Čtení/Zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/legacydiagram/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nesmí být None. Použijte prázdný řetězec, pokud je potřeba.<br/>            Čtení/Zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/legacydiagram/is_decorative/) | Získá nebo nastaví možnost „Označit jako dekorativní“<br/>            Čtení/Zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/legacydiagram/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze ke čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/legacydiagram/is_grouped/) | Určuje, zda je tvar seskupen.<br/>            Pouze ke čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides/legacydiagram/parent_group/) | Vrací rodičovský objekt GroupShape, pokud je tvar seskupen. Jinak vrací None.<br/>            Pouze ke čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/legacydiagram/slide/) | Vrací nadřazený snímek tvaru.<br/>            Pouze ke čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/legacydiagram/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Pouze ke čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/cs/aspose.slides/legacydiagram/graphical_object_lock/) | Vrací zámky tvaru.<br/>            Pouze ke čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |

## Metody

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/legacydiagram/get_image/#) | Vrací miniaturu tvaru.<br/>            Jako výchozí se používá typ ShapeThumbnailBounds.Shape pro ohraničení miniatury tvaru. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | Ukládá obsah tvaru jako SVG soubor. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Ukládá obsah tvaru jako SVG soubor. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/legacydiagram/remove_placeholder/#) | Definuje, že tento tvar není zástupný znak. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | Přidá nový zástupný znak, pokud neexistuje, a nastaví vlastnosti zástupného znaku na zadaný. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/legacydiagram/get_base_placeholder/#) | Vrací základní tvar zástupného znaku (tvar z rozložení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn).<br/>            Pokud aktuální tvar není zděděn, vrací None. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides/legacydiagram/get_visual_bounds/#) | Získá vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu. |
| [`convert_to_smart_art(self)`](/slides/python-net/cs/aspose.slides/legacydiagram/convert_to_smart_art/#) | Převede legacy diagram na editovatelný objekt SmartArt.<br/>            Vytvořený objekt SmartArt je přidán do nadřazeného skupinového tvaru ve stejné pozici. |
| [`convert_to_group_shape(self)`](/slides/python-net/cs/aspose.slides/legacydiagram/convert_to_group_shape/#) | Převede legacy diagram na editovatelný skupinový tvar.<br/>            Vytvořený objekt GroupShape je přidán do nadřazeného skupinového tvaru ve stejné pozici. |

### Viz také
* třída [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject)
* třída [`LegacyDiagram`](/slides/python-net/cs/aspose.slides/legacydiagram)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)