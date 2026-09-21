---
title: GeometryShape class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/geometryshape/
---
## GeometryShape klasse

Vertegenwoordigt de bovenliggende klasse voor alle geometrische vormen.

**Overerving:**[`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

Het type GeometryShape bevat de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/geometryshape/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/geometryshape/placeholder/) | Retourneert de plaatshouder voor een vorm. Retourneert None als de vorm geen plaatshouder heeft.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/geometryshape/custom_data/) | Retourneert de aangepaste gegevens van de vorm.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/geometryshape/raw_frame/) | Haalt op of stelt de ruwe vormframe-eigenschappen in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/geometryshape/frame/) | Haalt op of stelt de vormframe-eigenschappen in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/geometryshape/line_format/) | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde soorten vormen die geen lijn-eigenschappen hebben.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/geometryshape/three_d_format/) | Retourneert het ThreeDFormat-object dat 3D-effect-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde soorten vormen die geen 3D-eigenschappen hebben.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/geometryshape/effect_format/) | Retourneert het EffectFormat-object dat pixel-effecten op een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde soorten vormen die geen effect-eigenschappen hebben.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/geometryshape/fill_format/) | Retourneert het FillFormat-object dat opvullings-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde soorten vormen die geen opvullings-eigenschappen hebben.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/geometryshape/hyperlink_click/) | Haalt op of stelt de hyperlink in die is gedefinieerd voor muisklik.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/geometryshape/hyperlink_mouse_over/) | Haalt op of stelt de hyperlink in die is gedefinieerd voor muis-over.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/geometryshape/hyperlink_manager/) | Retourneert de hyperlink-manager.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/geometryshape/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/Schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/geometryshape/z_order_position/) | Retourneert de positie van een vorm in de z-volgorde.<br/>            Shapes[0] retourneert de vorm achteraan in de z-volgorde,<br/>            en Shapes[Shapes.Count - 1] retourneert de vorm vooraan in de z-volgorde.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/geometryshape/connection_site_count/) | Retourneert het aantal aansluitpunten op de vorm.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/geometryshape/rotation/) | Haalt op of stelt het aantal graden in dat de opgegeven vorm rond de z-as draait.<br/>            Een positieve waarde duidt op een klokwijs draaien; een negatieve waarde duidt op tegen-klokwijs draaien.<br/>            Lezen/Schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/geometryshape/x/) | Haalt op of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/geometryshape/y/) | Haalt op of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/geometryshape/width/) | Haalt op of stelt de breedte van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/geometryshape/height/) | Haalt op of stelt de hoogte van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/geometryshape/black_white_mode/) | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus..<br/>            Lezen/Schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/geometryshape/unique_id/) | Retourneert een interne, presentatie-gebonden identifier bedoeld voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden herhaald, mag deze niet worden behandeld<br/>            als een permanente unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/geometryshape/office_interop_shape_id/) | Retourneert een dia-gebonden unieke identifier die constant blijft gedurende de levensduur van de vorm en<br/>            PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elke locatie in het document.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/geometryshape/alternative_text/) | Haalt op of stelt de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/Schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/geometryshape/alternative_text_title/) | Haalt op of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/Schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/geometryshape/name/) | Haalt op of stelt de naam van een vorm in.<br/>            Mag niet None zijn. Gebruik een lege tekenreeks indien nodig.<br/>            Lezen/Schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/geometryshape/is_decorative/) | Haalt op of stelt de optie 'Mark as decorative' in<br/>            Lezen/Schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/geometryshape/shape_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IBaseShapeLock`](/slides/python-net/nl/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/geometryshape/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/geometryshape/parent_group/) | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Anders retourneert None.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/geometryshape/slide/) | Retourneert de bovenliggende dia van een vorm.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/geometryshape/presentation/) | Retourneert de bovenliggende presentatie van een dia.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/nl/aspose.slides/geometryshape/shape_style/) | Retourneert het stijlobject van de vorm.<br/>            Alleen-lezen [`IShapeStyle`](/slides/python-net/nl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type/) | Haalt op of stelt het geometry-preset-type in.<br/>            Opmerking: bij wijziging van de waarde worden alle aanpassingswaarden gereset naar hun standaardwaarden.<br/>            Lezen/Schrijven [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/nl/aspose.slides/geometryshape/adjustments/) | Retourneert een collectie van de aanpassingswaarden van de vorm.<br/>            Alleen-lezen [`IAdjustValueCollection`](/slides/python-net/nl/aspose.slides/iadjustvaluecollection). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/geometryshape/get_image/#) | Retourneert een miniatuur van de vorm.<br/>            ShapeThumbnailBounds.Shape miniatuurgrenzen type wordt standaard gebruikt. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | Retourneert een miniatuur van de vorm. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/geometryshape/remove_placeholder/#) | Definieert dat deze vorm geen plaatshouder is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | Voegt een nieuwe plaatshouder toe als er geen is en stelt plaatshouder-eigenschappen in op een gespecificeerde. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/geometryshape/get_base_placeholder/#) | Retourneert een basisplaatshoudervorm (vorm van de lay-out en/of meester-dia waarvan de huidige vorm is geërfd).<br/>            Een None wordt geretourneerd als de huidige vorm niet geërfd is. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/geometryshape/get_visual_bounds/#) | Haalt de visuele grenzen van de vorm op, berekend vanuit de weergegeven inhoud. |
| [`get_geometry_paths(self)`](/slides/python-net/nl/aspose.slides/geometryshape/get_geometry_paths/#) | Retourneert een kopie van het pad van de geometry-vorm. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/nl/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | Werkt de geometry van de vorm bij vanuit [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath) object. Coördinaten moeten relatief zijn aan de linkerbovenhoek van de vorm.<br/>            Wijzigt het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/nl/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | Werkt de geometry van de vorm bij vanuit een array van [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath). Coördinaten moeten relatief zijn aan de linkerbovenhoek van de vorm.<br/>            Wijzigt het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/nl/aspose.slides/geometryshape/create_shape_elements/#) | Maakt een array van de elementen van de vorm aan en retourneert deze. |

### Zie ook
* klasse [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)