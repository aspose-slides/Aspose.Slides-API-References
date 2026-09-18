---
title: ShapeCollection class
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/shapecollection/
---
## ShapeCollection osztály

A formák gyűjteményét képviseli.

A ShapeCollection típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`parent_group`](/slides/python-net/hu/aspose.slides/shapecollection/parent_group/) | A formák gyűjteményéhez tartozó szülőcsoport-alakzat objektumot adja vissza.<br/>            Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |

Az adott indexen lévő elemet adja vissza.            Csak olvasható [`IShape`](/slides/python-net/hu/aspose.slides/ishape).

## Indexer

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides/shapecollection/__getitem__/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/hu/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és hozzáadja<br/>            a formagyűjtemény végéhez. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/hu/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál, és hozzáadja<br/>            a formagyűjtemény végéhez. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál,<br/>            és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Új diagramot hoz létre, mintapéldány adatokat és beállításokat inicializál,<br/>            és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/hu/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | Új Zoom-keretet hoz létre, és a formagyűjtemény végéhez adja hozzá. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/hu/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Új Zoom-keretet hoz létre, és a formagyűjtemény végéhez adja hozzá. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Új Zoom-keretet hoz létre, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Új Zoom-keretet hoz létre előre definiált képpel, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/hu/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Új Section Zoom-keretet hoz létre, és a formagyűjtemény végéhez adja hozzá. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/hu/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Új Section Zoom-keretet hoz létre előre definiált képpel, és a formagyűjtemény végéhez adja hozzá. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Új Section Zoom-keretet hoz létre, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Új Section Zoom-keretet hoz létre előre definiált képpel, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/hu/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Új OLE-objektum-keretet hoz létre, és a formagyűjtemény végéhez adja hozzá. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/hu/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Új OLE-objektum-keretet hoz létre, és a formagyűjtemény végéhez adja hozzá. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Új OLE-objektum-keretet hoz létre, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Új OLE-objektum-keretet hoz létre, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/hu/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | Új videó-keretet hoz létre, és a formagyűjtemény végéhez adja hozzá. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/hu/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | Új videó-keretet hoz létre, és a formagyűjtemény végéhez adja hozzá. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/hu/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Új audio-keretet hoz létre beágyazott WAV fájllal, és a formagyűjtemény végéhez adja hozzá.<br/>            A beágyazott hang a Presentation.Audios gyűjteménybe kerül. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/hu/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Új audio-keretet hoz létre, és a Presentation.Audios listából egy meglévő audio-objektummal a formagyűjtemény végéhez adja hozzá. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Új audio-keretet hoz létre beágyazott WAV fájllal, és a megadott indexnél szúrja be a formagyűjteménybe.<br/>            A beágyazott hang a Presentation.Audios gyűjteménybe kerül. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Új audio-keretet hoz létre, és a Presentation.Audios listából egy meglévő audio-objektummal a megadott indexnél szúrja be a formagyűjteménybe. |
| [`to_array(self)`](/slides/python-net/hu/aspose.slides/shapecollection/to_array/#) | Létrehozza és visszaadja a formákat tartalmazó tömböt. |
| [`to_array(self, start_index, count)`](/slides/python-net/hu/aspose.slides/shapecollection/to_array/#int-int) | Létrehozza és visszaadja a megadott tartományban lévő formákat tartalmazó tömböt. |
| [`reorder(self, index, shape)`](/slides/python-net/hu/aspose.slides/shapecollection/reorder/#int-ishape) | Áthelyezi a megadott formát egy új pozícióba a formagyűjteményen belül. |
| [`reorder(self, index, shapes)`](/slides/python-net/hu/aspose.slides/shapecollection/reorder/#int-listishape) | Áthelyezi a megadott formákat a formagyűjteményben, és a megadott indexnél kezdi el elhelyezni őket. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/hu/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | Új automatikus alakzatot hoz létre alapértelmezett formázással, és a formagyűjtemény végéhez adja hozzá.<br/>            |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hu/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Új automatikus alakzatot hoz létre, és a formagyűjtemény végéhez adja hozzá, opcionálisan alapértelmezett sablonformázással inicializálva. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Új automatikus alakzatot hoz létre, és a megadott indexnél szúrja be a formagyűjteménybe, alapértelmezett sablonformázást alkalmazva. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Új automatikus alakzatot hoz létre, és a megadott indexnél szúrja be a formagyűjteménybe, opcionálisan alapértelmezett sablonstílussal inicializálva. |
| [`add_group_shape(self)`](/slides/python-net/hu/aspose.slides/shapecollection/add_group_shape/#) | Új, üres csoport-alakzatot hoz létre, és a formagyűjtemény végéhez adja hozzá.<br/>            A csoport kerete automatikusan nő, hogy befogadja a hozzáadott alakzatokat. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/hu/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | Új csoport-alakzatot hoz létre, átalakítja a megadott SVG-képet egyedi alakzatokká, és a formagyűjtemény végéhez adja hozzá. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/hu/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | Új kötőelemet hoz létre alapértelmezett sablonstílussal, és a formagyűjtemény végéhez adja hozzá. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hu/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | Új kötőelemet hoz létre, és a formagyűjtemény végéhez adja hozzá, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | Új kötőelemet hoz létre, és a megadott indexnél szúrja be a formagyűjteménybe, alapértelmezett sablonstílust alkalmazva. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Új kötőelemet hoz létre, és a megadott indexnél szúrja be a formagyűjteménybe, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/hu/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | Létrehozza a megadott alakzat másolatát, és a formagyűjtemény végéhez adja hozzá. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/hu/aspose.slides/shapecollection/add_clone/#ishape-float-float) | Létrehozza a megadott alakzat másolatát, és a formagyűjtemény végéhez adja hozzá.<br/>            Az új alakzat megtartja a `source_shape` szélességét és magasságát. |
| [`add_clone(self, source_shape)`](/slides/python-net/hu/aspose.slides/shapecollection/add_clone/#ishape) | Létrehozza a megadott alakzat másolatát, és a formagyűjtemény végéhez adja hozzá.<br/>            A klónozott alakzat megtartja az eredeti pozícióját és méretét. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | Létrehozza a megadott alakzat másolatát, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | Létrehozza a megadott alakzat másolatát, és a megadott indexnél szúrja be a formagyűjteménybe.<br/>            Az új alakzat megtartja a `source_shape` szélességét és magasságát. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_clone/#int-ishape) | Létrehozza a megadott alakzat másolatát, és a megadott indexnél szúrja be a formagyűjteménybe.<br/>            A klónozott alakzat megtartja az eredeti pozícióját és méretét. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/hu/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | SmartArt diagrammot hoz létre, és a formagyűjtemény végéhez adja hozzá. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/hu/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | Új Summary Zoom-keretet hoz létre, és a formagyűjtemény végéhez adja hozzá. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Új Summary Zoom-keretet hoz létre, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | Új videó-keretet hoz létre, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/hu/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | Új audio-keretet hoz létre CD-sávhoz csatolva, és a formagyűjtemény végéhez adja hozzá. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Új audio-keretet hoz létre CD-sávhoz csatolva, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/hu/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | Új audio-keretet hoz létre külső hangfájlhoz csatolva, és a formagyűjtemény végéhez adja hozzá. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Új audio-keretet hoz létre külső hangfájlhoz csatolva, és a megadott indexnél szúrja be a formagyűjteményt. |
| [`index_of(self, shape)`](/slides/python-net/hu/aspose.slides/shapecollection/index_of/#ishape) | Visszaadja a megadott alakzat első előfordulásának nulláról induló indexét a gyűjteményben. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/hu/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | Új rectangle auto shape-t hoz létre matematikai tartalomhoz, és a formagyűjtemény végéhez adja hozzá. |
| [`insert_group_shape(self, index)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_group_shape/#int) | Új üres csoport-alakzatot hoz létre, és a megadott indexnél szúrja be a formagyűjteménybe.<br/>            A csoport kerete automatikusan nő, hogy befogadja a hozzáadott alakzatokat. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/hu/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Új kép-keretet hoz létre a megadott képpel, és a formagyűjtemény végéhez adja hozzá. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Új kép-keretet hoz létre a megadott képpel, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/hu/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | Új táblázatot hoz létre, és a formagyűjtemény végéhez adja hozzá. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/hu/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | Új táblázatot hoz létre, és a megadott indexnél szúrja be a formagyűjteménybe. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/shapecollection/remove_at/#int) | Eltávolítja a megadott indexű alakzatot a formagyűjteményből. |
| [`remove(self, shape)`](/slides/python-net/hu/aspose.slides/shapecollection/remove/#ishape) | Eltávolítja a megadott alakzat első előfordulását a formagyűjteményből. |
| [`clear(self)`](/slides/python-net/hu/aspose.slides/shapecollection/clear/#) | Eltávolít minden alakzatot a formagyűjteményből. |

### Lásd még
* osztály [`IShape`](/slides/python-net/hu/aspose.slides/ishape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)