---
title: AutoShape class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/autoshape/
---
## AutoShape classe

Represents an AutoShape.

**Inheritance:**[`AutoShape`](/slides/python-net/pt/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/pt/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/pt/aspose.slides/shape)

The AutoShape type exposes the following members:

## Propriedades

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides/autoshape/is_text_holder/) | Determina se a forma é TextHolder_PPT.<br/>            Somente leitura **bool**. |
| [`placeholder`](/slides/python-net/pt/aspose.slides/autoshape/placeholder/) | Retorna o placeholder de uma forma. Retorna None se a forma não tem placeholder.<br/>            Somente leitura [`IPlaceholder`](/slides/python-net/pt/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pt/aspose.slides/autoshape/custom_data/) | Retorna os dados personalizados da forma.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pt/aspose.slides/autoshape/raw_frame/) | Retorna ou define as propriedades da moldura de forma bruta.<br/>            Leitura/Gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pt/aspose.slides/autoshape/frame/) | Retorna ou define as propriedades da moldura da forma.<br/>            Leitura/Gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pt/aspose.slides/autoshape/line_format/) | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não possuem propriedades de linha.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/autoshape/three_d_format/) | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3D para uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não possuem propriedades 3D.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides/autoshape/effect_format/) | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não possuem propriedades de efeito.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides/autoshape/fill_format/) | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não possuem propriedades de preenchimento.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/autoshape/hyperlink_click/) | Retorna ou define o hyperlink definido para clique do mouse.<br/>            Leitura/Gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/autoshape/hyperlink_mouse_over/) | Retorna ou define o hyperlink definido para passagem do mouse.<br/>            Leitura/Gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/autoshape/hyperlink_manager/) | Retorna o gerenciador de hyperlinks.<br/>            Somente leitura [`IHyperlinkManager`](/slides/python-net/pt/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pt/aspose.slides/autoshape/hidden/) | Determina se a forma está oculta.<br/>            Leitura/Gravação **bool**. |
| [`z_order_position`](/slides/python-net/pt/aspose.slides/autoshape/z_order_position/) | Retorna a posição de uma forma na ordem z.<br/>            Shapes[0] retorna a forma que está no fundo da ordem z,<br/>            e Shapes[Shapes.Count - 1] retorna a forma que está na frente da ordem z.<br/>            Somente leitura **int**. |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides/autoshape/connection_site_count/) | Retorna o número de pontos de conexão na forma.<br/>            Somente leitura **int**. |
| [`rotation`](/slides/python-net/pt/aspose.slides/autoshape/rotation/) | Retorna ou define o número de graus que a forma especificada é rotacionada ao redor do eixo z.<br/>            Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário.<br/>            Leitura/Gravação **float**. |
| [`x`](/slides/python-net/pt/aspose.slides/autoshape/x/) | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/Gravação **float**. |
| [`y`](/slides/python-net/pt/aspose.slides/autoshape/y/) | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/Gravação **float**. |
| [`width`](/slides/python-net/pt/aspose.slides/autoshape/width/) | Obtém ou define a largura da forma, medida em pontos.<br/>            Leitura/Gravação **float**. |
| [`height`](/slides/python-net/pt/aspose.slides/autoshape/height/) | Obtém ou define a altura da forma, medida em pontos.<br/>            Leitura/Gravação **float**. |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides/autoshape/black_white_mode/) | Propriedade que especifica como uma forma será renderizada no modo de exibição preto-e-branco.<br/>            Leitura/Gravação [`BlackWhiteMode`](/slides/python-net/pt/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pt/aspose.slides/autoshape/unique_id/) | Retorna um identificador interno, de escopo de apresentação, destinado ao uso por add-ins ou outro código.<br/>            Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado<br/>            como uma chave única persistente.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.office_interop_shape_id`](/slides/python-net/pt/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides/autoshape/office_interop_shape_id/) | Retorna um identificador único de escopo de slide que permanece constante durante a vida útil da forma e<br/>            permite que o PowerPoint ou código interop faça referência confiável à forma de qualquer parte do documento.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.unique_id`](/slides/python-net/pt/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pt/aspose.slides/autoshape/alternative_text/) | Retorna ou define o texto alternativo associado a uma forma.<br/>            Leitura/Gravação **str**. |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides/autoshape/alternative_text_title/) | Retorna ou define o título do texto alternativo associado a uma forma.<br/>            Leitura/Gravação **str**. |
| [`name`](/slides/python-net/pt/aspose.slides/autoshape/name/) | Retorna ou define o nome de uma forma.<br/>            Deve não ser None. Use uma string vazia se necessário.<br/>            Leitura/Gravação **str**. |
| [`is_decorative`](/slides/python-net/pt/aspose.slides/autoshape/is_decorative/) | Obtém ou define a opção 'Marcar como decorativo'<br/>            Leitura/Gravação **bool**. |
| [`shape_lock`](/slides/python-net/pt/aspose.slides/autoshape/shape_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IAutoShapeLock`](/slides/python-net/pt/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/pt/aspose.slides/autoshape/is_grouped/) | Determina se a forma está agrupada.<br/>            Somente leitura **bool**. |
| [`parent_group`](/slides/python-net/pt/aspose.slides/autoshape/parent_group/) | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna None.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pt/aspose.slides/autoshape/slide/) | Retorna o slide pai de uma forma.<br/>            Somente leitura [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pt/aspose.slides/autoshape/presentation/) | Retorna a apresentação pai de um slide.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/pt/aspose.slides/autoshape/shape_style/) | Retorna o objeto de estilo da forma.<br/>            Somente leitura [`IShapeStyle`](/slides/python-net/pt/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/pt/aspose.slides/autoshape/shape_type/) | Retorna ou define o tipo de preset de geometria.<br/>            Nota: ao mudar o valor, todos os valores de ajuste serão redefinidos para seus valores padrão.<br/>            Leitura/Gravação [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/pt/aspose.slides/autoshape/adjustments/) | Retorna uma coleção dos valores de ajuste da forma.<br/>            Somente leitura [`IAdjustValueCollection`](/slides/python-net/pt/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/pt/aspose.slides/autoshape/auto_shape_lock/) | Retorna os bloqueios do autoshape.<br/>            Somente leitura [`IAutoShapeLock`](/slides/python-net/pt/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/pt/aspose.slides/autoshape/text_frame/) | Retorna o objeto TextFrame do AutoShape.<br/>            Somente leitura [`ITextFrame`](/slides/python-net/pt/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/pt/aspose.slides/autoshape/use_background_fill/) | Determina se este autoshape deve ser preenchido com o preenchimento de fundo do slide em vez de ser especificado por estilo ou formato de preenchimento.<br/>            Leitura/Gravação **bool**. |
| [`is_text_box`](/slides/python-net/pt/aspose.slides/autoshape/is_text_box/) | Especifica se a forma é uma caixa de texto. |

## Métodos

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/autoshape/get_image/#) | Retorna a miniatura da forma.<br/>            O tipo ShapeThumbnailBounds.Shape de limites da miniatura da forma é usado por padrão. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Retorna a miniatura da forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Salva o conteúdo da Shape como arquivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva o conteúdo da Shape como arquivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides/autoshape/remove_placeholder/#) | Define que esta forma não é um placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides/autoshape/get_base_placeholder/#) | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada).<br/>            Retorna None se a forma atual não for herdada. |
| [`get_visual_bounds(self)`](/slides/python-net/pt/aspose.slides/autoshape/get_visual_bounds/#) | Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado. |
| [`get_geometry_paths(self)`](/slides/python-net/pt/aspose.slides/autoshape/get_geometry_paths/#) | Retorna a cópia do caminho da forma geométrica. As coordenadas são relativas ao canto superior esquerdo da forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pt/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Atualiza a geometria da forma a partir do objeto [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma.<br/>            Altera o tipo da forma ([`GeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/geometryshape/shape_type)) para [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pt/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Atualiza a geometria da forma a partir de um array de [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma.<br/>            Altera o tipo da forma ([`GeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/geometryshape/shape_type)) para [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/pt/aspose.slides/autoshape/create_shape_elements/#) | Cria e retorna um array dos elementos da forma. |
| [`add_text_frame(self, text)`](/slides/python-net/pt/aspose.slides/autoshape/add_text_frame/#str) | Adiciona um novo TextFrame a uma forma.<br/>            Se a forma já possui TextFrame, então simplesmente altera seu texto. |

### Veja Também
* classe [`AutoShape`](/slides/python-net/pt/aspose.slides/autoshape)
* classe [`GeometryShape`](/slides/python-net/pt/aspose.slides/geometryshape)
* classe [`Shape`](/slides/python-net/pt/aspose.slides/shape)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)