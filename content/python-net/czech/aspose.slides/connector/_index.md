---
title: Connector class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/connector/
---
## Connector třída

Představuje konektor.

**Dědičnost:**[`Connector`](/slides/python-net/cs/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

Typ Connector vystavuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/connector/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze pro čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/connector/placeholder/) | Vrací zástupný prvek pro tvar. Vrací None, pokud tvar žádný zástupný prvek nemá.<br/>            Pouze pro čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/connector/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/connector/raw_frame/) | Vrací nebo nastavuje vlastnosti surového rámečku tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/connector/frame/) | Vrací nebo nastavuje vlastnosti rámečku tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/connector/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Poznámka: může vracet None pro určité typy tvarů, které nemají vlastnosti čáry.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/connector/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje vlastnosti 3D efektu pro tvar.<br/>            Poznámka: může vracet None pro určité typy tvarů, které nemají 3D vlastnosti.<br/>            Pouze pro čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/connector/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vracet None pro určité typy tvarů, které nemají vlastnosti efektu.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/connector/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar.<br/>            Poznámka: může vracet None pro určité typy tvarů, které nemají vlastnosti výplně.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/connector/hyperlink_click/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/connector/hyperlink_mouse_over/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/connector/hyperlink_manager/) | Vrací správce hypertextových odkazů.<br/>            Pouze pro čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides/connector/hidden/) | Určuje, zda je tvar skryt.<br/>            Čtení/Zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/connector/z_order_position/) | Vrací pozici tvaru v z-řadě.<br/>            Shapes[0] vrací tvar na zadní straně z-řady,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na přední straně z-řady.<br/>            Pouze pro čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/connector/connection_site_count/) | Vrací počet připojovacích míst na tvaru.<br/>            Pouze pro čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/connector/rotation/) | Vrací nebo nastavuje počet stupňů, o které je tvar otočen kolem osy z.<br/>            Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota<br/>            značí otočení proti směru hodinových ručiček.<br/>            Čtení/Zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/connector/x/) | Vrací nebo nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/connector/y/) | Vrací nebo nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/connector/width/) | Vrací nebo nastavuje šířku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/connector/height/) | Vrací nebo nastavuje výšku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/connector/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení..<br/>            Čtení/Zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/connector/unique_id/) | Vrací interní, prezentací omezený identifikátor určený pro použití doplňky nebo jiný kód.<br/>            Protože může být uživatelem nebo programově přepsán, neměl by být považován<br/>            za trvalý jedinečný klíč.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/connector/office_interop_shape_id/) | Vrací jedinečný identifikátor omezený na snímek, který zůstává konstantní po celou dobu existence tvaru a<br/>            umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/connector/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Čtení/Zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/connector/alternative_text_title/) | Vrací nebo nastavuje název alternativního textu spojeného s tvarem.<br/>            Čtení/Zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/connector/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nesmí být None. Použijte prázdný řetězec, pokud je potřeba.<br/>            Čtení/Zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/connector/is_decorative/) | Získává nebo nastavuje volbu „Označit jako dekorativní“<br/>            Čtení/Zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/connector/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IConnectorLock`](/slides/python-net/cs/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/connector/is_grouped/) | Určuje, zda je tvar seskupen.<br/>            Pouze pro čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides/connector/parent_group/) | Vrací nadřazený objekt GroupShape, pokud je tvar seskupen. Jinak vrací None.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/connector/slide/) | Vrací nadřazený snímek tvaru.<br/>            Pouze pro čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/connector/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/cs/aspose.slides/connector/shape_style/) | Vrací objekt stylu tvaru.<br/>            Pouze pro čtení [`IShapeStyle`](/slides/python-net/cs/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/cs/aspose.slides/connector/shape_type/) | Vrací nebo nastavuje typ AutoShape.<br/>            Čtení/Zápis [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/cs/aspose.slides/connector/adjustments/) | Vrací kolekci hodnot úprav tvaru.<br/>            Pouze pro čtení [`IAdjustValueCollection`](/slides/python-net/cs/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/cs/aspose.slides/connector/connector_lock/) | Vrací zámky konektoru.<br/>            Pouze pro čtení [`IConnectorLock`](/slides/python-net/cs/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/cs/aspose.slides/connector/start_shape_connected_to/) | Vrací nebo nastavuje tvar, ke kterému je připojen začátek konektoru.<br/>            Čtení/Zápis [`IShape`](/slides/python-net/cs/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/cs/aspose.slides/connector/end_shape_connected_to/) | Vrací nebo nastavuje tvar, ke kterému je připojen konec konektoru.<br/>            Čtení/Zápis [`IShape`](/slides/python-net/cs/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/cs/aspose.slides/connector/start_shape_connection_site_index/) | Vrací nebo nastavuje index připojovacího místa pro počáteční tvar.<br/>            Čtení/Zápis **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/cs/aspose.slides/connector/end_shape_connection_site_index/) | Vrací nebo nastavuje index připojovacího místa pro koncový tvar.<br/>            Čtení/Zápis **int**. |

## Metody

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/connector/get_image/#) | Vrací miniaturu tvaru.<br/>            Typ ShapeThumbnailBounds.Shape se používá jako výchozí. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/connector/write_as_svg/#iorawiobase) | Ukládá obsah Shape jako SVG soubor. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Ukládá obsah Shape jako SVG soubor. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/connector/remove_placeholder/#) | Definuje, že tento tvar není zástupcem. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/connector/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupce na zadaný. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/connector/get_base_placeholder/#) | Vrací základní tvar zástupce (tvar z rozvržení a/nebo hlavní snímku, ze kterého je aktuální tvar zděděn).<br/>            Vrací None, pokud aktuální tvar není zděděn. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides/connector/get_visual_bounds/#) | Získá vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu. |
| [`get_geometry_paths(self)`](/slides/python-net/cs/aspose.slides/connector/get_geometry_paths/#) | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/cs/aspose.slides/connector/set_geometry_path/#igeometrypath) | Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>             hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/cs/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrii tvaru z pole [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>             hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/cs/aspose.slides/connector/create_shape_elements/#) | Vytvoří a vrátí pole elementů tvaru. |
| [`reroute(self)`](/slides/python-net/cs/aspose.slides/connector/reroute/#) | Přesměruje konektor tak, aby zvolil nejkratší možnou cestu mezi tvary, které spojuje. |

### Viz také
* třída [`Connector`](/slides/python-net/cs/aspose.slides/connector)
* třída [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)