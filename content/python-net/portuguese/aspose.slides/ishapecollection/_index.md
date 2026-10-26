---
title: IShapeCollection class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ishapecollection/
---
## IShapeCollection classe

Representa uma coleção de formas.

O tipo IShapeCollection expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`parent_group`](/slides/python-net/pt/aspose.slides/ishapecollection/parent_group/) | Obtém o objeto de forma de grupo pai para a coleção de formas.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |

Obtém o elemento no índice especificado.            Somente leitura [`IShape`](/slides/python-net/pt/aspose.slides/ishape).

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides/ishapecollection/__getitem__/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e adiciona<br/>            ao final da coleção de formas. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e adiciona<br/>            ao final da coleção de formas. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações,<br/>            e o insere na coleção de formas no índice especificado. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações,<br/>            e o insere na coleção de formas no índice especificado. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Cria um novo quadro de Zoom e o insere na coleção de formas no índice especificado. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Cria um novo quadro de Zoom com uma imagem predefinida e o insere na coleção de formas<br/>            no índice especificado. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Cria um novo quadro de Zoom de seção e o adiciona ao final da coleção de formas. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Cria um novo quadro de Zoom de seção com uma imagem predefinida e o adiciona ao final da<br/>            coleção de formas. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Cria um novo quadro de Zoom de seção e o insere na coleção de formas no<br/>            índice especificado. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Cria um novo quadro de Zoom de seção com uma imagem predefinida e o insere na coleção de formas<br/>            no índice especificado. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Cria um novo quadro de áudio com um arquivo WAV incorporado e o adiciona ao final da<br/>            coleção de formas. O áudio incorporado é adicionado à coleção Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Cria um novo quadro de áudio e o adiciona ao final da coleção de formas usando um<br/>            objeto de áudio existente da lista Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Cria um novo quadro de áudio com um arquivo WAV incorporado e o insere na coleção de formas<br/>            no índice especificado. O áudio incorporado é adicionado à coleção Presentation.Audios<br/>            . |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Cria um novo quadro de áudio e o insere na coleção de formas no índice especificado<br/>            usando um objeto de áudio existente da lista Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/pt/aspose.slides/ishapecollection/to_array/#) | Cria e devolve um array que contém todas as formas. |
| [`to_array(self, start_index, count)`](/slides/python-net/pt/aspose.slides/ishapecollection/to_array/#int-int) | Cria e devolve um array que contém todas as formas no intervalo especificado. |
| [`reorder(self, index, shape)`](/slides/python-net/pt/aspose.slides/ishapecollection/reorder/#int-ishape) | Move a forma especificada para uma nova posição dentro da coleção de formas. |
| [`reorder(self, index, shapes)`](/slides/python-net/pt/aspose.slides/ishapecollection/reorder/#int-listishape) | Move as formas especificadas dentro da coleção de formas, posicionando-as a partir do índice fornecido. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Cria uma nova forma automática com formatação padrão e a adiciona ao final da<br/>            coleção de formas. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Cria uma nova forma automática e a adiciona ao final da coleção de formas, opcionalmente<br/>            inicializando-a com formatação padrão de modelo. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Cria uma nova forma automática e a insere na coleção de formas no índice especificado,<br/>            aplicando formatação padrão de modelo. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Cria uma nova forma automática e a insere na coleção de formas no índice especificado,<br/>            opcionalmente inicializando-a com estilo padrão de modelo. |
| [`add_group_shape(self)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_group_shape/#) | Cria uma nova forma de grupo vazia e a adiciona ao final da coleção de formas.<br/>            O quadro do grupo ajustará automaticamente para acomodar quaisquer formas adicionadas a ele. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Cria uma nova forma de grupo, converte a imagem SVG especificada em formas individuais,<br/>            e adiciona o grupo resultante ao final da coleção de formas. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Cria uma nova forma de conector com estilo de modelo padrão e a adiciona ao final da<br/>            coleção de formas. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Cria uma nova forma de conector e a adiciona ao final da coleção de formas,<br/>            opcionalmente aplicando estilo padrão de modelo. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Cria uma nova forma de conector e a insere na coleção de formas no índice especificado,<br/>            aplicando estilo padrão de modelo. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Cria uma nova forma de conector e a insere na coleção de formas no índice especificado,<br/>            opcionalmente aplicando estilo padrão de modelo. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.<br/>            A nova forma mantém a largura e altura do `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_clone/#ishape) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.<br/>            A forma clonada mantém a posição e tamanho originais. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado.<br/>            A nova forma mantém a largura e altura do `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado.<br/>            A forma clonada mantém a posição e tamanho originais. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Cria um diagrama SmartArt e o adiciona ao final da coleção de formas. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Cria um novo quadro de Zoom de resumo e o adiciona ao final da coleção de formas. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Cria um novo quadro de Zoom de resumo e o insere na coleção de formas no índice especificado. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Cria um novo quadro de vídeo e o insere na coleção de formas no índice especificado. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | Cria um novo quadro de áudio vinculado a uma faixa de CD e o adiciona ao final da coleção de formas. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Cria um novo quadro de áudio vinculado a uma faixa de CD e o insere na coleção de formas<br/>            no índice especificado. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o adiciona ao final da<br/>            coleção de formas. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o insere na coleção de formas<br/>            no índice especificado. |
| [`index_of(self, shape)`](/slides/python-net/pt/aspose.slides/ishapecollection/index_of/#ishape) | Retorna o índice baseado em zero da primeira ocorrência da forma especificada na coleção. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Cria uma nova forma automática retangular para hospedar conteúdo matemático e a adiciona ao<br/>            final da coleção de formas. |
| [`insert_group_shape(self, index)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_group_shape/#int) | Cria uma nova forma de grupo vazia e a insere na coleção de formas no índice especificado.<br/>            O quadro do grupo ajustará automaticamente para acomodar quaisquer formas adicionadas a ele. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Cria um novo quadro de imagem contendo a imagem especificada e o adiciona ao final da<br/>            coleção de formas. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Cria um novo quadro de imagem contendo a imagem especificada e o insere na coleção de<br/>            formas no índice especificado. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/pt/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Cria uma nova tabela e a adiciona ao final da coleção de formas. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/pt/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Cria uma nova tabela e a insere na coleção de formas no índice especificado. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides/ishapecollection/remove_at/#int) | Remove a forma no índice especificado da coleção de formas. |
| [`remove(self, shape)`](/slides/python-net/pt/aspose.slides/ishapecollection/remove/#ishape) | Remove a primeira ocorrência da forma especificada da coleção de formas. |
| [`clear(self)`](/slides/python-net/pt/aspose.slides/ishapecollection/clear/#) | Remove todas as formas da coleção de formas. |


### Veja Também
* classe [`IShape`](/slides/python-net/pt/aspose.slides/ishape)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)