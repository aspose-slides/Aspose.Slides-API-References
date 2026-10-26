---
title: SmartArt class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.smartart/smartart/
---
## SmartArt klasse

Representeert een SmartArt-diagram

**Erfelijkheid:**[`SmartArt`](/slides/python-net/nl/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

Het SmartArt-type bevat de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides.smartart/smartart/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides.smartart/smartart/placeholder/) | Retourneert de placeholder voor een vorm. Retourneert None als de vorm geen placeholder heeft.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides.smartart/smartart/custom_data/) | Retourneert de aangepaste gegevens van de vorm.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides.smartart/smartart/raw_frame/) | Retourneert of stelt de ruwe vormframe-eigenschappen in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides.smartart/smartart/frame/) | Retourneert of stelt de vormframe-eigenschappen in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides.smartart/smartart/line_format/) | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde types van vormen die geen lijn-eigenschappen hebben.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides.smartart/smartart/three_d_format/) | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde types van vormen die geen 3D-eigenschappen hebben.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides.smartart/smartart/effect_format/) | Retourneert het EffectFormat-object dat pixel-effecten op een vorm toepast.<br/>            Opmerking: kan None retourneren voor bepaalde types van vormen die geen effecteigenschappen hebben.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides.smartart/smartart/fill_format/) | Retourneert het FillFormat-object dat opvulopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde types van vormen die geen opvuleigenschappen hebben.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides.smartart/smartart/hyperlink_click/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik.<br/>            Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over.<br/>            Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides.smartart/smartart/hyperlink_manager/) | Retourneert de hyperlink-beheerder.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides.smartart/smartart/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides.smartart/smartart/z_order_position/) | Retourneert de positie van een vorm in de z-volgorde.<br/>            Shapes[0] retourneert de vorm die zich aan de achterkant van de z-volgorde bevindt,<br/>            en Shapes[Shapes.Count - 1] retourneert de vorm die zich aan de voorkant van de z-volgorde bevindt.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides.smartart/smartart/connection_site_count/) | Retourneert het aantal verbindingspunten op de vorm.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides.smartart/smartart/rotation/) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid.<br/>            Een positieve waarde geeft een klokgewijze rotatie aan; een negatieve waarde<br/>            geeft een tegenklokgewijze rotatie aan.<br/>            Lezen/schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides.smartart/smartart/x/) | Haalt op of stelt de x-coördinaat van de linkerbovencorner van de vorm in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides.smartart/smartart/y/) | Haalt op of stelt de y-coördinaat van de linkerbovencorner van de vorm in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides.smartart/smartart/width/) | Haalt op of stelt de breedte van de vorm in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides.smartart/smartart/height/) | Haalt op of stelt de hoogte van de vorm in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides.smartart/smartart/black_white_mode/) | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-witweergavemodus.<br/>            Lezen/schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides.smartart/smartart/unique_id/) | Retourneert een interne, presentatie-gebonden identifier bedoeld voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programatisch kan worden herkend, mag deze niet worden behandeld<br/>            als een persistent unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides.smartart/smartart/office_interop_shape_id/) | Retourneert een dia-gebonden unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code betrouwbaar laat verwijzen naar de vorm vanuit elke plek in het document.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides.smartart/smartart/alternative_text/) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides.smartart/smartart/alternative_text_title/) | Retourneert of stelt de titel van de alternatieve tekst die aan een vorm is gekoppeld.<br/>            Lezen/schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides.smartart/smartart/name/) | Retourneert of stelt de naam van een vorm in.<br/>            Mag niet None zijn. Gebruik een lege tekenreeks indien nodig.<br/>            Lezen/schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides.smartart/smartart/is_decorative/) | Haalt op of stelt de optie 'Mark as decorative' in<br/>            Lezen/schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides.smartart/smartart/shape_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides.smartart/smartart/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides.smartart/smartart/parent_group/) | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Anders retourneert het None.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides.smartart/smartart/slide/) | Retourneert de bovenliggende dia van een vorm.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides.smartart/smartart/presentation/) | Retourneert de bovenliggende presentatie van een dia.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/nl/aspose.slides.smartart/smartart/graphical_object_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/nl/aspose.slides.smartart/smartart/all_nodes/) | Retourneert collecties van alle knooppunten in het SmartArt-object.<br/>            Alleen-lezen [`ISmartArtNodeCollection`](/slides/python-net/nl/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/nl/aspose.slides.smartart/smartart/nodes/) | Retourneert collecties van hoofdknopen in het SmartArt-object.<br/>            Alleen-lezen [`ISmartArtNodeCollection`](/slides/python-net/nl/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/nl/aspose.slides.smartart/smartart/layout/) | Retourneert of stelt de lay-out van het SmartArt-object in.<br/>            Lezen/schrijven [`SmartArtLayoutType`](/slides/python-net/nl/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/nl/aspose.slides.smartart/smartart/quick_style/) | Retourneert of stelt de snelle stijl van het SmartArt-object in.<br/>            Lezen/schrijven [`SmartArtQuickStyleType`](/slides/python-net/nl/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/nl/aspose.slides.smartart/smartart/color_style/) | Retourneert of stelt de kleurstijl van het SmartArt-object in.<br/>            Lezen/schrijven [`SmartArtColorType`](/slides/python-net/nl/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/nl/aspose.slides.smartart/smartart/is_reversed/) | Retourneer of stel de status van het SmartArt-diagram in met betrekking tot (links-naar-rechts) LTR of (rechts-naar-links) RTL, als het diagram omkering ondersteunt.<br/>            Lezen/schrijven **bool**. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides.smartart/smartart/get_image/#) | Retourneert de miniatuur van de vorm.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | Retourneert de miniatuur van de vorm. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides.smartart/smartart/remove_placeholder/#) | Definieert dat deze vorm geen placeholder is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven placeholder. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides.smartart/smartart/get_base_placeholder/#) | Retourneert een basis placeholder-vorm (vorm van de lay-out en/of masterslide waar de huidige vorm van is geërfd).<br/>            Een None wordt geretourneerd als de huidige vorm niet is geërfd. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides.smartart/smartart/get_visual_bounds/#) | Haalt de visuele grenzen van de vorm op, berekend op basis van de gerenderde inhoud. |

### Zie ook
* klasse [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* klasse [`SmartArt`](/slides/python-net/nl/aspose.slides.smartart/smartart)
* module [`aspose.slides.smartart`](/slides/python-net/nl/aspose.slides.smartart)
* bibliotheek [`Aspose.Slides`](/slides/python-net)