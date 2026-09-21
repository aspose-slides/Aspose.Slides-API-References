---
title: Shape class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shape/
---
## Shape-klasse

Represent een shape op een dia.

Het Shape-type geeft de volgende leden weer:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/shape/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/shape/placeholder/) | Geeft de placeholder voor een vorm terug. Geeft None terug als de vorm geen placeholder heeft.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/shape/custom_data/) | Geeft de aangepaste gegevens van de vorm terug.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/shape/raw_frame/) | Geeft de eigenschappen van het ruwe vormframe terug of stelt ze in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/shape/frame/) | Geeft de eigenschappen van het vormframe terug of stelt ze in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/shape/line_format/) | Geeft het LineFormat-object terug dat lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde vormen die geen lijn-eigenschappen hebben.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/shape/three_d_format/) | Geeft het ThreeDFormat-object terug dat 3D-effecteigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde vormen die geen 3D-eigenschappen hebben.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/shape/effect_format/) | Geeft het EffectFormat-object terug dat pixel-effecten op een vorm toepast.<br/>            Opmerking: kan None teruggeven voor bepaalde vormen die geen effecteigenschappen hebben.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/shape/fill_format/) | Geeft het FillFormat-object terug dat opvulopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde vormen die geen opvuleigenschappen hebben.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/shape/hyperlink_click/) | Geeft de hyperlink terug die is gedefinieerd voor muisklik, of stelt deze in.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/shape/hyperlink_mouse_over/) | Geeft de hyperlink terug die is gedefinieerd voor muisover, of stelt deze in.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/shape/hyperlink_manager/) | Geeft de hyperlinkbeheerder terug.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/shape/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/Schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/shape/z_order_position/) | Geeft de positie van een vorm in de z-orde terug.<br/>            Shapes[0] geeft de vorm terug die zich achterin de z-orde bevindt,<br/>            en Shapes[Shapes.Count - 1] geeft de vorm terug die zich voorin de z-orde bevindt.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/shape/connection_site_count/) | Geeft het aantal verbindingspunten op de vorm terug.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/shape/rotation/) | Geeft het aantal graden terug of stelt het in waarmee de opgegeven vorm rond de z-as wordt gedraaid.<br/>            Een positieve waarde duidt een klokwijzerrotatie aan; een negatieve waarde<br/>            duidt een tegen-de-klokrotatie aan.<br/>            Lezen/Schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/shape/x/) | Haalt de x-coördinaat op van de linkerbovenhoek van de vorm, gemeten in points, of stelt deze in.<br/>            Lezen/Schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/shape/y/) | Haalt de y-coördinaat op van de linkerbovenhoek van de vorm, gemeten in points, of stelt deze in.<br/>            Lezen/Schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/shape/width/) | Haalt de breedte van de vorm op, gemeten in points, of stelt deze in.<br/>            Lezen/Schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/shape/height/) | Haalt de hoogte van de vorm op, gemeten in points, of stelt deze in.<br/>            Lezen/Schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/shape/black_white_mode/) | De eigenschap bepaalt hoe een vorm wordt weergegeven in zwart-wit weergavemodus.<br/>            Lezen/Schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id/) | Geeft een interne, presentatiegerichte identifier terug die bedoeld is voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden herschikt, mag deze niet worden behandeld<br/>            als een persistent unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id/) | Geeft een dia-gebonden unieke identifier terug die constant blijft gedurende de levensduur van de vorm en<br/>            PowerPoint of interop-code in staat stelt om de vorm betrouwbaar te refereren vanuit elk deel van het document.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/shape/alternative_text/) | Geeft de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/shape/alternative_text_title/) | Geeft de titel van de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/shape/name/) | Geeft de naam van een vorm terug of stelt deze in.<br/>            Mag niet None zijn. Gebruik een lege tekenreekswaarde indien nodig.<br/>            Lezen/Schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/shape/is_decorative/) | Haalt de optie 'Mark as decorative' op of stelt deze in<br/>            Lezen/Schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/shape/shape_lock/) | Geeft de vergrendelingen van de vorm terug.<br/>            Alleen-lezen [`IBaseShapeLock`](/slides/python-net/nl/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/shape/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/shape/parent_group/) | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Anders wordt None teruggegeven.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/shape/slide/) | Geeft de bovenliggende dia van een vorm terug.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/shape/presentation/) | Geeft de bovenliggende presentatie van een dia terug.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |

## Methoden

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/shape/get_image/#) | Geeft een miniatuur van de vorm terug.<br/>            ShapeThumbnailBounds.Shape wordt standaard gebruikt als type voor miniatuurgrenzen. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | Geeft een miniatuur van de vorm terug. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/shape/write_as_svg/#iorawiobase) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/shape/remove_placeholder/#) | Definieert dat deze vorm geen placeholder is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/shape/add_placeholder/#iplaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/shape/get_base_placeholder/#) | Geeft een basis placeholder-vorm terug (een vorm uit de lay-out en/of masterdia waarvan de huidige vorm is geërfd).<br/>            Er wordt None teruggegeven als de huidige vorm niet geërfd is. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/shape/get_visual_bounds/#) | Haalt de visuele grenzen van de vorm op, berekend uit de gerenderde inhoud. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)