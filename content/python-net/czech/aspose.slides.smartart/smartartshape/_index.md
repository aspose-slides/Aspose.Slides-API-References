---
title: SmartArtShape class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.smartart/smartartshape/
---
## SmartArtShape třída

Represents SmartArt shape

**Inheritance:**[`SmartArtShape`](/slides/python-net/cs/aspose.slides.smartart/smartartshape) → [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

The SmartArtShape type exposes the following members:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze pro čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/placeholder/) | Vrací zástupný prvek pro tvar. Vrací None, pokud tvar nemá zástupný prvek.<br/>            Pouze pro čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/raw_frame/) | Vrací nebo nastavuje vlastnosti surového rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti čáry.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje 3D efekty pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají 3D vlastnosti.<br/>            Pouze pro čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti efektu.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti výplně.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/hyperlink_click/) | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | Vrací nebo nastavuje hyperodkaz definovaný pro přejetí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/hyperlink_manager/) | Vrací správce hyperodkazů.<br/>            Pouze pro čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/Zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/z_order_position/) | Vrací pozici tvaru ve vrstvě z.<br/>            Shapes[0] vrací tvar na konci vrstvy z,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na začátku vrstvy z.<br/>            Pouze pro čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/connection_site_count/) | Vrací počet připojovacích míst na tvaru.<br/>            Pouze pro čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/rotation/) | Vrací nebo nastavuje počet stupňů, o které je zadaný tvar otočen kolem osy z.<br/>            Kladná hodnota značí otáčení po směru hodinových ručiček; záporná hodnota<br/>            značí otáčení proti směru hodinových ručiček.<br/>            Čtení/Zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/x/) | Získá nebo nastaví x-souřadnici levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/y/) | Získá nebo nastaví y-souřadnici levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/width/) | Získá nebo nastaví šířku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/height/) | Získá nebo nastaví výšku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu.<br/>            Čtení/Zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/unique_id/) | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována<br/>            za trvalý jedinečný klíč.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a<br/>            umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/alternative_text/) | Vrací nebo nastavuje alternativní text přiřazený k tvaru.<br/>            Čtení/Zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/alternative_text_title/) | Vrací nebo nastavuje titulek alternativního textu přiřazeného k tvaru.<br/>            Čtení/Zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nesmí být None. Použijte prázdný řetězec, pokud je potřeba.<br/>            Čtení/Zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/is_decorative/) | Získá nebo nastaví možnost 'Mark as decorative'<br/>            Čtení/Zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IBaseShapeLock`](/slides/python-net/cs/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/is_grouped/) | Určuje, zda je tvar seskupený.<br/>            Pouze pro čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/parent_group/) | Vrací nadřazený objekt GroupShape, pokud je tvar seskupený. Jinak vrací None.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/slide/) | Vrací nadřazený snímek tvaru.<br/>            Pouze pro čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/shape_style/) | Vrací objekt stylu tvaru.<br/>            Pouze pro čtení [`IShapeStyle`](/slides/python-net/cs/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/shape_type/) | Vrací nebo nastavuje předdefinovaný typ geometrie.<br/>            Poznámka: při změně hodnoty se všechny hodnoty úprav resetují na výchozí hodnoty.<br/>            Čtení/Zápis [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/adjustments/) | Vrací kolekci hodnot úprav tvaru.<br/>            Pouze pro čtení [`IAdjustValueCollection`](/slides/python-net/cs/aspose.slides/iadjustvaluecollection). |
| [`text_frame`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/text_frame/) | Vrací text SmartArt tvaru.<br/>            Pouze pro čtení [`ITextFrame`](/slides/python-net/cs/aspose.slides/itextframe). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/get_image/#) | Vrací miniaturu tvaru.<br/>            Výchozí typ ohraničení miniatury ShapeThumbnailBounds.Shape se používá. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase) | Uloží obsah tvaru jako SVG soubor. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Uloží obsah tvaru jako SVG soubor. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/remove_placeholder/#) | Definuje, že tento tvar není zástupný prvek. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud žádný není, a nastaví jeho vlastnosti na zadaný. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavní snímek, ze kterého je aktuální tvar zděděn).<br/>            Pokud aktuální tvar není zděděn, vrátí None. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/get_visual_bounds/#) | Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [`get_geometry_paths(self)`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/set_geometry_path/#igeometrypath) | Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>             hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrii tvaru z pole [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>             hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/cs/aspose.slides.smartart/smartartshape/create_shape_elements/#) | Vytvoří a vrátí pole prvků tvaru. |

### Viz také
* třída [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* třída [`SmartArtShape`](/slides/python-net/cs/aspose.slides.smartart/smartartshape)
* modul [`aspose.slides.smartart`](/slides/python-net/cs/aspose.slides.smartart)
* knihovna [`Aspose.Slides`](/slides/python-net)