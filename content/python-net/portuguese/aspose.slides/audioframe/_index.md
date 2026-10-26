---
title: AudioFrame class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/audioframe/
---
## AudioFrame classe

Representa um clipe de áudio em um slide.

**Herança:**[`AudioFrame`](/slides/python-net/pt/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/pt/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/pt/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/pt/aspose.slides/shape)

O tipo AudioFrame expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides/audioframe/is_text_holder/) | Determina se a shape é TextHolder_PPT.<br/>            Somente leitura **bool**. |
| [`placeholder`](/slides/python-net/pt/aspose.slides/audioframe/placeholder/) | Retorna o placeholder para uma shape. Retorna None se a shape não tem placeholder.<br/>            Somente leitura [`IPlaceholder`](/slides/python-net/pt/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pt/aspose.slides/audioframe/custom_data/) | Retorna os dados personalizados da shape.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pt/aspose.slides/audioframe/raw_frame/) | Retorna ou define as propriedades brutas do frame da shape.<br/>            Leitura/gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pt/aspose.slides/audioframe/frame/) | Retorna ou define as propriedades do frame da shape.<br/>            Leitura/gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pt/aspose.slides/audioframe/line_format/) | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma shape.<br/>            Nota: pode retornar None para certos tipos de shapes que não possuem propriedades de linha.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/audioframe/three_d_format/) | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3d para uma shape.<br/>            Nota: pode retornar None para certos tipos de shapes que não possuem propriedades 3d.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides/audioframe/effect_format/) | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma shape.<br/>            Nota: pode retornar None para certos tipos de shapes que não possuem propriedades de efeito.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides/audioframe/fill_format/) | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma shape.<br/>            Nota: pode retornar None para certos tipos de shapes que não possuem propriedades de preenchimento.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/audioframe/hyperlink_click/) | Retorna ou define o hyperlink definido para clique do mouse.<br/>            Leitura/gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/audioframe/hyperlink_mouse_over/) | Retorna ou define o hyperlink definido para mouse over.<br/>            Leitura/gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/audioframe/hyperlink_manager/) | Retorna o gerenciador de hyperlink.<br/>            Somente leitura [`IHyperlinkManager`](/slides/python-net/pt/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pt/aspose.slides/audioframe/hidden/) | Determina se a shape está oculta.<br/>            Leitura/gravação **bool**. |
| [`z_order_position`](/slides/python-net/pt/aspose.slides/audioframe/z_order_position/) | Retorna a posição de uma shape na ordem Z.<br/>            Shapes[0] retorna a shape no fundo da ordem Z,<br/>            e Shapes[Shapes.Count - 1] retorna a shape na frente da ordem Z.<br/>            Somente leitura **int**. |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides/audioframe/connection_site_count/) | Retorna o número de pontos de conexão na shape.<br/>            Somente leitura **int**. |
| [`rotation`](/slides/python-net/pt/aspose.slides/audioframe/rotation/) | Retorna ou define o número de graus que a shape especificada está rotacionada ao redor do eixo Z.<br/>            Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário.<br/>            Leitura/gravação **float**. |
| [`x`](/slides/python-net/pt/aspose.slides/audioframe/x/) | Obtém ou define a coordenada x do canto superior esquerdo da shape, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`y`](/slides/python-net/pt/aspose.slides/audioframe/y/) | Obtém ou define a coordenada y do canto superior esquerdo da shape, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`width`](/slides/python-net/pt/aspose.slides/audioframe/width/) | Obtém ou define a largura da shape, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`height`](/slides/python-net/pt/aspose.slides/audioframe/height/) | Obtém ou define a altura da shape, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides/audioframe/black_white_mode/) | A propriedade especifica como uma shape será renderizada no modo de exibição em preto e branco.<br/>            Leitura/gravação [`BlackWhiteMode`](/slides/python-net/pt/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pt/aspose.slides/audioframe/unique_id/) | Retorna um identificador interno, limitado à apresentação, destinado ao uso por add-ins ou outro código.<br/>            Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado<br/>            como uma chave única persistente.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.office_interop_shape_id`](/slides/python-net/pt/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides/audioframe/office_interop_shape_id/) | Retorna um identificador único limitado ao slide que permanece constante durante a vida da shape e<br/>            permite que o PowerPoint ou código interop referencie a shape de forma confiável a partir de qualquer lugar no documento.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.unique_id`](/slides/python-net/pt/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pt/aspose.slides/audioframe/alternative_text/) | Retorna ou define o texto alternativo associado a uma shape.<br/>            Leitura/gravação **str**. |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides/audioframe/alternative_text_title/) | Retorna ou define o título do texto alternativo associado a uma shape.<br/>            Leitura/gravação **str**. |
| [`name`](/slides/python-net/pt/aspose.slides/audioframe/name/) | Retorna ou define o nome de uma shape.<br/>            Deve não ser None. Use string vazia se necessário.<br/>            Leitura/gravação **str**. |
| [`is_decorative`](/slides/python-net/pt/aspose.slides/audioframe/is_decorative/) | Obtém ou define a opção 'Marcar como decorativo'<br/>            Leitura/gravação **bool**. |
| [`shape_lock`](/slides/python-net/pt/aspose.slides/audioframe/shape_lock/) | Retorna os bloqueios da shape.<br/>            Somente leitura [`IPictureFrameLock`](/slides/python-net/pt/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/pt/aspose.slides/audioframe/is_grouped/) | Determina se a shape está agrupada.<br/>            Somente leitura **bool**. |
| [`parent_group`](/slides/python-net/pt/aspose.slides/audioframe/parent_group/) | Retorna o objeto GroupShape pai se a shape estiver agrupada. Caso contrário, retorna None.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pt/aspose.slides/audioframe/slide/) | Retorna o slide pai de uma shape.<br/>            Somente leitura [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pt/aspose.slides/audioframe/presentation/) | Retorna a apresentação pai de um slide.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/pt/aspose.slides/audioframe/shape_style/) | Retorna o objeto de estilo da shape.<br/>            Somente leitura [`IShapeStyle`](/slides/python-net/pt/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/pt/aspose.slides/audioframe/shape_type/) | Retorna ou define o tipo AutoShape para um PictureFrame.<br/>            São permitidos todos os itens do conjunto [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype), <br/>            exceto todos os tipos de linhas:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Leitura/gravação [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/pt/aspose.slides/audioframe/adjustments/) | Retorna uma coleção dos valores de ajuste da shape.<br/>            Somente leitura [`IAdjustValueCollection`](/slides/python-net/pt/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/pt/aspose.slides/audioframe/picture_frame_lock/) | Retorna os bloqueios da shape.<br/>            Somente leitura [`IPictureFrameLock`](/slides/python-net/pt/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/pt/aspose.slides/audioframe/picture_format/) | Retorna o objeto PictureFillFormat para um picture frame.<br/>            Somente leitura [`IPictureFillFormat`](/slides/python-net/pt/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/pt/aspose.slides/audioframe/relative_scale_height/) | Retorna ou define a escala da altura (relativa ao tamanho original da imagem) do picture frame. Valor 1.0 corresponde a 100%.<br/>            Leitura/gravação **float**. |
| [`relative_scale_width`](/slides/python-net/pt/aspose.slides/audioframe/relative_scale_width/) | Retorna ou define a escala da largura (relativa ao tamanho original da imagem) do picture frame. Valor 1.0 corresponde a 100%.<br/>            Leitura/gravação **float**. |
| [`is_cameo`](/slides/python-net/pt/aspose.slides/audioframe/is_cameo/) | Determina se o PictureFrame é um objeto Cameo ou não.<br/>            Somente leitura **bool**. |
| [`audio_cd_start_track`](/slides/python-net/pt/aspose.slides/audioframe/audio_cd_start_track/) | Retorna ou define um índice de faixa inicial.<br/>            Leitura/gravação **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/pt/aspose.slides/audioframe/audio_cd_start_track_time/) | Retorna ou define um tempo de faixa inicial.<br/>            Leitura/gravação **int**. |
| [`audio_cd_end_track`](/slides/python-net/pt/aspose.slides/audioframe/audio_cd_end_track/) | Retorna ou define um índice de última faixa<br/>            Leitura/gravação **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/pt/aspose.slides/audioframe/audio_cd_end_track_time/) | Retorna ou define um tempo de última faixa.<br/>            Leitura/gravação **int**. |
| [`volume`](/slides/python-net/pt/aspose.slides/audioframe/volume/) | Retorna ou define o volume do áudio.<br/>            Leitura/gravação [`AudioVolumeMode`](/slides/python-net/pt/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/pt/aspose.slides/audioframe/play_mode/) | Retorna ou define o modo de reprodução do áudio.<br/>            Leitura/gravação [`AudioPlayModePreset`](/slides/python-net/pt/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/pt/aspose.slides/audioframe/hide_at_showing/) | Determina se um AudioFrame está oculto.<br/>            Leitura/gravação **bool**. |
| [`play_loop_mode`](/slides/python-net/pt/aspose.slides/audioframe/play_loop_mode/) | Determina se um áudio está em loop.<br/>            Leitura/gravação **bool**. |
| [`play_across_slides`](/slides/python-net/pt/aspose.slides/audioframe/play_across_slides/) | Determina se o áudio está tocando ao longo dos slides.<br/>             Leitura/gravação **bool**. |
| [`rewind_audio`](/slides/python-net/pt/aspose.slides/audioframe/rewind_audio/) | Determina se o áudio é automaticamente rebobinado ao início após a reprodução. <br/>             Leitura/gravação **bool**. |
| [`embedded`](/slides/python-net/pt/aspose.slides/audioframe/embedded/) | Determina se um som está incorporado a uma apresentação.<br/>            Somente leitura **bool**. |
| [`link_path_long`](/slides/python-net/pt/aspose.slides/audioframe/link_path_long/) | Retorna ou define o nome de um arquivo de áudio que está vinculado a um AudioFrame.<br/>            Leitura/gravação **str**. |
| [`embedded_audio`](/slides/python-net/pt/aspose.slides/audioframe/embedded_audio/) | Retorna ou define o objeto de áudio incorporado.<br/>            Leitura/gravação [`IAudio`](/slides/python-net/pt/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/pt/aspose.slides/audioframe/fade_in_duration/) | Especifica a duração em milissegundos para o fade-in inicial da mídia.<br/>             Leitura/gravação **float**. |
| [`fade_out_duration`](/slides/python-net/pt/aspose.slides/audioframe/fade_out_duration/) | Especifica a duração em milissegundos para o fade-out final da mídia.<br/>             Leitura/gravação **float**. |
| [`volume_value`](/slides/python-net/pt/aspose.slides/audioframe/volume_value/) | Retorna ou define o volume do áudio em porcentagem.<br/>             Leitura/gravação **float**. |
| [`trim_from_start`](/slides/python-net/pt/aspose.slides/audioframe/trim_from_start/) | Especifica a duração em milissegundos a ser removida do início da mídia durante a reprodução.<br/>            Leitura/gravação **float**. |
| [`trim_from_end`](/slides/python-net/pt/aspose.slides/audioframe/trim_from_end/) | Especifica a duração em milissegundos a ser removida do final da mídia durante a reprodução.<br/>            Leitura/gravação **float**. |
| [`caption_tracks`](/slides/python-net/pt/aspose.slides/audioframe/caption_tracks/) | Obtém a coleção de legendas fechadas associadas ao áudio frame.<br/>            Esta propriedade é somente leitura e retorna um [`ICaptionsCollection`](/slides/python-net/pt/aspose.slides/icaptionscollection) contendo todas as faixas de legenda. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/audioframe/get_image/#) | Retorna a miniatura da shape.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type é usado por padrão. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Retorna a miniatura da shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Salva o conteúdo da Shape como arquivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva o conteúdo da Shape como arquivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides/audioframe/remove_placeholder/#) | Define que esta shape não é um placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides/audioframe/get_base_placeholder/#) | Retorna uma shape placeholder básica (shape do layout e/ou slide mestre da qual a shape atual é herdada).<br/>            Retorna None se a shape atual não for herdada. |
| [`get_visual_bounds(self)`](/slides/python-net/pt/aspose.slides/audioframe/get_visual_bounds/#) | Obtém os limites visuais da shape calculados a partir do seu conteúdo renderizado. |
| [`get_geometry_paths(self)`](/slides/python-net/pt/aspose.slides/audioframe/get_geometry_paths/#) | Retorna a cópia do caminho da shape de geometria. As coordenadas são relativas ao canto superior esquerdo da shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pt/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | Atualiza a geometria da shape a partir do objeto [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da shape.<br/>             Altera o tipo da shape ([`GeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/geometryshape/shape_type)) para [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pt/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | Atualiza a geometria da shape a partir de array de [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da shape.<br/>             Altera o tipo da shape ([`GeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/geometryshape/shape_type)) para [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/pt/aspose.slides/audioframe/create_shape_elements/#) | Cria e retorna um array dos elementos da shape. |


### Veja Também
* class [`AudioFrame`](/slides/python-net/pt/aspose.slides/audioframe)
* class [`GeometryShape`](/slides/python-net/pt/aspose.slides/geometryshape)
* class [`PictureFrame`](/slides/python-net/pt/aspose.slides/pictureframe)
* class [`Shape`](/slides/python-net/pt/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)