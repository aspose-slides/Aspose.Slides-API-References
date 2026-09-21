---
title: IShapeCollection class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/
---
## IShapeCollection klasse

Stelt een collectie van vormen voor.

Het IShapeCollection type biedt de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`parent_group`](/slides/python-net/nl/aspose.slides/ishapecollection/parent_group/) | Haalt het bovenliggende groepsvormobject op voor de vormenverzameling.<br/>            Alleen-lezen [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape). |

Haalt het element op op de opgegeven index.
            Alleen-lezen [`IShape`](/slides/python-net/nl/aspose.slides/ishape).

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides/ishapecollection/__getitem__/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Maakt een nieuw diagram, initialiseert het met voorbeeldserie-gegevens en instellingen, en voegt<br/>            het toe aan het einde van de vormenverzameling. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Maakt een nieuw diagram, Initialiseert het met voorbeeldserie-gegevens en instellingen, en voegt<br/>            het toe aan het einde van de vormenverzameling. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Maakt een nieuw diagram, Initialiseert het met voorbeeldserie-gegevens en instellingen,<br/>            en voegt het in de vormenverzameling in op de opgegeven index. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Maakt een nieuw diagram, Initialiseert het met voorbeeldserie-gegevens en instellingen,<br/>            en voegt het in de vormenverzameling in op de opgegeven index. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormenverzameling. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormenverzameling. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Maakt een nieuw OLE-objectframe en voegt het in de vormenverzameling in op de opgegeven index. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Maakt een nieuw OLE-objectframe en voegt het in de vormenverzameling in op de opgegeven index. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormenverzameling. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormenverzameling. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Maakt een nieuw Zoom-frame en voegt het in de vormenverzameling in op de opgegeven index. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de vormenverzameling in<br/>            op de opgegeven index. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Maakt een nieuw Sectie Zoom-frame en voegt het toe aan het einde van de vormenverzameling. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Maakt een nieuw Sectie Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de<br/>            vormenverzameling. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Maakt een nieuw Sectie Zoom-frame en voegt het in de vormenverzameling in op de<br/>            opgegeven index. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Maakt een nieuw Sectie Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de vormenverzameling in op de<br/>            opgegeven index. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Maakt een nieuw video-frame en voegt het toe aan het einde van de vormenverzameling. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Maakt een nieuw video-frame en voegt het toe aan het einde van de vormenverzameling. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Maakt een nieuw audio-frame met een ingebedde WAV-bestand en voegt het toe aan het einde van de<br/>            vormenverzameling. De ingebedde audio wordt toegevoegd aan de Presentation.Audios-verzameling. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Maakt een nieuw audio-frame en voegt het toe aan het einde van de vormenverzameling met behulp van een<br/>            bestaand audio-object uit de Presentation.Audios-lijst. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Maakt een nieuw audio-frame met een ingebedde WAV-bestand en voegt het in de vormen<br/>            verzameling in op de opgegeven index. De ingebedde audio wordt toegevoegd aan de Presentation.Audios<br/>            verzameling. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Maakt een nieuw audio-frame en voegt het in de vormenverzameling in op de opgegeven index<br/>            met behulp van een bestaand audio-object uit de Presentation.Audios-lijst. |
| [`to_array(self)`](/slides/python-net/nl/aspose.slides/ishapecollection/to_array/#) | Maakt en retourneert een array die alle vormen bevat. |
| [`to_array(self, start_index, count)`](/slides/python-net/nl/aspose.slides/ishapecollection/to_array/#int-int) | Maakt en retourneert een array die alle vormen in het opgegeven bereik bevat. |
| [`reorder(self, index, shape)`](/slides/python-net/nl/aspose.slides/ishapecollection/reorder/#int-ishape) | Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormenverzameling. |
| [`reorder(self, index, shapes)`](/slides/python-net/nl/aspose.slides/ishapecollection/reorder/#int-listishape) | Verplaatst de opgegeven vormen binnen de vormenverzameling, beginnend op de opgegeven index. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Maakt een nieuwe auto-vorm met standaardopmaak en voegt deze toe aan het einde van de<br/>            vormenverzameling. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Maakt een nieuwe auto-vorm en voegt deze toe aan het einde van de vormenverzameling, eventueel<br/>            te initialiseren met standaard sjabloonopmaak. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Maakt een nieuwe auto-vorm en voegt deze in de vormenverzameling in op de opgegeven index,<br/>            met standaard sjabloonopmaak. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Maakt een nieuwe auto-vorm en voegt deze in de vormenverzameling in op de opgegeven index,<br/>            eventueel te initialiseren met standaard sjabloonstijl. |
| [`add_group_shape(self)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_group_shape/#) | Maakt een nieuw leeg groepsvorm en voegt deze toe aan het einde van de vormenverzameling.<br/>            Het frame van de groep past zich automatisch aan om alle toegevoegde vormen te bevatten. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Maakt een nieuw groepsvorm, zet de opgegeven SVG-afbeelding om naar individuele vormen,<br/>            en voegt de resulterende groep toe aan het einde van de vormenverzameling. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Maakt een nieuw connector-vorm met standaard sjabloonstijl en voegt deze toe aan het einde van de<br/>            vormenverzameling. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Maakt een nieuw connector-vorm en voegt deze toe aan het einde van de vormenverzameling,<br/>            eventueel met standaard sjabloonstijl. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Maakt een nieuw connector-vorm en voegt deze in de vormenverzameling in op de opgegeven index,<br/>            met standaard sjabloonstijl. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Maakt een nieuw connector-vorm en voegt deze in de vormenverzameling in op de opgegeven index,<br/>            eventueel met standaard sjabloonstijl. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormenverzameling. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormenverzameling.<br/>            De nieuwe vorm behoudt de breedte en hoogte van de `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_clone/#ishape) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormenverzameling.<br/>            De gekloonde vorm behoudt de positie en grootte van het origineel. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Maakt een kopie van de opgegeven vorm en voegt deze in de vormenverzameling in op de opgegeven index. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Maakt een kopie van de opgegeven vorm en voegt deze in de vormenverzameling in op de opgegeven index.<br/>            De nieuwe vorm behoudt de breedte en hoogte van de `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Maakt een kopie van de opgegeven vorm en voegt deze in de vormenverzameling in op de opgegeven index.<br/>            De gekloonde vorm behoudt de positie en grootte van het origineel. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Maakt een SmartArt-diagram en voegt dit toe aan het einde van de vormenverzameling. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Maakt een nieuw Samenvatting Zoom-frame en voegt het toe aan het einde van de vormenverzameling. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Maakt een nieuw Samenvatting Zoom-frame en voegt het in de vormenverzameling in op de opgegeven index. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Maakt een nieuw video-frame en voegt het in de vormenverzameling in op de opgegeven index. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het toe aan het einde van de vormenverzameling. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het in de vormenverzameling in<br/>            op de opgegeven index. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Maakt een nieuw audio-frame gekoppeld aan een extern audio-bestand en voegt het toe aan het einde van<br/>            de vormenverzameling. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Maakt een nieuw audio-frame gekoppeld aan een extern audio-bestand en voegt het in de vormenverzameling in<br/>            op de opgegeven index. |
| [`index_of(self, shape)`](/slides/python-net/nl/aspose.slides/ishapecollection/index_of/#ishape) | Retourneert de nul-gebaseerde index van de eerste voorkoming van de opgegeven vorm in de verzameling. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Maakt een nieuwe rechthoekige auto-vorm om wiskundige inhoud te bevatten en voegt deze toe aan het<br/>            einde van de vormenverzameling. |
| [`insert_group_shape(self, index)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_group_shape/#int) | Maakt een nieuw leeg groepsvorm en voegt deze in de vormenverzameling in op de opgegeven index.<br/>            Het frame van de groep past zich automatisch aan om alle toegevoegde vormen te bevatten. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Maakt een nieuw afbeeldingframe met de opgegeven afbeelding en voegt dit toe aan het einde van de<br/>            vormenverzameling. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Maakt een nieuw afbeeldingframe met de opgegeven afbeelding en voegt dit in de vormenverzameling in op de opgegeven index. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/nl/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Maakt een nieuwe tabel en voegt deze toe aan het einde van de vormenverzameling. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/nl/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Maakt een nieuwe tabel en voegt deze in de vormenverzameling in op de opgegeven index. |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides/ishapecollection/remove_at/#int) | Verwijdert de vorm op de opgegeven index uit de vormenverzameling. |
| [`remove(self, shape)`](/slides/python-net/nl/aspose.slides/ishapecollection/remove/#ishape) | Verwijdert de eerste voorkoming van de opgegeven vorm uit de vormenverzameling. |
| [`clear(self)`](/slides/python-net/nl/aspose.slides/ishapecollection/clear/#) | Verwijdert alle vormen uit de vormenverzameling. |

### Zie ook
* klasse [`IShape`](/slides/python-net/nl/aspose.slides/ishape)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)