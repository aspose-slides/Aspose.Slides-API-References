---
title: PictureFrame class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/pictureframe/
---
## PictureFrame klasse

Stelt een frame met een afbeelding voor.

**Erfenis:**[`PictureFrame`](/slides/python-net/nl/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

Het PictureFrame-type geeft de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/pictureframe/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/pictureframe/placeholder/) | Retourneert de placeholder voor een vorm. Retourneert None als de vorm geen placeholder heeft.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/pictureframe/custom_data/) | Retourneert de aangepaste gegevens van de vorm.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/pictureframe/raw_frame/) | Retourneert of stelt de ruwe vormframe-eigenschappen in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/pictureframe/frame/) | Retourneert of stelt de vormframe-eigenschappen in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/pictureframe/line_format/) | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde vormen die geen lijn-eigenschappen hebben.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/pictureframe/three_d_format/) | Retourneert het ThreeDFormat-object dat 3d-effecteigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde vormen die geen 3d-eigenschappen hebben.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/pictureframe/effect_format/) | Retourneert het EffectFormat-object dat pixel-effecten bevat die op een vorm worden toegepast.<br/>            Opmerking: kan None retourneren voor bepaalde vormen die geen effecteigenschappen hebben.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/pictureframe/fill_format/) | Retourneert het FillFormat-object dat vulopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde vormen die geen vul-eigenschappen hebben.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/pictureframe/hyperlink_click/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/pictureframe/hyperlink_mouse_over/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/pictureframe/hyperlink_manager/) | Retourneert de hyperlinkmanager.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/pictureframe/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/Schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/pictureframe/z_order_position/) | Retourneert de positie van een vorm in de z-volgorde.<br/>            Shapes[0] retourneert de vorm aan de achterkant van de z-volgorde,<br/>            en Shapes[Shapes.Count - 1] retourneert de vorm aan de voorkant van de z-volgorde.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/pictureframe/connection_site_count/) | Retourneert het aantal verbindingspunten op de vorm.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/pictureframe/rotation/) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid.<br/>            Een positieve waarde duidt op een rotatie met de klok mee; een negatieve waarde duidt op een rotatie tegen de klok in.<br/>            Lezen/Schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/pictureframe/x/) | Krijgt of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/pictureframe/y/) | Krijgt of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/pictureframe/width/) | Krijgt of stelt de breedte van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/pictureframe/height/) | Krijgt of stelt de hoogte van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/pictureframe/black_white_mode/) | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus..<br/>            Lezen/Schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/pictureframe/unique_id/) | Retourneert een interne, presentatiespecifieke identifier bedoeld voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden hertoegewezen, mag deze niet worden behandeld als een blijvende unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/pictureframe/office_interop_shape_id/) | Retourneert een slide-specifieke unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanaf overal in het document.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/pictureframe/alternative_text/) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/Schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/pictureframe/alternative_text_title/) | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/Schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/pictureframe/name/) | Retourneert of stelt de naam van een vorm in.<br/>            Mag niet None zijn. Gebruik een lege tekenreekswaarde indien nodig.<br/>            Lezen/Schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/pictureframe/is_decorative/) | Krijgt of stelt de optie 'Mark as decorative' in<br/>            Lezen/Schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/pictureframe/shape_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IPictureFrameLock`](/slides/python-net/nl/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/pictureframe/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/pictureframe/parent_group/) | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Anders wordt None geretourneerd.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/pictureframe/slide/) | Retourneert de bovenliggende slide van een vorm.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/pictureframe/presentation/) | Retourneert de bovenliggende presentatie van een slide.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/nl/aspose.slides/pictureframe/shape_style/) | Retourneert het stijlobject van de vorm.<br/>            Alleen-lezen [`IShapeStyle`](/slides/python-net/nl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/nl/aspose.slides/pictureframe/shape_type/) | Retourneert of stelt het AutoShape-type voor een PictureFrame in.<br/>            Alle items van de set [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) zijn toegestaan, behalve alle soorten lijnen:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Lezen/Schrijven [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/nl/aspose.slides/pictureframe/adjustments/) | Retourneert een verzameling van aanpassingswaarden van de vorm.<br/>            Alleen-lezen [`IAdjustValueCollection`](/slides/python-net/nl/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/nl/aspose.slides/pictureframe/picture_frame_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IPictureFrameLock`](/slides/python-net/nl/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/nl/aspose.slides/pictureframe/picture_format/) | Retourneert het PictureFillFormat-object voor een picture frame.<br/>            Alleen-lezen [`IPictureFillFormat`](/slides/python-net/nl/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/nl/aspose.slides/pictureframe/relative_scale_height/) | Retourneert of stelt de schaal van de hoogte (relatief aan de oorspronkelijke afbeeldinggrootte) van het picture frame in. Waarde 1.0 komt overeen met 100%.<br/>            Lezen/Schrijven **float**. |
| [`relative_scale_width`](/slides/python-net/nl/aspose.slides/pictureframe/relative_scale_width/) | Retourneert of stelt de schaal van de breedte (relatief aan de oorspronkelijke afbeeldinggrootte) van het picture frame in. Waarde 1.0 komt overeen met 100%.<br/>            Lezen/Schrijven **float**. |
| [`is_cameo`](/slides/python-net/nl/aspose.slides/pictureframe/is_cameo/) | Bepaalt of het PictureFrame een Cameo-object is of niet.<br/>            Alleen-lezen **bool**. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/pictureframe/get_image/#) | Retourneert vormthumbnail.<br/>            ShapeThumbnailBounds.Shape wordt standaard gebruikt als type voor vormthumbnail-bounds. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Retourneert vormthumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/pictureframe/remove_placeholder/#) | Definieert dat deze vorm geen placeholder is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven placeholder. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/pictureframe/get_base_placeholder/#) | Retourneert een basis-placeholdervorm (vorm van de lay-out en/of masterslide waarvan de huidige vorm is geërfd).<br/>            Een None wordt geretourneerd als de huidige vorm niet geërfd is. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/pictureframe/get_visual_bounds/#) | Haal de visuele grenzen van de vorm op, berekend vanuit de gerenderde inhoud. |
| [`get_geometry_paths(self)`](/slides/python-net/nl/aspose.slides/pictureframe/get_geometry_paths/#) | Retourneert een kopie van het pad van de geometrievorm. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/nl/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Werkt de vormgeometrie bij vanuit het [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)-object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm.<br/>             Verandert het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/nl/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Werkt de vormgeometrie bij vanuit een array van [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm.<br/>             Verandert het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/nl/aspose.slides/pictureframe/create_shape_elements/#) | Maakt een array van elementen van de vorm en retourneert deze. |

### Zie ook
* klasse [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape)
* klasse [`PictureFrame`](/slides/python-net/nl/aspose.slides/pictureframe)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)