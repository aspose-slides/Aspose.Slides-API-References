---
title: IShapeCollection class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/
---
## IShapeCollection třída

Represents a collection of shapes.

The IShapeCollection type exposes the following members:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`parent_group`](/slides/python-net/cs/aspose.slides/ishapecollection/parent_group/) | Gets the parent group shape object for the shapes collection.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |

Získá prvek na určeném indexu.
            Pouze pro čtení [`IShape`](/slides/python-net/cs/aspose.slides/ishape).

## Indexer

| Název | Description |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides/ishapecollection/__getitem__/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Vytvoří nový graf, inicializuje jej pomocí ukázkových dat řad a nastavení a přidá jej na konec kolekce tvarů. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Vytvoří nový graf, inicializuje jej pomocí ukázkových dat řad a nastavení a přidá jej na konec kolekce tvarů. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Vytvoří nový graf, inicializuje jej pomocí ukázkových dat řad a nastavení a vloží jej do kolekce tvarů na zadaný index. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Vytvoří nový graf, inicializuje jej pomocí ukázkových dat řad a nastavení a vloží jej do kolekce tvarů na zadaný index. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Vytvoří nový OLE objektový rámec a přidá jej na konec kolekce tvarů. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Vytvoří nový OLE objektový rámec a přidá jej na konec kolekce tvarů. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Vytvoří nový OLE objektový rámec a vloží jej do kolekce tvarů na zadaný index. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Vytvoří nový OLE objektový rámec a vloží jej do kolekce tvarů na zadaný index. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Vytvoří nový Zoom rámec a přidá jej na konec kolekce tvarů. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Vytvoří nový Zoom rámec a přidá jej na konec kolekce tvarů. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Vytvoří nový Zoom rámec a vloží jej do kolekce tvarů na zadaný index. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Vytvoří nový Zoom rámec s předdefinovaným obrázkem a vloží jej do kolekce tvarů<br/>            na zadaný index. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Vytvoří nový Sekční Zoom rámec a přidá jej na konec kolekce tvarů. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Vytvoří nový Sekční Zoom rámec s předdefinovaným obrázkem a přidá jej na konec<br/>            kolekce tvarů. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Vytvoří nový Sekční Zoom rámec a vloží jej do kolekce tvarů na<br/>            zadaný index. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Vytvoří nový Sekční Zoom rámec s předdefinovaným obrázkem a vloží jej do kolekce<br/>            tvarů na zadaný index. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Vytvoří nový video rámec a přidá jej na konec kolekce tvarů. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Vytvoří nový video rámec a přidá jej na konec kolekce tvarů. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Vytvoří nový audio rámec s vloženým souborem WAV a přidá jej na konec<br/>            kolekce tvarů. Vložený zvuk je přidán do kolekce Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Vytvoří nový audio rámec a přidá jej na konec kolekce tvarů pomocí<br/>            existujícího audio objektu ze seznamu Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Vytvoří nový audio rámec s vloženým souborem WAV a vloží jej do kolekce tvarů<br/>            na zadaný index. Vložený zvuk je přidán do kolekce Presentation.Audios<br/>            kolekce. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Vytvoří nový audio rámec a vloží jej do kolekce tvarů na zadaný index<br/>            pomocí existujícího audio objektu ze seznamu Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/cs/aspose.slides/ishapecollection/to_array/#) | Vytvoří a vrátí pole obsahující všechny tvary. |
| [`to_array(self, start_index, count)`](/slides/python-net/cs/aspose.slides/ishapecollection/to_array/#int-int) | Vytvoří a vrátí pole obsahující všechny tvary ve specifikovaném rozsahu. |
| [`reorder(self, index, shape)`](/slides/python-net/cs/aspose.slides/ishapecollection/reorder/#int-ishape) | Přesune zadaný tvar na novou pozici v rámci kolekce tvarů. |
| [`reorder(self, index, shapes)`](/slides/python-net/cs/aspose.slides/ishapecollection/reorder/#int-listishape) | Přesune zadané tvary v rámci kolekce tvarů, umístí je počínaje daným indexem. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec<br/>            kolekce tvarů. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Vytvoří nový automatický tvar a přidá jej na konec kolekce tvarů, volitelně<br/>            jej inicializuje s výchozím formátováním šablony. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaný index,<br/>            použije výchozí formátování šablony. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaný index,<br/>            volitelně jej inicializuje s výchozím stylem šablony. |
| [`add_group_shape(self)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_group_shape/#) | Vytvoří nový prázdný skupinový tvar a přidá jej na konec kolekce tvarů.<br/>            Rámec skupiny se automaticky přizpůsobí tak, aby pojmul všechny přidané tvary. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Vytvoří nový skupinový tvar, převede zadaný SVG obrázek na jednotlivé tvary,<br/>            a přidá vzniklou skupinu na konec kolekce tvarů. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Vytvoří nový konektorový tvar s výchozím stylem šablony a přidá jej na konec<br/>            kolekce tvarů. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Vytvoří nový konektorový tvar a přidá jej na konec kolekce tvarů,<br/>            volitelně použije výchozí styl šablony. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Vytvoří nový konektorový tvar a vloží jej do kolekce tvarů na zadaný index,<br/>            použije výchozí styl šablony. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Vytvoří nový konektorový tvar a vloží jej do kolekce tvarů na zadaný index,<br/>            volitelně použije výchozí styl šablony. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů.<br/>            Nový tvar zachová šířku a výšku `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_clone/#ishape) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů.<br/>            Klonovaný tvar zachová původní pozici a velikost. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index.<br/>            Nový tvar zachová šířku a výšku `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index.<br/>            Klonovaný tvar zachová původní pozici a velikost. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Vytvoří diagram SmartArt a přidá jej na konec kolekce tvarů. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Vytvoří nový souhrnný Zoom rámec a přidá jej na konec kolekce tvarů. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Vytvoří nový souhrnný Zoom rámec a vloží jej do kolekce tvarů na zadaný index. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Vytvoří nový video rámec a vloží jej do kolekce tvarů na zadaný index. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | Vytvoří nový audio rámec propojený s CD stopou a přidá jej na konec kolekce tvarů. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Vytvoří nový audio rámec propojený s CD stopou a vloží jej do kolekce tvarů<br/>            na zadaný index. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Vytvoří nový audio rámec propojený s externím audio souborem a přidá jej na konec<br/>            kolekce tvarů. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Vytvoří nový audio rámec propojený s externím audio souborem a vloží jej do kolekce tvarů<br/>            na zadaný index. |
| [`index_of(self, shape)`](/slides/python-net/cs/aspose.slides/ishapecollection/index_of/#ishape) | Vrátí nulový index prvního výskytu zadaného tvaru v kolekci. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Vytvoří nový obdélníkový automatický tvar pro matematický obsah a přidá jej na<br/>            konec kolekce tvarů. |
| [`insert_group_shape(self, index)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_group_shape/#int) | Vytvoří nový prázdný skupinový tvar a vloží jej do kolekce tvarů na zadaný index.<br/>            Rámec skupiny se automaticky přizpůsobí tak, aby pojmul všechny přidané tvary. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Vytvoří nový rámeček s obrázkem obsahujícím zadaný obrázek a přidá jej na konec<br/>            kolekce tvarů. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Vytvoří nový rámeček s obrázkem obsahujícím zadaný obrázek a vloží jej do kolekce tvarů<br/>            na zadaný index. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/cs/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Vytvoří novou tabulku a přidá ji na konec kolekce tvarů. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/cs/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Vytvoří novou tabulku a vloží ji do kolekce tvarů na zadaný index. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides/ishapecollection/remove_at/#int) | Odstraní tvar na zadaném indexu z kolekce tvarů. |
| [`remove(self, shape)`](/slides/python-net/cs/aspose.slides/ishapecollection/remove/#ishape) | Odstraní první výskyt zadaného tvaru z kolekce tvarů. |
| [`clear(self)`](/slides/python-net/cs/aspose.slides/ishapecollection/clear/#) | Odstraní všechny tvary z kolekce tvarů. |


### Viz také
* třída [`IShape`](/slides/python-net/cs/aspose.slides/ishape)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)