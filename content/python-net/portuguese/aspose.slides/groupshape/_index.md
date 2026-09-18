---
title: GroupShape class
second_title: Aspose.Slides para Python via .NET – Referência da API
description: 
type: docs
url: /pt/aspose.slides/groupshape/
---
## GroupShape classe

Represents a group of shapes on a slide.

**Inheritance:**[`GroupShape`](/slides/python-net/pt/aspose.slides/groupshape) → [`Shape`](/slides/python-net/pt/aspose.slides/shape)

The GroupShape type exposes the following members:

## Propriedades

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides/groupshape/is_text_holder/) | Determina se a forma é TextHolder_PPT.<br/>            Somente leitura **bool**. |
| [`placeholder`](/slides/python-net/pt/aspose.slides/groupshape/placeholder/) | Retorna o espaço reservado para uma forma. Retorna None se a forma não tem espaço reservado.<br/>            Somente leitura [`IPlaceholder`](/slides/python-net/pt/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pt/aspose.slides/groupshape/custom_data/) | Retorna os dados personalizados da forma.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pt/aspose.slides/groupshape/raw_frame/) | Retorna ou define as propriedades brutas da moldura da forma.<br/>            Leitura/gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pt/aspose.slides/groupshape/frame/) | Retorna ou define as propriedades da moldura da forma.<br/>            Leitura/gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pt/aspose.slides/groupshape/line_format/) | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma.<br/>            Nota: Retorna None para objetos GroupShape porque eles não têm propriedades de linha.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/groupshape/three_d_format/) | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3D para uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não possuem propriedades 3D.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides/groupshape/effect_format/) | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não possuem propriedades de efeito.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides/groupshape/fill_format/) | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não possuem propriedades de preenchimento.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/groupshape/hyperlink_click/) | Retorna ou define o hiperlink definido para clique do mouse.<br/>            Leitura/gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/groupshape/hyperlink_mouse_over/) | Retorna ou define o hiperlink definido para passagem do mouse.<br/>            Leitura/gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/groupshape/hyperlink_manager/) | Retorna o gerenciador de hiperlink.<br/>            Somente leitura [`IHyperlinkManager`](/slides/python-net/pt/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pt/aspose.slides/groupshape/hidden/) | Determina se a forma está oculta.<br/>            Leitura/gravação **bool**. |
| [`z_order_position`](/slides/python-net/pt/aspose.slides/groupshape/z_order_position/) | Retorna a posição de uma forma na ordem z.<br/>            Shapes[0] retorna a forma na parte de trás da ordem z,<br/>            e Shapes[Shapes.Count - 1] retorna a forma na frente da ordem z.<br/>            Somente leitura **int**. |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides/groupshape/connection_site_count/) | Retorna o número de pontos de conexão na forma.<br/>            Somente leitura **int**. |
| [`rotation`](/slides/python-net/pt/aspose.slides/groupshape/rotation/) | Retorna ou define o número de graus que a forma especificada é girada ao redor do eixo z.<br/>            Um valor positivo indica rotação no sentido horário; um valor negativo<br/>            indica rotação no sentido anti-horário.<br/>            Leitura/gravação **float**. |
| [`x`](/slides/python-net/pt/aspose.slides/groupshape/x/) | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`y`](/slides/python-net/pt/aspose.slides/groupshape/y/) | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`width`](/slides/python-net/pt/aspose.slides/groupshape/width/) | Obtém ou define a largura da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`height`](/slides/python-net/pt/aspose.slides/groupshape/height/) | Obtém ou define a altura da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides/groupshape/black_white_mode/) | A propriedade especifica como uma forma será renderizada no modo de exibição preto-e-branco..<br/>            Leitura/gravação [`BlackWhiteMode`](/slides/python-net/pt/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pt/aspose.slides/groupshape/unique_id/) | Retorna um identificador interno, limitado à apresentação, destinado ao uso por complementos ou outro código.<br/>            Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado<br/>            como uma chave única persistente.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.office_interop_shape_id`](/slides/python-net/pt/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides/groupshape/office_interop_shape_id/) | Retorna um identificador único limitado ao slide que permanece constante durante a vida útil da forma e<br/>            permite que o PowerPoint ou código interop faça referência confiável à forma de qualquer ponto do documento.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.unique_id`](/slides/python-net/pt/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pt/aspose.slides/groupshape/alternative_text/) | Retorna ou define o texto alternativo associado a uma forma.<br/>            Leitura/gravação **str**. |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides/groupshape/alternative_text_title/) | Retorna ou define o título do texto alternativo associado a uma forma.<br/>            Leitura/gravação **str**. |
| [`name`](/slides/python-net/pt/aspose.slides/groupshape/name/) | Retorna ou define o nome de uma forma.<br/>            Não pode ser None. Use string vazia se necessário.<br/>            Leitura/gravação **str**. |
| [`is_decorative`](/slides/python-net/pt/aspose.slides/groupshape/is_decorative/) | Obtém ou define a opção 'Marcar como decorativo'<br/>            Leitura/gravação **bool**. |
| [`shape_lock`](/slides/python-net/pt/aspose.slides/groupshape/shape_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IGroupShapeLock`](/slides/python-net/pt/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/pt/aspose.slides/groupshape/is_grouped/) | Determina se a forma está agrupada.<br/>            Somente leitura **bool**. |
| [`parent_group`](/slides/python-net/pt/aspose.slides/groupshape/parent_group/) | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário retorna None.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pt/aspose.slides/groupshape/slide/) | Retorna o slide pai de uma forma.<br/>            Somente leitura [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pt/aspose.slides/groupshape/presentation/) | Retorna a apresentação pai de um slide.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/pt/aspose.slides/groupshape/group_shape_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IGroupShapeLock`](/slides/python-net/pt/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/pt/aspose.slides/groupshape/shapes/) | Retorna a coleção de formas dentro do grupo.<br/>            Somente leitura [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection). |

## Métodos

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/groupshape/get_image/#) | Retorna a miniatura da forma.<br/>            O tipo ShapeThumbnailBounds.Shape é usado por padrão para limites da miniatura da forma. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | Retorna a miniatura da forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/groupshape/write_as_svg/#iorawiobase) | Salva o conteúdo da Forma como arquivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva o conteúdo da Forma como arquivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides/groupshape/remove_placeholder/#) | Define que esta forma não é um espaço reservado. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides/groupshape/add_placeholder/#iplaceholder) | Adiciona um novo espaço reservado se não houver e define as propriedades do espaço reservado para um especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides/groupshape/get_base_placeholder/#) | Retorna uma forma de espaço reservado básica (forma do layout e/ou slide mestre da qual a forma atual é herdada).<br/>            None é retornado se a forma atual não for herdada. |
| [`get_visual_bounds(self)`](/slides/python-net/pt/aspose.slides/groupshape/get_visual_bounds/#) | Obtém os limites visuais da forma calculados a partir do seu conteúdo renderizado. |

### Veja Também
* classe [`GroupShape`](/slides/python-net/pt/aspose.slides/groupshape)
* classe [`Shape`](/slides/python-net/pt/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)