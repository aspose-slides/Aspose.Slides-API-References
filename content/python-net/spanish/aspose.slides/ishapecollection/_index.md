---
title: IShapeCollection class
second_title: Aspose.Slides para Python a través de .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/ishapecollection/
---
## IShapeCollection clase

Representa una colección de formas.

El tipo IShapeCollection expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`parent_group`](/slides/python-net/es/aspose.slides/ishapecollection/parent_group/) | Obtiene el objeto de forma de grupo padre para la colección de formas.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |

Obtiene el elemento en el índice especificado.
            Sólo lectura [`IShape`](/slides/python-net/es/aspose.slides/ishape).

## Indexador

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides/ishapecollection/__getitem__/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/es/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Crea un nuevo gráfico, lo inicializa con datos de serie de muestra y configuraciones, y lo agrega<br/>            al final de la colección de formas. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/es/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Crea un nuevo gráfico, lo inicializa con datos de serie de muestra y configuraciones, y lo agrega<br/>            al final de la colección de formas. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Crea un nuevo gráfico, lo inicializa con datos de serie de muestra y configuraciones,<br/>            y lo inserta en la colección de formas en el índice especificado. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Crea un nuevo gráfico, lo inicializa con datos de serie de muestra y configuraciones,<br/>            y lo inserta en la colección de formas en el índice especificado. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/es/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/es/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/es/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Crea un nuevo marco Zoom y lo agrega al final de la colección de formas. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/es/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Crea un nuevo marco Zoom y lo agrega al final de la colección de formas. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Crea un nuevo marco Zoom y lo inserta en la colección de formas en el índice especificado. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Crea un nuevo marco Zoom con una imagen predefinida y lo inserta en la colección de formas<br/>            en el índice especificado. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/es/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Crea un nuevo marco de Zoom de sección y lo agrega al final de la colección de formas. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/es/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Crea un nuevo marco de Zoom de sección con una imagen predefinida y lo agrega al final de la<br/>            colección de formas. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Crea un nuevo marco de Zoom de sección y lo inserta en la colección de formas en el<br/>            índice especificado. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Crea un nuevo marco de Zoom de sección con una imagen predefinida y lo inserta en la colección de formas<br/>            en el índice especificado. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/es/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Crea un nuevo marco de video y lo agrega al final de la colección de formas. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/es/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Crea un nuevo marco de video y lo agrega al final de la colección de formas. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/es/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Crea un nuevo marco de audio con un archivo WAV incrustado y lo agrega al final de la<br/>            colección de formas. El audio incrustado se agrega a la colección Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/es/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Crea un nuevo marco de audio y lo agrega al final de la colección de formas usando un<br/>            objeto de audio existente de la lista Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Crea un nuevo marco de audio con un archivo WAV incrustado y lo inserta en la colección de formas<br/>            en el índice especificado. El audio incrustado se agrega a la colección Presentation.Audios<br/>            . |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Crea un nuevo marco de audio y lo inserta en la colección de formas en el índice especificado<br/>            usando un objeto de audio existente de la lista Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/es/aspose.slides/ishapecollection/to_array/#) | Crea y devuelve una matriz que contiene todas las formas. |
| [`to_array(self, start_index, count)`](/slides/python-net/es/aspose.slides/ishapecollection/to_array/#int-int) | Crea y devuelve una matriz que contiene todas las formas en el rango especificado. |
| [`reorder(self, index, shape)`](/slides/python-net/es/aspose.slides/ishapecollection/reorder/#int-ishape) | Mueve la forma especificada a una nueva posición dentro de la colección de formas. |
| [`reorder(self, index, shapes)`](/slides/python-net/es/aspose.slides/ishapecollection/reorder/#int-listishape) | Mueve las formas especificadas dentro de la colección de formas, colocándolas a partir del índice indicado. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/es/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Crea una nueva forma automática con formato predeterminado y la agrega al final de la<br/>            colección de formas. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/es/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Crea una nueva forma automática y la agrega al final de la colección de formas, opcionalmente<br/>            inicializándola con el formato de plantilla predeterminado. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado,<br/>            aplicando el formato de plantilla predeterminado. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado,<br/>            opcionalmente inicializándola con el estilo de plantilla predeterminado. |
| [`add_group_shape(self)`](/slides/python-net/es/aspose.slides/ishapecollection/add_group_shape/#) | Crea una nueva forma de grupo vacía y la agrega al final de la colección de formas.<br/>            El marco del grupo se ajustará automáticamente para encajar cualquier forma añadida. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/es/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Crea una nueva forma de grupo, convierte la imagen SVG especificada en formas individuales,<br/>            y agrega el grupo resultante al final de la colección de formas. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/es/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Crea una nueva forma conector con estilo de plantilla predeterminado y la agrega al final del<br/>            colección de formas. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/es/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Crea una nueva forma conector y la agrega al final de la colección de formas,<br/>            opcionalmente aplicando el estilo de plantilla predeterminado. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Crea una nueva forma conector y la inserta en la colección de formas en el índice especificado,<br/>            aplicando el estilo de plantilla predeterminado. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Crea una nueva forma conector y la inserta en la colección de formas en el índice especificado,<br/>            opcionalmente aplicando el estilo de plantilla predeterminado. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/es/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Crea una copia de la forma especificada y la agrega al final de la colección de formas. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/es/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Crea una copia de la forma especificada y la agrega al final de la colección de formas.<br/>            La nueva forma conserva el ancho y la altura del `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/es/aspose.slides/ishapecollection/add_clone/#ishape) | Crea una copia de la forma especificada y la agrega al final de la colección de formas.<br/>            La forma clonada conserva la posición y el tamaño del original. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado.<br/>            La nueva forma conserva el ancho y la altura del `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado.<br/>            La forma clonada conserva la posición y el tamaño del original. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/es/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Crea un diagrama SmartArt y lo agrega al final de la colección de formas. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/es/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Crea un nuevo marco Summary Zoom y lo agrega al final de la colección de formas. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Crea un nuevo marco Summary Zoom y lo inserta en la colección de formas en el índice especificado. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Crea un nuevo marco de video y lo inserta en la colección de formas en el índice especificado. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/es/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | Crea un nuevo marco de audio vinculado a una pista de CD y lo agrega al final de la colección de formas. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Crea un nuevo marco de audio vinculado a una pista de CD y lo inserta en la colección de formas<br/>            en el índice especificado. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/es/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo agrega al final de la<br/>            colección de formas. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo inserta en la colección de formas<br/>            en el índice especificado. |
| [`index_of(self, shape)`](/slides/python-net/es/aspose.slides/ishapecollection/index_of/#ishape) | Devuelve el índice basado en cero de la primera aparición de la forma especificada en la colección. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/es/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Crea una nueva forma automática rectangular para alojar contenido matemático y la agrega al final de la<br/>            colección de formas. |
| [`insert_group_shape(self, index)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_group_shape/#int) | Crea una nueva forma de grupo vacía y la inserta en la colección de formas en el índice especificado.<br/>            El marco del grupo se ajustará automáticamente para encajar cualquier forma añadida. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/es/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Crea un nuevo marco de imagen que contiene la imagen especificada y lo agrega al final del<br/>            colección de formas. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Crea un nuevo marco de imagen que contiene la imagen especificada y lo inserta en la colección de formas<br/>            en el índice especificado. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/es/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Crea una nueva tabla y la agrega al final de la colección de formas. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/es/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Crea una nueva tabla y la inserta en la colección de formas en el índice especificado. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides/ishapecollection/remove_at/#int) | Elimina la forma en el índice especificado de la colección de formas. |
| [`remove(self, shape)`](/slides/python-net/es/aspose.slides/ishapecollection/remove/#ishape) | Elimina la primera aparición de la forma especificada de la colección de formas. |
| [`clear(self)`](/slides/python-net/es/aspose.slides/ishapecollection/clear/#) | Elimina todas las formas de la colección de formas. |

### Ver también
* clase [`IShape`](/slides/python-net/es/aspose.slides/ishape)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)