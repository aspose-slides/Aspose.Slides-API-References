---
title: IShapeCollection class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/
---
## IShapeCollection klass

Representerar en samling av former.

IShapeCollection-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`parent_group`](/slides/python-net/sv/aspose.slides/ishapecollection/parent_group/) | Hämtar föräldergruppens formobjekt för formsamlingen.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |

Hämtar elementet på det angivna indexet.<br/>            Skrivskyddad [`IShape`](/slides/python-net/sv/aspose.slides/ishape).

## Index

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides/ishapecollection/__getitem__/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Skapar ett nytt diagram, initierar det med exempelserie-data och inställningar, och lägger till<br/>            det i slutet av formsamlingen. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Skapar ett nytt diagram, initierar det med exempelserie-data och inställningar, och lägger till<br/>            det i slutet av formsamlingen. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Skapar ett nytt diagram, initierar det med exempelserie-data och inställningar,<br/>            och sätter in det i formsamlingen på angivet index. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Skapar ett nytt diagram, initierar det med exempelserie-data och inställningar,<br/>            och sätter in det i formsamlingen på angivet index. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Skapar ett nytt OLE-objektram och lägger till det i slutet av formsamlingen. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Skapar ett nytt OLE-objektram och lägger till det i slutet av formsamlingen. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Skapar ett nytt OLE-objektram och sätter in det i formsamlingen på angivet index. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Skapar ett nytt OLE-objektram och sätter in det i formsamlingen på angivet index. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Skapar ett nytt Zoom-ram och lägger till det i slutet av formsamlingen. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Skapar ett nytt Zoom-ram och lägger till det i slutet av formsamlingen. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Skapar ett nytt Zoom-ram och sätter in det i formsamlingen på angivet index. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Skapar ett nytt Zoom-ram med en fördefinierad bild och sätter in det i formsamlingen<br/>            på angivet index. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Skapar ett nytt sektion Zoom-ram och lägger till det i slutet av formsamlingen. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Skapar ett nytt sektion Zoom-ram med en fördefinierad bild och lägger till det i slutet av<br/>            formsamlingen. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Skapar ett nytt sektion Zoom-ram och sätter in det i formsamlingen på det<br/>            angivna indexet. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Skapar ett nytt sektion Zoom-ram med en fördefinierad bild och sätter in det i formsamlingen<br/>            på det angivna indexet. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Skapar ett nytt videoram och lägger till det i slutet av formsamlingen. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Skapar ett nytt videoram och lägger till det i slutet av formsamlingen. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Skapar ett nytt ljudram med en inbäddad WAV-fil och lägger till det i slutet av<br/>            formsamlingen. Det inbäddade ljudet läggs till i Presentation.Audios-samlingen. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Skapar ett nytt ljudram och lägger till det i slutet av formsamlingen med ett<br/>            befintligt ljudobjekt från Presentation.Audios-listan. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Skapar ett nytt ljudram med en inbäddad WAV-fil och sätter in det i formsamlingen<br/>            på det angivna indexet. Det inbäddade ljudet läggs till i Presentation.Audios<br/>            samlingen. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Skapar ett nytt ljudram och sätter in det i formsamlingen på det angivna indexet<br/>            med ett befintligt ljudobjekt från Presentation.Audios-listan. |
| [`to_array(self)`](/slides/python-net/sv/aspose.slides/ishapecollection/to_array/#) | Skapar och returnerar en array som innehåller alla former. |
| [`to_array(self, start_index, count)`](/slides/python-net/sv/aspose.slides/ishapecollection/to_array/#int-int) | Skapar och returnerar en array som innehåller alla former i det angivna intervallet. |
| [`reorder(self, index, shape)`](/slides/python-net/sv/aspose.slides/ishapecollection/reorder/#int-ishape) | Flyttar den angivna formen till en ny position inom formsamlingen. |
| [`reorder(self, index, shapes)`](/slides/python-net/sv/aspose.slides/ishapecollection/reorder/#int-listishape) | Flyttar de angivna formerna inom formsamlingen, och placerar dem med start vid det angivna indexet. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Skapar en ny autoform med standardformatering och lägger till den i slutet av<br/>            formsamlingen. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Skapar en ny autoform och lägger till den i slutet av formsamlingen, eventuellt<br/>            med standardmallens formatering. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Skapar en ny autoform och sätter in den i formsamlingen på det angivna indexet,<br/>            med standardmallens formatering. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Skapar en ny autoform och sätter in den i formsamlingen på det angivna indexet,<br/>            eventuellt med standardmallens styling. |
| [`add_group_shape(self)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_group_shape/#) | Skapar en ny tom gruppform och lägger till den i slutet av formsamlingen.<br/>            Gruppens ram justeras automatiskt för att passa alla former som läggs till. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Skapar en ny gruppform, konverterar den angivna SVG-bilden till individuella former,<br/>            och lägger till den resulterande gruppen i slutet av formsamlingen. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Skapar en ny anslutningsform med standardmallens styling och lägger till den i slutet av<br/>            formsamlingen. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Skapar en ny anslutningsform och lägger till den i slutet av formsamlingen,<br/>            eventuellt med standardmallens styling. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Skapar en ny anslutningsform och sätter in den i formsamlingen på det angivna indexet,<br/>            med standardmallens styling. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Skapar en ny anslutningsform och sätter in den i formsamlingen på det angivna indexet,<br/>            eventuellt med standardmallens styling. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.<br/>            Den nya formen behåller bredd och höjd från `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_clone/#ishape) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.<br/>            Den klonade formen behåller originalets position och storlek. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Skapar en kopia av den angivna formen och sätter in den i formsamlingen på det angivna indexet. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Skapar en kopia av den angivna formen och sätter in den i formsamlingen på det angivna indexet.<br/>            Den nya formen behåller bredd och höjd från `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Skapar en kopia av den angivna formen och sätter in den i formsamlingen på det angivna indexet.<br/>            Den klonade formen behåller originalets position och storlek. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Skapar ett SmartArt-diagram och lägger till det i slutet av formsamlingen. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Skapar ett nytt sammanfattnings-Zoom-ram och lägger till det i slutet av formsamlingen. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Skapar ett nytt sammanfattnings-Zoom-ram och sätter in det i formsamlingen på det angivna indexet. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Skapar ett nytt videoram och sätter in det i formsamlingen på det angivna indexet. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | Skapar ett nytt ljudram kopplat till ett CD-spår och lägger till det i slutet av formsamlingen. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Skapar ett nytt ljudram kopplat till ett CD-spår och sätter in det i formsamlingen<br/>            på det angivna indexet. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Skapar ett nytt ljudram kopplat till en extern ljudfil och lägger till det i slutet av<br/>            formsamlingen. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Skapar ett nytt ljudram kopplat till en extern ljudfil och sätter in det i formsamlingen<br/>            på det angivna indexet. |
| [`index_of(self, shape)`](/slides/python-net/sv/aspose.slides/ishapecollection/index_of/#ishape) | Returnerar det nollbaserade indexet för den första förekomsten av den angivna formen i samlingen. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Skapar en ny rektangel-autoform för att hysa matematiskt innehåll och lägger till den i<br/>            slutet av formsamlingen. |
| [`insert_group_shape(self, index)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_group_shape/#int) | Skapar en ny tom gruppform och sätter in den i formsamlingen på det angivna indexet.<br/>            Gruppens ram justeras automatiskt för att passa alla former som läggs till. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Skapar ett nytt bildram som innehåller den angivna bilden och lägger till den i slutet av<br/>            formsamlingen. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Skapar ett nytt bildram som innehåller den angivna bilden och sätter in den i formsamlingen<br/>            på det angivna indexet. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/sv/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Skapar en ny tabell och lägger till den i slutet av formsamlingen. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/sv/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Skapar en ny tabell och sätter in den i formsamlingen på det angivna indexet. |
| [`remove_at(self, index)`](/slides/python-net/sv/aspose.slides/ishapecollection/remove_at/#int) | Tar bort formen på det angivna indexet från formsamlingen. |
| [`remove(self, shape)`](/slides/python-net/sv/aspose.slides/ishapecollection/remove/#ishape) | Tar bort den första förekomsten av den angivna formen från formsamlingen. |
| [`clear(self)`](/slides/python-net/sv/aspose.slides/ishapecollection/clear/#) | Tar bort alla former från formsamlingen. |

### Se även
* klass [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)