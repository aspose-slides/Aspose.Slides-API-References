---
title: AudioFrame class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/audioframe/
---
## AudioFrame třída

Představuje zvukový klip na snímku.

**Dědičnost:**[`AudioFrame`](/slides/python-net/cs/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/cs/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

Typ AudioFrame obsahuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/audioframe/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze pro čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/audioframe/placeholder/) | Vrací zástupný prvek pro tvar. Vrací None, pokud tvar nemá zástupný prvek.<br/>            Pouze pro čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/audioframe/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/audioframe/raw_frame/) | Vrací nebo nastaví surové vlastnosti rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/audioframe/frame/) | Vrací nebo nastaví vlastnosti rámce tvaru.<br/>            Čtení/zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/audioframe/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti čáry.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/audioframe/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje 3D efektní vlastnosti pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají 3D vlastnosti.<br/>            Pouze pro čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/audioframe/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti efektu.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/audioframe/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně formátování pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti výplně.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/audioframe/hyperlink_click/) | Vrací nebo nastaví hyperodkaz definovaný pro kliknutí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/audioframe/hyperlink_mouse_over/) | Vrací nebo nastaví hyperodkaz definovaný pro přejetí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/audioframe/hyperlink_manager/) | Vrací správce hyperodkazů.<br/>            Pouze pro čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides/audioframe/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/audioframe/z_order_position/) | Vrací pozici tvaru v z-řadě.<br/>            Shapes[0] vrací tvar na zadní pozici z-řady,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na přední pozici z-řady.<br/>            Pouze pro čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/audioframe/connection_site_count/) | Vrací počet připojovacích míst na tvaru.<br/>            Pouze pro čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/audioframe/rotation/) | Vrací nebo nastaví počet stupňů, o které je určený tvar otočen kolem z-osy.<br/>            Kladná hodnota označuje otáčení po směru hodinových ručiček; záporná hodnota<br/>            označuje otáčení proti směru hodinových ručiček.<br/>            Čtení/zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/audioframe/x/) | Získá nebo nastaví souřadnici x levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/audioframe/y/) | Získá nebo nastaví souřadnici y levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/audioframe/width/) | Získá nebo nastaví šířku tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/audioframe/height/) | Získá nebo nastaví výšku tvaru, měřenou v bodech.<br/>            Čtení/zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/audioframe/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení..<br/>            Čtení/zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/audioframe/unique_id/) | Vrací interní identifikátor v rozsahu prezentace určený pro použití doplňky nebo jiným kódem.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována<br/>            za trvalý jedinečný klíč.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/audioframe/office_interop_shape_id/) | Vrací jedinečný identifikátor v rozsahu snímku, který zůstává konstantní po celou životnost tvaru a<br/>            umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/audioframe/alternative_text/) | Vrací nebo nastaví alternativní text spojený s tvarem.<br/>            Čtení/zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/audioframe/alternative_text_title/) | Vrací nebo nastaví název alternativního textu spojeného s tvarem.<br/>            Čtení/zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/audioframe/name/) | Vrací nebo nastaví název tvaru.<br/>            Nesmí být None. Použijte prázdný řetězec, pokud je to potřeba.<br/>            Čtení/zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/audioframe/is_decorative/) | Získá nebo nastaví možnost 'Označit jako dekorativní'<br/>            Čtení/zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/audioframe/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IPictureFrameLock`](/slides/python-net/cs/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/audioframe/is_grouped/) | Určuje, zda je tvar seskupen.<br/>            Pouze pro čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides/audioframe/parent_group/) | Vrací objekt GroupShape rodiče, pokud je tvar seskupen. Jinak vrací None.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/audioframe/slide/) | Vrací nadřízený snímek tvaru.<br/>            Pouze pro čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/audioframe/presentation/) | Vrací nadřízenou prezentaci snímku.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/cs/aspose.slides/audioframe/shape_style/) | Vrací objekt stylu tvaru.<br/>            Pouze pro čtení [`IShapeStyle`](/slides/python-net/cs/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/cs/aspose.slides/audioframe/shape_type/) | Vrací nebo nastaví typ AutoShape pro PictureFrame.<br/>            Všechna položky ze sady [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) jsou povoleny, <br/>            kromě všech druhů čar:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Čtení/zápis [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/cs/aspose.slides/audioframe/adjustments/) | Vrací kolekci hodnot úprav tvaru.<br/>            Pouze pro čtení [`IAdjustValueCollection`](/slides/python-net/cs/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/cs/aspose.slides/audioframe/picture_frame_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IPictureFrameLock`](/slides/python-net/cs/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/cs/aspose.slides/audioframe/picture_format/) | Vrací objekt PictureFillFormat pro rámeček obrázku.<br/>            Pouze pro čtení [`IPictureFillFormat`](/slides/python-net/cs/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/cs/aspose.slides/audioframe/relative_scale_height/) | Vrací nebo nastaví měřítko výšky (relativně k původní velikosti obrázku) rámečku obrázku. Hodnota 1.0 odpovídá 100 %.<br/>            Čtení/zápis **float**. |
| [`relative_scale_width`](/slides/python-net/cs/aspose.slides/audioframe/relative_scale_width/) | Vrací nebo nastaví měřítko šířky (relativně k původní velikosti obrázku) rámečku obrázku. Hodnota 1.0 odpovídá 100 %.<br/>            Čtení/zápis **float**. |
| [`is_cameo`](/slides/python-net/cs/aspose.slides/audioframe/is_cameo/) | Určuje, zda je PictureFrame objektem Cameo či nikoliv.<br/>            Pouze pro čtení **bool**. |
| [`audio_cd_start_track`](/slides/python-net/cs/aspose.slides/audioframe/audio_cd_start_track/) | Vrací nebo nastaví počáteční index stopy.<br/>            Čtení/zápis **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/cs/aspose.slides/audioframe/audio_cd_start_track_time/) | Vrací nebo nastaví čas začátku stopy.<br/>            Čtení/zápis **int**. |
| [`audio_cd_end_track`](/slides/python-net/cs/aspose.slides/audioframe/audio_cd_end_track/) | Vrací nebo nastaví poslední index stopy<br/>            Čtení/zápis **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/cs/aspose.slides/audioframe/audio_cd_end_track_time/) | Vrací nebo nastaví čas konce stopy.<br/>            Čtení/zápis **int**. |
| [`volume`](/slides/python-net/cs/aspose.slides/audioframe/volume/) | Vrací nebo nastaví hlasitost zvuku.<br/>            Čtení/zápis [`AudioVolumeMode`](/slides/python-net/cs/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/cs/aspose.slides/audioframe/play_mode/) | Vrací nebo nastaví režim přehrávání zvuku.<br/>            Čtení/zápis [`AudioPlayModePreset`](/slides/python-net/cs/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/cs/aspose.slides/audioframe/hide_at_showing/) | Určuje, zda je AudioFrame skrytý.<br/>            Čtení/zápis **bool**. |
| [`play_loop_mode`](/slides/python-net/cs/aspose.slides/audioframe/play_loop_mode/) | Určuje, zda se zvuk přehrává ve smyčce.<br/>            Čtení/zápis **bool**. |
| [`play_across_slides`](/slides/python-net/cs/aspose.slides/audioframe/play_across_slides/) | Určuje, zda se zvuk přehrává napříč snímky.<br/>            Čtení/zápis **bool**. |
| [`rewind_audio`](/slides/python-net/cs/aspose.slides/audioframe/rewind_audio/) | Určuje, zda se zvuk automaticky po přehrání přetočí na začátek.<br/>            Čtení/zápis **bool**. |
| [`embedded`](/slides/python-net/cs/aspose.slides/audioframe/embedded/) | Určuje, zda je zvuk vložen do prezentace.<br/>            Pouze pro čtení **bool**. |
| [`link_path_long`](/slides/python-net/cs/aspose.slides/audioframe/link_path_long/) | Vrací nebo nastaví název zvukového souboru, který je propojen s AudioFrame.<br/>            Čtení/zápis **str**. |
| [`embedded_audio`](/slides/python-net/cs/aspose.slides/audioframe/embedded_audio/) | Vrací nebo nastaví vložený zvukový objekt.<br/>            Čtení/zápis [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/cs/aspose.slides/audioframe/fade_in_duration/) | Určuje časové trvání počátečního fade-in médií v milisekundách.<br/>            Čtení/zápis **float**. |
| [`fade_out_duration`](/slides/python-net/cs/aspose.slides/audioframe/fade_out_duration/) | Určuje časové trvání koncového fade-out médií v milisekundách.<br/>            Čtení/zápis **float**. |
| [`volume_value`](/slides/python-net/cs/aspose.slides/audioframe/volume_value/) | Vrací nebo nastaví hlasitost zvuku v procentech.<br/>            Čtení/zápis **float**. |
| [`trim_from_start`](/slides/python-net/cs/aspose.slides/audioframe/trim_from_start/) | Určuje časové trvání, které má být při přehrávání odebráno od začátku médií, v milisekundách.<br/>            Čtení/zápis **float**. |
| [`trim_from_end`](/slides/python-net/cs/aspose.slides/audioframe/trim_from_end/) | Určuje časové trvání, které má být při přehrávání odebráno od konce médií, v milisekundách.<br/>            Čtení/zápis **float**. |
| [`caption_tracks`](/slides/python-net/cs/aspose.slides/audioframe/caption_tracks/) | Získá kolekci skrytých titulků spojených s audio rámcem.<br/>            Tato vlastnost je pouze pro čtení a vrací [`ICaptionsCollection`](/slides/python-net/cs/aspose.slides/icaptionscollection) obsahující všechny stopy titulků. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/audioframe/get_image/#) | Vrací miniaturu tvaru.<br/>            Výchozí je použita hodnota ShapeThumbnailBounds.Shape pro omezení miniatury tvaru. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Uloží obsah tvaru jako soubor SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Uloží obsah tvaru jako soubor SVG. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/audioframe/remove_placeholder/#) | Definuje, že tento tvar není zástupný prvek. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud žádný není, a nastaví jeho vlastnosti na zadané. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/audioframe/get_base_placeholder/#) | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar odvozen).<br/>            Vrací None, pokud aktuální tvar není odvozen. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides/audioframe/get_visual_bounds/#) | Získá vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu. |
| [`get_geometry_paths(self)`](/slides/python-net/cs/aspose.slides/audioframe/get_geometry_paths/#) | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/cs/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>             hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/cs/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrii tvaru z pole [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému<br/>             hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/cs/aspose.slides/audioframe/create_shape_elements/#) | Vytvoří a vrátí pole prvků tvaru. |

### Viz také
* třída [`AudioFrame`](/slides/python-net/cs/aspose.slides/audioframe)
* třída [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape)
* třída [`PictureFrame`](/slides/python-net/cs/aspose.slides/pictureframe)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)