---
title: AutoShape class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/autoshape/
---
## AutoShape klasse

Stelt een AutoShape voor.

**Erfelijkheid:**[`AutoShape`](/slides/python-net/nl/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

Het AutoShape-type stelt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/autoshape/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/autoshape/placeholder/) | Geeft de tijdelijke aanduiding voor een vorm terug. Retourneert None als de vorm geen tijdelijke aanduiding heeft.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/autoshape/custom_data/) | Geeft de aangepaste gegevens van de vorm terug.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/autoshape/raw_frame/) | Geeft de ruwe vormframe-eigenschappen terug of stelt ze in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/autoshape/frame/) | Geeft de vormframe-eigenschappen terug of stelt ze in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/autoshape/line_format/) | Geeft het LineFormat-object terug dat lijnopmaakeigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde vormen die geen lijn-eigenschappen hebben.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/autoshape/three_d_format/) | Geeft het ThreeDFormat-object terug dat 3D-effecteigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/autoshape/effect_format/) | Geeft het EffectFormat-object terug dat pixel-effecten op een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde vormen die geen effect-eigenschappen hebben.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/autoshape/fill_format/) | Geeft het FillFormat-object terug dat opvulopmaakeigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde vormen die geen opvuleigenschappen hebben.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/autoshape/hyperlink_click/) | Geeft de hyperlink terug die is gedefinieerd voor muisklik, of stelt deze in.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/autoshape/hyperlink_mouse_over/) | Geeft de hyperlink terug die is gedefinieerd voor muisover, of stelt deze in.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/autoshape/hyperlink_manager/) | Geeft de hyperlink-beheerder terug.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/autoshape/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/Schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/autoshape/z_order_position/) | Geeft de positie van een vorm in de z-volgorde terug.<br/>            Shapes[0] geeft de vorm terug die zich achterin de z-volgorde bevindt,<br/>            en Shapes[Shapes.Count - 1] geeft de vorm terug die zich voorin de z-volgorde bevindt.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/autoshape/connection_site_count/) | Geeft het aantal verbindingspunten op de vorm terug.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/autoshape/rotation/) | Geeft het aantal graden terug of stelt het in waarmee de opgegeven vorm rond de z-as wordt gedraaid.<br/>            Een positieve waarde duidt op rotatie met de klok mee; een negatieve waarde duidt op rotatie tegen de klok in.<br/>            Lezen/Schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/autoshape/x/) | Geeft de x-coördinaat van de linkerbovenhoek van de vorm terug of stelt deze in, gemeten in points.<br/>            Lezen/Schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/autoshape/y/) | Geeft de y-coördinaat van de linkerbovenhoek van de vorm terug of stelt deze in, gemeten in points.<br/>            Lezen/Schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/autoshape/width/) | Geeft de breedte van de vorm terug of stelt deze in, gemeten in points.<br/>            Lezen/Schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/autoshape/height/) | Geeft de hoogte van de vorm terug of stelt deze in, gemeten in points.<br/>            Lezen/Schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/autoshape/black_white_mode/) | Eigenschap bepaalt hoe een vorm wordt weergegeven in zwart-wit weergavemodus.<br/>            Lezen/Schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/autoshape/unique_id/) | Geeft een interne, presentatiespecifieke identificatie terug die bedoeld is voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden hertoegewezen, mag hij niet worden beschouwd als een permanente unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/autoshape/office_interop_shape_id/) | Geeft een dia-specifieke unieke identificatie terug die constant blijft voor de levensduur van de vorm en<br/>            PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/autoshape/alternative_text/) | Geeft de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/autoshape/alternative_text_title/) | Geeft de titel van de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/autoshape/name/) | Geeft de naam van een vorm terug of stelt deze in.<br/>            Mag niet None zijn. Gebruik een lege tekenreeks indien nodig.<br/>            Lezen/Schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/autoshape/is_decorative/) | Geeft de optie 'Mark as decorative' terug of stelt deze in<br/>            Lezen/Schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/autoshape/shape_lock/) | Geeft de vergrendelingen van de vorm terug.<br/>            Alleen-lezen [`IAutoShapeLock`](/slides/python-net/nl/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/autoshape/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/autoshape/parent_group/) | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Anders wordt None geretourneerd.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/autoshape/slide/) | Geeft de bovenliggende dia van een vorm terug.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/autoshape/presentation/) | Geeft de bovenliggende presentatie van een dia terug.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/nl/aspose.slides/autoshape/shape_style/) | Geeft het stijlobject van de vorm terug.<br/>            Alleen-lezen [`IShapeStyle`](/slides/python-net/nl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/nl/aspose.slides/autoshape/shape_type/) | Geeft het vooraf ingestelde type van de geometrie terug of stelt dit in.<br/>            Opmerking: bij wijziging van de waarde worden alle aanpassingswaarden teruggezet naar hun standaardwaarden.<br/>            Lezen/Schrijven [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/nl/aspose.slides/autoshape/adjustments/) | Geeft een verzameling van de aanpassingswaarden van de vorm terug.<br/>            Alleen-lezen [`IAdjustValueCollection`](/slides/python-net/nl/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/nl/aspose.slides/autoshape/auto_shape_lock/) | Geeft de vergrendelingen van de autoshape terug.<br/>            Alleen-lezen [`IAutoShapeLock`](/slides/python-net/nl/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/nl/aspose.slides/autoshape/text_frame/) | Geeft het TextFrame-object voor de AutoShape terug.<br/>            Alleen-lezen [`ITextFrame`](/slides/python-net/nl/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/nl/aspose.slides/autoshape/use_background_fill/) | Bepaalt of deze autoshape moet worden gevuld met de achtergrondvulling van de dia in plaats van die opgegeven door stijl of opvulformaat.<br/>            Lezen/Schrijven **bool**. |
| [`is_text_box`](/slides/python-net/nl/aspose.slides/autoshape/is_text_box/) | Geeft aan of de vorm een tekstvak is. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/autoshape/get_image/#) | Geeft een miniatuur van de vorm terug.<br/>            ShapeThumbnailBounds.Shape miniatuur-bounds-type wordt standaard gebruikt. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Geeft een miniatuur van de vorm terug. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/autoshape/remove_placeholder/#) | Definieert dat deze vorm geen tijdelijke aanduiding is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Voegt een nieuwe tijdelijke aanduiding toe als er geen is en stelt de eigenschappen van de tijdelijke aanduiding in op een opgegeven. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/autoshape/get_base_placeholder/#) | Geeft een basis-placeholder-vorm terug (vorm van de lay-out en/of masterslide waarvan de huidige vorm is geërfd).<br/>            Een None wordt geretourneerd als de huidige vorm niet geërfd is. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/autoshape/get_visual_bounds/#) | Haalt de visuele grenzen van de vorm op, berekend vanuit de gerenderde inhoud. |
| [`get_geometry_paths(self)`](/slides/python-net/nl/aspose.slides/autoshape/get_geometry_paths/#) | Geeft een kopie van het pad van de geometrievorm terug. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/nl/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Werkt de geometrie van de vorm bij vanuit een [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)-object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm.<br/>             Verandert het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/nl/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Werkt de geometrie van de vorm bij vanuit een array van [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm.<br/>             Verandert het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/nl/aspose.slides/autoshape/create_shape_elements/#) | Creëert en geeft een array van de elementen van de vorm terug. |
| [`add_text_frame(self, text)`](/slides/python-net/nl/aspose.slides/autoshape/add_text_frame/#str) | Voegt een nieuw TextFrame toe aan een vorm.<br/>            Als de vorm al een TextFrame heeft, wordt de tekst eenvoudigweg aangepast. |

### Zie ook
* klasse [`AutoShape`](/slides/python-net/nl/aspose.slides/autoshape)
* klasse [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)