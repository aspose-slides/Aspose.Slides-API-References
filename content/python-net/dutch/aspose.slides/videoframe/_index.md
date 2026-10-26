---
title: VideoFrame class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/videoframe/
---
## VideoFrame klasse

Representeert een video-clip op een dia.

**Inheritance:**[`VideoFrame`](/slides/python-net/nl/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/nl/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

Het type VideoFrame biedt de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/videoframe/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/videoframe/placeholder/) | Geeft de placeholder voor een vorm terug. Geeft None terug als de vorm geen placeholder heeft.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/videoframe/custom_data/) | Geeft de aangepaste gegevens van de vorm terug.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/videoframe/raw_frame/) | Geeft de ruwe shape frame-eigenschappen terug of stelt ze in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/videoframe/frame/) | Geeft de shape frame-eigenschappen terug of stelt ze in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/videoframe/line_format/) | Geeft het LineFormat-object terug dat lijneigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde vormen die geen lijneigenschappen hebben.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/videoframe/three_d_format/) | Geeft het ThreeDFormat-object terug dat 3d-effecteigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde vormen die geen 3d-eigenschappen hebben.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/videoframe/effect_format/) | Geeft het EffectFormat-object terug dat pixel-effecten op een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde vormen die geen effecteigenschappen hebben.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/videoframe/fill_format/) | Geeft het FillFormat-object terug dat vul-opmaakeigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde vormen die geen vulling hebben.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/videoframe/hyperlink_click/) | Geeft de hyperlink terug die is gedefinieerd voor muisklik.<br/>            Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/videoframe/hyperlink_mouse_over/) | Geeft de hyperlink terug die is gedefinieerd voor muis-over.<br/>            Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/videoframe/hyperlink_manager/) | Geeft de hyperlink-manager terug.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/videoframe/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/videoframe/z_order_position/) | Geeft de positie van een vorm in de z-order terug.<br/>            Shapes[0] geeft de vorm achter in de z-order terug,<br/>            en Shapes[Shapes.Count - 1] geeft de vorm voor in de z-order terug.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/videoframe/connection_site_count/) | Geeft het aantal verbindingplaatsen op de vorm terug.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/videoframe/rotation/) | Geeft of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid.<br/>            Een positieve waarde betekent met de klok mee; een negatieve waarde betekent tegen de klok in.<br/>            Lezen/schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/videoframe/x/) | Geeft de x-coördinaat van de linkerbovenhoek van de vorm terug of stelt deze in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/videoframe/y/) | Geeft de y-coördinaat van de linkerbovenhoek van de vorm terug of stelt deze in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/videoframe/width/) | Geeft de breedte van de vorm terug of stelt deze in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/videoframe/height/) | Geeft de hoogte van de vorm terug of stelt deze in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/videoframe/black_white_mode/) | Eigenschap specificeert hoe een vorm wordt gerenderd in zwart-wit weergavemodus.<br/>            Lezen/schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/videoframe/unique_id/) | Geeft een interne, presentatie-specifieke identifier terug die bedoeld is voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde herhaaldelijk kan worden toegewezen door de gebruiker of programmatisch, mag hij niet worden beschouwd als een permanente unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/videoframe/office_interop_shape_id/) | Geeft een dia-specifieke unieke identifier terug die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code betrouwbaar laat refereren naar de vorm vanuit elke locatie in het document.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/videoframe/alternative_text/) | Geeft de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in.<br/>            Lezen/schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/videoframe/alternative_text_title/) | Geeft de titel van de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in.<br/>            Lezen/schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/videoframe/name/) | Geeft de naam van een vorm terug of stelt deze in.<br/>            Mag niet None zijn. Gebruik een lege tekenreeks indien nodig.<br/>            Lezen/schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/videoframe/is_decorative/) | Geeft de optie 'Mark as decorative' terug of stelt deze in<br/>            Lezen/schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/videoframe/shape_lock/) | Geeft de vergrendelingen van de vorm terug.<br/>            Alleen-lezen [`IPictureFrameLock`](/slides/python-net/nl/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/videoframe/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/videoframe/parent_group/) | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Anders wordt None teruggegeven.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/videoframe/slide/) | Geeft de bovenliggende dia van een vorm terug.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/videoframe/presentation/) | Geeft de bovenliggende presentatie van een dia terug.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/nl/aspose.slides/videoframe/shape_style/) | Geeft het stijlobject van de vorm terug.<br/>            Alleen-lezen [`IShapeStyle`](/slides/python-net/nl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/nl/aspose.slides/videoframe/shape_type/) | Geeft of stelt het AutoShape-type voor een PictureFrame in.<br/>            Er zijn alle items van de set [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) toegestaan, <br/>            behalve alle soorten lijnen:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Lezen/schrijven [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/nl/aspose.slides/videoframe/adjustments/) | Geeft een verzameling van de aanpassingswaarden van de vorm terug.<br/>            Alleen-lezen [`IAdjustValueCollection`](/slides/python-net/nl/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/nl/aspose.slides/videoframe/picture_frame_lock/) | Geeft de vergrendelingen van de vorm terug.<br/>            Alleen-lezen [`IPictureFrameLock`](/slides/python-net/nl/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/nl/aspose.slides/videoframe/picture_format/) | Geeft het PictureFillFormat-object voor een picture frame terug.<br/>            Alleen-lezen [`IPictureFillFormat`](/slides/python-net/nl/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/nl/aspose.slides/videoframe/relative_scale_height/) | Geeft de schaal van de hoogte (relatief aan de originele afbeelding) van het picture frame terug of stelt deze in. Waarde 1,0 komt overeen met 100%.<br/>            Lezen/schrijven **float**. |
| [`relative_scale_width`](/slides/python-net/nl/aspose.slides/videoframe/relative_scale_width/) | Geeft de schaal van de breedte (relatief aan de originele afbeelding) van het picture frame terug of stelt deze in. Waarde 1,0 komt overeen met 100%.<br/>            Lezen/schrijven **float**. |
| [`is_cameo`](/slides/python-net/nl/aspose.slides/videoframe/is_cameo/) | Bepaalt of het PictureFrame een Cameo-object is of niet.<br/>            Alleen-lezen **bool**. |
| [`rewind_video`](/slides/python-net/nl/aspose.slides/videoframe/rewind_video/) | Bepaalt of een video automatisch wordt teruggespoeld naar het begin zodra de film klaar is met afspelen.<br/>            Lezen/schrijven **bool**. |
| [`play_loop_mode`](/slides/python-net/nl/aspose.slides/videoframe/play_loop_mode/) | Bepaalt of een video in een lus wordt afgespeeld.<br/>            Lezen/schrijven **bool**. |
| [`hide_at_showing`](/slides/python-net/nl/aspose.slides/videoframe/hide_at_showing/) | Bepaalt of een VideoFrame verborgen is.<br/>            Lezen/schrijven **bool**. |
| [`volume`](/slides/python-net/nl/aspose.slides/videoframe/volume/) | Geeft het audiovolume terug of stelt dit in.<br/>            Lezen/schrijven [`AudioVolumeMode`](/slides/python-net/nl/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/nl/aspose.slides/videoframe/play_mode/) | Geeft de afspeelmodus van de video terug of stelt deze in.<br/>            Lezen/schrijven [`VideoPlayModePreset`](/slides/python-net/nl/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/nl/aspose.slides/videoframe/full_screen_mode/) | Bepaalt of een video in volledig-scherm modus wordt getoond.<br/>            Lezen/schrijven **bool**. |
| [`link_path_long`](/slides/python-net/nl/aspose.slides/videoframe/link_path_long/) | Geeft de naam van een video-bestand dat gekoppeld is aan een VideoFrame terug of stelt deze in.<br/>            Lezen/schrijven **str**. |
| [`embedded_video`](/slides/python-net/nl/aspose.slides/videoframe/embedded_video/) | Geeft het ingebedde video-object terug of stelt dit in.<br/>            Lezen/schrijven [`IVideo`](/slides/python-net/nl/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/nl/aspose.slides/videoframe/trim_from_start/) | Trim start [ms] |
| [`trim_from_end`](/slides/python-net/nl/aspose.slides/videoframe/trim_from_end/) | Trim end [ms] |
| [`caption_tracks`](/slides/python-net/nl/aspose.slides/videoframe/caption_tracks/) | Geeft de verzameling van gesloten ondertitels die bij het video-frame horen terug.<br/>             Deze eigenschap is alleen-lezen en retourneert een [`ICaptionsCollection`](/slides/python-net/nl/aspose.slides/icaptionscollection) die alle ondertitel-sporen bevat. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/videoframe/get_image/#) | Geeft een miniatuur van de vorm terug.<br/>            ShapeThumbnailBounds.Shape vorm-miniatuur-grens type wordt standaard gebruikt. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Geeft een miniatuur van de vorm terug. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/videoframe/remove_placeholder/#) | Definieert dat deze vorm geen placeholder is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een gespecificeerde. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/videoframe/get_base_placeholder/#) | Geeft een basis-placeholder-vorm terug (vorm van de layout en/of master-dia waarvan de huidige vorm is geërfd).<br/>            Een None wordt geretourneerd als de huidige vorm niet geërfd is. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/videoframe/get_visual_bounds/#) | Geeft de visuele grenzen van de vorm terug, berekend vanuit de gerenderde inhoud. |
| [`get_geometry_paths(self)`](/slides/python-net/nl/aspose.slides/videoframe/get_geometry_paths/#) | Geeft een kopie van het pad van de geometrie-vorm terug. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/nl/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Werkt de vorm-geometrie bij vanuit [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)-object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm.<br/>             Wijzigt het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/nl/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Werkt de vorm-geometrie bij vanuit een array van [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm.<br/>             Wijzigt het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/nl/aspose.slides/videoframe/create_shape_elements/#) | Maakt en retourneert een array van vorm-elementen. |

### Zie ook
* klasse [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape)
* klasse [`PictureFrame`](/slides/python-net/nl/aspose.slides/pictureframe)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* klasse [`VideoFrame`](/slides/python-net/nl/aspose.slides/videoframe)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)