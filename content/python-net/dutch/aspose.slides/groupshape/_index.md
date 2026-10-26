---
title: GroupShape class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/groupshape/
---
## GroupShape klasse

Vertegenwoordigt een groep vormen op een dia.

**Inheritance:**[`GroupShape`](/slides/python-net/nl/aspose.slides/groupshape) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

Het GroupShape-type biedt de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/groupshape/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/groupshape/placeholder/) | Retourneert de plaatshouder voor een vorm. Retourneert None als de vorm geen plaatshouder heeft.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/groupshape/custom_data/) | Retourneert de aangepaste gegevens van de vorm.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/groupshape/raw_frame/) | Retourneert of stelt de onbewerkte vormframe-eigenschappen in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/groupshape/frame/) | Retourneert of stelt de vormframe-eigenschappen in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/groupshape/line_format/) | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: Retourneert None voor GroupShape-objecten omdat ze geen lijn-eigenschappen hebben.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/groupshape/three_d_format/) | Retourneert het ThreeDFormat-object dat 3D-effect-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde vormtypen die geen 3D-eigenschappen hebben.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/groupshape/effect_format/) | Retourneert het EffectFormat-object dat pixel-effecten op een vorm toepast.<br/>            Opmerking: kan None retourneren voor bepaalde vormtypen die geen effect-eigenschappen hebben.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/groupshape/fill_format/) | Retourneert het FillFormat-object dat opvul-opmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde vormtypen die geen opvul-eigenschappen hebben.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/groupshape/hyperlink_click/) | Retourneert of stelt de hyperlink in die wordt gedefinieerd voor een muisklik.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/groupshape/hyperlink_mouse_over/) | Retourneert of stelt de hyperlink in die wordt gedefinieerd voor muis-over.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/groupshape/hyperlink_manager/) | Retourneert de hyperlink-beheerder.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/groupshape/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/Schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/groupshape/z_order_position/) | Retourneert de positie van een vorm in de z-volgorde.<br/>            Shapes[0] retourneert de vorm aan de achterkant van de z-volgorde,<br/>            en Shapes[Shapes.Count - 1] retourneert de vorm aan de voorkant van de z-volgorde.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/groupshape/connection_site_count/) | Retourneert het aantal verbindingsplaatsen op de vorm.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/groupshape/rotation/) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid.<br/>            Een positieve waarde duidt op klokwijs draaien; een negatieve waarde duidt op tegen-klokwijs draaien.<br/>            Lezen/Schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/groupshape/x/) | Haalt of stelt de x-coördinate van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/groupshape/y/) | Haalt of stelt de y-coördinate van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/groupshape/width/) | Haalt of stelt de breedte van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/groupshape/height/) | Haalt of stelt de hoogte van de vorm in, gemeten in punten.<br/>            Lezen/Schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/groupshape/black_white_mode/) | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit-weergavemodus.<br/>            Lezen/Schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/groupshape/unique_id/) | Retourneert een interne, presentatie-specifieke identifier bedoeld voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden hertoegewezen, mag hij niet worden beschouwd als een persistente unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/groupshape/office_interop_shape_id/) | Retourneert een dia-specifieke unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/groupshape/alternative_text/) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/Schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/groupshape/alternative_text_title/) | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/Schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/groupshape/name/) | Retourneert of stelt de naam van een vorm in.<br/>            Mag niet None zijn. Gebruik een lege tekenreeks als dat nodig is.<br/>            Lezen/Schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/groupshape/is_decorative/) | Haalt of stelt de optie ‘Mark as decorative’ in.<br/>            Lezen/Schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/groupshape/shape_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IGroupShapeLock`](/slides/python-net/nl/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/groupshape/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/groupshape/parent_group/) | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Retourneert anders None.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/groupshape/slide/) | Retourneert de bovenliggende dia van een vorm.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/groupshape/presentation/) | Retourneert de bovenliggende presentatie van een dia.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/nl/aspose.slides/groupshape/group_shape_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IGroupShapeLock`](/slides/python-net/nl/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/nl/aspose.slides/groupshape/shapes/) | Retourneert de collectie van vormen binnen de groep.<br/>            Alleen-lezen [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/groupshape/get_image/#) | Retourneert miniatuur van de vorm.<br/>            ShapeThumbnailBounds.Shape miniatuurrandtype wordt standaard gebruikt. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | Retourneert miniatuur van de vorm. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/groupshape/write_as_svg/#iorawiobase) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/groupshape/remove_placeholder/#) | Definieert dat deze vorm geen plaatshouder is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/groupshape/add_placeholder/#iplaceholder) | Voegt een nieuwe plaatshouder toe als er geen is en stelt plaatshouder-eigenschappen in op een opgegeven. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/groupshape/get_base_placeholder/#) | Retourneert een basisplaatshouder-vorm (vorm van de lay-out en/of master-dia waar de huidige vorm van is geërfd).<br/>            Een None wordt geretourneerd als de huidige vorm niet is geërfd. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/groupshape/get_visual_bounds/#) | Haalt de visuele grenzen van de vorm op die zijn berekend uit de gerenderde inhoud. |


### Zie ook
* klasse [`GroupShape`](/slides/python-net/nl/aspose.slides/groupshape)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)