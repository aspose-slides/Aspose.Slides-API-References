---
title: VideoFrame class
second_title: Aspose.Slides pro Python přes .NET API Referenci
description: 
type: docs
url: /cs/aspose.slides/videoframe/
---
## VideoFrame třída

Typ VideoFrame poskytuje následující členy.

**Dědičnost:**[`VideoFrame`](/slides/python-net/cs/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/cs/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/videoframe/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze ke čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/videoframe/placeholder/) | Vrací zástupný znak pro tvar. Vrací None, pokud tvar nemá zástupný znak.<br/>            Pouze ke čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/videoframe/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze ke čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/videoframe/raw_frame/) | Vrací nebo nastavuje vlastnosti surového rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/videoframe/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/videoframe/line_format/) | Vrací objekt LineFormat, který obsahuje nastavení čáry pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají čárové vlastnosti.<br/>            Pouze ke čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/videoframe/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje 3D efektové vlastnosti pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají 3D vlastnosti.<br/>            Pouze ke čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/videoframe/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají efektové vlastnosti.<br/>            Pouze ke čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/videoframe/fill_format/) | Vrací objekt FillFormat, který obsahuje nastavení výplně pro tvar.<br/>            Poznámka: může vrátit None pro určité typy tvarů, které nemají výplňové vlastnosti.<br/>            Pouze ke čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/videoframe/hyperlink_click/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/videoframe/hyperlink_mouse_over/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro přechod myši.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/videoframe/hyperlink_manager/) | Vrací správce hypertextových odkazů.<br/>            Pouze ke čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides/videoframe/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/Zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/videoframe/z_order_position/) | Vrací pozici tvaru v z-pořadí.<br/>            Shapes[0] vrací tvar na zadní straně z-pořadí,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na přední straně z-pořadí.<br/>            Pouze ke čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/videoframe/connection_site_count/) | Vrací počet připojených míst na tvaru.<br/>            Pouze ke čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/videoframe/rotation/) | Vrací nebo nastavuje počet stupňů, o které je tvar otočen kolem osy z.<br/>            kladná hodnota značí otáčení po směru hodinových ručiček; záporná hodnota<br/>            značí otáčení proti směru hodinových ručiček.<br/>            Čtení/Zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/videoframe/x/) | Získává nebo nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/videoframe/y/) | Získává nebo nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/videoframe/width/) | Získává nebo nastavuje šířku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/videoframe/height/) | Získává nebo nastavuje výšku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/videoframe/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílé zobrazování..<br/>            Čtení/Zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/videoframe/unique_id/) | Vrací interní, prezentací omezený identifikátor určený pro použití doplňky nebo jiný kód.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována<br/>            za trvalý jedinečný klíč.<br/>            Pouze ke čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/videoframe/office_interop_shape_id/) | Vrací jedinečný identifikátor omezený na snímek, který zůstává konstantní po celou dobu existence tvaru a<br/>            umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze ke čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/videoframe/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Čtení/Zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/videoframe/alternative_text_title/) | Vrací nebo nastavuje nadpis alternativního textu spojeného s tvarem.<br/>            Čtení/Zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/videoframe/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nesmí být None. Použijte prázdný řetězec, pokud je potřeba.<br/>            Čtení/Zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/videoframe/is_decorative/) | Získává nebo nastavuje možnost „Označit jako dekorativní“<br/>            Čtení/Zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/videoframe/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze ke čtení [`IPictureFrameLock`](/slides/python-net/cs/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/videoframe/is_grouped/) | Určuje, zda je tvar seskupený.<br/>            Pouze ke čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides/videoframe/parent_group/) | Vrací objekt GroupShape rodiče, pokud je tvar seskupen. Jinak vrací None.<br/>            Pouze ke čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/videoframe/slide/) | Vrací rodičovský snímek tvaru.<br/>            Pouze ke čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/videoframe/presentation/) | Vrací rodičovskou prezentaci snímku.<br/>            Pouze ke čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/cs/aspose.slides/videoframe/shape_style/) | Vrací objekt stylu tvaru.<br/>            Pouze ke čtení [`IShapeStyle`](/slides/python-net/cs/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/cs/aspose.slides/videoframe/shape_type/) | Vrací nebo nastavuje typ AutoShape pro PictureFrame.<br/>            Povolené jsou všechny položky ze sady [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype), <br/>            kromě všech druhů čar:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Čtení/Zápis [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/cs/aspose.slides/videoframe/adjustments/) | Vrací kolekci hodnot úprav tvaru.<br/>            Pouze ke čtení [`IAdjustValueCollection`](/slides/python-net/cs/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/cs/aspose.slides/videoframe/picture_frame_lock/) | Vrací zámky tvaru.<br/>            Pouze ke čtení [`IPictureFrameLock`](/slides/python-net/cs/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/cs/aspose.slides/videoframe/picture_format/) | Vrací objekt PictureFillFormat pro rámec obrázku.<br/>            Pouze ke čtení [`IPictureFillFormat`](/slides/python-net/cs/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/cs/aspose.slides/videoframe/relative_scale_height/) | Vrací nebo nastavuje měřítko výšky (relativně k originální velikosti obrázku) pro rámec obrázku. Hodnota 1.0 odpovídá 100 %.<br/>            Čtení/Zápis **float**. |
| [`relative_scale_width`](/slides/python-net/cs/aspose.slides/videoframe/relative_scale_width/) | Vrací nebo nastavuje měřítko šířky (relativně k originální velikosti obrázku) pro rámec obrázku. Hodnota 1.0 odpovídá 100 %.<br/>            Čtení/Zápis **float**. |
| [`is_cameo`](/slides/python-net/cs/aspose.slides/videoframe/is_cameo/) | Určuje, zda je PictureFrame objekt Cameo nebo ne.<br/>            Pouze ke čtení **bool**. |
| [`rewind_video`](/slides/python-net/cs/aspose.slides/videoframe/rewind_video/) | Určuje, zda se video automaticky přetočí na začátek<br/>            jakmile přehrávání skončí.<br/>            Čtení/Zápis **bool**. |
| [`play_loop_mode`](/slides/python-net/cs/aspose.slides/videoframe/play_loop_mode/) | Určuje, zda je video v smyčce.<br/>            Čtení/Zápis **bool**. |
| [`hide_at_showing`](/slides/python-net/cs/aspose.slides/videoframe/hide_at_showing/) | Určuje, zda je VideoFrame skrytý.<br/>            Čtení/Zápis **bool**. |
| [`volume`](/slides/python-net/cs/aspose.slides/videoframe/volume/) | Vrací nebo nastavuje hlasitost zvuku.<br/>            Čtení/Zápis [`AudioVolumeMode`](/slides/python-net/cs/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/cs/aspose.slides/videoframe/play_mode/) | Vrací nebo nastavuje režim přehrávání videa.<br/>            Čtení/Zápis [`VideoPlayModePreset`](/slides/python-net/cs/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/cs/aspose.slides/videoframe/full_screen_mode/) | Určuje, zda se video zobrazuje v režimu celé obrazovky.<br/>            Čtení/Zápis **bool**. |
| [`link_path_long`](/slides/python-net/cs/aspose.slides/videoframe/link_path_long/) | Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame.<br/>            Čtení/Zápis **str**. |
| [`embedded_video`](/slides/python-net/cs/aspose.slides/videoframe/embedded_video/) | Vrací nebo nastavuje vložený objekt videa.<br/>            Čtení/Zápis [`IVideo`](/slides/python-net/cs/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/cs/aspose.slides/videoframe/trim_from_start/) | Oříznout začátek [ms] |
| [`trim_from_end`](/slides/python-net/cs/aspose.slides/videoframe/trim_from_end/) | Oříznout konec [ms] |
| [`caption_tracks`](/slides/python-net/cs/aspose.slides/videoframe/caption_tracks/) | Vrací kolekci uzavřených titulků spojených s video rámcem.<br/>             Tato vlastnost je pouze ke čtení a vrací [`ICaptionsCollection`](/slides/python-net/cs/aspose.slides/icaptionscollection) obsahující všechny stopy titulků. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/videoframe/get_image/#) | Vrací miniaturu tvaru.<br/>            ShapeThumbnailBounds.Shape typ ohraničení miniatury tvaru se používá ve výchozím nastavení. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Ukládá obsah tvaru jako SVG soubor. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Ukládá obsah tvaru jako SVG soubor. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/videoframe/remove_placeholder/#) | Definuje, že tento tvar není zástupný znak. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Přidá nový zástupný znak, pokud neexistuje, a nastaví vlastnosti zástupného znaku na specifikovaný. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/videoframe/get_base_placeholder/#) | Vrací základní tvar zástupného místa (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn).<br/>            Vrací None, pokud aktuální tvar není zděděn. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides/videoframe/get_visual_bounds/#) | Získává vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu. |
| [`get_geometry_paths(self)`](/slides/python-net/cs/aspose.slides/videoframe/get_geometry_paths/#) | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/cs/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>             hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/cs/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrii tvaru z pole [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>             hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/cs/aspose.slides/videoframe/create_shape_elements/#) | Vytvoří a vrátí pole prvků tvaru. |

### Viz také
* třída [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape)
* třída [`PictureFrame`](/slides/python-net/cs/aspose.slides/pictureframe)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* třída [`VideoFrame`](/slides/python-net/cs/aspose.slides/videoframe)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)