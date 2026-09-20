---
title: OleObjectFrame class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/oleobjectframe/
---
## OleObjectFrame třída

Zastupuje OLE objekt na snímku.

**Dědičnost:**[`OleObjectFrame`](/slides/python-net/cs/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

Typ OleObjectFrame exponuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/oleobjectframe/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze pro čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/oleobjectframe/placeholder/) | Vrací zástupný prvek pro tvar. Vrací None, pokud tvar nemá žádný zástupný prvek.<br/>            Pouze pro čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/oleobjectframe/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/oleobjectframe/raw_frame/) | Vrací nebo nastavuje vlastnosti surového rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/oleobjectframe/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/oleobjectframe/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti čáry.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/oleobjectframe/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje 3D efektové vlastnosti pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají 3D vlastnosti.<br/>            Pouze pro čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/oleobjectframe/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají efektové vlastnosti.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/oleobjectframe/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti formátování výplně pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají vlastnosti výplně.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/oleobjectframe/hyperlink_click/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro najetí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/oleobjectframe/hyperlink_manager/) | Vrací správce hypertextových odkazů.<br/>            Pouze pro čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides/oleobjectframe/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/oleobjectframe/z_order_position/) | Vrací pozici tvaru v z-řádu.<br/>            Shapes[0] vrací tvar na zadní pozici z-řádu,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na přední pozici z-řádu.<br/>            Pouze pro čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/oleobjectframe/connection_site_count/) | Vrací počet spojovacích míst na tvaru.<br/>            Pouze pro čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/oleobjectframe/rotation/) | Vrací nebo nastavuje počet stupňů, o které je daný tvar otočen kolem<br/>            osy z. Kladná hodnota označuje otočení ve směru hodinových ručiček; záporná hodnota<br/>            označuje otočení proti směru hodinových ručiček.<br/>            Čtení/zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/oleobjectframe/x/) | Vrací nebo nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/oleobjectframe/y/) | Vrací nebo nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/oleobjectframe/width/) | Vrací nebo nastavuje šířku tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/oleobjectframe/height/) | Vrací nebo nastavuje výšku tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/oleobjectframe/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení..<br/>            Čtení/zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/oleobjectframe/unique_id/) | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována<br/>            za trvalý jedinečný klíč.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/oleobjectframe/office_interop_shape_id/) | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou dobu existence tvaru a<br/>            umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/oleobjectframe/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Čtení/zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/oleobjectframe/alternative_text_title/) | Vrací nebo nastavuje titulek alternativního textu spojeného s tvarem.<br/>            Čtení/zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/oleobjectframe/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nesmí být None. Použijte prázdný řetězec, pokud je potřeba.<br/>            Čtení/zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/oleobjectframe/is_decorative/) | Vrací nebo nastavuje volbu 'Označit jako dekorativní'<br/>            Čtení/zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/oleobjectframe/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/oleobjectframe/is_grouped/) | Určuje, zda je tvar seskupený.<br/>            Pouze pro čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides/oleobjectframe/parent_group/) | Vrací nadřazený objekt GroupShape, pokud je tvar seskupený. Jinak vrací None.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/oleobjectframe/slide/) | Vrací nadřazený snímek tvaru.<br/>            Pouze pro čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/oleobjectframe/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/cs/aspose.slides/oleobjectframe/graphical_object_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/cs/aspose.slides/oleobjectframe/substitute_picture_format/) | Vrací objekt vlastností výplně obrázku OleObject.<br/>            Pouze pro čtení [`IPictureFillFormat`](/slides/python-net/cs/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/cs/aspose.slides/oleobjectframe/substitute_picture_title/) | Vrací nebo nastavuje titulek ikony OleObject.<br/>            Čtení/zápis **str**. |
| [`object_name`](/slides/python-net/cs/aspose.slides/oleobjectframe/object_name/) | Vrací nebo nastavuje název objektu.<br/>            Čtení/zápis **str**. |
| [`object_prog_id`](/slides/python-net/cs/aspose.slides/oleobjectframe/object_prog_id/) | Vrací ProgID objektu.<br/>            Pouze pro čtení **str**. |
| [`link_file_name`](/slides/python-net/cs/aspose.slides/oleobjectframe/link_file_name/) | Vrací úplnou cestu k propojenému souboru. Použije se krátký název souboru.<br/>            Pouze pro čtení **str**. |
| [`link_path_long`](/slides/python-net/cs/aspose.slides/oleobjectframe/link_path_long/) | Vrací úplnou cestu k propojenému souboru. Použije se dlouhý název souboru.<br/>            Čtení/zápis **str**. |
| [`link_path_relative`](/slides/python-net/cs/aspose.slides/oleobjectframe/link_path_relative/) | Vrací relativní cestu k propojenému souboru, pokud existuje, jinak vrací prázdný řetězec.<br/>             Pouze pro čtení **str**. |
| [`embedded_file_label`](/slides/python-net/cs/aspose.slides/oleobjectframe/embedded_file_label/) | Vrací název souboru vloženého OLE objektu |
| [`embedded_file_name`](/slides/python-net/cs/aspose.slides/oleobjectframe/embedded_file_name/) | Vrací cestu k vloženému OLE objektu |
| [`embedded_data`](/slides/python-net/cs/aspose.slides/oleobjectframe/embedded_data/) | Vrací nebo nastavuje informace o vložených OLE datech.<br/>            Čtení/zápis [`IOleEmbeddedDataInfo`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/cs/aspose.slides/oleobjectframe/is_object_icon/) | Určuje, zda je objekt viditelný jako ikona.<br/>            Čtení/zápis **bool**. |
| [`is_object_link`](/slides/python-net/cs/aspose.slides/oleobjectframe/is_object_link/) | Určuje, zda je objekt propojen s externím souborem.<br/>            Pouze pro čtení **bool**. |
| [`update_automatic`](/slides/python-net/cs/aspose.slides/oleobjectframe/update_automatic/) | Určuje, jestli je propojený vložený objekt automaticky aktualizován při otevření nebo tisku prezentace.<br/>            Čtení/zápis **bool**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/oleobjectframe/get_image/#) | Vrací miniaturu tvaru.<br/>            Typ ShapeThumbnailBounds.Shape pro ohraničení miniatury tvaru se používá jako výchozí. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Ukládá obsah tvaru jako soubor SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Ukládá obsah tvaru jako soubor SVG. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/oleobjectframe/remove_placeholder/#) | Definuje, že tento tvar není zástupný prvek. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud žádný není, a nastaví vlastnosti zástupného prvku na zadaný. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/oleobjectframe/get_base_placeholder/#) | Vrací základní tvar zástupného prvku (tvar z rozložení a/nebo master snímku, ze kterého je aktuální tvar děděn).<br/>            Vrací None, pokud aktuální tvar není děděn. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides/oleobjectframe/get_visual_bounds/#) | Vrací vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/cs/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Nastavuje informace o vložených OLE datech.<br/>            <br/>            Tato metoda mění vlastnosti objektu tak, aby odrážely nová data a <br/>            nastaví příznak IsObjectLink na false, což naznačuje, že OLE objekt je vložený. |

### Viz také
* třída [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject)
* třída [`OleObjectFrame`](/slides/python-net/cs/aspose.slides/oleobjectframe)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)