---
title: ShapeCollection class
second_title: Referencia API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/shapecollection/
---
## ShapeCollection clase

Representa una colección de formas.

El tipo ShapeCollection expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`parent_group`](/slides/python-net/es/aspose.slides/shapecollection/parent_group/) | Obtiene el objeto de forma de grupo padre para la colección de formas.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
|  | Obtiene el elemento en el índice especificado.<br/>            Solo lectura [`IShape`](/slides/python-net/es/aspose.slides/ishape). |

## Indexador

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides/shapecollection/__getitem__/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/es/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Crea un nuevo chart, lo inicializa con datos y configuraciones de serie de muestra y lo agrega<br/>            al final de la colección de formas. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/es/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Crea un nuevo chart, lo inicializa con datos y configuraciones de serie de muestra y lo agrega<br/>            al final de la colección de formas. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/es/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Crea un nuevo chart, lo inicializa con datos y configuraciones de serie de muestra,<br/>            y lo inserta en la colección de formas en el índice especificado. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/es/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Crea un nuevo chart, lo inicializa con datos y configuraciones de serie de muestra,<br/>            y lo inserta en la colección de formas en el índice especificado. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/es/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | Crea un nuevo Zoom frame y lo agrega al final de la colección de formas. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/es/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Crea un nuevo Zoom frame y lo agrega al final de la colección de formas. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/es/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Crea un nuevo Zoom frame y lo inserta en la colección de formas en el índice especificado. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/es/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Crea un nuevo Zoom frame con una imagen predefinida y lo inserta en la colección de formas<br/>            en el índice especificado. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/es/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Crea un nuevo Section Zoom frame y lo agrega al final de la colección de formas. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/es/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Crea un nuevo Section Zoom frame con una imagen predefinida y lo agrega al final de la colección de formas. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/es/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Crea un nuevo Section Zoom frame y lo inserta en la colección de formas en el índice especificado. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/es/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Crea un nuevo Section Zoom frame con una imagen predefinida y lo inserta en la colección de formas<br/>            en el índice especificado. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/es/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Crea un nuevo OLE object frame y lo agrega al final de la colección de formas. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/es/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Crea un nuevo OLE object frame y lo agrega al final de la colección de formas. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/es/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Crea un nuevo OLE object frame y lo inserta en la colección de formas en el índice especificado. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/es/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Crea un nuevo OLE object frame y lo inserta en la colección de formas en el índice especificado. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/es/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | Crea un nuevo video frame y lo agrega al final de la colección de formas. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/es/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | Crea un nuevo video frame y lo agrega al final de la colección de formas. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/es/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Crea un nuevo audio frame con un archivo WAV incrustado y lo agrega al final de la<br/>            colección de formas. El audio incrustado se agrega a la colección Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/es/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Crea un nuevo audio frame y lo agrega al final de la colección de formas usando un<br/>            objeto de audio existente de la lista Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/es/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Crea un nuevo audio frame con un archivo WAV incrustado y lo inserta en la colección de<br/>            formas en el índice especificado. El audio incrustado se agrega a la colección Presentation.Audios<br/>            . |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/es/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Crea un nuevo audio frame y lo inserta en la colección de formas en el índice especificado<br/>            usando un objeto de audio existente de la lista Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/es/aspose.slides/shapecollection/to_array/#) | Crea y devuelve una matriz que contiene todas las formas. |
| [`to_array(self, start_index, count)`](/slides/python-net/es/aspose.slides/shapecollection/to_array/#int-int) | Crea y devuelve una matriz que contiene todas las formas en el rango especificado. |
| [`reorder(self, index, shape)`](/slides/python-net/es/aspose.slides/shapecollection/reorder/#int-ishape) | Mueve la forma especificada a una nueva posición dentro de la colección de formas. |
| [`reorder(self, index, shapes)`](/slides/python-net/es/aspose.slides/shapecollection/reorder/#int-listishape) | Mueve las formas especificadas dentro de la colección de formas, colocándolas empezando en el índice indicado. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/es/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | Crea un nuevo auto shape con formato predeterminado y lo agrega al final de la<br/>            colección de formas. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/es/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Crea un nuevo auto shape y lo agrega al final de la colección de formas, opcionalmente<br/>            inicializándolo con el formato de plantilla predeterminado. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/es/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Crea un nuevo auto shape y lo inserta en la colección de formas en el índice especificado,<br/>            aplicando el formato de plantilla predeterminado. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/es/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Crea un nuevo auto shape y lo inserta en la colección de formas en el índice especificado,<br/>            opcionalmente inicializándolo con el estilo de plantilla predeterminado. |
| [`add_group_shape(self)`](/slides/python-net/es/aspose.slides/shapecollection/add_group_shape/#) | Crea un nuevo grupo de formas vacío y lo agrega al final de la colección de formas.<br/>            El marco del grupo se ajustará automáticamente para acomodar cualquier forma añadida. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/es/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | Crea un nuevo grupo de formas, convierte la imagen SVG especificada en formas individuales,<br/>            y agrega el grupo resultante al final de la colección de formas. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/es/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | Crea un nuevo connector shape con estilo de plantilla predeterminado y lo agrega al final de la<br/>            colección de formas. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/es/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | Crea un nuevo connector shape y lo agrega al final de la colección de formas,<br/>            opcionalmente aplicando estilo de plantilla predeterminado. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/es/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | Crea un nuevo connector shape y lo inserta en la colección de formas en el índice especificado,<br/>            aplicando estilo de plantilla predeterminado. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/es/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Crea un nuevo connector shape y lo inserta en la colección de formas en el índice especificado,<br/>            opcionalmente aplicando estilo de plantilla predeterminado. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/es/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | Crea una copia de la forma especificada y la agrega al final de la colección de formas. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/es/aspose.slides/shapecollection/add_clone/#ishape-float-float) | Crea una copia de la forma especificada y la agrega al final de la colección de formas.<br/>            La nueva forma conserva el ancho y la altura del `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/es/aspose.slides/shapecollection/add_clone/#ishape) | Crea una copia de la forma especificada y la agrega al final de la colección de formas.<br/>            La forma clonada conserva la posición y el tamaño originales. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/es/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/es/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado.<br/>            La nueva forma conserva el ancho y la altura del `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/es/aspose.slides/shapecollection/insert_clone/#int-ishape) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado.<br/>            La forma clonada conserva la posición y el tamaño originales. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/es/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Crea un diagrama SmartArt y lo agrega al final de la colección de formas. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/es/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | Crea un nuevo Summary Zoom frame y lo agrega al final de la colección de formas. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/es/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Crea un nuevo Summary Zoom frame y lo inserta en la colección de formas en el índice especificado. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/es/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | Crea un nuevo video frame y lo inserta en la colección de formas en el índice especificado. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/es/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | Crea un nuevo audio frame vinculado a una pista de CD y lo agrega al final de la colección de formas. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/es/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Crea un nuevo audio frame vinculado a una pista de CD y lo inserta en la colección de formas<br/>            en el índice especificado. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/es/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | Crea un nuevo audio frame vinculado a un archivo de audio externo y lo agrega al final de<br/>            la colección de formas. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/es/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Crea un nuevo audio frame vinculado a un archivo de audio externo y lo inserta en la colección de<br/>            formas en el índice especificado. |
| [`index_of(self, shape)`](/slides/python-net/es/aspose.slides/shapecollection/index_of/#ishape) | Devuelve el índice basado en cero de la primera aparición de la forma especificada en la colección. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/es/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | Crea un nuevo auto shape rectangular para alojar contenido matemático y lo agrega al<br/>            final de la colección de formas. |
| [`insert_group_shape(self, index)`](/slides/python-net/es/aspose.slides/shapecollection/insert_group_shape/#int) | Crea un nuevo grupo de formas vacío y lo inserta en la colección de formas en el índice especificado.<br/>            El marco del grupo se ajustará automáticamente para acomodar cualquier forma añadida. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/es/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Crea un nuevo picture frame que contiene la imagen especificada y lo agrega al final de la<br/>            colección de formas. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/es/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Crea un nuevo picture frame que contiene la imagen especificada y lo inserta en la colección de<br/>            formas en el índice especificado. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/es/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | Crea una nueva tabla y la agrega al final de la colección de formas. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/es/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | Crea una nueva tabla y la inserta en la colección de formas en el índice especificado. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides/shapecollection/remove_at/#int) | Elimina la forma en el índice especificado de la colección de formas. |
| [`remove(self, shape)`](/slides/python-net/es/aspose.slides/shapecollection/remove/#ishape) | Elimina la primera aparición de la forma especificada de la colección de formas. |
| [`clear(self)`](/slides/python-net/es/aspose.slides/shapecollection/clear/#) | Elimina todas las formas de la colección de formas. |

### Ver también
* clase [`IShape`](/slides/python-net/es/aspose.slides/ishape)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)