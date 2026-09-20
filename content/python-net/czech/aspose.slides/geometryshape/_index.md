---
title: GeometryShape class
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides/geometryshape/
---
## GeometryShape třída

Reprezentuje nadtřídu pro všechny geometrické tvary.

**Dědičnost:**[`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

Typ GeometryShape vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/geometryshape/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze pro čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/geometryshape/placeholder/) | Vrací zástupný prvek pro tvar. Vrátí None, pokud tvar nemá žádný zástupný prvek.<br/>            Pouze pro čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/geometryshape/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/geometryshape/raw_frame/) | Vrací nebo nastavuje vlastnosti surového rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/geometryshape/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/geometryshape/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti čáry pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti čáry.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/geometryshape/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje 3D efektní vlastnosti pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají 3D vlastnosti.<br/>            Pouze pro čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/geometryshape/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti efektu.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/geometryshape/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti výplně.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/geometryshape/hyperlink_click/) | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/geometryshape/hyperlink_mouse_over/) | Vrací nebo nastavuje hyperodkaz definovaný pro přejetí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/geometryshape/hyperlink_manager/) | Vrací správce hyperodkazů.<br/>            Pouze pro čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides/geometryshape/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/geometryshape/z_order_position/) | Vrací pozici tvaru v z-pořadí.<br/>            Shapes[0] vrací tvar na konci z-pořadí,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na začátku z-pořadí.<br/>            Pouze pro čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/geometryshape/connection_site_count/) | Vrací počet spojovacích míst na tvaru.<br/>            Pouze pro čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/geometryshape/rotation/) | Vrací nebo nastavuje počet stupňů, o které je daný tvar otočen okolo osy z.<br/>            Kladná hodnota značí otáčení po směru hodinových ručiček; záporná hodnota<br/>            značí otáčení proti směru hodinových ručiček.<br/>            Čtení/zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/geometryshape/x/) | Vrací nebo nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/geometryshape/y/) | Vrací nebo nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/geometryshape/width/) | Vrací nebo nastavuje šířku tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/geometryshape/height/) | Vrací nebo nastavuje výšku tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/geometryshape/black_white_mode/) | Vlastnost určuje, jak bude tvar renderován v černobílém režimu.<br/>            Čtení/zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/geometryshape/unique_id/) | Vrací interní, prezentací-specifický identifikátor určený pro použití doplňky nebo jiný kód.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována<br/>            za trvalý jedinečný klíč.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/geometryshape/office_interop_shape_id/) | Vrací jedinečný identifikátor v rozsahu snímku, který zůstává konstantní po celou dobu existence tvaru a<br/>            umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/geometryshape/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Čtení/zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/geometryshape/alternative_text_title/) | Vrací nebo nastavuje titulek alternativního textu spojeného s tvarem.<br/>            Čtení/zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/geometryshape/name/) | Vrací nebo nastavuje název tvaru.<br/>            Musí být nenulový. Použijte prázdný řetězec, pokud je potřeba.<br/>            Čtení/zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/geometryshape/is_decorative/) | Vrací nebo nastavuje volbu „Označit jako dekorativní“<br/>            Čtení/zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/geometryshape/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IBaseShapeLock`](/slides/python-net/cs/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/geometryshape/is_grouped/) | Určuje, zda je tvar seskupený.<br/>            Pouze pro čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides/geometryshape/parent_group/) | Vrací objekt GroupShape rodiče, pokud je tvar seskupený. Jinak vrátí None.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/geometryshape/slide/) | Vrací nadřazený snímek tvaru.<br/>            Pouze pro čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/geometryshape/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/cs/aspose.slides/geometryshape/shape_style/) | Vrací objekt stylu tvaru.<br/>            Pouze pro čtení [`IShapeStyle`](/slides/python-net/cs/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type/) | Vrací nebo nastavuje předdefinovaný typ geometrie.<br/>            Poznámka: při změně hodnoty se všechny hodnoty úprav resetují na výchozí.<br/>            Čtení/zápis [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/cs/aspose.slides/geometryshape/adjustments/) | Vrací kolekci hodnot úprav tvaru.<br/>            Pouze pro čtení [`IAdjustValueCollection`](/slides/python-net/cs/aspose.slides/iadjustvaluecollection). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/geometryshape/get_image/#) | Vrací miniaturu tvaru.<br/>            Typ ShapeThumbnailBounds.Shape je použit jako výchozí. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | Uloží obsah tvaru jako soubor SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Uloží obsah tvaru jako soubor SVG. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/geometryshape/remove_placeholder/#) | Definuje, že tento tvar není zástupný prvek. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud žádný není, a nastaví jeho vlastnosti na zadané. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/geometryshape/get_base_placeholder/#) | Vrací základní zástupný tvar (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn).<br/>            Vrátí None, pokud aktuální tvar není zděděn. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides/geometryshape/get_visual_bounds/#) | Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [`get_geometry_paths(self)`](/slides/python-net/cs/aspose.slides/geometryshape/get_geometry_paths/#) | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/cs/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>             hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/cs/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrii tvaru z pole [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>             hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/cs/aspose.slides/geometryshape/create_shape_elements/#) | Vytvoří a vrátí pole prvků tvaru. |

### Viz také
* třída [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)