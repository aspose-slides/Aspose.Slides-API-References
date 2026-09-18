---
title: LegacyDiagram class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/legacydiagram/
---
## LegacyDiagram classe

Representa um objeto de diagrama legado.

**Herança:**[`LegacyDiagram`](/slides/python-net/pt/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/pt/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pt/aspose.slides/shape)

O tipo LegacyDiagram expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides/legacydiagram/is_text_holder/) | Determina se a forma é TextHolder_PPT.<br/>            Somente leitura **bool**. |
| [`placeholder`](/slides/python-net/pt/aspose.slides/legacydiagram/placeholder/) | Retorna o placeholder para uma forma. Retorna None se a forma não tem placeholder.<br/>            Somente leitura [`IPlaceholder`](/slides/python-net/pt/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pt/aspose.slides/legacydiagram/custom_data/) | Retorna os dados personalizados da forma.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pt/aspose.slides/legacydiagram/raw_frame/) | Obtém ou define as propriedades brutas da moldura da forma.<br/>            Leitura/gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pt/aspose.slides/legacydiagram/frame/) | Obtém ou define as propriedades da moldura da forma.<br/>            Leitura/gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pt/aspose.slides/legacydiagram/line_format/) | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de linha.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/legacydiagram/three_d_format/) | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3D para uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades 3D.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides/legacydiagram/effect_format/) | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de efeito.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides/legacydiagram/fill_format/) | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de preenchimento.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/legacydiagram/hyperlink_click/) | Obtém ou define o hyperlink definido para clique do mouse.<br/>            Leitura/gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/legacydiagram/hyperlink_mouse_over/) | Obtém ou define o hyperlink definido para passagem do mouse.<br/>            Leitura/gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/legacydiagram/hyperlink_manager/) | Retorna o gerenciador de hyperlink.<br/>            Somente leitura [`IHyperlinkManager`](/slides/python-net/pt/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pt/aspose.slides/legacydiagram/hidden/) | Determina se a forma está oculta.<br/>            Leitura/gravação **bool**. |
| [`z_order_position`](/slides/python-net/pt/aspose.slides/legacydiagram/z_order_position/) | Retorna a posição de uma forma na ordem Z.<br/>            Shapes[0] retorna a forma mais ao fundo da ordem Z,<br/>            e Shapes[Shapes.Count - 1] retorna a forma mais ao frente da ordem Z.<br/>            Somente leitura **int**. |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides/legacydiagram/connection_site_count/) | Retorna o número de pontos de conexão na forma.<br/>            Somente leitura **int**. |
| [`rotation`](/slides/python-net/pt/aspose.slides/legacydiagram/rotation/) | Obtém ou define o número de graus que a forma especificada está rotacionada ao redor do eixo Z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário.<br/>            Leitura/gravação **float**. |
| [`x`](/slides/python-net/pt/aspose.slides/legacydiagram/x/) | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`y`](/slides/python-net/pt/aspose.slides/legacydiagram/y/) | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`width`](/slides/python-net/pt/aspose.slides/legacydiagram/width/) | Obtém ou define a largura da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`height`](/slides/python-net/pt/aspose.slides/legacydiagram/height/) | Obtém ou define a altura da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides/legacydiagram/black_white_mode/) | Propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco.<br/>            Leitura/gravação [`BlackWhiteMode`](/slides/python-net/pt/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pt/aspose.slides/legacydiagram/unique_id/) | Retorna um identificador interno, limitado à apresentação, destinado ao uso por complementos ou outro código.<br/>            Como este valor pode ser reassigned pelo usuário ou programaticamente, ele não deve ser tratado<br/>            como uma chave única persistente.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.office_interop_shape_id`](/slides/python-net/pt/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides/legacydiagram/office_interop_shape_id/) | Retorna um identificador único limitado ao slide que permanece constante durante a vida útil da forma e<br/>            permite que o PowerPoint ou código de interop faça referência confiável à forma de qualquer ponto do documento.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.unique_id`](/slides/python-net/pt/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pt/aspose.slides/legacydiagram/alternative_text/) | Obtém ou define o texto alternativo associado a uma forma.<br/>            Leitura/gravação **str**. |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides/legacydiagram/alternative_text_title/) | Obtém ou define o título do texto alternativo associado a uma forma.<br/>            Leitura/gravação **str**. |
| [`name`](/slides/python-net/pt/aspose.slides/legacydiagram/name/) | Obtém ou define o nome de uma forma.<br/>            Deve não ser None. Use valor de string vazia se necessário.<br/>            Leitura/gravação **str**. |
| [`is_decorative`](/slides/python-net/pt/aspose.slides/legacydiagram/is_decorative/) | Obtém ou define a opção 'Marcar como decorativo'<br/>            Leitura/gravação **bool**. |
| [`shape_lock`](/slides/python-net/pt/aspose.slides/legacydiagram/shape_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IGraphicalObjectLock`](/slides/python-net/pt/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pt/aspose.slides/legacydiagram/is_grouped/) | Determina se a forma está agrupada.<br/>            Somente leitura **bool**. |
| [`parent_group`](/slides/python-net/pt/aspose.slides/legacydiagram/parent_group/) | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna None.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pt/aspose.slides/legacydiagram/slide/) | Retorna o slide pai de uma forma.<br/>            Somente leitura [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pt/aspose.slides/legacydiagram/presentation/) | Retorna a apresentação pai de um slide.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pt/aspose.slides/legacydiagram/graphical_object_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IGraphicalObjectLock`](/slides/python-net/pt/aspose.slides/igraphicalobjectlock). |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/legacydiagram/get_image/#) | Retorna a miniatura da forma.<br/>            O tipo ShapeThumbnailBounds.Shape é usado por padrão para os limites da miniatura da forma. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | Retorna a miniatura da forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | Salva o conteúdo da Shape como arquivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva o conteúdo da Shape como arquivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides/legacydiagram/remove_placeholder/#) | Define que esta forma não é um placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | Adiciona um novo placeholder se não houver um e define as propriedades do placeholder para um especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides/legacydiagram/get_base_placeholder/#) | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada).<br/>            None é retornado se a forma atual não for herdada. |
| [`get_visual_bounds(self)`](/slides/python-net/pt/aspose.slides/legacydiagram/get_visual_bounds/#) | Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado. |
| [`convert_to_smart_art(self)`](/slides/python-net/pt/aspose.slides/legacydiagram/convert_to_smart_art/#) | Converte diagrama legado em objeto SmartArt editável. <br/>            O objeto SmartArt criado é adicionado ao grupo de formas pai na mesma posição. |
| [`convert_to_group_shape(self)`](/slides/python-net/pt/aspose.slides/legacydiagram/convert_to_group_shape/#) | Converte diagrama legado em grupo de formas editável. <br/>            O objeto GroupShape criado é adicionado ao grupo de formas pai na mesma posição. |

### Veja Também
* classe [`GraphicalObject`](/slides/python-net/pt/aspose.slides/graphicalobject)
* classe [`LegacyDiagram`](/slides/python-net/pt/aspose.slides/legacydiagram)
* classe [`Shape`](/slides/python-net/pt/aspose.slides/shape)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)