---
title: VideoFrame class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/videoframe/
---
## VideoFrame klasse

Stelt een video-clip op een dia voor.

**Erfenis:**[`VideoFrame`](/slides/python-net/nl/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/nl/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

Het VideoFrame-type maakt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/videoframe/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/videoframe/placeholder/) | Retourneert de tijdelijke aanduiding voor een vorm. Retourneert None als de vorm geen tijdelijke aanduiding heeft.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/videoframe/custom_data/) | Retourneert de aangepaste gegevens van de vorm.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/videoframe/raw_frame/) | Retourneert of stelt de ruwe vormframe-eigenschappen in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/videoframe/frame/) | Retourneert of stelt de vormframe-eigenschappen in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/videoframe/line_format/) | Retourneert het LineFormat-object dat lijn-opmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde vormen die geen lijn-eigenschappen hebben.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/videoframe/three_d_format/) | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/videoframe/effect_format/) | Retourneert het EffectFormat-object dat pixel-effecten op een vorm toepast.<br/>            Opmerking: kan None retourneren voor bepaalde vormen die geen effect-eigenschappen hebben.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/videoframe/fill_format/) | Retourneert het FillFormat-object dat opvul-opmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde vormen die geen opvul-eigenschappen hebben.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/videoframe/hyperlink_click/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik.<br/>            Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/videoframe/hyperlink_mouse_over/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over.<br/>            Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/videoframe/hyperlink_manager/) | Retourneert de hyperlink-beheerder.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/videoframe/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/videoframe/z_order_position/) | Retourneert de positie van een vorm in de z-volgorde.<br/>            Shapes[0] retourneert de vorm achterin de z-volgorde,<br/>            en Shapes[Shapes.Count - 1] retourneert de vorm voorin de z-volgorde.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/videoframe/connection_site_count/) | Retourneert het aantal verbindingspunten op de vorm.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/videoframe/rotation/) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid.<br/>            Een positieve waarde betekent klokwijzerrotatie; een negatieve waarde<br/>            betekent tegen-klokwijzerrotatie.<br/>            Lezen/schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/videoframe/x/) | Haal het x-coördinaat op of stel het in van de linkerbovenhoek van de vorm, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/videoframe/y/) | Haal het y-coördinaat op of stel het in van de linkerbovenhoek van de vorm, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/videoframe/width/) | Haal de breedte van de vorm op of stel deze in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/videoframe/height/) | Haal de hoogte van de vorm op of stel deze in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/videoframe/black_white_mode/) | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus.<br/>            Lezen/schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/videoframe/unique_id/) | Retourneert een interne, presentatie-gebaseerde identifier bedoeld voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden hertoegewezen, mag deze niet worden beschouwd<br/>            als een blijvende unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/videoframe/office_interop_shape_id/) | Retourneert een dia-gebaseerde unieke identifier die constant blijft gedurende de levensduur van de vorm en<br/>            PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/videoframe/alternative_text/) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/videoframe/alternative_text_title/) | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/videoframe/name/) | Retourneert of stelt de naam van een vorm in.<br/>            Mag niet None zijn. Gebruik een lege tekenreeks indien nodig.<br/>            Lezen/schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/videoframe/is_decorative/) | Haal of stel de 'Mark as decorative' optie in<br/>            Lezen/schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/videoframe/shape_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IPictureFrameLock`](/slides/python-net/nl/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/videoframe/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/videoframe/parent_group/) | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Retourneert anders None.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/videoframe/slide/) | Retourneert de bovenliggende dia van een vorm.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/videoframe/presentation/) | Retourneert de bovenliggende presentatie van een dia.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/nl/aspose.slides/videoframe/shape_style/) | Retourneert het stijl-object van de vorm.<br/>            Alleen-lezen [`IShapeStyle`](/slides/python-net/nl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/nl/aspose.slides/videoframe/shape_type/) | Retourneert of stelt het AutoShape-type in voor een PictureFrame.<br/>            Alle items van de set [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) zijn toegestaan,<br/>            behalve alle soorten lijnen:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Lezen/schrijven [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/nl/aspose.slides/videoframe/adjustments/) | Retourneert een collectie van de aanpassingswaarden van de vorm.<br/>            Alleen-lezen [`IAdjustValueCollection`](/slides/python-net/nl/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/nl/aspose.slides/videoframe/picture_frame_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IPictureFrameLock`](/slides/python-net/nl/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/nl/aspose.slides/videoframe/picture_format/) | Retourneert het PictureFillFormat-object voor een afbeeldingsframe.<br/>            Alleen-lezen [`IPictureFillFormat`](/slides/python-net/nl/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/nl/aspose.slides/videoframe/relative_scale_height/) | Retourneert of stelt de schaal van de hoogte (relatief aan de originele afbeeldingsgrootte) van het afbeeldingsframe in. Waarde 1.0 komt overeen met 100%.\n            Lezen/schrijven **float**. |
| [`relative_scale_width`](/slides/python-net/nl/aspose.slides/videoframe/relative_scale_width/) | Retourneert of stelt de schaal van de breedte (relatief aan de originele afbeeldingsgrootte) van het afbeeldingsframe in. Waarde 1.0 komt overeen met 100%.\n            Lezen/schrijven **float**. |
| [`is_cameo`](/slides/python-net/nl/aspose.slides/videoframe/is_cameo/) | Bepaalt of het PictureFrame een Cameo-object is of niet.\n            Alleen-lezen **bool**. |
| [`rewind_video`](/slides/python-net/nl/aspose.slides/videoframe/rewind_video/) | Bepaalt of een video automatisch wordt teruggespoeld naar het begin\n            zodra de film is afgelopen.\n            Lezen/schrijven **bool**. |
| [`play_loop_mode`](/slides/python-net/nl/aspose.slides/videoframe/play_loop_mode/) | Bepaalt of een video in een lus wordt afgespeeld.\n            Lezen/schrijven **bool**. |
| [`hide_at_showing`](/slides/python-net/nl/aspose.slides/videoframe/hide_at_showing/) | Bepaalt of een VideoFrame verborgen is.\n            Lezen/schrijven **bool**. |
| [`volume`](/slides/python-net/nl/aspose.slides/videoframe/volume/) | Retourneert of stelt het audiovolume in.\n            Lezen/schrijven [`AudioVolumeMode`](/slides/python-net/nl/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/nl/aspose.slides/videoframe/volume_value/) | Retourneert of stelt het exacte videovolume in als een percentage.\n             De waarde wordt uitgedrukt als een percentage van 0 tot 100. Gebruik deze eigenschap\n             om volume-waarden te lezen of in te stellen die nauwkeuriger zijn dan de vooraf gedefinieerde\n             niveaus die beschikbaar zijn via de [`VideoFrame.volume`](/slides/python-net/nl/aspose.slides/videoframe/volume)-eigenschap.\n             Lezen/schrijven **float**. |
| [`play_mode`](/slides/python-net/nl/aspose.slides/videoframe/play_mode/) | Retourneert of stelt de afspeelmodus van de video in.\n            Lezen/schrijven [`VideoPlayModePreset`](/slides/python-net/nl/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/nl/aspose.slides/videoframe/full_screen_mode/) | Bepaalt of een video in de volledige-schermmodus wordt weergegeven.\n            Lezen/schrijven **bool**. |
| [`link_path_long`](/slides/python-net/nl/aspose.slides/videoframe/link_path_long/) | Retourneert of stelt de naam van een videobestand in dat is gekoppeld aan een VideoFrame.\n            Lezen/schrijven **str**. |
| [`embedded_video`](/slides/python-net/nl/aspose.slides/videoframe/embedded_video/) | Retourneert of stelt het ingebedde video-object in.\n            Lezen/schrijven [`IVideo`](/slides/python-net/nl/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/nl/aspose.slides/videoframe/trim_from_start/) | Begin trim [ms] |
| [`trim_from_end`](/slides/python-net/nl/aspose.slides/videoframe/trim_from_end/) | Eind trim [ms] |
| [`caption_tracks`](/slides/python-net/nl/aspose.slides/videoframe/caption_tracks/) | Haalt de collectie van gesloten bijschriften op die bij het video-frame horen.<br/>             Deze eigenschap is alleen-lezen en retourneert een [`ICaptionsCollection`](/slides/python-net/nl/aspose.slides/icaptionscollection) met alle ondertitel-sporen. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/videoframe/get_image/#) | Retourneert een miniatuur van de vorm.<br/>            ShapeThumbnailBounds.Shape wordt standaard gebruikt als type voor miniatuuraanduidingen van de vorm. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Retourneert een miniatuur van de vorm. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/videoframe/remove_placeholder/#) | Definieert dat deze vorm geen tijdelijke aanduiding is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Voegt een nieuwe tijdelijke aanduiding toe als er geen is en stelt de eigenschappen van de tijdelijke aanduiding in op een opgegeven. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/videoframe/get_base_placeholder/#) | Retourneert een basis-tijdelijke-aanduidingsvorm (vorm van de lay-out en/of masterslide waarvan de huidige vorm is geërfd).<br/>            Een None wordt geretourneerd als de huidige vorm niet geërfd is. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/videoframe/get_visual_bounds/#) | Haalt de visuele begrenzing van de vorm op die is berekend op basis van de gerenderde inhoud. |
| [`get_geometry_paths(self)`](/slides/python-net/nl/aspose.slides/videoframe/get_geometry_paths/#) | Retourneert een kopie van het pad van de geometrievorm. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/nl/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Werkt de geometrie van de vorm bij vanuit het [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)-object. Coördinaten moeten relatief zijn ten opzichte van de linkse<br/>             bovenhoek van de vorm.<br/>             Verandert het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/nl/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Werkt de geometrie van de vorm bij vanuit een array van [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath). Coördinaten moeten relatief zijn ten opzichte van de linkse<br/>             bovenhoek van de vorm.<br/>             Verandert het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/nl/aspose.slides/videoframe/create_shape_elements/#) | Maakt en retourneert een array van de elementen van de vorm. |

### Zie ook
* klasse [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape)
* klasse [`PictureFrame`](/slides/python-net/nl/aspose.slides/pictureframe)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* klasse [`VideoFrame`](/slides/python-net/nl/aspose.slides/videoframe)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)