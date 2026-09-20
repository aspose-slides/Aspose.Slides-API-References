---
title: ShapeCollection class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/shapecollection/
---
## ShapeCollection třída

Reprezentuje kolekci tvarů.

The ShapeCollection type exposes the following members:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`parent_group`](/slides/python-net/cs/aspose.slides/shapecollection/parent_group/) | Získá objekt nadřazeného skupinového tvaru pro kolekci tvarů.<br/>            Pouze pro čtení [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |

Získá prvek na zadaném indexu.
            Pouze pro čtení [`IShape`](/slides/python-net/cs/aspose.slides/ishape).

## Indexér

| Název | Popis |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides/shapecollection/__getitem__/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/cs/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními a přidá jej na konec kolekce tvarů. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/cs/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními a přidá jej na konec kolekce tvarů. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními,<br/>            a vloží jej do kolekce tvarů na zadaném indexu. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními,<br/>            a vloží jej do kolekce tvarů na zadaném indexu. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/cs/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | Vytvoří nový snímek Zoom a přidá jej na konec kolekce tvarů. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/cs/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Vytvoří nový snímek Zoom a přidá jej na konec kolekce tvarů. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Vytvoří nový snímek Zoom a vloží jej do kolekce tvarů na zadaném indexu. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Vytvoří nový snímek Zoom s předdefinovaným obrázkem a vloží jej do kolekce tvarů<br/>            na zadaném indexu. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/cs/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Vytvoří nový snímek Section Zoom a přidá jej na konec kolekce tvarů. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/cs/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Vytvoří nový snímek Section Zoom s předdefinovaným obrázkem a přidá jej na konec kolekce tvarů. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Vytvoří nový snímek Section Zoom a vloží jej do kolekce tvarů na zadaném indexu. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Vytvoří nový snímek Section Zoom s předdefinovaným obrázkem a vloží jej do<br/>            kolekce tvarů na zadaném indexu. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/cs/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Vytvoří nový OLE objektový snímek a přidá jej na konec kolekce tvarů. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/cs/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Vytvoří nový OLE objektový snímek a přidá jej na konec kolekce tvarů. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Vytvoří nový OLE objektový snímek a vloží jej do kolekce tvarů na zadaném indexu. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Vytvoří nový OLE objektový snímek a vloží jej do kolekce tvarů na zadaném indexu. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/cs/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | Vytvoří nový video snímek a přidá jej na konec kolekce tvarů. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/cs/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | Vytvoří nový video snímek a přidá jej na konec kolekce tvarů. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/cs/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Vytvoří nový audio snímek s vloženým souborem WAV a přidá jej na konec<br/>            kolekce tvarů. Vložený audio soubor je přidán do kolekce Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/cs/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Vytvoří nový audio snímek a přidá jej na konec kolekce tvarů pomocí<br/>            existujícího audio objektu ze seznamu Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Vytvoří nový audio snímek s vloženým souborem WAV a vloží jej do kolekce tvarů<br/>            na zadaném indexu. Vložený audio soubor je přidán do kolekce Presentation.Audios<br/>            . |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Vytvoří nový audio snímek a vloží jej do kolekce tvarů na zadaném indexu<br/>            pomocí existujícího audio objektu ze seznamu Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/cs/aspose.slides/shapecollection/to_array/#) | Vytvoří a vrátí pole, které obsahuje všechny tvary. |
| [`to_array(self, start_index, count)`](/slides/python-net/cs/aspose.slides/shapecollection/to_array/#int-int) | Vytvoří a vrátí pole, které obsahuje všechny tvary ve zadaném rozsahu. |
| [`reorder(self, index, shape)`](/slides/python-net/cs/aspose.slides/shapecollection/reorder/#int-ishape) | Přesune zadaný tvar na novou pozici v rámci kolekce tvarů. |
| [`reorder(self, index, shapes)`](/slides/python-net/cs/aspose.slides/shapecollection/reorder/#int-listishape) | Přesune zadané tvary v rámci kolekce tvarů, umístí je počínaje zadaným indexem. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/cs/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec<br/>            kolekce tvarů. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/cs/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Vytvoří nový automatický tvar a přidá jej na konec kolekce tvarů, volitelně<br/>            inicializuje jej výchozím formátováním šablony. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu,<br/>            použije výchozí formátování šablony. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaném indexu,<br/>            volitelně jej inicializuje výchozím styly šablony. |
| [`add_group_shape(self)`](/slides/python-net/cs/aspose.slides/shapecollection/add_group_shape/#) | Vytvoří nový prázdný skupinový tvar a přidá jej na konec kolekce tvarů.<br/>            Rám skupiny se automaticky přizpůsobí tak, aby pojmul všechny přidané tvary. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/cs/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | Vytvoří nový skupinový tvar, převede zadaný SVG obrázek na jednotlivé tvary,<br/>            a přidá vzniklou skupinu na konec kolekce tvarů. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/cs/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | Vytvoří nový propojující tvar s výchozím stylem šablony a přidá jej na konec<br/>            kolekce tvarů. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/cs/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | Vytvoří nový propojující tvar a přidá jej na konec kolekce tvarů,<br/>            volitelně použije výchozí styl šablony. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | Vytvoří nový propojující tvar a vloží jej do kolekce tvarů na zadaném indexu,<br/>            použije výchozí styl šablony. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Vytvoří nový propojující tvar a vloží jej do kolekce tvarů na zadaném indexu,<br/>            volitelně použije výchozí styl šablony. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/cs/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/cs/aspose.slides/shapecollection/add_clone/#ishape-float-float) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů.<br/>            Nový tvar zachovává šířku a výšku `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/cs/aspose.slides/shapecollection/add_clone/#ishape) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů.<br/>            Klonovaný tvar zachovává původní pozici a velikost. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu.<br/>            Nový tvar zachovává šířku a výšku `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_clone/#int-ishape) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaném indexu.<br/>            Klonovaný tvar zachovává původní pozici a velikost. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/cs/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Vytvoří diagram SmartArt a přidá jej na konec kolekce tvarů. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/cs/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | Vytvoří nový snímek Summary Zoom a přidá jej na konec kolekce tvarů. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Vytvoří nový snímek Summary Zoom a vloží jej do kolekce tvarů na zadaném indexu. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | Vytvoří nový video snímek a vloží jej do kolekce tvarů na zadaném indexu. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/cs/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | Vytvoří nový audio snímek propojený s CD stopou a přidá jej na konec kolekce tvarů. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Vytvoří nový audio snímek propojený s CD stopou a vloží jej do kolekce tvarů<br/>            na zadaném indexu. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/cs/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | Vytvoří nový audio snímek propojený s externím audio souborem a přidá jej na konec<br/>            kolekce tvarů. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Vytvoří nový audio snímek propojený s externím audio souborem a vloží jej do kolekce<br/>            tvarů na zadaném indexu. |
| [`index_of(self, shape)`](/slides/python-net/cs/aspose.slides/shapecollection/index_of/#ishape) | Vrátí nulový index prvního výskytu zadaného tvaru v kolekci. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/cs/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | Vytvoří nový obdélníkový automatický tvar pro matematický obsah a přidá jej do<br/>            konce kolekce tvarů. |
| [`insert_group_shape(self, index)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_group_shape/#int) | Vytvoří nový prázdný skupinový tvar a vloží jej do kolekce tvarů na zadaném indexu.<br/>            Rám skupiny se automaticky přizpůsobí tak, aby pojmul všechny přidané tvary. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/cs/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Vytvoří nový obrázkový snímek obsahující zadaný obrázek a přidá jej na konec<br/>            kolekce tvarů. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Vytvoří nový obrázkový snímek obsahující zadaný obrázek a vloží jej do kolekce<br/>            tvarů na zadaném indexu. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/cs/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | Vytvoří novou tabulku a přidá ji na konec kolekce tvarů. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/cs/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | Vytvoří novou tabulku a vloží ji do kolekce tvarů na zadaném indexu. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides/shapecollection/remove_at/#int) | Odstraní tvar na zadaném indexu z kolekce tvarů. |
| [`remove(self, shape)`](/slides/python-net/cs/aspose.slides/shapecollection/remove/#ishape) | Odstraní první výskyt zadaného tvaru z kolekce tvarů. |
| [`clear(self)`](/slides/python-net/cs/aspose.slides/shapecollection/clear/#) | Odstraní všechny tvary z kolekce tvarů. |

### Viz také
* třída [`IShape`](/slides/python-net/cs/aspose.slides/ishape)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)