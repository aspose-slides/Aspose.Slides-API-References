---
title: PictureFrame class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/pictureframe/
---
## PictureFrame classe

Representa um quadro com uma imagem dentro.

**Herança:**[`PictureFrame`](/slides/python-net/pt/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/pt/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/pt/aspose.slides/shape)

O tipo PictureFrame expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides/pictureframe/is_text_holder/) | Determina se a forma é TextHolder_PPT.<br/>            Somente leitura **bool**. |
| [`placeholder`](/slides/python-net/pt/aspose.slides/pictureframe/placeholder/) | Retorna o placeholder de uma forma. Retorna None se a forma não possui placeholder.<br/>            Somente leitura [`IPlaceholder`](/slides/python-net/pt/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pt/aspose.slides/pictureframe/custom_data/) | Retorna os dados personalizados da forma.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pt/aspose.slides/pictureframe/raw_frame/) | Retorna ou define as propriedades brutas da moldura da forma.<br/>            Leitura/escrita [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pt/aspose.slides/pictureframe/frame/) | Retorna ou define as propriedades da moldura da forma.<br/>            Leitura/escrita [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pt/aspose.slides/pictureframe/line_format/) | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de linha.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/pictureframe/three_d_format/) | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3D para uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades 3D.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides/pictureframe/effect_format/) | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de efeito.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides/pictureframe/fill_format/) | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de preenchimento.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/pictureframe/hyperlink_click/) | Retorna ou define o hyperlink definido para clique do mouse.<br/>            Leitura/escrita [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/pictureframe/hyperlink_mouse_over/) | Retorna ou define o hyperlink definido para passagem do mouse.<br/>            Leitura/escrita [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/pictureframe/hyperlink_manager/) | Retorna o gerenciador de hyperlink.<br/>            Somente leitura [`IHyperlinkManager`](/slides/python-net/pt/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pt/aspose.slides/pictureframe/hidden/) | Determina se a forma está oculta.<br/>            Leitura/escrita **bool**. |
| [`z_order_position`](/slides/python-net/pt/aspose.slides/pictureframe/z_order_position/) | Retorna a posição de uma forma na ordem Z.<br/>            Shapes[0] retorna a forma que está no fundo da ordem Z,<br/>            e Shapes[Shapes.Count - 1] retorna a forma que está na frente da ordem Z.<br/>            Somente leitura **int**. |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides/pictureframe/connection_site_count/) | Retorna o número de pontos de conexão na forma.<br/>            Somente leitura **int**. |
| [`rotation`](/slides/python-net/pt/aspose.slides/pictureframe/rotation/) | Retorna ou define o número de graus que a forma especificada é rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário.<br/>            Leitura/escrita **float**. |
| [`x`](/slides/python-net/pt/aspose.slides/pictureframe/x/) | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/escrita **float**. |
| [`y`](/slides/python-net/pt/aspose.slides/pictureframe/y/) | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/escrita **float**. |
| [`width`](/slides/python-net/pt/aspose.slides/pictureframe/width/) | Obtém ou define a largura da forma, medida em pontos.<br/>            Leitura/escrita **float**. |
| [`height`](/slides/python-net/pt/aspose.slides/pictureframe/height/) | Obtém ou define a altura da forma, medida em pontos.<br/>            Leitura/escrita **float**. |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides/pictureframe/black_white_mode/) | A propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco..<br/>            Leitura/escrita [`BlackWhiteMode`](/slides/python-net/pt/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pt/aspose.slides/pictureframe/unique_id/) | Retorna um identificador interno, de escopo de apresentação, destinado ao uso por complementos ou outro código.<br/>            Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado<br/>            como uma chave única persistente.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.office_interop_shape_id`](/slides/python-net/pt/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides/pictureframe/office_interop_shape_id/) | Retorna um identificador exclusivo de escopo de slide que permanece constante durante a vida útil da forma e<br/>            permite que o PowerPoint ou código interop a referencie de forma confiável a partir de qualquer ponto do documento.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.unique_id`](/slides/python-net/pt/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pt/aspose.slides/pictureframe/alternative_text/) | Retorna ou define o texto alternativo associado a uma forma.<br/>            Leitura/escrita **str**. |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides/pictureframe/alternative_text_title/) | Retorna ou define o título do texto alternativo associado a uma forma.<br/>            Leitura/escrita **str**. |
| [`name`](/slides/python-net/pt/aspose.slides/pictureframe/name/) | Retorna ou define o nome de uma forma.<br/>            Não deve ser None. Use uma string vazia se necessário.<br/>            Leitura/escrita **str**. |
| [`is_decorative`](/slides/python-net/pt/aspose.slides/pictureframe/is_decorative/) | Obtém ou define a opção 'Marcar como decorativo'<br/>            Leitura/escrita **bool**. |
| [`shape_lock`](/slides/python-net/pt/aspose.slides/pictureframe/shape_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IPictureFrameLock`](/slides/python-net/pt/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/pt/aspose.slides/pictureframe/is_grouped/) | Determina se a forma está agrupada.<br/>            Somente leitura **bool**. |
| [`parent_group`](/slides/python-net/pt/aspose.slides/pictureframe/parent_group/) | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna None.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pt/aspose.slides/pictureframe/slide/) | Retorna o slide pai de uma forma.<br/>            Somente leitura [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pt/aspose.slides/pictureframe/presentation/) | Retorna a apresentação pai de um slide.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/pt/aspose.slides/pictureframe/shape_style/) | Retorna o objeto de estilo da forma.<br/>            Somente leitura [`IShapeStyle`](/slides/python-net/pt/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/pt/aspose.slides/pictureframe/shape_type/) | Retorna ou define o tipo AutoShape para um PictureFrame.<br/>            São permitidos todos os itens do conjunto [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype), <br/>            exceto todos os tipos de linhas:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Leitura/escrita [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/pt/aspose.slides/pictureframe/adjustments/) | Retorna uma coleção de valores de ajuste da forma.<br/>            Somente leitura [`IAdjustValueCollection`](/slides/python-net/pt/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/pt/aspose.slides/pictureframe/picture_frame_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IPictureFrameLock`](/slides/python-net/pt/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/pt/aspose.slides/pictureframe/picture_format/) | Retorna o objeto PictureFillFormat de um quadro de imagem.<br/>            Somente leitura [`IPictureFillFormat`](/slides/python-net/pt/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/pt/aspose.slides/pictureframe/relative_scale_height/) | Retorna ou define a escala de altura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%.<br/>            Leitura/escrita **float**. |
| [`relative_scale_width`](/slides/python-net/pt/aspose.slides/pictureframe/relative_scale_width/) | Retorna ou define a escala de largura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%.<br/>            Leitura/escrita **float**. |
| [`is_cameo`](/slides/python-net/pt/aspose.slides/pictureframe/is_cameo/) | Determina se o PictureFrame é um objeto Cameo ou não.<br/>            Somente leitura **bool**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/pictureframe/get_image/#) | Retorna a miniatura da forma.<br/>            O tipo ShapeThumbnailBounds.Shape é usado por padrão para limites da miniatura da forma. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Retorna a miniatura da forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Salva o conteúdo da Forma como arquivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva o conteúdo da Forma como arquivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides/pictureframe/remove_placeholder/#) | Define que esta forma não é um placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides/pictureframe/get_base_placeholder/#) | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada).<br/>            None é retornado se a forma atual não for herdada. |
| [`get_visual_bounds(self)`](/slides/python-net/pt/aspose.slides/pictureframe/get_visual_bounds/#) | Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado. |
| [`get_geometry_paths(self)`](/slides/python-net/pt/aspose.slides/pictureframe/get_geometry_paths/#) | Retorna uma cópia do caminho da forma geométrica. As coordenadas são relativas ao canto superior esquerdo da forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pt/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Atualiza a geometria da forma a partir do objeto [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma.<br/>             Altera o tipo da forma ([`GeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/geometryshape/shape_type)) para [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pt/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Atualiza a geometria da forma a partir de um array de [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma.<br/>             Altera o tipo da forma ([`GeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/geometryshape/shape_type)) para [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/pt/aspose.slides/pictureframe/create_shape_elements/#) | Cria e retorna um array dos elementos da forma. |

### Veja Também
* classe [`GeometryShape`](/slides/python-net/pt/aspose.slides/geometryshape)
* classe [`PictureFrame`](/slides/python-net/pt/aspose.slides/pictureframe)
* classe [`Shape`](/slides/python-net/pt/aspose.slides/shape)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)