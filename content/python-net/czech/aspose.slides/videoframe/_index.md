---
title: VideoFrame class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/videoframe/
---
## VideoFrame třída

Reprezentuje video klip na snímku.

**Dědičnost:**[`VideoFrame`](/slides/python-net/cs/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/cs/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

Typ VideoFrame vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/videoframe/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Pouze pro čtení **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides/videoframe/placeholder/) | Vrací zástupný prvek pro tvar. Vrací None, pokud tvar nemá zástupný prvek.<br/>            Pouze pro čtení [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/videoframe/custom_data/) | Vrací vlastní data tvaru.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/videoframe/raw_frame/) | Vrací nebo nastavuje surové vlastnosti rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides/videoframe/frame/) | Vrací nebo nastavuje vlastnosti rámce tvaru.<br/>            Čtení/Zápis [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides/videoframe/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti čáry.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/videoframe/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje 3D efektní vlastnosti tvaru.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají 3D vlastnosti.<br/>            Pouze pro čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/videoframe/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti efektu.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/videoframe/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti formátování výplně pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti výplně.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/videoframe/hyperlink_click/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/videoframe/hyperlink_mouse_over/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší.<br/>            Čtení/Zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/videoframe/hyperlink_manager/) | Vrací správce hypertextových odkazů.<br/>            Pouze pro čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides/videoframe/hidden/) | Určuje, zda je tvar skrytý.<br/>            Čtení/Zápis **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/videoframe/z_order_position/) | Vrací pozici tvaru v z-řadě.<br/>            Shapes[0] vrací tvar na zadní části z-řady,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na přední části z-řady.<br/>            Pouze pro čtení **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/videoframe/connection_site_count/) | Vrací počet připojovacích míst na tvaru.<br/>            Pouze pro čtení **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides/videoframe/rotation/) | Vrací nebo nastavuje počet stupňů, o které je daný tvar otočen kolem osy z.<br/>            Kladná hodnota značí otáčení ve směru hodinových ručiček; záporná hodnota<br/>            značí otáčení proti směru hodinových ručiček.<br/>            Čtení/Zápis **float**. |
| [`x`](/slides/python-net/cs/aspose.slides/videoframe/x/) | Vrací nebo nastavuje x-ovou souřadnici levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides/videoframe/y/) | Vrací nebo nastavuje y-ovou souřadnici levého horního rohu tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides/videoframe/width/) | Vrací nebo nastavuje šířku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/videoframe/height/) | Vrací nebo nastavuje výšku tvaru, měřenou v bodech.<br/>            Čtení/Zápis **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/videoframe/black_white_mode/) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení.<br/>            Čtení/Zápis [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides/videoframe/unique_id/) | Vrací interní identifikátor v rámci prezentace určený k použití doplňky nebo jiným kódem.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, neměla by být považována<br/>            za trvalý jedinečný klíč.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/videoframe/office_interop_shape_id/) | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Pouze pro čtení **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/videoframe/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Čtení/Zápis **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/videoframe/alternative_text_title/) | Vrací nebo nastavuje titulek alternativního textu spojeného s tvarem.<br/>            Čtení/Zápis **str**. |
| [`name`](/slides/python-net/cs/aspose.slides/videoframe/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nemůže být None. V případě potřeby použijte prázdný řetězec.<br/>            Čtení/Zápis **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/videoframe/is_decorative/) | Vrací nebo nastavuje volbu 'Označit jako dekorativní'<br/>            Čtení/Zápis **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/videoframe/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IPictureFrameLock`](/slides/python-net/cs/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/videoframe/is_grouped/) | Určuje, zda je tvar seskupený.<br/>            Pouze pro čtení **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides/videoframe/parent_group/) | Vrací nadřazený objekt GroupShape, pokud je tvar seskupen. Jinak vrací None.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides/videoframe/slide/) | Vrací nadřazený snímek tvaru.<br/>            Pouze pro čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/videoframe/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/cs/aspose.slides/videoframe/shape_style/) | Vrací objekt stylu tvaru.<br/>            Pouze pro čtení [`IShapeStyle`](/slides/python-net/cs/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/cs/aspose.slides/videoframe/shape_type/) | Vrací nebo nastavuje typ AutoShape pro PictureFrame.<br/>            Přípustné jsou všechny položky ze sady [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype), <br/>            kromě všech druhů čar:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Čtení/Zápis [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/cs/aspose.slides/videoframe/adjustments/) | Vrací kolekci hodnot úpravy tvaru.<br/>            Pouze pro čtení [`IAdjustValueCollection`](/slides/python-net/cs/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/cs/aspose.slides/videoframe/picture_frame_lock/) | Vrací zámky tvaru.<br/>            Pouze pro čtení [`IPictureFrameLock`](/slides/python-net/cs/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/cs/aspose.slides/videoframe/picture_format/) | Vrací objekt PictureFillFormat pro rámeček obrázku.<br/>            Pouze pro čtení [`IPictureFillFormat`](/slides/python-net/cs/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/cs/aspose.slides/videoframe/relative_scale_height/) | Vrací nebo nastavuje měřítko výšky (relativně k původní velikosti obrázku) rámečku obrázku. Hodnota 1.0 odpovídá 100 %.<br/>            Čtení/Zápis **float**. |
| [`relative_scale_width`](/slides/python-net/cs/aspose.slides/videoframe/relative_scale_width/) | Vrací nebo nastavuje měřítko šířky (relativně k původní velikosti obrázku) rámečku obrázku. Hodnota 1.0 odpovídá 100 %.<br/>            Čtení/Zápis **float**. |
| [`is_cameo`](/slides/python-net/cs/aspose.slides/videoframe/is_cameo/) | Určuje, zda je PictureFrame objektem Cameo, či nikoli.<br/>            Pouze pro čtení **bool**. |
| [`rewind_video`](/slides/python-net/cs/aspose.slides/videoframe/rewind_video/) | Určuje, zda se video automaticky přetáčí na začátek<br/>            hned po dokončení přehrávání.<br/>            Čtení/Zápis **bool**. |
| [`play_loop_mode`](/slides/python-net/cs/aspose.slides/videoframe/play_loop_mode/) | Určuje, zda je video smyčkované.<br/>            Čtení/Zápis **bool**. |
| [`hide_at_showing`](/slides/python-net/cs/aspose.slides/videoframe/hide_at_showing/) | Určuje, zda je VideoFrame skrytý.<br/>            Čtení/Zápis **bool**. |
| [`volume`](/slides/python-net/cs/aspose.slides/videoframe/volume/) | Vrací nebo nastavuje hlasitost zvuku.<br/>            Čtení/Zápis [`AudioVolumeMode`](/slides/python-net/cs/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/cs/aspose.slides/videoframe/volume_value/) | Vrací nebo nastavuje přesnou hlasitost videa jako procento.<br/>            Hodnota je vyjádřena v procentech od 0 do 100. Použijte tuto vlastnost<br/>            k načtení nebo nastavení hodnot hlasitosti, které jsou přesnější než předdefinované<br/>            úrovně dostupné přes vlastnost [`VideoFrame.volume`](/slides/python-net/cs/aspose.slides/videoframe/volume).<br/>            Čtení/Zápis **float**. |
| [`play_mode`](/slides/python-net/cs/aspose.slides/videoframe/play_mode/) | Vrací nebo nastavuje režim přehrávání videa.<br/>            Čtení/Zápis [`VideoPlayModePreset`](/slides/python-net/cs/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/cs/aspose.slides/videoframe/full_screen_mode/) | Určuje, zda je video zobrazováno v režimu celé obrazovky.<br/>            Čtení/Zápis **bool**. |
| [`link_path_long`](/slides/python-net/cs/aspose.slides/videoframe/link_path_long/) | Vrací nebo nastavuje název video souboru, který je propojen s VideoFrame.<br/>            Čtení/Zápis **str**. |
| [`embedded_video`](/slides/python-net/cs/aspose.slides/videoframe/embedded_video/) | Vrací nebo nastavuje vložený video objekt.<br/>            Čtení/Zápis [`IVideo`](/slides/python-net/cs/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/cs/aspose.slides/videoframe/trim_from_start/) | Oříznout začátek [ms] |
| [`trim_from_end`](/slides/python-net/cs/aspose.slides/videoframe/trim_from_end/) | Oříznout konec [ms] |
| [`caption_tracks`](/slides/python-net/cs/aspose.slides/videoframe/caption_tracks/) | Vrací kolekci uzavřených titulků spojených s video rámečkem.<br/>             Tato vlastnost je pouze pro čtení a vrací [`ICaptionsCollection`](/slides/python-net/cs/aspose.slides/icaptionscollection) obsahující všechny stopky titulků. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/videoframe/get_image/#) | Vrací miniaturu tvaru.<br/>            Výchozí typ ohraničení miniatury tvaru ShapeThumbnailBounds.Shape je použit. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Ukládá obsah tvaru jako SVG soubor. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Ukládá obsah tvaru jako SVG soubor. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/videoframe/remove_placeholder/#) | Definuje, že tento tvar není zástupný prvek. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na zadaný. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/videoframe/get_base_placeholder/#) | Vrací základní zástupný tvar (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn).<br/>            Pokud aktuální tvar není zděděn, vrátí None. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides/videoframe/get_visual_bounds/#) | Vrací vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [`get_geometry_paths(self)`](/slides/python-net/cs/aspose.slides/videoframe/get_geometry_paths/#) | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/cs/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/cs/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Aktualizuje geometrii tvaru z pole [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru.<br/>             Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/cs/aspose.slides/videoframe/create_shape_elements/#) | Vytvoří a vrátí pole prvků tvaru. |

### Viz také
* třída [`GeometryShape`](/slides/python-net/cs/aspose.slides/geometryshape)
* třída [`PictureFrame`](/slides/python-net/cs/aspose.slides/pictureframe)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* třída [`VideoFrame`](/slides/python-net/cs/aspose.slides/videoframe)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)