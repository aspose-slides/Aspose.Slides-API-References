---
title: Table class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/table/
---
## Table klasse

Stelt een tabel voor op een dia.

**Erfenis:**[`Table`](/slides/python-net/nl/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/nl/aspose.slides/shape)

Het Table-type exposeert de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/table/is_text_holder/) | Bepaalt of de vorm TextHolder_PPT is.<br/>            Alleen-lezen **bool**. |
| [`placeholder`](/slides/python-net/nl/aspose.slides/table/placeholder/) | Retourneert de tijdelijke aanduiding voor een vorm. Retourneert None als de vorm geen tijdelijke aanduiding heeft.<br/>            Alleen-lezen [`IPlaceholder`](/slides/python-net/nl/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/nl/aspose.slides/table/custom_data/) | Retourneert de aangepaste gegevens van de vorm.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/table/raw_frame/) | Retourneert of stelt de eigenschappen van het ruwe vormkader in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/nl/aspose.slides/table/frame/) | Retourneert of stelt de eigenschappen van het vormkader in.<br/>            Lezen/Schrijven [`IShapeFrame`](/slides/python-net/nl/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/nl/aspose.slides/table/line_format/) | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde typen vormen die geen lijn-eigenschappen hebben.<br/>            Alleen-lezen [`ILineFormat`](/slides/python-net/nl/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/table/three_d_format/) | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een vorm bevat.<br/>            Opmerking: kan None retourneren voor bepaalde typen vormen die geen 3D-eigenschappen hebben.<br/>            Alleen-lezen [`IThreeDFormat`](/slides/python-net/nl/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/nl/aspose.slides/table/effect_format/) | Retourneert het EffectFormat-object dat pixel-effecten op een vorm toepast.<br/>            Opmerking: kan None retourneren voor bepaalde typen vormen die geen effecteigenschappen hebben.<br/>            Alleen-lezen [`IEffectFormat`](/slides/python-net/nl/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/nl/aspose.slides/table/fill_format/) | Retourneert een TableFormat.FillFormat-object dat de opvulopmaak voor de Table bevat.<br/>            Alleen-lezen [`IFillFormat`](/slides/python-net/nl/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/table/hyperlink_click/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/table/hyperlink_mouse_over/) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisover.<br/>            Lezen/Schrijven [`IHyperlink`](/slides/python-net/nl/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/table/hyperlink_manager/) | Retourneert de hyperlinkmanager.<br/>            Alleen-lezen [`IHyperlinkManager`](/slides/python-net/nl/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/nl/aspose.slides/table/hidden/) | Bepaalt of de vorm verborgen is.<br/>            Lezen/Schrijven **bool**. |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/table/z_order_position/) | Retourneert de positie van een vorm in de z-volgorde.<br/>            Shapes[0] retourneert de vorm achteraan in de z-volgorde,<br/>            en Shapes[Shapes.Count - 1] retourneert de vorm vooraan in de z-volgorde.<br/>            Alleen-lezen **int**. |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/table/connection_site_count/) | Retourneert het aantal verbindingpunten op de vorm.<br/>            Alleen-lezen **int**. |
| [`rotation`](/slides/python-net/nl/aspose.slides/table/rotation/) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm om de z-as wordt geroteerd.<br/>            Een positieve waarde duidt op een klokwijzerrotatie; een negatieve waarde<br/>            duidt op een tegenklokwijzerrotatie.<br/>            Lezen/Schrijven **float**. |
| [`x`](/slides/python-net/nl/aspose.slides/table/x/) | Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm op, gemeten in points.<br/>            Lezen/Schrijven **float**. |
| [`y`](/slides/python-net/nl/aspose.slides/table/y/) | Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm op, gemeten in points.<br/>            Lezen/Schrijven **float**. |
| [`width`](/slides/python-net/nl/aspose.slides/table/width/) | Haalt of stelt de breedte van de vorm op, gemeten in points.<br/>            Lezen/Schrijven **float**. |
| [`height`](/slides/python-net/nl/aspose.slides/table/height/) | Haalt of stelt de hoogte van de vorm op, gemeten in points.<br/>            Lezen/Schrijven **float**. |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/table/black_white_mode/) | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus.<br/>            Lezen/Schrijven [`BlackWhiteMode`](/slides/python-net/nl/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/nl/aspose.slides/table/unique_id/) | Retourneert een interne, presentatie-gebonden identifier bedoeld voor gebruik door add-ins of andere code.<br/>            Omdat deze waarde door de gebruiker of programmatisch kan worden hertoegewezen, mag deze niet worden behandeld<br/>            als een permanente unieke sleutel.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.office_interop_shape_id`](/slides/python-net/nl/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/table/office_interop_shape_id/) | Retourneert een unieke identifier die aan de dia is gebonden en constant blijft gedurende de levensduur van de vorm en<br/>            PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanaf elke locatie in het document.<br/>            Alleen-lezen **int**.<br/>            Zie ook [`Shape.unique_id`](/slides/python-net/nl/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/table/alternative_text/) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/Schrijven **str**. |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/table/alternative_text_title/) | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld.<br/>            Lezen/Schrijven **str**. |
| [`name`](/slides/python-net/nl/aspose.slides/table/name/) | Retourneert of stelt de naam van een vorm in.<br/>            Mag niet None zijn. Gebruik een lege tekenreeks indien nodig.<br/>            Lezen/Schrijven **str**. |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/table/is_decorative/) | Haalt of stelt de 'Mark as decorative' optie in<br/>            Lezen/Schrijven **bool**. |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/table/shape_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/table/is_grouped/) | Bepaalt of de vorm gegroepeerd is.<br/>            Alleen-lezen **bool**. |
| [`parent_group`](/slides/python-net/nl/aspose.slides/table/parent_group/) | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Retourneert anders None.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/nl/aspose.slides/table/slide/) | Retourneert de bovenliggende dia van een vorm.<br/>            Alleen-lezen [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/nl/aspose.slides/table/presentation/) | Retourneert de bovenliggende presentatie van een dia.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/nl/aspose.slides/table/graphical_object_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IGraphicalObjectLock`](/slides/python-net/nl/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/nl/aspose.slides/table/rows/) | Retourneert de collectie van rijen.<br/>            Alleen-lezen [`IRowCollection`](/slides/python-net/nl/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/nl/aspose.slides/table/columns/) | Retourneert de collectie van kolommen.<br/>            Alleen-lezen [`IColumnCollection`](/slides/python-net/nl/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/nl/aspose.slides/table/table_format/) | Retourneert het TableFormat-object dat opmaak-eigenschappen voor deze tabel bevat.<br/>            Alleen-lezen [`ITableFormat`](/slides/python-net/nl/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/nl/aspose.slides/table/style_preset/) | Haalt of stelt de ingesloten tabelstijl in.<br/>            Lezen/Schrijven [`TableStylePreset`](/slides/python-net/nl/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/nl/aspose.slides/table/right_to_left/) | Bepaalt of de tabel een van rechts naar links leesvolgorde heeft.<br/>            Lezen/Schrijven **bool**. |
| [`first_row`](/slides/python-net/nl/aspose.slides/table/first_row/) | Bepaalt of de eerste rij van een tabel moet worden getekend met een speciale opmaak.<br/>            Lezen/Schrijven **bool**. |
| [`first_col`](/slides/python-net/nl/aspose.slides/table/first_col/) | Bepaalt of de eerste kolom van een tabel moet worden getekend met een speciale opmaak.<br/>            Lezen/Schrijven **bool**. |
| [`last_row`](/slides/python-net/nl/aspose.slides/table/last_row/) | Bepaalt of de laatste rij van een tabel moet worden getekend met een speciale opmaak.<br/>            Lezen/Schrijven **bool**. |
| [`last_col`](/slides/python-net/nl/aspose.slides/table/last_col/) | Bepaalt of de laatste kolom van een tabel moet worden getekend met een speciale opmaak.<br/>            Lezen/Schrijven **bool**. |
| [`horizontal_banding`](/slides/python-net/nl/aspose.slides/table/horizontal_banding/) | Bepaalt of de even rijen moeten worden getekend met een andere opmaak.<br/>            Lezen/Schrijven **bool**. |
| [`vertical_banding`](/slides/python-net/nl/aspose.slides/table/vertical_banding/) | Bepaalt of de even kolommen moeten worden getekend met een andere opmaak.<br/>            Lezen/Schrijven **bool**. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/table/get_image/#) | Retourneert miniatuur van vorm.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Retourneert miniatuur van vorm. |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/table/write_as_svg/#iorawiobase) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slaat de inhoud van Shape op als SVG-bestand. |
| [`set_text_format(self, source)`](/slides/python-net/nl/aspose.slides/table/set_text_format/#iportionformat) | Stelt de gedefinieerde portion-format-eigenschappen in voor alle portions van tabelcellen. |
| [`set_text_format(self, source)`](/slides/python-net/nl/aspose.slides/table/set_text_format/#iparagraphformat) | Stelt de gedefinieerde alinea-format-eigenschappen in voor alle alinea's van tabelcellen. |
| [`set_text_format(self, source)`](/slides/python-net/nl/aspose.slides/table/set_text_format/#itextframeformat) | Stelt de gedefinieerde tekstframe-format-eigenschappen in voor alle tekstframes van tabelcellen. |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/table/remove_placeholder/#) | Definieert dat deze vorm geen placeholder is. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/table/add_placeholder/#iplaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven. |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/table/get_base_placeholder/#) | Retourneert een basis placeholder-shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            Een None wordt geretourneerd als de huidige vorm niet geërfd is. |
| [`get_visual_bounds(self)`](/slides/python-net/nl/aspose.slides/table/get_visual_bounds/#) | Haalt de visuele grenzen van de vorm op, berekend vanuit de gerenderde inhoud. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/nl/aspose.slides/table/merge_cells/#icell-icell-bool) | Voegt aangrenzende cellen samen. |

### Zie ook
* klasse [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject)
* klasse [`Shape`](/slides/python-net/nl/aspose.slides/shape)
* klasse [`Table`](/slides/python-net/nl/aspose.slides/table)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)