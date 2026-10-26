---
title: IShape class
second_title: Aspose.Slides pro Python přes .NET API reference
description: 
type: docs
url: /cs/aspose.slides/ishape/
---
## IShape třída

Representuje tvar na snímku.

Typ IShape obsahuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/ishape/is_text_holder/) | Určuje, zda je tvar TextHolder.<br/>            Pouze ke čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/ishape/placeholder/) | Vrací placeholder pro tvar.<br/>            Pouze ke čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/ishape/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze ke čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/ishape/raw_frame/) | Vrací nebo nastavuje vlastnosti surového rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/ishape/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/ishape/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Pouze ke čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/ishape/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Pouze ke čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/ishape/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Pouze ke čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/ishape/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti formátování výplně pro tvar.<br/>            Pouze ke čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/cs/aspose.slides/ishape/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/ishape/z_order_position/) | Vrací pozici tvaru v pořadí z.<br/>            Shapes[0] vrací tvar na zadní pozici v pořadí z,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na přední pozici v pořadí z.<br/>            Pouze ke čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/ishape/connection_site_count/) | Vrací počet připojovacích míst na tvaru.<br/>            Pouze ke čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/ishape/rotation/) | Vrací nebo nastavuje počet stupňů, o které je daný tvar otočen kolem osy z.<br/>            Kladná hodnota značí rotaci po směru hodinových ručiček; záporná hodnota<br/>            značí rotaci proti směru hodinových ručiček.<br/>            Čtení/zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/ishape/x/) | Získá nebo nastaví souřadnici x levého horního rohu tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/ishape/y/) | Získá nebo nastaví souřadnici y levého horního rohu tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/ishape/width/) | Získá nebo nastaví šířku tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/ishape/height/) | Získá nebo nastaví výšku tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/ishape/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Čtení/zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/ishape/alternative_text_title/) | Vrací nebo nastavuje nadpis alternativního textu spojeného s tvarem.<br/>            Čtení/zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/ishape/name/) | Vrací nebo nastavuje název tvaru.<br/>            Čtení/zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/ishape/is_decorative/) | Získá nebo nastaví možnost 'Mark as decorative'<br/>            Čtení/zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/ishape/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze ke čtení [`IBaseShapeLock`](/slides/python-net/cs/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/ishape/unique_id/) | Vrací interní identifikátor v rámci prezentace určený k použití doplňky nebo jiným kódem.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, neměla by být považována<br/>            za trvalý unikátní klíč.<br/>            Pouze ke čtení **int**.<br/>            Viz také [`IShape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/ishape/office_interop_shape_id/) | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou dobu existence tvaru a<br/>            umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar z libovolného místa dokumentu.<br/>            Pouze ke čtení **int**.<br/>            Viz také [`IShape.unique_id`](/slides/python-net/cs/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/ishape/is_grouped/) | Určuje, zda je tvar seskupený.<br/>            Pouze ke čtení **bool**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/ishape/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení.<br/>            Čtení/zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/cs/aspose.slides/ishape/parent_group/) | Vrací nadřazený objekt GroupShape, pokud je tvar seskupen. Jinak vrací None.<br/>            Pouze ke čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/ishape/hyperlink_manager/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/ishape/get_image/#) | Vrací náhled tvaru.<br/>            Výchozí je použit typ ShapeThumbnailBounds.Shape pro ohraničení náhledu tvaru. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Vrací náhled tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/ishape/write_as_svg/#iorawiobase) | Ukládá obsah tvaru jako soubor SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Ukládá obsah tvaru jako soubor SVG. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/ishape/add_placeholder/#iplaceholder) | Přidá nový placeholder, pokud žádný neexistuje, a nastaví vlastnosti placeholderu na zadaný. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/ishape/remove_placeholder/#) | Definuje, že tento tvar není placeholder. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/ishape/get_base_placeholder/#) | Vrací základní placeholder tvar (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn).<br/>            Pokud aktuální tvar není zděděn, vrací se None. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)