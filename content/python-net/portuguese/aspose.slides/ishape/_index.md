---
title: IShape class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/ishape/
---
## IShape classe

Representa uma forma em um slide.

O tipo IShape expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides/ishape/is_text_holder/) | Determina se a forma é TextHolder.<br/>            Somente leitura **bool**. |
| [`placeholder`](/slides/python-net/pt/aspose.slides/ishape/placeholder/) | Retorna o placeholder para uma forma.<br/>            Somente leitura [`IPlaceholder`](/slides/python-net/pt/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pt/aspose.slides/ishape/custom_data/) | Retorna os dados personalizados da forma.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pt/aspose.slides/ishape/raw_frame/) | Retorna ou define as propriedades brutas da moldura da forma.<br/>            Leitura/Gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pt/aspose.slides/ishape/frame/) | Retorna ou define as propriedades da moldura da forma.<br/>            Leitura/Gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pt/aspose.slides/ishape/line_format/) | Retorna o objeto LineFormat que contém as propriedades de formatação de linha para uma forma.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/ishape/three_d_format/) | Retorna o objeto ThreeDFormat que contém as propriedades de formatação de linha para uma forma.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides/ishape/effect_format/) | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides/ishape/fill_format/) | Retorna o objeto FillFormat que contém as propriedades de formatação de preenchimento para uma forma.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/pt/aspose.slides/ishape/hidden/) | Determina se a forma está oculta.<br/>            Leitura/Gravação **bool**. |
| [`z_order_position`](/slides/python-net/pt/aspose.slides/ishape/z_order_position/) | Retorna a posição de uma forma na ordem z.<br/>            Shapes[0] retorna a forma no fundo da ordem z,<br/>            e Shapes[Shapes.Count - 1] retorna a forma na frente da ordem z.<br/>            Somente leitura **int**. |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides/ishape/connection_site_count/) | Retorna o número de pontos de conexão na forma.<br/>            Somente leitura **int**. |
| [`rotation`](/slides/python-net/pt/aspose.slides/ishape/rotation/) | Retorna ou define o número de graus que a forma especificada está girada ao redor<br/>            do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo<br/>            indica rotação no sentido anti-horário.<br/>            Leitura/Gravação **float**. |
| [`x`](/slides/python-net/pt/aspose.slides/ishape/x/) | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/Gravação **float**. |
| [`y`](/slides/python-net/pt/aspose.slides/ishape/y/) | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/Gravação **float**. |
| [`width`](/slides/python-net/pt/aspose.slides/ishape/width/) | Obtém ou define a largura da forma, medida em pontos.<br/>            Leitura/Gravação **float**. |
| [`height`](/slides/python-net/pt/aspose.slides/ishape/height/) | Obtém ou define a altura da forma, medida em pontos.<br/>            Leitura/Gravação **float**. |
| [`alternative_text`](/slides/python-net/pt/aspose.slides/ishape/alternative_text/) | Retorna ou define o texto alternativo associado a uma forma.<br/>            Leitura/Gravação **str**. |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides/ishape/alternative_text_title/) | Retorna ou define o título do texto alternativo associado a uma forma.<br/>            Leitura/Gravação **str**. |
| [`name`](/slides/python-net/pt/aspose.slides/ishape/name/) | Retorna ou define o nome de uma forma.<br/>            Leitura/Gravação **str**. |
| [`is_decorative`](/slides/python-net/pt/aspose.slides/ishape/is_decorative/) | Obtém ou define a opção 'Marcar como decorativo'<br/>            Leitura/Gravação **bool**. |
| [`shape_lock`](/slides/python-net/pt/aspose.slides/ishape/shape_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IBaseShapeLock`](/slides/python-net/pt/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/pt/aspose.slides/ishape/unique_id/) | Retorna um identificador interno, com escopo de apresentação, destinado ao uso por complementos ou outro código.<br/>            Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado<br/>            como uma chave única persistente.<br/>            Somente leitura **int**.<br/>            Veja também [`IShape.office_interop_shape_id`](/slides/python-net/pt/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides/ishape/office_interop_shape_id/) | Retorna um identificador único com escopo de slide que permanece constante durante a vida útil da forma e<br/>            permite que o PowerPoint ou código interop referencie a forma de forma confiável a partir de qualquer ponto do documento.<br/>            Somente leitura **int**.<br/>            Veja também [`IShape.unique_id`](/slides/python-net/pt/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/pt/aspose.slides/ishape/is_grouped/) | Determina se a forma está agrupada.<br/>            Somente leitura **bool**. |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides/ishape/black_white_mode/) | A propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco.<br/>            Leitura/Gravação [`BlackWhiteMode`](/slides/python-net/pt/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/pt/aspose.slides/ishape/parent_group/) | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna None.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pt/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/ishape/hyperlink_manager/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/ishape/get_image/#) | Retorna a miniatura da forma.<br/>            O tipo ShapeThumbnailBounds.Shape de limites de miniatura de forma é usado por padrão. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Retorna a miniatura da forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/ishape/write_as_svg/#iorawiobase) | Salva o conteúdo da Forma como arquivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva o conteúdo da Forma como arquivo SVG. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides/ishape/add_placeholder/#iplaceholder) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides/ishape/remove_placeholder/#) | Define que esta forma não é um placeholder. |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides/ishape/get_base_placeholder/#) | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada).<br/>            None é retornado se a forma atual não for herdada. |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)