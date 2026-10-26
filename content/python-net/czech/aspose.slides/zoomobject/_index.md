---
title: ZoomObject class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/zoomobject/
---
## Třída ZoomObject

Představuje objekt Zoom na snímku.

**Dědičnost:**[`ZoomObject`](/slides/python-net/cs/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

Typ ZoomObject vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/zoomobject/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze pro čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/zoomobject/placeholder/) | Vrací zástupný prvek pro tvar. Vrací None, pokud tvar nemá zástupný prvek.<br/>            Pouze pro čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/zoomobject/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/zoomobject/raw_frame/) | Získá nebo nastaví vlastnosti surového rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/zoomobject/frame/) | Získá nebo nastaví vlastnosti rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/zoomobject/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Poznámka: u některých typů tvarů, které nemají čárové vlastnosti, může vrátit None.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/zoomobject/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje 3D efekty pro tvar.<br/>            Poznámka: u některých typů tvarů, které nemají 3D vlastnosti, může vrátit None.<br/>            Pouze pro čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/zoomobject/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: u některých typů tvarů, které nemají efektní vlastnosti, může vrátit None.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/zoomobject/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar.<br/>            Poznámka: u některých typů tvarů, které nemají výplňové vlastnosti, může vrátit None.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/zoomobject/hyperlink_click/) | Získá nebo nastaví hyperodkaz definovaný pro kliknutí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/zoomobject/hyperlink_mouse_over/) | Získá nebo nastaví hyperodkaz definovaný pro přejetí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/zoomobject/hyperlink_manager/) | Vrací správce hyperodkazů.<br/>            Pouze pro čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides/zoomobject/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/Zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/zoomobject/z_order_position/) | Vrací pozici tvaru v z-pořadí.<br/>            Shapes[0] vrací tvar na pozadí z-pořadí,<br/>            a Shapes[Shapes.Count - 1] vrací tvar v popředí z-pořadí.<br/>            Pouze pro čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/zoomobject/connection_site_count/) | Vrací počet připojovacích míst na tvaru.<br/>            Pouze pro čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/zoomobject/rotation/) | Získá nebo nastaví počet stupňů, o které je určený tvar otočen kolem osy z.<br/>            Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček.<br/>            Čtení/Zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/zoomobject/x/) | Získá nebo nastaví souřadnici x levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/zoomobject/y/) | Získá nebo nastaví souřadnici y levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/zoomobject/width/) | Získá nebo nastaví šířku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/zoomobject/height/) | Získá nebo nastaví výšku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/zoomobject/black_white_mode/) | Vlastnost určuje, jak se tvar zobrazí v černobílém režimu.<br/>            Čtení/Zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/zoomobject/unique_id/) | Vrací interní, prezentací omezený identifikátor určený pro použití doplňky nebo jiný kód.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována<br/>            za trvalý jedinečný klíč.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/zoomobject/office_interop_shape_id/) | Vrací jedinečný identifikátor omezený na snímek, který zůstává konstantní po celou životnost tvaru a<br/>            umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/zoomobject/alternative_text/) | Získá nebo nastaví alternativní text spojený s tvarem.<br/>            Čtení/Zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/zoomobject/alternative_text_title/) | Získá nebo nastaví název alternativního textu spojeného s tvarem.<br/>            Čtení/Zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/zoomobject/name/) | Získá nebo nastaví název tvaru.<br/>            Nesmí být None. Použijte prázdný řetězec, pokud je potřeba.<br/>            Čtení/Zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/zoomobject/is_decorative/) | Získá nebo nastaví možnost „Označit jako dekorativní“<br/>            Čtení/Zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/zoomobject/shape_lock/) | Vrací zamknutí tvaru.<br/>            Pouze pro čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/zoomobject/is_grouped/) | Určuje, zda je tvar seskupený.<br/>            Pouze pro čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides/zoomobject/parent_group/) | Vrací nadřazený objekt GroupShape, pokud je tvar seskupen. Jinak vrací None.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/zoomobject/slide/) | Vrací nadřazený snímek tvaru.<br/>            Pouze pro čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/zoomobject/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/cs/aspose.slides/zoomobject/graphical_object_lock/) | Vrací zamknutí tvaru.<br/>            Pouze pro čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/cs/aspose.slides/zoomobject/image_type/) | Získá nebo nastaví typ obrázku zoom objektu.<br/>            Čtení/Zápis [`ZoomImageType`](/slides/python-net/cs/aspose.slides/zoomimagetype).<br/>            Výchozí hodnota: Preview |
| [`return_to_parent`](/slides/python-net/cs/aspose.slides/zoomobject/return_to_parent/) | Získá nebo nastaví chování navigace v prezentaci.<br/>            Čtení/Zápis **bool**.<br/>            Výchozí hodnota: false |
| [`show_background`](/slides/python-net/cs/aspose.slides/zoomobject/show_background/) | Získá nebo nastaví, zda Zoom použije pozadí cílového snímku.<br/>            Čtení/Zápis **bool**.<br/>            Výchozí hodnota: true |
| [`zoom_image`](/slides/python-net/cs/aspose.slides/zoomobject/zoom_image/) | Získá nebo nastaví obrázek pro zoom objekt.<br/>            Čtení/Zápis [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/cs/aspose.slides/zoomobject/transition_duration/) | Získá nebo nastaví dobu trvání přechodu mezi Zoom a snímkem.<br/>            Čtení/Zápis **float**.<br/>            Výchozí hodnota: 1.0f |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/zoomobject/get_image/#) | Vrací miniaturu tvaru.<br/>            ShapeThumbnailBounds.Shape miniatura tvaru je použita ve výchozím nastavení. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | Uloží obsah tvaru jako SVG soubor. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Uloží obsah tvaru jako SVG soubor. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/zoomobject/remove_placeholder/#) | Definuje, že tento tvar není zástupný prvek. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud žádný neexistuje, a nastaví vlastnosti zástupného prvku na zadaný. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/zoomobject/get_base_placeholder/#) | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavní snímky, ze které je aktuální tvar zděděn). Vrací None, pokud aktuální tvar není zděděn. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides/zoomobject/get_visual_bounds/#) | Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |

### Viz také
* třída [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* třída [`ZoomObject`](/slides/python-net/cs/aspose.slides/zoomobject)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)