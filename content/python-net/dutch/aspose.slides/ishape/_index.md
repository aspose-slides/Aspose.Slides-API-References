---
title: IShape class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishape/
---
## IShape klasse

Stelt een vorm op een dia voor.

Het IShape-type maakt de volgende leden beschikbaar:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/ishape/is_text_holder/) | Bepaalt of de vorm een TextHolder is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/ishape/placeholder/) | Retourneert de tijdelijke aanduiding voor een vorm.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/ishape/custom_data/) | Retourneert de aangepaste gegevens van de vorm.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/ishape/raw_frame/) | Retourneert of stelt de ruwe eigenschappen van het vormframe in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/ishape/frame/) | Retourneert of stelt de eigenschappen van het vormframe in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/ishape/line_format/) | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/ishape/three_d_format/) | Retourneert het ThreeDFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/ishape/effect_format/) | Retourneert het EffectFormat-object dat pixel-effecten op een vorm bevat.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/ishape/fill_format/) | Retourneert het FillFormat-object dat opvul-opmaak-eigenschappen voor een vorm bevat.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/nl/aspose.slides/ishape/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/ishape/z_order_position/) | Retourneert de positie van een vorm in de z-volgorde.<br/>            Shapes[0] retourneert de vorm achterin de z-volgorde,<br/>            en Shapes[Shapes.Count - 1] retourneert de vorm voorin de z-volgorde.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/ishape/connection_site_count/) | Retourneert het aantal verbindingspunten op de vorm.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/ishape/rotation/) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid.<br/>            Een positieve waarde geeft een klokwijse rotatie aan; een negatieve waarde<br/>            geeft een tegen-klokwijse rotatie aan.<br/>            Lezen/schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/ishape/x/) | Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in points.<br/>            Lezen/schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/ishape/y/) | Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in points.<br/>            Lezen/schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/ishape/width/) | Haalt of stelt de breedte van de vorm in, gemeten in points.<br/>            Lezen/schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/ishape/height/) | Haalt of stelt de hoogte van de vorm in, gemeten in points.<br/>            Lezen/schrijven **float**. |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/ishape/alternative_text/) | Retourneert of stelt de alternatieve tekst bij een vorm in.<br/>            Lezen/schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/ishape/alternative_text_title/) | Retourneert of stelt de titel van de alternatieve tekst bij een vorm in.<br/>            Lezen/schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/ishape/name/) | Retourneert of stelt de naam van een vorm in.<br/>            Lezen/schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/ishape/is_decorative/) | Haalt of stelt de optie 'Mark as decorative' in<br/>            Lezen/schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/ishape/shape_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IBaseShapeLock`](/slides/python-net/nl/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/ishape/unique_id/) | Retourneert een interne, presentatie-specifieke identificatie bedoeld voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden herkend, mag deze niet worden behandeld<br/>            als een blijvende unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`IShape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/ishape/office_interop_shape_id/) | Retourneert een uniek identificatie-nummer dat scope is per dia en gedurende de levensduur van de vorm constant blijft en<br/>            PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`IShape.unique_id`](/slides/python-net/nl/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/ishape/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/ishape/black_white_mode/) | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus..<br/>            Lezen/schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/nl/aspose.slides/ishape/parent_group/) | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Anders retourneert het None.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/ishape/hyperlink_manager/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/ishape/get_image/#) | Retourneert een miniatuur van de vorm.<br/>            ShapeThumbnailBounds.Shape wordt standaard gebruikt voor het type van miniatuurbounds. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Retourneert een miniatuur van de vorm. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/ishape/write_as_svg/#iorawiobase) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/ishape/add_placeholder/#iplaceholder) | Voegt een nieuwe tijdelijke aanduiding toe als er geen is en stelt de eigenschappen van de tijdelijke aanduiding in op een opgegeven. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/ishape/remove_placeholder/#) | Geeft aan dat deze vorm geen tijdelijke aanduiding is. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/ishape/get_base_placeholder/#) | Retourneert een basis-tijdelijke-aanduidings-vorm (vorm van de lay-out en/of master-dia waarvan de huidige vorm is geërfd).<br/>            Een None wordt geretourneerd als de huidige vorm niet geërfd is. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)