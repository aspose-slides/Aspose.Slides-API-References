---
title: IShapeCollection class
second_title: Aspose.Slides a Python számára .NET-en keresztüli API-referenciája
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/
---
## IShapeCollection osztály

A formák gyűjteményét képviseli.

Az IShapeCollection típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`parent_group`](/slides/python-net/hu/aspose.slides/ishapecollection/parent_group/) | A szülő csoport shape objektumot adja vissza a shape gyűjteményhez.<br/>Csak olvasható [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape). |

Megkapja a megadott indexű elemet.
Csak olvasható [`IShape`](/slides/python-net/hu/aspose.slides/ishape).

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides/ishapecollection/__getitem__/) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Új diagramot hoz létre, minta sorozat adatokat és beállításokat inicializál, és a shape gyűjtemény végéhez adja. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Új diagramot hoz létre, minta sorozat adatokat és beállításokat inicializál, és a shape gyűjtemény végéhez adja. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Új diagramot hoz létre, minta sorozat adatokat és beállításokat inicializál, és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Új diagramot hoz létre, minta sorozat adatokat és beállításokat inicializál, és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Új OLE objektumkeretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Új OLE objektumkeretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Új OLE objektumkeretet hoz létre, és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Új OLE objektumkeretet hoz létre, és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Új Zoom keretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Új Zoom keretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Új Zoom keretet hoz létre, és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Új Zoom keretet hoz létre előre definiált képpel, és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Új Szakasz Zoom keretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Új Szakasz Zoom keretet hoz létre előre definiált képpel, és a shape gyűjtemény végéhez adja. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Új Szakasz Zoom keretet hoz létre, és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Új Szakasz Zoom keretet hoz létre előre definiált képpel, és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Új video keretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Új video keretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Új audio keretet hoz létre beágyazott WAV fájllal, és a shape gyűjtemény végéhez adja. A beágyazott hangot a Presentation.Audios gyűjteményhez adja hozzá. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Új audio keretet hoz létre, és a Presentation.Audios listából egy meglévő hangobjektumot felhasználva a shape gyűjtemény végéhez adja. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Új audio keretet hoz létre beágyazott WAV fájllal, és a megadott indexnél szúrja be a shape gyűjteménybe. A beágyazott hangot a Presentation.Audios gyűjteményhez adja hozzá. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Új audio keretet hoz létre, és a Presentation.Audios listából egy meglévő hangobjektumot felhasználva a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`to_array(self)`](/slides/python-net/hu/aspose.slides/ishapecollection/to_array/#) | Létrehoz és visszaad egy tömböt, amely az összes shape-et tartalmazza. |
| [`to_array(self, start_index, count)`](/slides/python-net/hu/aspose.slides/ishapecollection/to_array/#int-int) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes shape-et tartalmazza. |
| [`reorder(self, index, shape)`](/slides/python-net/hu/aspose.slides/ishapecollection/reorder/#int-ishape) | Áthelyezi a megadott shape-et egy új pozícióba a shape gyűjteményen belül. |
| [`reorder(self, index, shapes)`](/slides/python-net/hu/aspose.slides/ishapecollection/reorder/#int-listishape) | Áthelyezi a megadott shape-eket a shape gyűjteményen belül, a megadott indexnél kezdve elhelyezve őket. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Új automatikus shape-et hoz létre alapértelmezett formázással, és a shape gyűjtemény végéhez adja. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Új automatikus shape-et hoz létre és a shape gyűjtemény végéhez adja, opcionálisan alapértelmezett sablonformázással inicializálva. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Új automatikus shape-et hoz létre, és a megadott indexnél szúrja be a shape gyűjteménybe, alapértelmezett sablonformázást alkalmazva. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Új automatikus shape-et hoz létre, és a megadott indexnél szúrja be a shape gyűjteménybe, opcionálisan alapértelmezett sablonstílussal inicializálva. |
| [`add_group_shape(self)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_group_shape/#) | Új üres csoport shape-et hoz létre és a shape gyűjtemény végéhez adja. A csoport kerete automatikusan igazodik a hozzáadott shape-ekhez. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Új csoport shape-et hoz létre, a megadott SVG képet egyedi shape-ekké konvertálja, és az eredményül kapott csoportot a shape gyűjtemény végéhez adja. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Új csatlakozó shape-et hoz létre alapértelmezett sablonstílussal, és a shape gyűjtemény végéhez adja. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Új csatlakozó shape-et hoz létre és a shape gyűjtemény végéhez adja, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Új csatlakozó shape-et hoz létre, és a megadott indexnél szúrja be a shape gyűjteménybe, alapértelmezett sablonstílust alkalmazva. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Új csatlakozó shape-et hoz létre, és a megadott indexnél szúrja be a shape gyűjteménybe, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Létrehoz egy másolatot a megadott shape-ről és a shape gyűjtemény végéhez adja. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Létrehoz egy másolatot a megadott shape-ről és a shape gyűjtemény végéhez adja. Az új shape megtartja a `source_shape` szélességét és magasságát. |
| [`add_clone(self, source_shape)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_clone/#ishape) | Létrehoz egy másolatot a megadott shape-ről és a shape gyűjtemény végéhez adja. A klónozott shape megtartja az eredeti pozícióját és méretét. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Létrehoz egy másolatot a megadott shape-ről és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Létrehoz egy másolatot a megadott shape-ről és a megadott indexnél szúrja be a shape gyűjteménybe. Az új shape megtartja a `source_shape` szélességét és magasságát. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Létrehoz egy másolatot a megadott shape-ről és a megadott indexnél szúrja be a shape gyűjteménybe. A klónozott shape megtartja az eredeti pozícióját és méretét. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | SmartArt diagramot hoz létre és a shape gyűjtemény végéhez adja. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Új Summary Zoom keretet hoz létre és a shape gyűjtemény végéhez adja. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Új Summary Zoom keretet hoz létre és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Új video keretet hoz létre és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | Új audio keretet hoz létre CD-sávhoz kapcsolva, és a shape gyűjtemény végéhez adja. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Új audio keretet hoz létre CD-sávhoz kapcsolva, és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Új audio keretet hoz létre külső audio fájlhoz kapcsolva, és a shape gyűjtemény végéhez adja. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Új audio keretet hoz létre külső audio fájlhoz kapcsolva, és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`index_of(self, shape)`](/slides/python-net/hu/aspose.slides/ishapecollection/index_of/#ishape) | Visszaadja a megadott shape első előfordulásának nulla-alapú indexét a gyűjteményben. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Új négyszögletes automatikus shape-et hoz létre matematikai tartalom befogadásához, és a shape gyűjtemény végéhez adja. |
| [`insert_group_shape(self, index)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_group_shape/#int) | Új üres csoport shape-et hoz létre és a megadott indexnél szúrja be a shape gyűjteménybe. A csoport kerete automatikusan igazodik a hozzáadott shape-ekhez. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Új képkockát hoz létre a megadott képpel, és a shape gyűjtemény végéhez adja. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Új képkockát hoz létre a megadott képpel, és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/hu/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Új táblát hoz létre és a shape gyűjtemény végéhez adja. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/hu/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Új táblát hoz létre és a megadott indexnél szúrja be a shape gyűjteménybe. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/ishapecollection/remove_at/#int) | Eltávolítja a megadott indexű shape-et a shape gyűjteményből. |
| [`remove(self, shape)`](/slides/python-net/hu/aspose.slides/ishapecollection/remove/#ishape) | Eltávolítja a megadott shape első előfordulását a shape gyűjteményből. |
| [`clear(self)`](/slides/python-net/hu/aspose.slides/ishapecollection/clear/#) | Eltávolítja az összes shape-et a shape gyűjteményből. |

### Lásd még
* osztály [`IShape`](/slides/python-net/hu/aspose.slides/ishape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)