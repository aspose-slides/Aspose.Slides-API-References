---
title: Ink class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.ink/ink/
---
## Ink klasse

Stelt een inktobject op een dia voor.

**Erfenis:**[`Ink`](/slides/python-net/nl/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

Het Ink-type maakt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides.ink/ink/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides.ink/ink/placeholder/) | Geeft de tijdelijke aanduiding voor een vorm terug. Geeft None terug als de vorm geen tijdelijke aanduiding heeft.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides.ink/ink/custom_data/) | Geeft de aangepaste gegevens van de vorm terug.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides.ink/ink/raw_frame/) | Geeft de ruwe vormframe-eigenschappen terug of stelt ze in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides.ink/ink/frame/) | Geeft de vormframe-eigenschappen terug of stelt ze in.<br/>            Lezen/schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides.ink/ink/line_format/) | Geeft het LineFormat-object terug dat de lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde soorten vormen die geen lijn-eigenschappen hebben.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides.ink/ink/three_d_format/) | Geeft het ThreeDFormat-object terug dat 3d-effecteigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde soorten vormen die geen 3d-eigenschappen hebben.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides.ink/ink/effect_format/) | Geeft het EffectFormat-object terug dat pixel-effecten op een vorm toepast.<br/>            Opmerking: kan None teruggeven voor bepaalde soorten vormen die geen effecteigenschappen hebben.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides.ink/ink/fill_format/) | Geeft het FillFormat-object terug dat opvulpopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None teruggeven voor bepaalde soorten vormen die geen opvuleigenschappen hebben.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides.ink/ink/hyperlink_click/) | Geeft de hyperlink terug of stelt deze in voor muisklik.<br/>            Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides.ink/ink/hyperlink_mouse_over/) | Geeft de hyperlink terug of stelt deze in voor muis-over.<br/>            Lezen/schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides.ink/ink/hyperlink_manager/) | Geeft de hyperlink-manager terug.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides.ink/ink/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides.ink/ink/z_order_position/) | Geeft de positie van een vorm in de z-volgorde terug.<br/>            Shapes[0] geeft de vorm aan de achterkant van de z-volgorde terug,<br/>            en Shapes[Shapes.Count - 1] geeft de vorm aan de voorkant van de z-volgorde terug.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides.ink/ink/connection_site_count/) | Geeft het aantal aansluitpunten op de vorm terug.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides.ink/ink/rotation/) | Geeft het aantal graden terug of stelt het in waarmee de opgegeven vorm rond de z-as gedraaid wordt.<br/>            Een positieve waarde geeft een rotatie met de klok mee aan; een negatieve waarde geeft een tegen-klok-richting rotatie aan.<br/>            Lezen/schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides.ink/ink/x/) | Haalt de x-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten, of stelt deze in.<br/>            Lezen/schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides.ink/ink/y/) | Haalt de y-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten, of stelt deze in.<br/>            Lezen/schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides.ink/ink/width/) | Haalt de breedte van de vorm op, gemeten in punten, of stelt deze in.<br/>            Lezen/schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides.ink/ink/height/) | Haalt de hoogte van de vorm op, gemeten in punten, of stelt deze in.<br/>            Lezen/schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides.ink/ink/black_white_mode/) | Eigenschap bepaalt hoe een vorm wordt weergegeven in zwart-wit weergavemodus..<br/>            Lezen/schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides.ink/ink/unique_id/) | Geeft een interne, per presentatie gescopeerde identifier terug die bedoeld is voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden opnieuw toegewezen, mag hij niet worden behandeld als een blijvende unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides.ink/ink/office_interop_shape_id/) | Geeft een dia-gescopeerde unieke identifier terug die gedurende de levensduur van de vorm constant blijft en PowerPoint of interop-code in staat stelt de vorm betrouwbaar vanuit elk deel van het document te refereren.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides.ink/ink/alternative_text/) | Geeft de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in.<br/>            Lezen/schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides.ink/ink/alternative_text_title/) | Geeft de titel van de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in.<br/>            Lezen/schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides.ink/ink/name/) | Geeft de naam van een vorm terug of stelt deze in.<br/>            Mag niet None zijn. Gebruik een lege tekenreeks indien nodig.<br/>            Lezen/schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides.ink/ink/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides.ink/ink/shape_lock/) | Geeft de vergrendelingen van de vorm terug.<br/>            Alleen-lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides.ink/ink/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides.ink/ink/parent_group/) | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Geeft anders None terug.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides.ink/ink/slide/) | Geeft de bovenliggende dia van een vorm terug.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides.ink/ink/presentation/) | Geeft de bovenliggende presentatie van een dia terug.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/nl/aspose.slides.ink/ink/graphical_object_lock/) | Geeft de vergrendelingen van de vorm terug.<br/>            Alleen-lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/nl/aspose.slides.ink/ink/traces/) | Haalt alle sporen op die zich in het IInk-element [`IInkTrace`](/slides/python-net/nl/aspose.slides.ink/iinktrace) bevinden.<br/>            Alleen-lezen. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides.ink/ink/get_image/#) | Geeft miniatuur van vorm terug.<br/>            ShapeThumbnailBounds.Shape miniatuurgrenzen-type wordt standaard gebruikt. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | Geeft miniatuur van vorm terug. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | Slaat de inhoud van vorm op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van vorm op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides.ink/ink/remove_placeholder/#) | Definieert dat deze vorm geen tijdelijke aanduiding is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | Voegt een nieuwe tijdelijke aanduiding toe als er geen is en stelt de tijdelijke aanduidingseigenschappen in op een opgegeven één. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides.ink/ink/get_base_placeholder/#) | Geeft een basis-tijdelijke-aanduidings-vorm terug (vorm van de lay-out en/of master-dia waar de huidige vorm van is geërfd).<br/>            Een None wordt teruggegeven als de huidige vorm niet geërfd is. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides.ink/ink/get_visual_bounds/#) | Haalt de visuele grenzen van de vorm op, berekend uit de gerenderde inhoud. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/nl/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | Registreert een afbeelding in de collectie van aangepaste afbeeldingen die worden gebruikt om visuele effecten voor inkt-penseel te simuleren.<br/>            Deze afbeeldingen worden gebruikt bij het renderen van inkt met specifieke [`InkEffectType`](/slides/python-net/nl/aspose.slides.ink/inkeffecttype)-waarden,<br/>            zoals Galaxy, Rainbow, enz. Door uw eigen afbeeldingen te leveren, kunt u bepalen hoe elk inkt-effect verschijnt. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/nl/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | Deregistreert een afbeelding uit de collectie van aangepaste afbeeldingen die worden gebruikt om visuele effecten voor inkt-penseel te simuleren<br/>            eerder geregistreerde afbeeldingen via **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide**. |

### Zie ook
* klasse [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject)
* klasse [`Ink`](/slides/python-net/nl/aspose.slides.ink/ink)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* module [`aspose.slides.ink`](/slides/python-net/nl/aspose.slides.ink)
* library [`Aspose.Slides`](/slides/python-net)