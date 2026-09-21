---
title: AudioFrame class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/audioframe/
---
## AudioFrame klasse

Stelt een audioclips voor op een dia.

**Erfenis:**[`AudioFrame`](/slides/python-net/nl/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/nl/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

Het AudioFrame-type onthult de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/audioframe/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/audioframe/placeholder/) | Geeft de placeholder voor een vorm terug. Geeft None als de vorm geen placeholder heeft.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/audioframe/custom_data/) | Geeft de aangepaste gegevens van de vorm terug.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/audioframe/raw_frame/) | Geeft of stelt de ruwe vormframe-eigenschappen in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/audioframe/frame/) | Geeft of stelt de vormframe-eigenschappen in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/audioframe/line_format/) | Geeft het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde typen vormen die geen lijn-eigenschappen hebben.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/audioframe/three_d_format/) | Geeft het ThreeDFormat-object dat 3D-effect-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde typen vormen die geen 3D-eigenschappen hebben.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/audioframe/effect_format/) | Geeft het EffectFormat-object dat pixel-effecten op een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde typen vormen die geen effect-eigenschappen hebben.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/audioframe/fill_format/) | Geeft het FillFormat-object dat vul-opmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde typen vormen die geen vul-eigenschappen hebben.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/audioframe/hyperlink_click/) | Geeft of stelt de hyperlink in die is gedefinieerd voor muisklik.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/audioframe/hyperlink_mouse_over/) | Geeft of stelt de hyperlink in die is gedefinieerd voor muis-over.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/audioframe/hyperlink_manager/) | Geeft de hyperlink-manager terug.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/audioframe/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/Schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/audioframe/z_order_position/) | Geeft de positie van een vorm in de z-volgorde terug.<br/>            Shapes[0] geeft de vorm aan het einde van de z-volgorde,<br/>            en Shapes[Shapes.Count - 1] geeft de vorm aan het begin van de z-volgorde.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/audioframe/connection_site_count/) | Geeft het aantal verbindingspunten op de vorm terug.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/audioframe/rotation/) | Geeft of stelt het aantal graden in dat de opgegeven vorm rond de z-as wordt gedraaid<br/>            Een positieve waarde duidt op rotatie met de klok mee; een negatieve waarde<br/>            duidt op rotatie tegen de klok in.<br/>            Lezen/Schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/audioframe/x/) | Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/audioframe/y/) | Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/audioframe/width/) | Haalt of stelt de breedte van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/audioframe/height/) | Haalt of stelt de hoogte van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/audioframe/black_white_mode/) | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit modus..<br/>            Lezen/Schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/audioframe/unique_id/) | Geeft een interne, presentatiespecifieke identifier terug bedoeld voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden herkend, mag deze niet worden behandeld<br/>            als een persistente unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/audioframe/office_interop_shape_id/) | Geeft een dia-specifieke unieke identifier terug die constant blijft gedurende de levensduur van de vorm en<br/>            PowerPoint of interop-code betrouwbaar laat verwijzen naar de vorm vanaf overal in het document.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/audioframe/alternative_text/) | Geeft of stelt de alternatieve tekst bij een vorm in.<br/>            Lezen/Schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/audioframe/alternative_text_title/) | Geeft of stelt de titel van de alternatieve tekst bij een vorm in.<br/>            Lezen/Schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/audioframe/name/) | Geeft of stelt de naam van een vorm in.<br/>            Mag niet None zijn. Gebruik een lege tekenreeks indien nodig.<br/>            Lezen/Schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/audioframe/is_decorative/) | Haalt of stelt de optie ‘Mark as decorative’ in.<br/>            Lezen/Schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/audioframe/shape_lock/) | Geeft de vergrendelingen van de vorm terug.<br/>            Alleen-lezen [`IPictureFrameLock`](/slides/python-net/nl/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/audioframe/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/audioframe/parent_group/) | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Anders wordt None teruggegeven.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/audioframe/slide/) | Geeft de bovenliggende dia van een vorm terug.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/audioframe/presentation/) | Geeft de bovenliggende presentatie van een dia terug.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/nl/aspose.slides/audioframe/shape_style/) | Geeft het stijl-object van de vorm terug.<br/>            Alleen-lezen [`IShapeStyle`](/slides/python-net/nl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/nl/aspose.slides/audioframe/shape_type/) | Geeft of stelt het AutoShape-type voor een PictureFrame in.<br/>            Er zijn alle items van de set [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) toegestaan,<br/>            behalve alle soorten lijnen:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Lezen/Schrijven [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/nl/aspose.slides/audioframe/adjustments/) | Geeft een collectie van aanpassingswaarden van de vorm terug.<br/>            Alleen-lezen [`IAdjustValueCollection`](/slides/python-net/nl/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/nl/aspose.slides/audioframe/picture_frame_lock/) | Geeft de vergrendelingen van de vorm terug.<br/>            Alleen-lezen [`IPictureFrameLock`](/slides/python-net/nl/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/nl/aspose.slides/audioframe/picture_format/) | Geeft het PictureFillFormat-object voor een picture-frame terug.<br/>            Alleen-lezen [`IPictureFillFormat`](/slides/python-net/nl/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/nl/aspose.slides/audioframe/relative_scale_height/) | Geeft of stelt de schaal van de hoogte (relatief aan de originele afbeelding) van het picture-frame in. Waarde 1.0 staat gelijk aan 100%.<br/>            Lezen/Schrijven **float**. |
| [`relative_scale_width`](/slides/python-net/nl/aspose.slides/audioframe/relative_scale_width/) | Geeft of stelt de schaal van de breedte (relatief aan de originele afbeelding) van het picture-frame in. Waarde 1.0 staat gelijk aan 100%.<br/>            Lezen/Schrijven **float**. |
| [`is_cameo`](/slides/python-net/nl/aspose.slides/audioframe/is_cameo/) | Bepaalt of het PictureFrame een Cameo-object is of niet.<br/>            Alleen-lezen **bool**. |
| [`audio_cd_start_track`](/slides/python-net/nl/aspose.slides/audioframe/audio_cd_start_track/) | Geeft of stelt een start-track-index in.<br/>            Lezen/Schrijven **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/nl/aspose.slides/audioframe/audio_cd_start_track_time/) | Geeft of stelt een start-track-tijd in.<br/>            Lezen/Schrijven **int**. |
| [`audio_cd_end_track`](/slides/python-net/nl/aspose.slides/audioframe/audio_cd_end_track/) | Geeft of stelt een laatste-track-index in.<br/>            Lezen/Schrijven **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/nl/aspose.slides/audioframe/audio_cd_end_track_time/) | Geeft of stelt een laatste-track-tijd in.<br/>            Lezen/Schrijven **int**. |
| [`volume`](/slides/python-net/nl/aspose.slides/audioframe/volume/) | Geeft of stelt het audio-volume in.<br/>            Lezen/Schrijven [`AudioVolumeMode`](/slides/python-net/nl/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/nl/aspose.slides/audioframe/play_mode/) | Geeft of stelt de audio-afspeel-modus in.<br/>            Lezen/Schrijven [`AudioPlayModePreset`](/slides/python-net/nl/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/nl/aspose.slides/audioframe/hide_at_showing/) | Bepaalt of een AudioFrame verborgen is.<br/>            Lezen/Schrijven **bool**. |
| [`play_loop_mode`](/slides/python-net/nl/aspose.slides/audioframe/play_loop_mode/) | Bepaalt of audio wordt herhaald.<br/>            Lezen/Schrijven **bool**. |
| [`play_across_slides`](/slides/python-net/nl/aspose.slides/audioframe/play_across_slides/) | Bepaalt of audio over de dia`s heen wordt afgespeeld.<br/>            Lezen/Schrijven **bool**. |
| [`rewind_audio`](/slides/python-net/nl/aspose.slides/audioframe/rewind_audio/) | Bepaalt of audio automatisch wordt teruggespoeld naar het begin na het afspelen.<br/>            Lezen/Schrijven **bool**. |
| [`embedded`](/slides/python-net/nl/aspose.slides/audioframe/embedded/) | Bepaalt of een geluid is ingebed in een presentatie.<br/>            Alleen-lezen **bool**. |
| [`link_path_long`](/slides/python-net/nl/aspose.slides/audioframe/link_path_long/) | Geeft of stelt de naam van een audiobestand in dat aan een AudioFrame is gekoppeld.<br/>            Lezen/Schrijven **str**. |
| [`embedded_audio`](/slides/python-net/nl/aspose.slides/audioframe/embedded_audio/) | Geeft of stelt een ingesloten audio-object in.<br/>            Lezen/Schrijven [`IAudio`](/slides/python-net/nl/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/nl/aspose.slides/audioframe/fade_in_duration/) | Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden.<br/>            Lezen/Schrijven **float**. |
| [`fade_out_duration`](/slides/python-net/nl/aspose.slides/audioframe/fade_out_duration/) | Specificeert de tijdsduur voor de eind-fade-out van de media in milliseconden.<br/>            Lezen/Schrijven **float**. |
| [`volume_value`](/slides/python-net/nl/aspose.slides/audioframe/volume_value/) | Geeft of stelt het audio-volume in procenten in.<br/>            Lezen/Schrijven **float**. |
| [`trim_from_start`](/slides/python-net/nl/aspose.slides/audioframe/trim_from_start/) | Specificeert de tijdsduur die aan het begin van de media moet worden weggelaten tijdens afspelen, in milliseconden.<br/>            Lezen/Schrijven **float**. |
| [`trim_from_end`](/slides/python-net/nl/aspose.slides/audioframe/trim_from_end/) | Specificeert de tijdsduur die aan het einde van de media moet worden weggelaten tijdens afspelen, in milliseconden.<br/>            Lezen/Schrijven **float**. |
| [`caption_tracks`](/slides/python-net/nl/aspose.slides/audioframe/caption_tracks/) | Haalt de collectie van gesloten ondertitels op die aan het audio-frame zijn gekoppeld.<br/>            Deze eigenschap is alleen-lezen en geeft een [`ICaptionsCollection`](/slides/python-net/nl/aspose.slides/icaptionscollection) terug met alle ondertitel-tracks. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/audioframe/get_image/#) | Geeft een miniatuur van de vorm terug.<br/>            ShapeThumbnailBounds.Shape vormminiatuur-bounds-type wordt standaard gebruikt. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Geeft een miniatuur van de vorm terug. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/audioframe/remove_placeholder/#) | Definieert dat deze vorm geen placeholder is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/audioframe/get_base_placeholder/#) | Geeft een basisplaceholder-vorm terug (vorm van de lay-out en/of masterslide waarvan de huidige vorm is geërfd).<br/>            Een None wordt geretourneerd als de huidige vorm niet is geërfd. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/audioframe/get_visual_bounds/#) | Haalt de visuele grenzen van de vorm op, berekend uit de gerenderde inhoud. |
| [`get_geometry_paths(self)`](/slides/python-net/nl/aspose.slides/audioframe/get_geometry_paths/#) | Geeft een kopie van het pad van de geometrievorm terug. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/nl/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | Werkt de vormgeometrie bij vanuit [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)-object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm.<br/>            Wijzigt het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/nl/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | Werkt de vormgeometrie bij vanuit een array van [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm.<br/>            Wijzigt het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/nl/aspose.slides/audioframe/create_shape_elements/#) | Creëert en geeft een array van vorm-elementen terug. |

### Zie ook
* klasse [`AudioFrame`](/slides/python-net/nl/aspose.slides/audioframe)
* klasse [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape)
* klasse [`PictureFrame`](/slides/python-net/nl/aspose.slides/pictureframe)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)