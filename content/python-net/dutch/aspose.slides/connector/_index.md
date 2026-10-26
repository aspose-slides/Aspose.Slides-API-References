---
title: Connector class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/connector/
---
## Connector klasse

Stelt een connector voor.

**Inheritance:**[`Connector`](/slides/python-net/nl/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

Het Connector-type geeft de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/connector/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/connector/placeholder/) | Retourneert de tijdelijke aanduiding voor een vorm. Retourneert None als de vorm geen tijdelijke aanduiding heeft.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/connector/custom_data/) | Retourneert de aangepaste gegevens van de vorm.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/connector/raw_frame/) | Retourneert of stelt de eigenschappen van het ruwe vormkader in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/connector/frame/) | Retourneert of stelt de eigenschappen van het vormkader in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/connector/line_format/) | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde soorten vormen die geen lijn-eigenschappen hebben.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/connector/three_d_format/) | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde soorten vormen die geen 3D-eigenschappen hebben.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/connector/effect_format/) | Retourneert het EffectFormat-object dat pixel-effecten toepast op een vorm.<br/>            Opmerking: kan None retourneren voor bepaalde soorten vormen die geen effect-eigenschappen hebben.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/connector/fill_format/) | Retourneert het FillFormat-object dat vulopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde soorten vormen die geen vul-eigenschappen hebben.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/connector/hyperlink_click/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik.<br/>            Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/connector/hyperlink_mouse_over/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over.<br/>            Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/connector/hyperlink_manager/) | Retourneert de hyperlink-beheerder.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/connector/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/connector/z_order_position/) | Retourneert de positie van een vorm in de z-volgorde.<br/>            Shapes[0] retourneert de vorm achter in de z-volgorde,<br/>            en Shapes[Shapes.Count - 1] retourneert de vorm vooraan in de z-volgorde.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/connector/connection_site_count/) | Retourneert het aantal verbindingspunten op de vorm.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/connector/rotation/) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid.<br/>            Een positieve waarde geeft draaiing met de klok mee aan; een negatieve waarde geeft draaiing tegen de klok in aan.<br/>            Lezen/schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/connector/x/) | Verkrijgt of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/connector/y/) | Verkrijgt of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/connector/width/) | Verkrijgt of stelt de breedte van de vorm in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/connector/height/) | Verkrijgt of stelt de hoogte van de vorm in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/connector/black_white_mode/) | Eigenschap specificeert hoe een vorm wordt gerenderd in zwart-wit weergavemodus.<br/>            Lezen/schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/connector/unique_id/) | Retourneert een interne, presentatie-gebonden identifier bedoeld voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden hertoegewezen, mag deze niet worden beschouwd als een permanente unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/connector/office_interop_shape_id/) | Retourneert een dia-gebonden unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code betrouwbaar laat refereren naar de vorm vanaf elke locatie in het document.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/connector/alternative_text/) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/connector/alternative_text_title/) | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/connector/name/) | Retourneert of stelt de naam van een vorm in.<br/>            Mag niet None zijn. Gebruik een lege tekenreeks indien nodig.<br/>            Lezen/schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/connector/is_decorative/) | Verkrijgt of stelt de optie 'Markeer als decoratief' in.<br/>            Lezen/schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/connector/shape_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IConnectorLock`](/slides/python-net/nl/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/connector/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/connector/parent_group/) | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Retourneert anders None.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/connector/slide/) | Retourneert de bovenliggende dia van een vorm.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/connector/presentation/) | Retourneert de bovenliggende presentatie van een dia.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/nl/aspose.slides/connector/shape_style/) | Retourneert het stijlobject van de vorm.<br/>            Alleen-lezen [`IShapeStyle`](/slides/python-net/nl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/nl/aspose.slides/connector/shape_type/) | Retourneert of stelt het AutoShape-type in.<br/>            Lezen/schrijven [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/nl/aspose.slides/connector/adjustments/) | Retourneert een verzameling van aanpassingswaarden van de vorm.<br/>            Alleen-lezen [`IAdjustValueCollection`](/slides/python-net/nl/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/nl/aspose.slides/connector/connector_lock/) | Retourneert de vergrendelingen van de connector.<br/>            Alleen-lezen [`IConnectorLock`](/slides/python-net/nl/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/nl/aspose.slides/connector/start_shape_connected_to/) | Retourneert of stelt de vorm in waaraan het begin van de connector moet worden gekoppeld.<br/>            Lezen/schrijven [`IShape`](/slides/python-net/nl/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/nl/aspose.slides/connector/end_shape_connected_to/) | Retourneert of stelt de vorm in waaraan het einde van de connector moet worden gekoppeld.<br/>            Lezen/schrijven [`IShape`](/slides/python-net/nl/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/nl/aspose.slides/connector/start_shape_connection_site_index/) | Retourneert of stelt de index van het verbindingspunt voor de startvorm in.<br/>            Lezen/schrijven **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/nl/aspose.slides/connector/end_shape_connection_site_index/) | Retourneert of stelt de index van het verbindingspunt voor de eindvorm in.<br/>            Lezen/schrijven **int**. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/connector/get_image/#) | Retourneert een miniatuur van de vorm.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type wordt standaard gebruikt. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Retourneert een miniatuur van de vorm. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/connector/write_as_svg/#iorawiobase) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/connector/remove_placeholder/#) | Definieert dat deze vorm geen tijdelijke aanduiding is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/connector/add_placeholder/#iplaceholder) | Voegt een nieuwe tijdelijke aanduiding toe als er geen is en stelt de eigenschappen van de tijdelijke aanduiding in op een opgegeven. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/connector/get_base_placeholder/#) | Retourneert een basis tijdelijke aanduidingsvorm (vorm uit de lay-out en/of masterslide waarvan de huidige vorm is geërfd).<br/>            Er wordt None geretourneerd als de huidige vorm niet is geërfd. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/connector/get_visual_bounds/#) | Verkrijgt de visuele grenzen van de vorm, berekend vanuit de gerenderde inhoud. |
| [`get_geometry_paths(self)`](/slides/python-net/nl/aspose.slides/connector/get_geometry_paths/#) | Retourneert een kopie van het pad van de geometrische vorm. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/nl/aspose.slides/connector/set_geometry_path/#igeometrypath) | Werk de vormgeometrie bij vanuit [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)-object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm.<br/>             Verandert het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/nl/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Werk de vormgeometrie bij vanuit een array van [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm.<br/>             Verandert het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/nl/aspose.slides/connector/create_shape_elements/#) | Creëert en retourneert een array van elementen van de vorm. |
| [`reroute(self)`](/slides/python-net/nl/aspose.slides/connector/reroute/#) | Leidt de connector opnieuw zodat deze het kortste mogelijke pad tussen de vormen die ze verbindt, neemt. |

### Zie ook
* klasse [`Connector`](/slides/python-net/nl/aspose.slides/connector)
* klasse [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)