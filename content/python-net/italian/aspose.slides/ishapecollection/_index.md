---
title: IShapeCollection class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/
---
## IShapeCollection classe

Rappresenta una raccolta di forme.

Il tipo IShapeCollection espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`parent_group`](/slides/python-net/it/aspose.slides/ishapecollection/parent_group/) | Ottiene l'oggetto forma di gruppo principale per la collezione di forme.<br/>            Solo lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |

Ottiene l'elemento all'indice specificato.
            Solo lettura [`IShape`](/slides/python-net/it/aspose.slides/ishape).

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides/ishapecollection/__getitem__/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/it/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Crea un nuovo grafico, lo inizializza con dati di esempio della serie e impostazioni, e lo aggiunge alla fine della collezione di forme. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/it/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Crea un nuovo grafico, lo inizializza con dati di esempio della serie e impostazioni, e lo aggiunge alla fine della collezione di forme. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Crea un nuovo grafico, lo inizializza con dati di esempio della serie e impostazioni, e lo inserisce nella collezione di forme all'indice specificato. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Crea un nuovo grafico, lo inizializza con dati di esempio della serie e impostazioni, e lo inserisce nella collezione di forme all'indice specificato. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/it/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Crea un nuovo frame oggetto OLE e lo aggiunge alla fine della collezione di forme. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/it/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Crea un nuovo frame oggetto OLE e lo aggiunge alla fine della collezione di forme. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Crea un nuovo frame oggetto OLE e lo inserisce nella collezione di forme all'indice specificato. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Crea un nuovo frame oggetto OLE e lo inserisce nella collezione di forme all'indice specificato. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/it/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Crea un nuovo frame Zoom e lo aggiunge alla fine della collezione di forme. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/it/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Crea un nuovo frame Zoom e lo aggiunge alla fine della collezione di forme. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Crea un nuovo frame Zoom e lo inserisce nella collezione di forme all'indice specificato. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Crea un nuovo frame Zoom con un'immagine predefinita e lo inserisce nella collezione di forme all'indice specificato. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/it/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Crea un nuovo frame Section Zoom e lo aggiunge alla fine della collezione di forme. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/it/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Crea un nuovo frame Section Zoom con un'immagine predefinita e lo aggiunge alla fine della collezione di forme. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Crea un nuovo frame Section Zoom e lo inserisce nella collezione di forme all'indice specificato. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Crea un nuovo frame Section Zoom con un'immagine predefinita e lo inserisce nella collezione di forme all'indice specificato. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/it/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Crea un nuovo frame video e lo aggiunge alla fine della collezione di forme. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/it/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Crea un nuovo frame video e lo aggiunge alla fine della collezione di forme. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/it/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Crea un nuovo frame audio con un file WAV incorporato e lo aggiunge alla fine della collezione di forme. L'audio incorporato viene aggiunto alla collezione Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/it/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Crea un nuovo frame audio e lo aggiunge alla fine della collezione di forme utilizzando un oggetto audio esistente dalla lista Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Crea un nuovo frame audio con un file WAV incorporato e lo inserisce nella collezione di forme all'indice specificato. L'audio incorporato viene aggiunto alla collezione Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Crea un nuovo frame audio e lo inserisce nella collezione di forme all'indice specificato utilizzando un oggetto audio esistente dalla lista Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/it/aspose.slides/ishapecollection/to_array/#) | Crea e restituisce un array che contiene tutte le forme. |
| [`to_array(self, start_index, count)`](/slides/python-net/it/aspose.slides/ishapecollection/to_array/#int-int) | Crea e restituisce un array che contiene tutte le forme nell'intervallo specificato. |
| [`reorder(self, index, shape)`](/slides/python-net/it/aspose.slides/ishapecollection/reorder/#int-ishape) | Sposta la forma specificata in una nuova posizione all'interno della collezione di forme. |
| [`reorder(self, index, shapes)`](/slides/python-net/it/aspose.slides/ishapecollection/reorder/#int-listishape) | Sposta le forme specificate all'interno della collezione di forme, posizionandole a partire dall'indice fornito. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/it/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Crea una nuova forma automatica con formattazione predefinita e la aggiunge alla fine della collezione di forme. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/it/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Crea una nuova forma automatica e la aggiunge alla fine della collezione di forme, opzionalmente inizializzandola con la formattazione del modello predefinito. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, applicando la formattazione del modello predefinito. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, opzionalmente inizializzandola con lo stile del modello predefinito. |
| [`add_group_shape(self)`](/slides/python-net/it/aspose.slides/ishapecollection/add_group_shape/#) | Crea una nuova forma di gruppo vuota e la aggiunge alla fine della collezione di forme.<br/>            Il frame del gruppo si adatterà automaticamente per contenere tutte le forme aggiunte. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/it/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Crea una nuova forma di gruppo, converte l'immagine SVG specificata in forme individuali, e aggiunge il gruppo risultante alla fine della collezione di forme. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/it/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Crea una nuova forma connettore con lo stile del modello predefinito e la aggiunge alla fine della collezione di forme. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/it/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Crea una nuova forma connettore e la aggiunge alla fine della collezione di forme, opzionalmente applicando lo stile del modello predefinito. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Crea una nuova forma connettore e la inserisce nella collezione di forme all'indice specificato, applicando lo stile del modello predefinito. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Crea una nuova forma connettore e la inserisce nella collezione di forme all'indice specificato, opzionalmente applicando lo stile del modello predefinito. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/it/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/it/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme.<br/>            La nuova forma mantiene la larghezza e l'altezza di `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/it/aspose.slides/ishapecollection/add_clone/#ishape) | Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme.<br/>            La forma clonata mantiene la posizione e le dimensioni originali. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Crea una copia della forma specificata e la inserisce nella collezione di forme all'indice specificato. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Crea una copia della forma specificata e la inserisce nella collezione di forme all'indice specificato.<br/>            La nuova forma mantiene la larghezza e l'altezza di `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Crea una copia della forma specificata e la inserisce nella collezione di forme all'indice specificato.<br/>            La forma clonata mantiene la posizione e le dimensioni originali. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/it/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Crea un diagramma SmartArt e lo aggiunge alla fine della collezione di forme. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/it/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Crea un nuovo frame Summary Zoom e lo aggiunge alla fine della collezione di forme. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Crea un nuovo frame Summary Zoom e lo inserisce nella collezione di forme all'indice specificato. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Crea un nuovo frame video e lo inserisce nella collezione di forme all'indice specificato. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/it/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | Crea un nuovo frame audio collegato a una traccia CD e lo aggiunge alla fine della collezione di forme. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Crea un nuovo frame audio collegato a una traccia CD e lo inserisce nella collezione di forme all'indice specificato. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/it/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Crea un nuovo frame audio collegato a un file audio esterno e lo aggiunge alla fine della collezione di forme. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Crea un nuovo frame audio collegato a un file audio esterno e lo inserisce nella collezione di forme all'indice specificato. |
| [`index_of(self, shape)`](/slides/python-net/it/aspose.slides/ishapecollection/index_of/#ishape) | Restituisce l'indice base zero della prima occorrenza della forma specificata nella collezione. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/it/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Crea una nuova forma automatica rettangolare per contenere contenuti matematici e la aggiunge alla fine della collezione di forme. |
| [`insert_group_shape(self, index)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_group_shape/#int) | Crea una nuova forma di gruppo vuota e la inserisce nella collezione di forme all'indice specificato.<br/>            Il frame del gruppo si adatterà automaticamente per contenere tutte le forme aggiunte. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/it/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Crea un nuovo frame immagine contenente l'immagine specificata e lo aggiunge alla fine della collezione di forme. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Crea un nuovo frame immagine contenente l'immagine specificata e lo inserisce nella collezione di forme all'indice specificato. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/it/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Crea una nuova tabella e la aggiunge alla fine della collezione di forme. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/it/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Crea una nuova tabella e la inserisce nella collezione di forme all'indice specificato. |
| [`remove_at(self, index)`](/slides/python-net/it/aspose.slides/ishapecollection/remove_at/#int) | Rimuove la forma all'indice specificato dalla collezione di forme. |
| [`remove(self, shape)`](/slides/python-net/it/aspose.slides/ishapecollection/remove/#ishape) | Rimuove la prima occorrenza della forma specificata dalla collezione di forme. |
| [`clear(self)`](/slides/python-net/it/aspose.slides/ishapecollection/clear/#) | Rimuove tutte le forme dalla collezione di forme. |

### Vedi anche
* classe [`IShape`](/slides/python-net/it/aspose.slides/ishape)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)