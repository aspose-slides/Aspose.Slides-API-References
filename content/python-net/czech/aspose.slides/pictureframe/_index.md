---
title: PictureFrame class
second_title: Aspose.Slides pro Python prostřednictvím .NET API referenční příručka
description: 
type: docs
url: /cs/aspose.slides/pictureframe/
---
## PictureFrame třída

Reprezentuje rámeček s obrázkem uvnitř.

**Inheritance:**[`PictureFrame`](/slides/python-net/cs/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

The PictureFrame type exposes the following members:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/pictureframe/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze pro čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/pictureframe/placeholder/) | Vrací zástupný prvek pro tvar. Vrací None, pokud tvar nemá zástupný prvek.<br/>            Pouze pro čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/pictureframe/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/pictureframe/raw_frame/) | Vrací nebo nastavuje vlastnosti surového rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/pictureframe/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/pictureframe/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti čáry.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/pictureframe/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje 3D efektové vlastnosti pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají 3D vlastnosti.<br/>            Pouze pro čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/pictureframe/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti efektů.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/pictureframe/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti výplně.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/pictureframe/hyperlink_click/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/pictureframe/hyperlink_mouse_over/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/pictureframe/hyperlink_manager/) | Vrací správce hypertextových odkazů.<br/>            Pouze pro čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides/pictureframe/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/pictureframe/z_order_position/) | Vrací pozici tvaru v pořadí z-order,<br/>            Shapes[0] vrací tvar na zadní části z-order, a Shapes[Shapes.Count - 1] vrací tvar v přední části z-order.<br/>            Pouze pro čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/pictureframe/connection_site_count/) | Vrací počet připojovacích míst na tvaru.<br/>            Pouze pro čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/pictureframe/rotation/) | Vrací nebo nastavuje počet stupňů, o které je zadaný tvar otočen kolem osy z. Kladná hodnota značí otáčení po směru hodinových ručiček; záporná hodnota značí otáčení proti směru hodinových ručiček.<br/>            Čtení/zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/pictureframe/x/) | Získává nebo nastavuje souřadnici x levého horního rohu tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/pictureframe/y/) | Získává nebo nastavuje souřadnici y levého horního rohu tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/pictureframe/width/) | Získává nebo nastavuje šířku tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/pictureframe/height/) | Získává nebo nastavuje výšku tvaru, měřeno v bodech.<br/>            Čtení/zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/pictureframe/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení.<br/>            Čtení/zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/pictureframe/unique_id/) | Vrací vnitřní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, neměla by být považována za trvalý jedinečný klíč.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/pictureframe/office_interop_shape_id/) | Vrací jedinečný identifikátor v rozsahu snímku, který zůstává konstantní po celou dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/pictureframe/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Čtení/zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/pictureframe/alternative_text_title/) | Vrací nebo nastavuje titulek alternativního textu spojeného s tvarem.<br/>            Čtení/zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/pictureframe/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nesmí být None. Pokud je to nutné, použijte prázdný řetězec.<br/>            Čtení/zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/pictureframe/is_decorative/) | Získává nebo nastavuje volbu 'Označit jako dekorativní'<br/>            Čtení/zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/pictureframe/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IPictureFrameLock`](/slides/python-net/cs/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/pictureframe/is_grouped/) | Určuje, zda je tvar seskupen.<br/>            Pouze pro čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides/pictureframe/parent_group/) | Vrací nadřazený objekt GroupShape, pokud je tvar seskupen. Jinak vrací None.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/pictureframe/slide/) | Vrací nadřazený snímek tvaru.<br/>            Pouze pro čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/pictureframe/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/cs/aspose.slides/pictureframe/shape_style/) | Vrací objekt stylu tvaru.<br/>            Pouze pro čtení [`IShapeStyle`](/slides/python-net/cs/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/cs/aspose.slides/pictureframe/shape_type/) | Vrací nebo nastavuje typ AutoShape pro PictureFrame.<br/>            Povolené jsou všechny položky ze sady [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype), kromě všech druhů čar:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Čtení/zápis [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/cs/aspose.slides/pictureframe/adjustments/) | Vrací kolekci hodnot úpravy tvaru.<br/>            Pouze pro čtení [`IAdjustValueCollection`](/slides/python-net/cs/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/cs/aspose.slides/pictureframe/picture_frame_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IPictureFrameLock`](/slides/python-net/cs/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/cs/aspose.slides/pictureframe/picture_format/) | Vrací objekt PictureFillFormat pro rámeček obrázku.<br/>            Pouze pro čtení [`IPictureFillFormat`](/slides/python-net/cs/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/cs/aspose.slides/pictureframe/relative_scale_height/) | Vrací nebo nastavuje měřítko výšky (relativně k původní velikosti obrázku) rámečku obrázku. Hodnota 1.0 odpovídá 100 %.<br/>            Čtení/zápis **float**. |
| [`relative_scale_width`](/slides/python-net/cs/aspose.slides/pictureframe/relative_scale_width/) | Vrací nebo nastavuje měřítko šířky (relativně k původní velikosti obrázku) rámečku obrázku. Hodnota 1.0 odpovídá 100 %.<br/>            Čtení/zápis **float**. |
| [`is_cameo`](/slides/python-net/cs/aspose.slides/pictureframe/is_cameo/) | Určuje, zda je PictureFrame objekt Cameo nebo ne.<br/>            Pouze pro čtení **bool**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/pictureframe/get_image/#) | Vrací miniaturu tvaru.<br/>            Typ ShapeThumbnailBounds.Shape se používá jako výchozí pro ohraničení miniatury tvaru. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Uloží obsah tvaru jako soubor SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Uloží obsah tvaru jako soubor SVG. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/pictureframe/remove_placeholder/#) | Definuje, že tento tvar není zástupný prvek. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na zadaný. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/pictureframe/get_base_placeholder/#) | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavní snímku, ze kterého je aktuální tvar zděděn).<br/>            Vrací None, pokud aktuální tvar není zděděn. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides/pictureframe/get_visual_bounds/#) | Získává vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [`get_geometry_paths(self)`](/slides/python-net/cs/aspose.slides/pictureframe/get_geometry_paths/#) | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/cs/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru.<br/>            Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/cs/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrii tvaru z pole [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru.<br/>            Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/cs/aspose.slides/pictureframe/create_shape_elements/#) | Vytvoří a vrátí pole elementů tvaru. |

### Viz také
* třída [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape)
* třída [`PictureFrame`](/slides/python-net/cs/aspose.slides/pictureframe)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)