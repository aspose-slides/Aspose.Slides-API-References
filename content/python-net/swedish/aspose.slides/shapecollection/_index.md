---
title: ShapeCollection class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/
---
## ShapeCollection klass

Representerar en samling av former.

Typen ShapeCollection exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`parent_group`](/slides/python-net/sv/aspose.slides/shapecollection/parent_group/) | Hämtar den överordnade gruppformen för samlingen av former.<br/>            Read-only [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |

Hämtar elementet på det angivna indexet.
            Read-only [`IShape`](/slides/python-net/sv/aspose.slides/ishape).

## Indexering

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides/shapecollection/__getitem__/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/sv/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Skapar ett nytt diagram, initierar det med exempeldata och inställningar, och lägger till<br/>            det i slutet av shape collection. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/sv/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Skapar ett nytt diagram, initierar det med exempeldata och inställningar, och lägger till<br/>            det i slutet av shape collection. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Skapar ett nytt diagram, initierar det med exempeldata och inställningar,<br/>            och infogar det i shape collection på det angivna indexet. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Skapar ett nytt diagram, initierar det med exempeldata och inställningar,<br/>            och infogar det i shape collection på det angivna indexet. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/sv/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | Skapar en ny Zoom-ram och lägger till den i slutet av shape collection. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/sv/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Skapar en ny Zoom-ram och lägger till den i slutet av shape collection. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Skapar en ny Zoom-ram och infogar den i shape collection på det angivna indexet. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Skapar en ny Zoom-ram med en fördefinierad bild och infogar den i shape collection<br/>            på det angivna indexet. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/sv/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Skapar en ny Section-Zoom-ram och lägger till den i slutet av shape collection. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/sv/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Skapar en ny Section-Zoom-ram med en fördefinierad bild och lägger till den i slutet av shape collection. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Skapar en ny Section-Zoom-ram och infogar den i shape collection på det angivna indexet. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Skapar en ny Section-Zoom-ram med en fördefinierad bild och infogar den i shape<br/>            collection på det angivna indexet. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/sv/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Skapar ett nytt OLE-objekt-ram och lägger till det i slutet av shape collection. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/sv/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Skapar ett nytt OLE-objekt-ram och lägger till det i slutet av shape collection. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Skapar ett nytt OLE-objekt-ram och infogar det i shape collection på det angivna indexet. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Skapar ett nytt OLE-objekt-ram och infogar det i shape collection på det angivna indexet. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/sv/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | Skapar ett nytt video-ram och lägger till det i slutet av shape collection. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/sv/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | Skapar ett nytt video-ram och lägger till det i slutet av shape collection. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/sv/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Skapar ett nytt audio-ram med en inbäddad WAV-fil och lägger till det i slutet av<br/>            shape collection. Det inbäddade ljudet läggs till i Presentation.Audios-samlingen. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/sv/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Skapar ett nytt audio-ram och lägger till det i slutet av shape collection med en<br/>            befintlig audio-objekt från Presentation.Audios-listan. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Skapar ett nytt audio-ram med en inbäddad WAV-fil och infogar det i shape<br/>            collection på det angivna indexet. Det inbäddade ljudet läggs till i Presentation.Audios-<br/>            samlingen. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Skapar ett nytt audio-ram och infogar det i shape collection på det angivna indexet<br/>            med ett befintligt audio-objekt från Presentation.Audios-listan. |
| [`to_array(self)`](/slides/python-net/sv/aspose.slides/shapecollection/to_array/#) | Skapar och returnerar en array som innehåller alla former. |
| [`to_array(self, start_index, count)`](/slides/python-net/sv/aspose.slides/shapecollection/to_array/#int-int) | Skapar och returnerar en array som innehåller alla former i det angivna intervallet. |
| [`reorder(self, index, shape)`](/slides/python-net/sv/aspose.slides/shapecollection/reorder/#int-ishape) | Flyttar den angivna formen till en ny position inom shape collection. |
| [`reorder(self, index, shapes)`](/slides/python-net/sv/aspose.slides/shapecollection/reorder/#int-listishape) | Flyttar de angivna formerna inom shape collection och placerar dem med start på det givna indexet. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/sv/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | Skapar en ny automatisk form med standardformatering och lägger till den i slutet av<br/>            shape collection. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/sv/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Skapar en ny automatisk form och lägger till den i slutet av shape collection, eventuellt<br/>            initierad med standardmallens formatering. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Skapar en ny automatisk form och infogar den i shape collection på det angivna indexet,<br/>            med standardmallens formatering. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Skapar en ny automatisk form och infogar den i shape collection på det angivna indexet,<br/>            eventuellt initierad med standardmallens stil. |
| [`add_group_shape(self)`](/slides/python-net/sv/aspose.slides/shapecollection/add_group_shape/#) | Skapar en ny tom gruppform och lägger till den i slutet av shape collection.<br/>            Gruppens ram justeras automatiskt för att rymma alla former som läggs till. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/sv/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | Skapar en ny gruppform, konverterar den angivna SVG-bilden till enskilda former,<br/>            och lägger till den resulterande gruppen i slutet av shape collection. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/sv/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | Skapar en ny anslutningsform med standardmallens stil och lägger till den i slutet av<br/>            shape collection. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/sv/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | Skapar en ny anslutningsform och lägger till den i slutet av shape collection,<br/>            eventuellt med standardmallens stil. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | Skapar en ny anslutningsform och infogar den i shape collection på det angivna indexet,<br/>            med standardmallens stil. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Skapar en ny anslutningsform och infogar den i shape collection på det angivna indexet,<br/>            eventuellt med standardmallens stil. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/sv/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | Skapar en kopia av den angivna formen och lägger till den i slutet av shape collection. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/sv/aspose.slides/shapecollection/add_clone/#ishape-float-float) | Skapar en kopia av den angivna formen och lägger till den i slutet av shape collection.<br/>            Den nya formen behåller `source_shape`s bredd och höjd. |
| [`add_clone(self, source_shape)`](/slides/python-net/sv/aspose.slides/shapecollection/add_clone/#ishape) | Skapar en kopia av den angivna formen och lägger till den i slutet av shape collection.<br/>            Den klonade formen behåller originalets position och storlek. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | Skapar en kopia av den angivna formen och infogar den i shape collection på det angivna indexet. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | Skapar en kopia av den angivna formen och infogar den i shape collection på det angivna indexet.<br/>            Den nya formen behåller `source_shape`s bredd och höjd. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_clone/#int-ishape) | Skapar en kopia av den angivna formen och infogar den i shape collection på det angivna indexet.<br/>            Den klonade formen behåller originalets position och storlek. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/sv/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Skapar ett SmartArt-diagram och lägger till det i slutet av shape collection. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/sv/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | Skapar en ny Sammanfattnings-Zoom-ram och lägger till den i slutet av shape collection. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Skapar en ny Sammanfattnings-Zoom-ram och infogar den i shape collection på det angivna indexet. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | Skapar ett nytt video-ram och infogar det i shape collection på det angivna indexet. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/sv/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | Skapar ett nytt audio-ram länkat till ett CD-spår och lägger till det i slutet av shape collection. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Skapar ett nytt audio-ram länkat till ett CD-spår och infogar det i shape collection<br/>            på det angivna indexet. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/sv/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | Skapar ett nytt audio-ram länkat till en extern ljudfil och lägger till det i slutet av<br/>            shape collection. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Skapar ett nytt audio-ram länkat till en extern ljudfil och infogar det i shape<br/>            collection på det angivna indexet. |
| [`index_of(self, shape)`](/slides/python-net/sv/aspose.slides/shapecollection/index_of/#ishape) | Returnerar det nollbaserade indexet för den första förekomsten av den angivna formen i samlingen. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/sv/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | Skapar en ny rektangulär auto-form för att hysa matematikinnehåll och lägger till den i<br/>            slutet av shape collection. |
| [`insert_group_shape(self, index)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_group_shape/#int) | Skapar en ny tom gruppform och infogar den i shape collection på det angivna indexet.<br/>            Gruppens ram justeras automatiskt för att rymma alla former som läggs till. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/sv/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Skapar en ny bild-ram som innehåller den angivna bilden och lägger till den i slutet av<br/>            shape collection. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Skapar en ny bild-ram som innehåller den angivna bilden och infogar den i shape<br/>            collection på det angivna indexet. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/sv/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | Skapar en ny tabell och lägger till den i slutet av shape collection. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/sv/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | Skapar en ny tabell och infogar den i shape collection på det angivna indexet. |
| [`remove_at(self, index)`](/slides/python-net/sv/aspose.slides/shapecollection/remove_at/#int) | Tar bort formen på det angivna indexet från shape collection. |
| [`remove(self, shape)`](/slides/python-net/sv/aspose.slides/shapecollection/remove/#ishape) | Tar bort den första förekomsten av den angivna formen från shape collection. |
| [`clear(self)`](/slides/python-net/sv/aspose.slides/shapecollection/clear/#) | Tar bort alla former från shape collection. |


### Se även
* klass [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)