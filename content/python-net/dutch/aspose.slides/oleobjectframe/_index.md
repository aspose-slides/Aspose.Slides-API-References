---
title: OleObjectFrame class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/oleobjectframe/
---
## OleObjectFrame klasse

Stelt een OLE-object op een dia voor.

**Inheritance:**[`OleObjectFrame`](/slides/python-net/nl/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

The OleObjectFrame type exposes the following members:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/oleobjectframe/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/oleobjectframe/placeholder/) | Geeft de tijdelijke aanduiding voor een vorm terug. Retourneert None als de vorm geen tijdelijke aanduiding heeft.<br/>            Alleen lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/oleobjectframe/custom_data/) | Geeft de aangepaste gegevens van de vorm terug.<br/>            Alleen lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/oleobjectframe/raw_frame/) | Geeft de ruwe eigenschappen van het vormkader terug of stelt ze in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/oleobjectframe/frame/) | Geeft de eigenschappen van het vormkader terug of stelt ze in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/oleobjectframe/line_format/) | Geeft het LineFormat-object terug dat de lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde soorten vormen die geen lijn-eigenschappen hebben.<br/>            Alleen lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/oleobjectframe/three_d_format/) | Geeft het ThreeDFormat-object terug dat 3D-effecteigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde soorten vormen die geen 3D-eigenschappen hebben.<br/>            Alleen lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/oleobjectframe/effect_format/) | Geeft het EffectFormat-object terug dat pixel-effecten bevat die op een vorm worden toegepast.<br/>            Opmerking: kan None retourneren voor bepaalde soorten vormen die geen effecteigenschappen hebben.<br/>            Alleen lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/oleobjectframe/fill_format/) | Geeft het FillFormat-object terug dat de opvulopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde soorten vormen die geen opvuleigenschappen hebben.<br/>            Alleen lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/oleobjectframe/hyperlink_click/) | Geeft de hyperlink terug die is gedefinieerd voor muisklik of stelt deze in.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Geeft de hyperlink terug die is gedefinieerd voor muisover of stelt deze in.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/oleobjectframe/hyperlink_manager/) | Geeft de hyperlinkmanager terug.<br/>            Alleen lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/oleobjectframe/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/Schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/oleobjectframe/z_order_position/) | Geeft de positie van een vorm in de z-volgorde terug.<br/>            Shapes[0] retourneert de vorm aan de achterkant van de z-volgorde,<br/>            en Shapes[Shapes.Count - 1] retourneert de vorm aan de voorkant van de z-volgorde.<br/>            Alleen lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/oleobjectframe/connection_site_count/) | Geeft het aantal aansluitpunten op de vorm terug.<br/>            Alleen lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/oleobjectframe/rotation/) | Geeft het aantal graden terug waarmee de opgegeven vorm rond de z-as is gedraaid of stelt dit in.<br/>            Een positieve waarde duidt op rotatie met de klok mee; een negatieve waarde<br/>            duidt op tegen de klok in rotatie.<br/>            Lezen/Schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/oleobjectframe/x/) | Geeft de x-coördinaat van de linkerbovenhoek van de vorm terug of stelt deze in, gemeten in points.<br/>            Lezen/Schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/oleobjectframe/y/) | Geeft de y-coördinaat van de linkerbovenhoek van de vorm terug of stelt deze in, gemeten in points.<br/>            Lezen/Schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/oleobjectframe/width/) | Geeft de breedte van de vorm terug of stelt deze in, gemeten in points.<br/>            Lezen/Schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/oleobjectframe/height/) | Geeft de hoogte van de vorm terug of stelt deze in, gemeten in points.<br/>            Lezen/Schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/oleobjectframe/black_white_mode/) | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus..<br/>            Lezen/Schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/oleobjectframe/unique_id/) | Geeft een interne, presentatie-gebonden identifier terug die bedoeld is voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden hertoegewezen, mag deze niet worden behandeld als een blijvende unieke sleutel.<br/>            Alleen lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/oleobjectframe/office_interop_shape_id/) | Geeft een slide-gebonden unieke identifier terug die constant blijft gedurende de levensduur van de vorm en<br/>            laat PowerPoint of interop-code de vorm betrouwbaar refereren vanuit elk deel van het document.<br/>            Alleen lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/oleobjectframe/alternative_text/) | Geeft de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/oleobjectframe/alternative_text_title/) | Geeft de titel van de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/oleobjectframe/name/) | Geeft de naam van een vorm terug of stelt deze in.<br/>            Mag niet None zijn. Gebruik een lege tekenreeks indien nodig.<br/>            Lezen/Schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/oleobjectframe/is_decorative/) | Geeft de optie 'Mark as decorative' terug of stelt deze in<br/>            Lezen/Schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/oleobjectframe/shape_lock/) | Geeft de vergrendelingen van de vorm terug.<br/>            Alleen lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/oleobjectframe/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/oleobjectframe/parent_group/) | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Anders wordt None geretourneerd.<br/>            Alleen lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/oleobjectframe/slide/) | Geeft de bovenliggende dia van een vorm terug.<br/>            Alleen lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/oleobjectframe/presentation/) | Geeft de bovenliggende presentatie van een dia terug.<br/>            Alleen lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/nl/aspose.slides/oleobjectframe/graphical_object_lock/) | Geeft de vergrendelingen van de vorm terug.<br/>            Alleen lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/nl/aspose.slides/oleobjectframe/substitute_picture_format/) | Geeft het OleObject-afbeeldingsvul-eigenschappenobject terug.<br/>            Alleen lezen [`IPictureFillFormat`](/slides/python-net/nl/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/nl/aspose.slides/oleobjectframe/substitute_picture_title/) | Geeft de titel voor het OleObject-pictogram terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`object_name`](/slides/python-net/nl/aspose.slides/oleobjectframe/object_name/) | Geeft de naam van een object terug of stelt deze in.<br/>            Lezen/Schrijven **str**. |
| [`object_prog_id`](/slides/python-net/nl/aspose.slides/oleobjectframe/object_prog_id/) | Geeft de ProgID van een object terug.<br/>            Alleen lezen **str**. |
| [`link_file_name`](/slides/python-net/nl/aspose.slides/oleobjectframe/link_file_name/) | Geeft het volledige pad naar een gekoppeld bestand terug. De korte bestandsnaam wordt gebruikt.<br/>            Alleen lezen **str**. |
| [`link_path_long`](/slides/python-net/nl/aspose.slides/oleobjectframe/link_path_long/) | Geeft het volledige pad naar een gekoppeld bestand terug. De lange bestandsnaam wordt gebruikt.<br/>            Lezen/Schrijven **str**. |
| [`link_path_relative`](/slides/python-net/nl/aspose.slides/oleobjectframe/link_path_relative/) | Geeft het relatieve pad naar een gekoppeld bestand terug indien aanwezig, anders wordt een lege tekenreeks geretourneerd.<br/>             Alleen lezen **str**. |
| [`embedded_file_label`](/slides/python-net/nl/aspose.slides/oleobjectframe/embedded_file_label/) | Geeft de bestandsnaam van het ingebedde OLE-object terug |
| [`embedded_file_name`](/slides/python-net/nl/aspose.slides/oleobjectframe/embedded_file_name/) | Geeft het pad van het ingebedde OLE-object terug |
| [`embedded_data`](/slides/python-net/nl/aspose.slides/oleobjectframe/embedded_data/) | Geeft informatie over OLE-ingebedde gegevens terug of stelt deze in.<br/>            Lezen/Schrijven [`IOleEmbeddedDataInfo`](/slides/python-net/nl/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/nl/aspose.slides/oleobjectframe/is_object_icon/) | Bepaalt of een object als pictogram zichtbaar is.<br/>            Lezen/Schrijven **bool**. |
| [`is_object_link`](/slides/python-net/nl/aspose.slides/oleobjectframe/is_object_link/) | Bepaalt of een object is gekoppeld aan een extern bestand.<br/>            Alleen lezen **bool**. |
| [`update_automatic`](/slides/python-net/nl/aspose.slides/oleobjectframe/update_automatic/) | Bepaalt of het gekoppelde ingebedde object automatisch wordt bijgewerkt wanneer de presentatie wordt geopend of afgedrukt.<br/>            Lezen/Schrijven **bool**. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/oleobjectframe/get_image/#) | Geeft de miniatuur van de vorm terug.<br/>            ShapeThumbnailBounds.Shape vormminiatuurgrenzenstype wordt standaard gebruikt. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Geeft de miniatuur van de vorm terug. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/oleobjectframe/remove_placeholder/#) | Definieert dat deze vorm geen tijdelijke aanduiding is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Voegt een nieuwe tijdelijke aanduiding toe als er geen is en stelt de eigenschappen van de tijdelijke aanduiding in op een opgegeven. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/oleobjectframe/get_base_placeholder/#) | Geeft een basis tijdelijke aanduidingsvorm terug (vorm van de lay-out en/of masterslide waarvan de huidige vorm is geërfd).<br/>            Er wordt None geretourneerd als de huidige vorm niet is geërfd. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/oleobjectframe/get_visual_bounds/#) | Geeft de visuele grenzen van de vorm terug, berekend aan de hand van de gerenderde inhoud. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/nl/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Stelt informatie over OLE-ingebedde gegevens in.<br/>            <br/>            Deze methode wijzigt de eigenschappen van het object om de nieuwe gegevens weer te geven en<br/>            stelt de IsObjectLink-vlag in op false, wat aangeeft dat het OLE-object is ingebed. |

### Zie ook
* klasse [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject)
* klasse [`OleObjectFrame`](/slides/python-net/nl/aspose.slides/oleobjectframe)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)