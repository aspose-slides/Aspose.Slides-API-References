---
title: ZoomFrame class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/zoomframe/
---
## ZoomFrame klasse

Stelt een Slide Zoom-object voor in een dia.

**Erfenis:**[`ZoomFrame`](/slides/python-net/nl/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/nl/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

Het ZoomFrame-type maakt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/zoomframe/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/zoomframe/placeholder/) | Retourneert de placeholder voor een vorm. Retourneert None als de vorm geen placeholder heeft.<br/>            Alleen lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/zoomframe/custom_data/) | Retourneert de aangepaste gegevens van de vorm.<br/>            Alleen lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/zoomframe/raw_frame/) | Retourneert of stelt de eigenschappen van het ruwe vormframe in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/zoomframe/frame/) | Retourneert of stelt de eigenschappen van het vormframe in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/zoomframe/line_format/) | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde typen vormen die geen lijn-eigenschappen hebben.<br/>            Alleen lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/zoomframe/three_d_format/) | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde typen vormen die geen 3D-eigenschappen hebben.<br/>            Alleen lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/zoomframe/effect_format/) | Retourneert het EffectFormat-object dat pixel-effecten bevat die op een vorm worden toegepast.<br/>            Opmerking: kan None retourneren voor bepaalde typen vormen die geen effect-eigenschappen hebben.<br/>            Alleen lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/zoomframe/fill_format/) | Retourneert het FillFormat-object dat vul-opmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde typen vormen die geen vul-eigenschappen hebben.<br/>            Alleen lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/zoomframe/hyperlink_click/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/zoomframe/hyperlink_mouse_over/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisover.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/zoomframe/hyperlink_manager/) | Retourneert de hyperlink-manager.<br/>            Alleen lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/zoomframe/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/Schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/zoomframe/z_order_position/) | Retourneert de positie van een vorm in de z-order.<br/>            Shapes[0] retourneert de vorm achterin de z-order,<br/>            en Shapes[Shapes.Count - 1] retourneert de vorm vooraan in de z-order.<br/>            Alleen lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/zoomframe/connection_site_count/) | Retourneert het aantal verbindingspunten op de vorm.<br/>            Alleen lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/zoomframe/rotation/) | Retourneert of stelt het aantal graden in dat de opgegeven vorm rond de z-as wordt geroteerd. Een positieve waarde duidt op een rotatie met de klok mee; een negatieve waarde duidt op een rotatie tegen de klok in.<br/>            Lezen/Schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/zoomframe/x/) | Haalt op of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/zoomframe/y/) | Haalt op of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/zoomframe/width/) | Haalt op of stelt de breedte van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/zoomframe/height/) | Haalt op of stelt de hoogte van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/zoomframe/black_white_mode/) | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus.<br/>            Lezen/Schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/zoomframe/unique_id/) | Retourneert een interne, presentatie-gerichte identifier die bedoeld is voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden her-toegewezen, mag deze niet worden beschouwd als een permanente unieke sleutel.<br/>            Alleen lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/zoomframe/office_interop_shape_id/) | Retourneert een unieke identifier die op dia-niveau is en constant blijft gedurende de levensduur van de vorm, en zodat PowerPoint of interop-code de vorm betrouwbaar kan refereren vanuit elke plaats in het document.<br/>            Alleen lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/zoomframe/alternative_text/) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/Schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/zoomframe/alternative_text_title/) | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/Schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/zoomframe/name/) | Retourneert of stelt de naam van een vorm in.<br/>            Mag niet None zijn. Gebruik een lege tekenreeks indien nodig.<br/>            Lezen/Schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/zoomframe/is_decorative/) | Haalt op of stelt de optie 'Mark as decorative' in.<br/>            Lezen/Schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/zoomframe/shape_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/zoomframe/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/zoomframe/parent_group/) | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Anders retourneert het None.<br/>            Alleen lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/zoomframe/slide/) | Retourneert de bovenliggende dia van een vorm.<br/>            Alleen lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/zoomframe/presentation/) | Retourneert de bovenliggende presentatie van een dia.<br/>            Alleen lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/nl/aspose.slides/zoomframe/graphical_object_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/nl/aspose.slides/zoomframe/image_type/) | Haalt op of stelt het afbeeldingstype van een zoom-object in.<br/>            Lezen/Schrijven [`ZoomImageType`](/slides/python-net/nl/aspose.slides/zoomimagetype).<br/>            Standaardwaarde: Preview |
| [`return_to_parent`](/slides/python-net/nl/aspose.slides/zoomframe/return_to_parent/) | Haalt op of stelt het navigatiegedrag in tijdens een diavoorstelling.<br/>            Lezen/Schrijven **bool**.<br/>            Standaardwaarde: false |
| [`show_background`](/slides/python-net/nl/aspose.slides/zoomframe/show_background/) | Haalt op of stelt de waarde in die aangeeft of de Zoom de achtergrond van de doel-dia zal gebruiken.<br/>            Lezen/Schrijven **bool**.<br/>            Standaardwaarde: true |
| [`zoom_image`](/slides/python-net/nl/aspose.slides/zoomframe/zoom_image/) | Haalt op of stelt de afbeelding voor het zoom-object in.<br/>            Lezen/Schrijven [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/nl/aspose.slides/zoomframe/transition_duration/) | Haalt op of stelt de duur van de overgang tussen Zoom en dia in.<br/>            Lezen/Schrijven **float**.<br/>            Standaardwaarde: 1.0f |
| [`target_slide`](/slides/python-net/nl/aspose.slides/zoomframe/target_slide/) | Haalt op of stelt het dia-object in waarnaar het Slide Zoom-object linkt.<br/>            Lezen/Schrijven [`ISlide`](/slides/python-net/nl/aspose.slides/islide). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/zoomframe/get_image/#) | Retourneert vorm-miniatuur.<br/>            ShapeThumbnailBounds.Shape vorm-miniatuurbereik type wordt standaard gebruikt. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | Retourneert vorm-miniatuur. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/zoomframe/remove_placeholder/#) | Definieert dat deze vorm geen placeholder is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/zoomframe/get_base_placeholder/#) | Retourneert een eenvoudige placeholder-vorm (vorm uit de lay-out en/of masterslide waar de huidige vorm van is geërfd).<br/>            Een None wordt geretourneerd als de huidige vorm niet geërfd is. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/zoomframe/get_visual_bounds/#) | Haalt de visuele grenzen van de vorm op, berekend op basis van de gerenderde inhoud. |

### Zie ook
* klasse [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* klasse [`ZoomFrame`](/slides/python-net/nl/aspose.slides/zoomframe)
* klasse [`ZoomObject`](/slides/python-net/nl/aspose.slides/zoomobject)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)