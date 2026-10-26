---
title: ShapeCollection class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/
---
## ShapeCollection klasse

Stelt een verzameling van vormen voor.

Het ShapeCollection-type geeft de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`parent_group`](/slides/python-net/nl/aspose.slides/shapecollection/parent_group/) | Haalt het bovenliggende groepsvormobject op voor de vormenverzameling.<br/>            Read-only [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |

Haalt het element op op de opgegeven index.
            Read-only [`IShape`](/slides/python-net/nl/aspose.slides/ishape).

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides/shapecollection/__getitem__/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/nl/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en -instellingen, en voegt<br/>            het toe aan het einde van de vormverzameling. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/nl/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en -instellingen, en voegt<br/>            het toe aan het einde van de vormverzameling. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en -instellingen,<br/>            en voegt het in de vormverzameling in op de opgegeven index. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en -instellingen,<br/>            en voegt het in de vormverzameling in op de opgegeven index. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/nl/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormverzameling. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/nl/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormverzameling. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Maakt een nieuw Zoom-frame en voegt het in de vormverzameling in op de opgegeven index. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de vormverzameling in<br/>            op de opgegeven index. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/nl/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Maakt een nieuw sectie-Zoom-frame en voegt het toe aan het einde van de vormverzameling. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/nl/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Maakt een nieuw sectie-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de vormverzameling. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Maakt een nieuw sectie-Zoom-frame en voegt het in de vormverzameling in op de opgegeven index. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Maakt een nieuw sectie-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de vorm<br/>            op de opgegeven index. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/nl/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/nl/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Maakt een nieuw OLE-objectframe en voegt het in de vormverzameling in op de opgegeven index. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Maakt een nieuw OLE-objectframe en voegt het in de vormverzameling in op de opgegeven index. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/nl/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | Maakt een nieuw video-frame en voegt het toe aan het einde van de vormverzameling. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/nl/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | Maakt een nieuw video-frame en voegt het toe aan het einde van de vormverzameling. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/nl/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Maakt een nieuw audio-frame met een ingebedde WAV-bestand en voegt het toe aan het einde van de<br/>            vormverzameling. Het ingebedde audio-bestand wordt toegevoegd aan de Presentation.Audios-verzameling. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/nl/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Maakt een nieuw audio-frame en voegt het toe aan het einde van de vormverzameling met behulp van een<br/>            bestaand audio-object uit de Presentation.Audios-lijst. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Maakt een nieuw audio-frame met een ingebedde WAV-bestand en voegt het in de vorm<br/>            op de opgegeven index. Het ingebedde audio-bestand wordt toegevoegd aan de Presentation.Audios<br/>            verzameling. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Maakt een nieuw audio-frame en voegt het in de vormverzameling in op de opgegeven index<br/>            met behulp van een bestaand audio-object uit de Presentation.Audios-lijst. |
| [`to_array(self)`](/slides/python-net/nl/aspose.slides/shapecollection/to_array/#) | Maakt en retourneert een array die alle vormen bevat. |
| [`to_array(self, start_index, count)`](/slides/python-net/nl/aspose.slides/shapecollection/to_array/#int-int) | Maakt en retourneert een array die alle vormen bevat binnen het opgegeven bereik. |
| [`reorder(self, index, shape)`](/slides/python-net/nl/aspose.slides/shapecollection/reorder/#int-ishape) | Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormverzameling. |
| [`reorder(self, index, shapes)`](/slides/python-net/nl/aspose.slides/shapecollection/reorder/#int-listishape) | Verplaatst de opgegeven vormen binnen de vormverzameling, en plaatst ze beginnend bij de opgegeven index. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/nl/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | Maakt een nieuwe auto-vorm met standaardopmaak en voegt het toe aan het einde van de<br/>            vormverzameling. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/nl/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Maakt een nieuwe auto-vorm en voegt het toe aan het einde van de vormverzameling, eventueel<br/>            initieel met standaard sjabloonopmaak. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Maakt een nieuwe auto-vorm en voegt het in de vormverzameling in op de opgegeven index,<br/>            met standaard sjabloonopmaak. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Maakt een nieuwe auto-vorm en voegt het in de vormverzameling in op de opgegeven index,<br/>            eventueel initieel met standaard sjabloonstijl. |
| [`add_group_shape(self)`](/slides/python-net/nl/aspose.slides/shapecollection/add_group_shape/#) | Maakt een nieuwe lege groepsvorm en voegt het toe aan het einde van de vormverzameling.<br/>            Het frame van de groep past zich automatisch aan om alle toegevoegde vormen te bevatten. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/nl/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | Maakt een nieuwe groepsvorm, converteert de opgegeven SVG-afbeelding naar individuele vormen,<br/>            en voegt de resulterende groep toe aan het einde van de vormverzameling. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/nl/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | Maakt een nieuwe connector-vorm met standaard sjabloonstijl en voegt het toe aan het einde van de<br/>            vormverzameling. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/nl/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | Maakt een nieuwe connector-vorm en voegt het toe aan het einde van de vormverzameling,<br/>            eventueel met standaard sjabloonstijl. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | Maakt een nieuwe connector-vorm en voegt het in de vormverzameling in op de opgegeven index,<br/>            met standaard sjabloonstijl. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Maakt een nieuwe connector-vorm en voegt het in de vormverzameling in op de opgegeven index,<br/>            eventueel met standaard sjabloonstijl. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/nl/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/nl/aspose.slides/shapecollection/add_clone/#ishape-float-float) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling.<br/>            De nieuwe vorm behoudt de breedte en hoogte van de `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/nl/aspose.slides/shapecollection/add_clone/#ishape) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling.<br/>            De gekloonde vorm behoudt de positie en grootte van het origineel. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de opgegeven index. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de opgegeven index.<br/>            De nieuwe vorm behoudt de breedte en hoogte van de `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_clone/#int-ishape) | Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de opgegeven index.<br/>            De gekloonde vorm behoudt de positie en grootte van het origineel. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/nl/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Maakt een SmartArt-diagram en voegt het toe aan het einde van de vormverzameling. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/nl/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | Maakt een nieuw Samenvatting-Zoom-frame en voegt het toe aan het einde van de vormverzameling. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Maakt een nieuw Samenvatting-Zoom-frame en voegt het in de vormverzameling in op de opgegeven index. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | Maakt een nieuw video-frame en voegt het in de vormverzameling in op de opgegeven index. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/nl/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het toe aan het einde van de vormverzameling. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het in de vormverzameling in<br/>            op de opgegeven index. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/nl/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het toe aan het einde van<br/>            de vormverzameling. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het in de vorm<br/>            op de opgegeven index. |
| [`index_of(self, shape)`](/slides/python-net/nl/aspose.slides/shapecollection/index_of/#ishape) | Retourneert de nulgebaseerde index van de eerste voorkoming van de opgegeven vorm in de verzameling. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/nl/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | Maakt een nieuwe rechthoekige auto-vorm om wiskundige inhoud te hosten en voegt het toe aan het einde van de<br/>            vormverzameling. |
| [`insert_group_shape(self, index)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_group_shape/#int) | Maakt een nieuwe lege groepsvorm en voegt deze in de vormverzameling in op de opgegeven index.<br/>            Het frame van de groep past zich automatisch aan om alle toegevoegde vormen te bevatten. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/nl/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Maakt een nieuw afbeelding-frame met de opgegeven afbeelding en voegt het toe aan het einde van de<br/>            vormverzameling. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Maakt een nieuw afbeelding-frame met de opgegeven afbeelding en voegt het in de vorm<br/>            verzameling op de opgegeven index in. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/nl/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | Maakt een nieuwe tabel en voegt deze toe aan het einde van de vormverzameling. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/nl/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | Maakt een nieuwe tabel en voegt deze in de vormverzameling in op de opgegeven index. |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides/shapecollection/remove_at/#int) | Verwijdert de vorm op de opgegeven index uit de vormverzameling. |
| [`remove(self, shape)`](/slides/python-net/nl/aspose.slides/shapecollection/remove/#ishape) | Verwijdert de eerste voorkoming van de opgegeven vorm uit de vormverzameling. |
| [`clear(self)`](/slides/python-net/nl/aspose.slides/shapecollection/clear/#) | Verwijdert alle vormen uit de vormverzameling. |

### Zie ook
* klasse [`IShape`](/slides/python-net/nl/aspose.slides/ishape)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)