---
title: SmartArtShape class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.smartart/smartartshape/
---
## classe SmartArtShape

Representa uma forma SmartArt

**Herança:**[`SmartArtShape`](/slides/python-net/pt/aspose.slides.smartart/smartartshape) → [`GeometryShape`](/slides/python-net/pt/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/pt/aspose.slides/shape)

O tipo SmartArtShape expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/is_text_holder/) | Determina se a forma é TextHolder_PPT.<br/>            Somente leitura **bool**. |
| [`placeholder`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/placeholder/) | Retorna o placeholder de uma forma. Retorna None se a forma não possuir placeholder.<br/>            Somente leitura [`IPlaceholder`](/slides/python-net/pt/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/custom_data/) | Retorna os dados personalizados da forma.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/raw_frame/) | Retorna ou define as propriedades da moldura bruta da forma.<br/>            Leitura/gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/frame/) | Retorna ou define as propriedades da moldura da forma.<br/>            Leitura/gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/line_format/) | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma.<br/>            Observação: pode retornar None para certos tipos de forma que não possuem propriedades de linha.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/three_d_format/) | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3D para uma forma.<br/>            Observação: pode retornar None para certos tipos de forma que não possuem propriedades 3D.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/effect_format/) | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma.<br/>            Observação: pode retornar None para certos tipos de forma que não possuem propriedades de efeito.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/fill_format/) | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma forma.<br/>            Observação: pode retornar None para certos tipos de forma que não possuem propriedades de preenchimento.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/hyperlink_click/) | Retorna ou define o hiperlink definido para clique do mouse.<br/>            Leitura/gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | Retorna ou define o hiperlink definido para passagem do mouse.<br/>            Leitura/gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/hyperlink_manager/) | Retorna o gerenciador de hiperlinks.<br/>            Somente leitura [`IHyperlinkManager`](/slides/python-net/pt/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/hidden/) | Determina se a forma está oculta.<br/>            Leitura/gravação **bool**. |
| [`z_order_position`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/z_order_position/) | Retorna a posição de uma forma na ordem z.<br/>            Shapes[0] retorna a forma na parte traseira da ordem z,<br/>            e Shapes[Shapes.Count - 1] retorna a forma na frente da ordem z.<br/>            Somente leitura **int**. |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/connection_site_count/) | Retorna o número de pontos de conexão na forma.<br/>            Somente leitura **int**. |
| [`rotation`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/rotation/) | Retorna ou define o número de graus que a forma especificada está rotacionada ao redor<br/>            do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo<br/>            indica rotação no sentido anti-horário.<br/>            Leitura/gravação **float**. |
| [`x`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/x/) | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`y`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/y/) | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`width`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/width/) | Obtém ou define a largura da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`height`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/height/) | Obtém ou define a altura da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/black_white_mode/) | Propriedade que especifica como uma forma será renderizada no modo de exibição em preto e branco.<br/>            Leitura/gravação [`BlackWhiteMode`](/slides/python-net/pt/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/unique_id/) | Retorna um identificador interno, limitado à apresentação, destinado ao uso por complementos ou outro código.<br/>            Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado<br/>            como uma chave única persistente.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.office_interop_shape_id`](/slides/python-net/pt/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | Retorna um identificador único limitado ao slide que permanece constante durante a vida útil da forma e<br/>            permite que o PowerPoint ou código de interop faça referência à forma de forma confiável a partir de qualquer ponto do documento.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.unique_id`](/slides/python-net/pt/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/alternative_text/) | Retorna ou define o texto alternativo associado a uma forma.<br/>            Leitura/gravação **str**. |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/alternative_text_title/) | Retorna ou define o título do texto alternativo associado a uma forma.<br/>            Leitura/gravação **str**. |
| [`name`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/name/) | Retorna ou define o nome de uma forma.<br/>            Deve não ser None. Use string vazia se necessário.<br/>            Leitura/gravação **str**. |
| [`is_decorative`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/is_decorative/) | Obtém ou define a opção 'Marcar como decorativo'<br/>            Leitura/gravação **bool**. |
| [`shape_lock`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/shape_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IBaseShapeLock`](/slides/python-net/pt/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/is_grouped/) | Determina se a forma está agrupada.<br/>            Somente leitura **bool**. |
| [`parent_group`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/parent_group/) | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna None.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/slide/) | Retorna o slide pai de uma forma.<br/>            Somente leitura [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/presentation/) | Retorna a apresentação pai de um slide.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/shape_style/) | Retorna o objeto de estilo da forma.<br/>            Somente leitura [`IShapeStyle`](/slides/python-net/pt/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/shape_type/) | Retorna ou define o tipo de predefinição de geometria.<br/>            Observação: ao mudar o valor, todos os valores de ajuste serão restaurados aos valores padrão.<br/>            Leitura/gravação [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/adjustments/) | Retorna uma coleção dos valores de ajuste da forma.<br/>            Somente leitura [`IAdjustValueCollection`](/slides/python-net/pt/aspose.slides/iadjustvaluecollection). |
| [`text_frame`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/text_frame/) | Retorna o texto da forma SmartArt.<br/>            Somente leitura [`ITextFrame`](/slides/python-net/pt/aspose.slides/itextframe). |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/get_image/#) | Retorna a miniatura da forma.<br/>            ShapeThumbnailBounds.Shape é usado como tipo padrão de limites da miniatura da forma. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/get_image/#shapethumbnailbounds-float-float) | Retorna a miniatura da forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase) | Salva o conteúdo da Forma como arquivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva o conteúdo da Forma como arquivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/remove_placeholder/#) | Define que esta forma não é um placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/add_placeholder/#iplaceholder) | Adiciona um novo placeholder se não houver um e define as propriedades do placeholder para um especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada).<br/>            Retorna None se a forma atual não for herdada. |
| [`get_visual_bounds(self)`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/get_visual_bounds/#) | Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado. |
| [`get_geometry_paths(self)`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | Retorna a cópia do caminho da forma de geometria. As coordenadas são relativas ao canto superior esquerdo da forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/set_geometry_path/#igeometrypath) | Atualiza a geometria da forma a partir do objeto [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior<br/>             esquerdo da forma.<br/>             Altera o tipo da forma ([`GeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/geometryshape/shape_type)) para [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/set_geometry_paths/#listigeometrypath) | Atualiza a geometria da forma a partir de um array de [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior<br/>             esquerdo da forma.<br/>             Altera o tipo da forma ([`GeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/geometryshape/shape_type)) para [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/pt/aspose.slides.smartart/smartartshape/create_shape_elements/#) | Cria e retorna um array dos elementos da forma. |


### Veja Também
* classe [`GeometryShape`](/slides/python-net/pt/aspose.slides/geometryshape)
* classe [`Shape`](/slides/python-net/pt/aspose.slides/shape)
* classe [`SmartArtShape`](/slides/python-net/pt/aspose.slides.smartart/smartartshape)
* módulo [`aspose.slides.smartart`](/slides/python-net/pt/aspose.slides.smartart)
* biblioteca [`Aspose.Slides`](/slides/python-net)