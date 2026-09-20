---
title: ZoomFrame class
second_title: Aspose.Slides pro Python přes .NET Reference API
description: 
type: docs
url: /cs/aspose.slides/zoomframe/
---
## Třída ZoomFrame

Represents a Slide Zoom object in a slide.

**Inheritance:**[`ZoomFrame`](/slides/python-net/cs/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/cs/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

The ZoomFrame type exposes the following members:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/zoomframe/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze pro čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/zoomframe/placeholder/) | Vrací zástupný prvek pro tvar. Vrátí None, pokud tvar nemá zástupný prvek.<br/>            Pouze pro čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/zoomframe/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/zoomframe/raw_frame/) | Vrací nebo nastavuje vlastnosti surového rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/zoomframe/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/zoomframe/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti čáry.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/zoomframe/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje 3D efekty pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají 3D vlastnosti.<br/>            Pouze pro čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/zoomframe/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti efektu.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/zoomframe/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti formátování výplně pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti výplně.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/zoomframe/hyperlink_click/) | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/zoomframe/hyperlink_mouse_over/) | Vrací nebo nastavuje hyperodkaz definovaný pro přejetí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/zoomframe/hyperlink_manager/) | Vrací správce hyperodkazů.<br/>            Pouze pro čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides/zoomframe/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/zoomframe/z_order_position/) | Vrací pozici tvaru v pořadí z.<br/>            Shapes[0] vrací tvar na konci řazení z,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na začátku řazení z.<br/>            Pouze pro čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/zoomframe/connection_site_count/) | Vrací počet připojovacích míst na tvaru.<br/>            Pouze pro čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/zoomframe/rotation/) | Vrací nebo nastavuje počet stupňů, o které je určený tvar otočen kolem osy z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček.<br/>            Čtení/zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/zoomframe/x/) | Vrací nebo nastavuje x-souřadnici levého horního rohu tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/zoomframe/y/) | Vrací nebo nastavuje y-souřadnici levého horního rohu tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/zoomframe/width/) | Vrací nebo nastavuje šířku tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/zoomframe/height/) | Vrací nebo nastavuje výšku tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/zoomframe/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení.<br/>            Čtení/zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/zoomframe/unique_id/) | Vrací vnitřní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována za trvalý jedinečný klíč.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/zoomframe/office_interop_shape_id/) | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/zoomframe/alternative_text/) | Vrací nebo nastavuje alternativní text přiřazený k tvaru.<br/>            Čtení/zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/zoomframe/alternative_text_title/) | Vrací nebo nastavuje název alternativního textu přiřazeného k tvaru.<br/>            Čtení/zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/zoomframe/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nesmí být None. Použijte prázdný řetězec, pokud je potřeba.<br/>            Čtení/zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/zoomframe/is_decorative/) | Vrací nebo nastavuje volbu 'Označit jako dekorativní'<br/>            Čtení/zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/zoomframe/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/zoomframe/is_grouped/) | Určuje, zda je tvar seskupen.<br/>            Pouze pro čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides/zoomframe/parent_group/) | Vrací objekt GroupShape rodiče, pokud je tvar seskupen. Jinak vrátí None.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/zoomframe/slide/) | Vrací nadřazený snímek tvaru.<br/>            Pouze pro čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/zoomframe/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/cs/aspose.slides/zoomframe/graphical_object_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/cs/aspose.slides/zoomframe/image_type/) | Vrací nebo nastavuje typ obrázku zoom objektu.<br/>            Čtení/zápis [`ZoomImageType`](/slides/python-net/cs/aspose.slides/zoomimagetype).<br/>            Výchozí hodnota: Preview |
| [`return_to_parent`](/slides/python-net/cs/aspose.slides/zoomframe/return_to_parent/) | Vrací nebo nastavuje chování navigace v prezentaci.<br/>            Čtení/zápis **bool**.<br/>            Výchozí hodnota: false |
| [`show_background`](/slides/python-net/cs/aspose.slides/zoomframe/show_background/) | Vrací nebo nastavuje hodnotu udávající, zda Zoom použije pozadí cílového snímku.<br/>            Čtení/zápis **bool**.<br/>            Výchozí hodnota: true |
| [`zoom_image`](/slides/python-net/cs/aspose.slides/zoomframe/zoom_image/) | Vrací nebo nastavuje obrázek pro zoom objekt.<br/>            Čtení/zápis [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/cs/aspose.slides/zoomframe/transition_duration/) | Vrací nebo nastavuje dobu trvání přechodu mezi Zoom a snímkem.<br/>            Čtení/zápis **float**.<br/>            Výchozí hodnota: 1.0f |
| [`target_slide`](/slides/python-net/cs/aspose.slides/zoomframe/target_slide/) | Vrací nebo nastavuje objekt snímku, na který odkazuje objekt Slide Zoom.<br/>            Čtení/zápis [`ISlide`](/slides/python-net/cs/aspose.slides/islide). |

## Metody

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/zoomframe/get_image/#) | Vrací miniaturu tvaru.<br/>            Typ ShapeThumbnailBounds.Shape je použit jako výchozí pro ohraničení miniatury tvaru. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | Uloží obsah tvaru jako soubor SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Uloží obsah tvaru jako soubor SVG. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/zoomframe/remove_placeholder/#) | Definuje, že tento tvar není zástupný prvek. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví jeho vlastnosti na určené. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/zoomframe/get_base_placeholder/#) | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn).<br/>            Vrátí None, pokud aktuální tvar není zděděn. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides/zoomframe/get_visual_bounds/#) | Vrací vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu. |

### Viz také
* třída [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* třída [`ZoomFrame`](/slides/python-net/cs/aspose.slides/zoomframe)
* třída [`ZoomObject`](/slides/python-net/cs/aspose.slides/zoomobject)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)