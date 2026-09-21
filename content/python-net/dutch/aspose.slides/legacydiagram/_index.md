---
title: LegacyDiagram class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/legacydiagram/
---
## LegacyDiagram klasse

Represents a legacy diagram object.

**Erfenis:**[`LegacyDiagram`](/slides/python-net/nl/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

The LegacyDiagram type exposes the following members:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/legacydiagram/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/legacydiagram/placeholder/) | Geeft de placeholder voor een vorm terug. Geeft None terug als de vorm geen placeholder heeft.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/legacydiagram/custom_data/) | Geeft de aangepaste gegevens van de vorm terug.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/legacydiagram/raw_frame/) | Geeft de eigenschappen van het ruwe vormkader terug of stelt ze in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/legacydiagram/frame/) | Geeft de eigenschappen van het vormkader terug of stelt ze in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/legacydiagram/line_format/) | Geeft het LineFormat-object terug dat lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde soorten vormen die geen lijn-eigenschappen hebben.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/legacydiagram/three_d_format/) | Geeft het ThreeDFormat-object terug dat 3D-effecteigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde soorten vormen die geen 3D-eigenschappen hebben.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/legacydiagram/effect_format/) | Geeft het EffectFormat-object terug dat pixel-effecten op een vorm toepast.<br/>            Opmerking: kan None teruggeven voor bepaalde soorten vormen die geen effect-eigenschappen hebben.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/legacydiagram/fill_format/) | Geeft het FillFormat-object terug dat vulopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde soorten vormen die geen vul-eigenschappen hebben.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/legacydiagram/hyperlink_click/) | Geeft de hyperlink terug die is gedefinieerd voor muisklik, of stelt deze in.<br/>            Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/legacydiagram/hyperlink_mouse_over/) | Geeft de hyperlink terug die is gedefinieerd voor muisover, of stelt deze in.<br/>            Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/legacydiagram/hyperlink_manager/) | Geeft de hyperlink-manager terug.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/legacydiagram/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/legacydiagram/z_order_position/) | Geeft de positie van een vorm in de z-volgorde terug.<br/>            Shapes[0] geeft de vorm terug die zich achterin de z-volgorde bevindt,<br/>            en Shapes[Shapes.Count - 1] geeft de vorm terug die zich voorin de z-volgorde bevindt.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/legacydiagram/connection_site_count/) | Geeft het aantal aansluitpunten op de vorm terug.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/legacydiagram/rotation/) | Geeft het aantal graden terug dat de opgegeven vorm rond de z-as is gedraaid, of stelt dit in.<br/>            Een positieve waarde duidt op rotatie met de klok mee; een negatieve waarde<br/>            duidt op rotatie tegen de klok in.<br/>            Lezen/schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/legacydiagram/x/) | Leest of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/legacydiagram/y/) | Leest of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/legacydiagram/width/) | Leest of stelt de breedte van de vorm in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/legacydiagram/height/) | Leest of stelt de hoogte van de vorm in, gemeten in punten.<br/>            Lezen/schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/legacydiagram/black_white_mode/) | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit modus.<br/>            Lezen/schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/legacydiagram/unique_id/) | Geeft een interne, presentatiespecifieke identifier terug, bedoeld voor gebruik door invoegtoepassingen of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden hergebruikt, mag deze niet worden beschouwd<br/>            als een blijvende unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/legacydiagram/office_interop_shape_id/) | Geeft een dia-specifieke unieke identifier terug die constant blijft gedurende de levensduur van de vorm en<br/>            PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elke plek in het document.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/legacydiagram/alternative_text/) | Geeft de alternatieve tekst die aan een vorm is gekoppeld terug, of stelt deze in.<br/>            Lezen/schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/legacydiagram/alternative_text_title/) | Geeft de titel van de alternatieve tekst die aan een vorm is gekoppeld terug, of stelt deze in.<br/>            Lezen/schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/legacydiagram/name/) | Geeft de naam van een vorm terug, of stelt deze in.<br/>            Mag niet None zijn. Gebruik een lege tekenreeks indien nodig.<br/>            Lezen/schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/legacydiagram/is_decorative/) | Leest of stelt de optie 'Mark as decorative' in<br/>            Lezen/schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/legacydiagram/shape_lock/) | Geeft de vergrendelingen van de vorm terug.<br/>            Alleen-lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/legacydiagram/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/legacydiagram/parent_group/) | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Anders wordt None teruggegeven.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/legacydiagram/slide/) | Geeft de bovenliggende dia van een vorm terug.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/legacydiagram/presentation/) | Geeft de bovenliggende presentatie van een dia terug.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/nl/aspose.slides/legacydiagram/graphical_object_lock/) | Geeft de vergrendelingen van de vorm terug.<br/>            Alleen-lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/legacydiagram/get_image/#) | Geeft een miniatuur van de vorm terug.<br/>            ShapeThumbnailBounds.Shape miniatuurbereiktype voor vormminiaturen wordt standaard gebruikt. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | Geeft een miniatuur van de vorm terug. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/legacydiagram/remove_placeholder/#) | Definieert dat deze vorm geen placeholder is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/legacydiagram/get_base_placeholder/#) | Geeft een basis-placeholder-vorm terug (vorm uit de lay-out en/of master-dia waarvan de huidige vorm is geërfd).<br/>            Er wordt None teruggegeven als de huidige vorm niet is geërfd. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/legacydiagram/get_visual_bounds/#) | Haalt de visuele grenzen van de vorm op, berekend vanuit de gerenderde inhoud. |
| [`convert_to_smart_art(self)`](/slides/python-net/nl/aspose.slides/legacydiagram/convert_to_smart_art/#) | Converteert een legacy-diagram naar een bewerkbaar SmartArt-object. <br/>            Het aangemaakte SmartArt-object wordt toegevoegd aan de bovenliggende groep-vorm op dezelfde positie. |
| [`convert_to_group_shape(self)`](/slides/python-net/nl/aspose.slides/legacydiagram/convert_to_group_shape/#) | Converteert een legacy-diagram naar een bewerkbare groep-vorm. <br/>            Het aangemaakte GroupShape-object wordt toegevoegd aan de bovenliggende groep-vorm op dezelfde positie. |

### Zie ook
* klasse [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject)
* klasse [`LegacyDiagram`](/slides/python-net/nl/aspose.slides/legacydiagram)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)