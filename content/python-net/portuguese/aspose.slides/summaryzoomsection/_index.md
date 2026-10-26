---
title: SummaryZoomSection class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection classe

Representa um objeto Summary Zoom Section em um quadro Summary Zoom.

**Herança:**[`SummaryZoomSection`](/slides/python-net/pt/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/pt/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/pt/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/pt/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pt/aspose.slides/shape)

O tipo SummaryZoomSection expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides/summaryzoomsection/is_text_holder/) | Determina se a forma é TextHolder_PPT.<br/>            Somente leitura **bool**. |
| [`placeholder`](/slides/python-net/pt/aspose.slides/summaryzoomsection/placeholder/) | Retorna o placeholder de uma forma. Retorna None se a forma não tem placeholder.<br/>            Somente leitura [`IPlaceholder`](/slides/python-net/pt/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pt/aspose.slides/summaryzoomsection/custom_data/) | Retorna os dados personalizados da forma.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pt/aspose.slides/summaryzoomsection/raw_frame/) | Retorna ou define as propriedades brutas da moldura da forma.<br/>            Leitura/gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pt/aspose.slides/summaryzoomsection/frame/) | Retorna ou define as propriedades da moldura da forma.<br/>            Leitura/gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pt/aspose.slides/summaryzoomsection/line_format/) | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de linha.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/summaryzoomsection/three_d_format/) | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3D para uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades 3D.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides/summaryzoomsection/effect_format/) | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de efeito.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides/summaryzoomsection/fill_format/) | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de preenchimento.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/summaryzoomsection/hyperlink_click/) | Retorna ou define o hyperlink definido para clique do mouse.<br/>            Leitura/gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | Retorna ou define o hyperlink definido para passagem do mouse.<br/>            Leitura/gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/summaryzoomsection/hyperlink_manager/) | Retorna o gerenciador de hyperlink.<br/>            Somente leitura [`IHyperlinkManager`](/slides/python-net/pt/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pt/aspose.slides/summaryzoomsection/hidden/) | Determina se a forma está oculta.<br/>            Leitura/gravação **bool**. |
| [`z_order_position`](/slides/python-net/pt/aspose.slides/summaryzoomsection/z_order_position/) | Retorna a posição de uma forma na ordem z.<br/>            Shapes[0] retorna a forma que está no fundo da ordem z,<br/>            e Shapes[Shapes.Count - 1] retorna a forma que está na frente da ordem z.<br/>            Somente leitura **int**. |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides/summaryzoomsection/connection_site_count/) | Retorna o número de pontos de conexão na forma.<br/>            Somente leitura **int**. |
| [`rotation`](/slides/python-net/pt/aspose.slides/summaryzoomsection/rotation/) | Retorna ou define o número de graus que a forma especificada está girada em torno do eixo z.<br/>            Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário.<br/>            Leitura/gravação **float**. |
| [`x`](/slides/python-net/pt/aspose.slides/summaryzoomsection/x/) | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`y`](/slides/python-net/pt/aspose.slides/summaryzoomsection/y/) | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`width`](/slides/python-net/pt/aspose.slides/summaryzoomsection/width/) | Obtém ou define a largura da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`height`](/slides/python-net/pt/aspose.slides/summaryzoomsection/height/) | Obtém ou define a altura da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides/summaryzoomsection/black_white_mode/) | A propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco.<br/>            Leitura/gravação [`BlackWhiteMode`](/slides/python-net/pt/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pt/aspose.slides/summaryzoomsection/unique_id/) | Retorna um identificador interno, limitado à apresentação, destinado ao uso por complementos ou outro código.<br/>            Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado<br/>            como uma chave única persistente.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.office_interop_shape_id`](/slides/python-net/pt/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides/summaryzoomsection/office_interop_shape_id/) | Retorna um identificador único limitado ao slide que permanece constante durante a vida útil da forma e<br/>            permite que o PowerPoint ou código de interop faça referência de forma confiável à forma de qualquer ponto do documento.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.unique_id`](/slides/python-net/pt/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pt/aspose.slides/summaryzoomsection/alternative_text/) | Retorna ou define o texto alternativo associado a uma forma.<br/>            Leitura/gravação **str**. |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides/summaryzoomsection/alternative_text_title/) | Retorna ou define o título do texto alternativo associado a uma forma.<br/>            Leitura/gravação **str**. |
| [`name`](/slides/python-net/pt/aspose.slides/summaryzoomsection/name/) | Retorna ou define o nome de uma forma.<br/>            Deve não ser None. Use string vazia se necessário.<br/>            Leitura/gravação **str**. |
| [`is_decorative`](/slides/python-net/pt/aspose.slides/summaryzoomsection/is_decorative/) | Obtém ou define a opção 'Marcar como decorativo'<br/>            Leitura/gravação **bool**. |
| [`shape_lock`](/slides/python-net/pt/aspose.slides/summaryzoomsection/shape_lock/) | Retorna as travas da forma.<br/>            Somente leitura [`IGraphicalObjectLock`](/slides/python-net/pt/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pt/aspose.slides/summaryzoomsection/is_grouped/) | Determina se a forma está agrupada.<br/>            Somente leitura **bool**. |
| [`parent_group`](/slides/python-net/pt/aspose.slides/summaryzoomsection/parent_group/) | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna None.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pt/aspose.slides/summaryzoomsection/slide/) | Retorna o slide pai de uma forma.<br/>            Somente leitura [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pt/aspose.slides/summaryzoomsection/presentation/) | Retorna a apresentação pai de um slide.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pt/aspose.slides/summaryzoomsection/graphical_object_lock/) | Retorna as travas da forma.<br/>            Somente leitura [`IGraphicalObjectLock`](/slides/python-net/pt/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/pt/aspose.slides/summaryzoomsection/image_type/) | Obtém ou define o tipo de imagem de um objeto zoom.<br/>            Leitura/gravação [`ZoomImageType`](/slides/python-net/pt/aspose.slides/zoomimagetype).<br/>            Valor padrão: Preview |
| [`return_to_parent`](/slides/python-net/pt/aspose.slides/summaryzoomsection/return_to_parent/) | Obtém ou define o comportamento de navegação na apresentação de slides.<br/>            Leitura/gravação **bool**.<br/>            Valor padrão: false |
| [`show_background`](/slides/python-net/pt/aspose.slides/summaryzoomsection/show_background/) | Obtém ou define o valor que especifica se o Zoom usará o plano de fundo do slide de destino.<br/>            Leitura/gravação **bool**.<br/>            Valor padrão: true |
| [`zoom_image`](/slides/python-net/pt/aspose.slides/summaryzoomsection/zoom_image/) | Obtém ou define a imagem para o objeto zoom.<br/>            Leitura/gravação [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/pt/aspose.slides/summaryzoomsection/transition_duration/) | Obtém ou define a duração da transição entre Zoom e slide.<br/>            Leitura/gravação **float**.<br/>            Valor padrão: 1.0f |
| [`target_section`](/slides/python-net/pt/aspose.slides/summaryzoomsection/target_section/) | Obtém ou define o objeto de seção ao qual o objeto Section Zoom está vinculado.<br/>            Leitura/gravação [`ISection`](/slides/python-net/pt/aspose.slides/isection). |
| [`title`](/slides/python-net/pt/aspose.slides/summaryzoomsection/title/) | Retorna o título em texto do objeto Summary Zoom Section. |
| [`description`](/slides/python-net/pt/aspose.slides/summaryzoomsection/description/) | Retorna a descrição em texto do objeto Summary Zoom Section. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/summaryzoomsection/get_image/#) | Retorna a miniatura da forma.<br/>            O tipo ShapeThumbnailBounds.Shape de limites da miniatura da forma é usado por padrão. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/summaryzoomsection/get_image/#shapethumbnailbounds-float-float) | Retorna a miniatura da forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase) | Salva o conteúdo da Forma como um arquivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva o conteúdo da Forma como um arquivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides/summaryzoomsection/remove_placeholder/#) | Define que esta forma não é um placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides/summaryzoomsection/get_base_placeholder/#) | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada).<br/>            None é retornado se a forma atual não for herdada. |
| [`get_visual_bounds(self)`](/slides/python-net/pt/aspose.slides/summaryzoomsection/get_visual_bounds/#) | Obtém os limites visuais da forma calculados a partir do seu conteúdo renderizado. |

### Veja Também
* classe [`GraphicalObject`](/slides/python-net/pt/aspose.slides/graphicalobject)
* classe [`SectionZoomFrame`](/slides/python-net/pt/aspose.slides/sectionzoomframe)
* classe [`Shape`](/slides/python-net/pt/aspose.slides/shape)
* classe [`SummaryZoomSection`](/slides/python-net/pt/aspose.slides/summaryzoomsection)
* classe [`ZoomObject`](/slides/python-net/pt/aspose.slides/zoomobject)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)