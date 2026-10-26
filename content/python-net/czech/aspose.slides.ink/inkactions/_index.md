---
title: InkActions class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.ink/inkactions/
---
## třída InkActions

Represents the root of ink actions.

**Dědičnost:**[`InkActions`](/slides/python-net/cs/aspose.slides.ink/inkactions) → [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

Typ InkActions poskytuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides.ink/inkactions/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze pro čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides.ink/inkactions/placeholder/) | Vrací zástupný objekt pro tvar. Vrací None, pokud tvar nemá zástupný objekt.<br/>            Pouze pro čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides.ink/inkactions/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides.ink/inkactions/raw_frame/) | Vrací nebo nastavuje vlastnosti syrového rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides.ink/inkactions/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides.ink/inkactions/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti čáry.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides.ink/inkactions/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje vlastnosti 3D efektu pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají 3D vlastnosti.<br/>            Pouze pro čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides.ink/inkactions/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti efektu.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides.ink/inkactions/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti formátování výplně pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti výplně.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides.ink/inkactions/hyperlink_click/) | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides.ink/inkactions/hyperlink_mouse_over/) | Vrací nebo nastavuje hyperodkaz definovaný pro přejetí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides.ink/inkactions/hyperlink_manager/) | Vrací správce hyperodkazů.<br/>            Pouze pro čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides.ink/inkactions/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides.ink/inkactions/z_order_position/) | Vrací pozici tvaru v pořadí z.<br/>            Shapes[0] vrací tvar na zadní pozici v pořadí z,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na přední pozici v pořadí z.<br/>            Pouze pro čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides.ink/inkactions/connection_site_count/) | Vrací počet připojených míst na tvaru.<br/>            Pouze pro čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides.ink/inkactions/rotation/) | Vrací nebo nastavuje počet stupňů, o které je daný tvar otočen kolem osy z.<br/>            Kladná hodnota označuje otáčení po směru hodinových ručiček; záporná hodnota<br/>            označuje otáčení proti směru hodinových ručiček.<br/>            Čtení/zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides.ink/inkactions/x/) | Získá nebo nastaví souřadnici x levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides.ink/inkactions/y/) | Získá nebo nastaví souřadnici y levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides.ink/inkactions/width/) | Získá nebo nastaví šířku tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides.ink/inkactions/height/) | Získá nebo nastaví výšku tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides.ink/inkactions/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení..<br/>            Čtení/zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides.ink/inkactions/unique_id/) | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována<br/>            za trvalý jedinečný klíč.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides.ink/inkactions/office_interop_shape_id/) | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides.ink/inkactions/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Čtení/zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides.ink/inkactions/alternative_text_title/) | Vrací nebo nastavuje titulek alternativního textu spojeného s tvarem.<br/>            Čtení/zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides.ink/inkactions/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nesmí být None. V případě potřeby použijte prázdný řetězec.<br/>            Čtení/zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides.ink/inkactions/is_decorative/) | Získá nebo nastaví volbu 'Označit jako dekorativní'<br/>            Čtení/zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides.ink/inkactions/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides.ink/inkactions/is_grouped/) | Určuje, zda je tvar seskupen.<br/>            Pouze pro čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides.ink/inkactions/parent_group/) | Vrací nadřazený objekt GroupShape, pokud je tvar seskupen. Jinak vrací None.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides.ink/inkactions/slide/) | Vrací nadřazený snímek tvaru.<br/>            Pouze pro čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides.ink/inkactions/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/cs/aspose.slides.ink/inkactions/graphical_object_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |

## Metody

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides.ink/inkactions/get_image/#) | Vrací miniaturu tvaru.<br/>            Výchozí se používá typ ShapeThumbnailBounds.Shape pro ohraničení miniatury tvaru. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides.ink/inkactions/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase) | Uloží obsah tvaru jako SVG soubor. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides.ink/inkactions/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Uloží obsah tvaru jako SVG soubor. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides.ink/inkactions/remove_placeholder/#) | Definuje, že tento tvar není zástupný objekt. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides.ink/inkactions/add_placeholder/#iplaceholder) | Přidá nový zástupný objekt, pokud žádný neexistuje, a nastaví vlastnosti zástupného objektu na zadaný. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides.ink/inkactions/get_base_placeholder/#) | Vrací základní tvar zástupného objektu (tvar z rozložení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn).<br/>            Pokud aktuální tvar není zděděn, vrátí None. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides.ink/inkactions/get_visual_bounds/#) | Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |

### Viz také
* třída [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject)
* třída [`InkActions`](/slides/python-net/cs/aspose.slides.ink/inkactions)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* modul [`aspose.slides.ink`](/slides/python-net/cs/aspose.slides.ink)
* knihovna [`Aspose.Slides`](/slides/python-net)