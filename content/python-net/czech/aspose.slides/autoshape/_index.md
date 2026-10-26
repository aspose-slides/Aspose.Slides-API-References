---
title: AutoShape class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/autoshape/
---
## AutoShape třída

Reprezentuje AutoShape.

**Dědičnost:**[`AutoShape`](/slides/python-net/cs/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

Typ AutoShape vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/autoshape/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze pro čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/autoshape/placeholder/) | Vrací zástupný prvek pro tvar. Vrátí None, pokud tvar nemá zástupný prvek.<br/>            Pouze pro čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/autoshape/custom_data/) | Vrací uživatelská data tvaru.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/autoshape/raw_frame/) | Vrací nebo nastavuje surové vlastnosti rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/autoshape/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/autoshape/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čar pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti čar.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/autoshape/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje 3D efektové vlastnosti pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají 3D vlastnosti.<br/>            Pouze pro čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/autoshape/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti efektů.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/autoshape/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti výplně.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/autoshape/hyperlink_click/) | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/autoshape/hyperlink_mouse_over/) | Vrací nebo nastavuje hyperodkaz definovaný pro přejetí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/autoshape/hyperlink_manager/) | Vrací správce hyperodkazů.<br/>            Pouze pro čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides/autoshape/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/Zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/autoshape/z_order_position/) | Vrací pozici tvaru v z-řadě.<br/>            Shapes[0] vrací tvar na zadní pozici z-řady,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na přední pozici z-řady.<br/>            Pouze pro čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/autoshape/connection_site_count/) | Vrací počet spojovacích míst na tvaru.<br/>            Pouze pro čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/autoshape/rotation/) | Vrací nebo nastavuje počet stupňů, o které je daný tvar otočen kolem osy z.<br/>            Kladná hodnota značí otáčení po směru hodinových ručiček; záporná hodnota<br/>            značí otáčení proti směru hodinových ručiček.<br/>            Čtení/Zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/autoshape/x/) | Vrací nebo nastavuje souřadnici x levého horního rohu tvaru, měřeno v bodech.<br/>            Čtení/Zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/autoshape/y/) | Vrací nebo nastavuje souřadnici y levého horního rohu tvaru, měřeno v bodech.<br/>            Čtení/Zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/autoshape/width/) | Vrací nebo nastavuje šířku tvaru, měřeno v bodech.<br/>            Čtení/Zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/autoshape/height/) | Vrací nebo nastavuje výšku tvaru, měřeno v bodech.<br/>            Čtení/Zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/autoshape/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu.<br/>            Čtení/Zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/autoshape/unique_id/) | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, neměla by být považována<br/>            za trvalý jedinečný klíč.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/autoshape/office_interop_shape_id/) | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a<br/>            umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/autoshape/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Čtení/Zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/autoshape/alternative_text_title/) | Vrací nebo nastavuje název alternativního textu spojeného s tvarem.<br/>            Čtení/Zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/autoshape/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nesmí být None. V případě potřeby použijte prázdný řetězec.<br/>            Čtení/Zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/autoshape/is_decorative/) | Vrací nebo nastavuje volbu 'Označit jako dekorativní'<br/>            Čtení/Zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/autoshape/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IAutoShapeLock`](/slides/python-net/cs/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/autoshape/is_grouped/) | Určuje, zda je tvar seskupený.<br/>            Pouze pro čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides/autoshape/parent_group/) | Vrací objekt GroupShape rodiče, pokud je tvar seskupený. Jinak vrací None.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/autoshape/slide/) | Vrací nadřazený snímek tvaru.<br/>            Pouze pro čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/autoshape/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/cs/aspose.slides/autoshape/shape_style/) | Vrací objekt stylu tvaru.<br/>            Pouze pro čtení [`IShapeStyle`](/slides/python-net/cs/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/cs/aspose.slides/autoshape/shape_type/) | Vrací nebo nastavuje přednastavený typ geometrie.<br/>            Poznámka: při změně hodnoty se všechny hodnoty úpravy resetují na výchozí.<br/>            Čtení/Zápis [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/cs/aspose.slides/autoshape/adjustments/) | Vrací kolekci hodnot úprav tvaru.<br/>            Pouze pro čtení [`IAdjustValueCollection`](/slides/python-net/cs/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/cs/aspose.slides/autoshape/auto_shape_lock/) | Vrací zámky autoshapu.<br/>            Pouze pro čtení [`IAutoShapeLock`](/slides/python-net/cs/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/cs/aspose.slides/autoshape/text_frame/) | Vrací objekt TextFrame pro AutoShape.<br/>            Pouze pro čtení [`ITextFrame`](/slides/python-net/cs/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/cs/aspose.slides/autoshape/use_background_fill/) | Určuje, zda má být tento autoshape vyplněn výplní pozadí snímku místo specifikace stylem nebo formátem výplně.<br/>            Čtení/Zápis **bool**. |
| [`is_text_box`](/slides/python-net/cs/aspose.slides/autoshape/is_text_box/) | Určuje, zda je tvar textovým polem. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/autoshape/get_image/#) | Vrací miniaturu tvaru.<br/>            Výchozí typ ohraničení miniatury tvaru ShapeThumbnailBounds.Shape se používá. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Uloží obsah tvaru jako SVG soubor. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Uloží obsah tvaru jako SVG soubor. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/autoshape/remove_placeholder/#) | Definuje, že tento tvar není zástupný prvek. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví jeho vlastnosti na určené. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/autoshape/get_base_placeholder/#) | Vrací základní zástupný tvar (tvar z rozložení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn).<br/>            Vrátí None, pokud aktuální tvar není zděděn. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides/autoshape/get_visual_bounds/#) | Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [`get_geometry_paths(self)`](/slides/python-net/cs/aspose.slides/autoshape/get_geometry_paths/#) | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/cs/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>             hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/cs/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrii tvaru z pole [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>             hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/cs/aspose.slides/autoshape/create_shape_elements/#) | Vytvoří a vrátí pole prvků tvaru. |
| [`add_text_frame(self, text)`](/slides/python-net/cs/aspose.slides/autoshape/add_text_frame/#str) | Přidá nový TextFrame k tvaru.<br/>            Pokud tvar již TextFrame má, jednoduše změní jeho text. |

### Viz také
* třída [`AutoShape`](/slides/python-net/cs/aspose.slides/autoshape)
* třída [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)