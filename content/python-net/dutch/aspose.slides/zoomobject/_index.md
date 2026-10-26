---
title: ZoomObject class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/zoomobject/
---
## ZoomObject klasse

Stelt een Zoom-object voor op een dia.

**Inheritance:**[`ZoomObject`](/slides/python-net/nl/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

Het ZoomObject-type maakt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/zoomobject/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/> Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/zoomobject/placeholder/) | Retourneert de placeholder voor een vorm. Retourneert None als de vorm geen placeholder heeft.<br/> Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/zoomobject/custom_data/) | Retourneert de aangepaste gegevens van de vorm.<br/> Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/zoomobject/raw_frame/) | Retourneert of stelt de ruwe shape-frame-eigenschappen in.<br/> Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/zoomobject/frame/) | Retourneert of stelt de shape-frame-eigenschappen in.<br/> Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/zoomobject/line_format/) | Retourneert het LineFormat-object dat lijn-opmaak-eigenschappen voor een vorm bevat.<br/> Opmerking: kan None retourneren voor bepaalde soorten vormen die geen lijn-eigenschappen hebben.<br/> Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/zoomobject/three_d_format/) | Retourneert het ThreeDFormat-object met 3D-effecteigenschappen voor een vorm.<br/> Opmerking: kan None retourneren voor bepaalde soorten vormen die geen 3D-eigenschappen hebben.<br/> Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/zoomobject/effect_format/) | Retourneert het EffectFormat-object dat pixel-effecten op een vorm toepast.<br/> Opmerking: kan None retourneren voor bepaalde soorten vormen die geen effect-eigenschappen hebben.<br/> Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/zoomobject/fill_format/) | Retourneert het FillFormat-object dat opvul-opmaakeigenschappen voor een vorm bevat.<br/> Opmerking: kan None retourneren voor bepaalde soorten vormen die geen opvul-eigenschappen hebben.<br/> Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/zoomobject/hyperlink_click/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik.<br/> Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/zoomobject/hyperlink_mouse_over/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over.<br/> Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/zoomobject/hyperlink_manager/) | Retourneert de hyperlink-beheerder.<br/> Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/zoomobject/hidden/) | Bepaalt of de vorm verborgen is.<br/> Lezen/schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/zoomobject/z_order_position/) | Retourneert de positie van een vorm in de z-order.<br/> Shapes[0] retourneert de vorm aan de achterkant van de z-order,<br/> en Shapes[Shapes.Count - 1] retourneert de vorm aan de voorkant van de z-order.<br/> Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/zoomobject/connection_site_count/) | Retourneert het aantal verbindingspunten op de vorm.<br/> Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/zoomobject/rotation/) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as gedraaid wordt<br/> Een positieve waarde duidt op klokwijzerrotatie; een negatieve waarde<br/> duidt op tegen-klokwijzerrotatie.<br/> Lezen/schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/zoomobject/x/) | Retourneert of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in points.<br/> Lezen/schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/zoomobject/y/) | Retourneert of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in points.<br/> Lezen/schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/zoomobject/width/) | Retourneert of stelt de breedte van de vorm in, gemeten in points.<br/> Lezen/schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/zoomobject/height/) | Retourneert of stelt de hoogte van de vorm in, gemeten in points.<br/> Lezen/schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/zoomobject/black_white_mode/) | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus..<br/> Lezen/schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/zoomobject/unique_id/) | Retourneert een interne, presentatie-gebonden identifier bedoeld voor gebruik door add-ins of andere code.<br/> Omdat deze waarde kan worden hertoegewezen door de gebruiker of programmatisch, mag deze niet worden behandeld<br/> als een persistent unieke sleutel.<br/> Alleen-lezen **int**.<br/> Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/zoomobject/office_interop_shape_id/) | Retourneert een dia-gebonden unieke identifier die constant blijft gedurende de levensduur van de vorm en<br/> PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document.<br/> Alleen-lezen **int**.<br/> Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/zoomobject/alternative_text/) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld.<br/> Lezen/schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/zoomobject/alternative_text_title/) | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld.<br/> Lezen/schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/zoomobject/name/) | Retourneert of stelt de naam van een vorm in.<br/> Mag niet None zijn. Gebruik een lege tekenreeks indien nodig.<br/> Lezen/schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/zoomobject/is_decorative/) | Retourneert of stelt de optie 'Mark as decorative' in<br/> Lezen/schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/zoomobject/shape_lock/) | Retourneert de vergrendelingen van de vorm.<br/> Alleen-lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/zoomobject/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/> Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/zoomobject/parent_group/) | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Retourneert anders None.<br/> Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/zoomobject/slide/) | Retourneert de bovenliggende dia van een vorm.<br/> Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/zoomobject/presentation/) | Retourneert de bovenliggende presentatie van een dia.<br/> Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/nl/aspose.slides/zoomobject/graphical_object_lock/) | Retourneert de vergrendelingen van de vorm.<br/> Alleen-lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/nl/aspose.slides/zoomobject/image_type/) | Retourneert of stelt het afbeeldingstype van een zoom-object in.<br/> Lezen/schrijven [`ZoomImageType`](/slides/python-net/nl/aspose.slides/zoomimagetype).<br/> Standaardwaarde: Preview |
| [`return_to_parent`](/slides/python-net/nl/aspose.slides/zoomobject/return_to_parent/) | Retourneert of stelt het navigatiegedrag in diavoorstelling in.<br/> Lezen/schrijven **bool**.<br/> Standaardwaarde: false |
| [`show_background`](/slides/python-net/nl/aspose.slides/zoomobject/show_background/) | Retourneert of stelt de waarde in die aangeeft of de Zoom de achtergrond van de bestemmingsdia zal gebruiken.<br/> Lezen/schrijven **bool**.<br/> Standaardwaarde: true |
| [`zoom_image`](/slides/python-net/nl/aspose.slides/zoomobject/zoom_image/) | Retourneert of stelt de afbeelding voor een zoom-object in.<br/> Lezen/schrijven [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/nl/aspose.slides/zoomobject/transition_duration/) | Retourneert of stelt de duur van de overgang tussen Zoom en dia in.<br/> Lezen/schrijven **float**.<br/> Standaardwaarde: 1.0f |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/zoomobject/get_image/#) | Retourneert miniatuur van de vorm.<br/> ShapeThumbnailBounds.Shape miniatuurgrenzen-type wordt standaard gebruikt. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | Retourneert miniatuur van de vorm. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/zoomobject/remove_placeholder/#) | Definieert dat deze vorm geen placeholder is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt de placeholder-eigenschappen in op een opgegeven. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/zoomobject/get_base_placeholder/#) | Retourneert een basis-placeholder-vorm (vorm van de lay-out en/of masterslide waarvan de huidige vorm is geërfd).<br/> Er wordt None geretourneerd als de huidige vorm niet geërfd is. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/zoomobject/get_visual_bounds/#) | Haalt de visuele grenzen van de vorm op, berekend vanuit de gerenderde inhoud. |

### Zie ook
* klasse [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* klasse [`ZoomObject`](/slides/python-net/nl/aspose.slides/zoomobject)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)