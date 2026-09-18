---
title: Chart class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/chart/
---
## Chart classe

Representa um gráfico em um slide.

**Inheritance:**[`Chart`](/slides/python-net/pt/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/pt/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pt/aspose.slides/shape)

O tipo Chart expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides.charts/chart/is_text_holder/) | Determina se a forma é TextHolder_PPT.<br/>            Somente leitura **bool**. |
| [`placeholder`](/slides/python-net/pt/aspose.slides.charts/chart/placeholder/) | Retorna o placeholder de uma forma. Retorna None se a forma não possui placeholder.<br/>            Somente leitura [`IPlaceholder`](/slides/python-net/pt/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pt/aspose.slides.charts/chart/custom_data/) | Retorna os dados personalizados da forma.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pt/aspose.slides.charts/chart/raw_frame/) | Retorna ou define as propriedades da moldura de forma bruta.<br/>            Leitura/gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pt/aspose.slides.charts/chart/frame/) | Retorna ou define as propriedades da moldura da forma.<br/>            Leitura/gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pt/aspose.slides.charts/chart/line_format/) | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de linha.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pt/aspose.slides.charts/chart/three_d_format/) | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3d para uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades 3d.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides.charts/chart/effect_format/) | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de efeito.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides.charts/chart/fill_format/) | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma forma.<br/>            Observação: pode retornar None para certos tipos de formas que não possuem propriedades de preenchimento.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides.charts/chart/hyperlink_click/) | Retorna ou define o hyperlink definido para clique do mouse.<br/>            Leitura/gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides.charts/chart/hyperlink_mouse_over/) | Retorna ou define o hyperlink definido para mouse over.<br/>            Leitura/gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides.charts/chart/hyperlink_manager/) | Retorna o gerenciador de hyperlinks.<br/>            Somente leitura [`IHyperlinkManager`](/slides/python-net/pt/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pt/aspose.slides.charts/chart/hidden/) | Determina se a forma está oculta.<br/>            Leitura/gravação **bool**. |
| [`z_order_position`](/slides/python-net/pt/aspose.slides.charts/chart/z_order_position/) | Retorna a posição de uma forma na ordem Z.<br/>            Shapes[0] retorna a forma mais ao fundo da ordem Z,<br/>            e Shapes[Shapes.Count - 1] retorna a forma mais à frente da ordem Z.<br/>            Somente leitura **int**. |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides.charts/chart/connection_site_count/) | Retorna o número de pontos de conexão na forma.<br/>            Somente leitura **int**. |
| [`rotation`](/slides/python-net/pt/aspose.slides.charts/chart/rotation/) | Retorna ou define o número de graus que a forma especificada está rotacionada ao redor do eixo z.<br/>            Um valor positivo indica rotação no sentido horário; um valor negativo<br/>            indica rotação no sentido anti-horário.<br/>            Leitura/gravação **float**. |
| [`x`](/slides/python-net/pt/aspose.slides.charts/chart/x/) | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`y`](/slides/python-net/pt/aspose.slides.charts/chart/y/) | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`width`](/slides/python-net/pt/aspose.slides.charts/chart/width/) | Obtém ou define a largura da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`height`](/slides/python-net/pt/aspose.slides.charts/chart/height/) | Obtém ou define a altura da forma, medida em pontos.<br/>            Leitura/gravação **float**. |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides.charts/chart/black_white_mode/) | A propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco..<br/>            Leitura/gravação [`BlackWhiteMode`](/slides/python-net/pt/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pt/aspose.slides.charts/chart/unique_id/) | Retorna um identificador interno, limitado à apresentação, destinado ao uso por complementos ou outro código.<br/>            Como este valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado<br/>            como uma chave única persistente.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.office_interop_shape_id`](/slides/python-net/pt/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides.charts/chart/office_interop_shape_id/) | Retorna um identificador único limitado ao slide que permanece constante durante a vida útil da forma e<br/>            permite que o PowerPoint ou código interop faça referência confiável à forma de qualquer lugar no documento.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.unique_id`](/slides/python-net/pt/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pt/aspose.slides.charts/chart/alternative_text/) | Retorna ou define o texto alternativo associado a uma forma.<br/>            Leitura/gravação **str**. |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides.charts/chart/alternative_text_title/) | Retorna ou define o título do texto alternativo associado a uma forma.<br/>            Leitura/gravação **str**. |
| [`name`](/slides/python-net/pt/aspose.slides.charts/chart/name/) | Retorna ou define o nome de uma forma.<br/>            Deve não ser None. Use uma string vazia se necessário.<br/>            Leitura/gravação **str**. |
| [`is_decorative`](/slides/python-net/pt/aspose.slides.charts/chart/is_decorative/) | Obtém ou define a opção 'Marcar como decorativo'<br/>            Leitura/gravação **bool**. |
| [`shape_lock`](/slides/python-net/pt/aspose.slides.charts/chart/shape_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IGraphicalObjectLock`](/slides/python-net/pt/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pt/aspose.slides.charts/chart/is_grouped/) | Determina se a forma está agrupada.<br/>            Somente leitura **bool**. |
| [`parent_group`](/slides/python-net/pt/aspose.slides.charts/chart/parent_group/) | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna None.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/chart/slide/) | Retorna o slide pai de uma forma.<br/>            Somente leitura [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/chart/presentation/) | Retorna a apresentação pai de um slide.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pt/aspose.slides.charts/chart/graphical_object_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IGraphicalObjectLock`](/slides/python-net/pt/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/pt/aspose.slides.charts/chart/plot_visible_cells_only/) | Determina se apenas as células visíveis são plotadas. False para plotar tanto células visíveis quanto ocultas.<br/>            Leitura/gravação **bool**. |
| [`display_blanks_as`](/slides/python-net/pt/aspose.slides.charts/chart/display_blanks_as/) | Retorna ou define a forma de plotar células vazias em um gráfico.<br/>            Leitura/gravação [`DisplayBlanksAsType`](/slides/python-net/pt/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/pt/aspose.slides.charts/chart/chart_data/) | Retorna informações sobre os dados vinculados ou incorporados associados a um gráfico.<br/>            Somente leitura [`IChartData`](/slides/python-net/pt/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/pt/aspose.slides.charts/chart/has_title/) | Determina se um gráfico tem título visível.<br/>            Leitura/gravação **bool**. |
| [`chart_title`](/slides/python-net/pt/aspose.slides.charts/chart/chart_title/) | Retorna ou define o título do gráfico.<br/>            Somente leitura [`IChartTitle`](/slides/python-net/pt/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/pt/aspose.slides.charts/chart/has_data_table/) | Determina se um gráfico tem tabela de dados.<br/>            Leitura/gravação **bool**. |
| [`has_legend`](/slides/python-net/pt/aspose.slides.charts/chart/has_legend/) | Determina se um gráfico tem legenda.<br/>            Leitura/gravação **bool**. |
| [`legend`](/slides/python-net/pt/aspose.slides.charts/chart/legend/) | Retorna ou define uma legenda para um gráfico.<br/>            Somente leitura [`ILegend`](/slides/python-net/pt/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/pt/aspose.slides.charts/chart/chart_data_table/) | Retorna a tabela de dados de um gráfico.<br/>            Somente leitura [`IDataTable`](/slides/python-net/pt/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/pt/aspose.slides.charts/chart/style/) | Retorna ou define o estilo do gráfico.<br/>            Leitura/gravação [`StyleType`](/slides/python-net/pt/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/pt/aspose.slides.charts/chart/type/) | Retorna ou define o tipo de gráfico.<br/>            Leitura/gravação [`ChartType`](/slides/python-net/pt/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/pt/aspose.slides.charts/chart/plot_area/) | Representa a área de plotagem de um gráfico.<br/>            Somente leitura [`IChartPlotArea`](/slides/python-net/pt/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/pt/aspose.slides.charts/chart/rotation_3d/) | Retorna uma rotação 3D de um gráfico.<br/>            Somente leitura [`IRotation3D`](/slides/python-net/pt/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/pt/aspose.slides.charts/chart/back_wall/) | Retorna um objeto que permite alterar o formato da parede traseira de um gráfico 3D.<br/>            Somente leitura [`IChartWall`](/slides/python-net/pt/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/pt/aspose.slides.charts/chart/side_wall/) | Retorna um objeto que permite alterar o formato da parede lateral de um gráfico 3D.<br/>            Somente leitura [`IChartWall`](/slides/python-net/pt/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/pt/aspose.slides.charts/chart/floor/) | Retorna um objeto que permite alterar o formato do piso de um gráfico 3D.<br/>            Somente leitura [`IChartWall`](/slides/python-net/pt/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/pt/aspose.slides.charts/chart/text_format/) | Retorna o formato de texto do gráfico.<br/>            A propriedade não se aplica aos seguintes tipos: [`ChartType.TREEMAP`](/slides/python-net/pt/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/pt/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/pt/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/pt/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/pt/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/pt/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Somente leitura [`IChartTextFormat`](/slides/python-net/pt/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/pt/aspose.slides.charts/chart/theme_manager/) | Retorna o gerenciador de tema.<br/>            Somente leitura [`IOverrideThemeManager`](/slides/python-net/pt/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/pt/aspose.slides.charts/chart/user_shapes/) | Especifica as formas desenhadas sobre o gráfico.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/pt/aspose.slides.charts/chart/axes/) | Fornece acesso aos eixos do gráfico.<br/>            Somente leitura [`IAxesManager`](/slides/python-net/pt/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/pt/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Especifica que os rótulos de dados acima do máximo do gráfico deverão ser mostrados.<br/>            Leitura/gravação **bool**. |
| [`has_rounded_corners`](/slides/python-net/pt/aspose.slides.charts/chart/has_rounded_corners/) | Especifica que a área do gráfico deve ter cantos arredondados.<br/>            Leitura/gravação **bool**. |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/chart/chart/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides.charts/chart/get_image/#) | Retorna a miniatura da forma.<br/>            O tipo de limites ShapeThumbnailBounds.Shape para miniatura de forma é usado por padrão. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Retorna a miniatura da forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Salva o conteúdo da Forma como arquivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva o conteúdo da Forma como arquivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides.charts/chart/remove_placeholder/#) | Define que esta forma não é um placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides.charts/chart/get_base_placeholder/#) | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre de onde a forma atual é herdada).<br/>            None é retornado se a forma atual não for herdada. |
| [`get_visual_bounds(self)`](/slides/python-net/pt/aspose.slides.charts/chart/get_visual_bounds/#) | Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado. |
| [`validate_chart_layout(self)`](/slides/python-net/pt/aspose.slides.charts/chart/validate_chart_layout/#) | Calcula os valores reais dos elementos do gráfico. Os valores reais incluem a posição dos elementos que implementam a interface IActualLayout <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            e os valores reais dos eixos (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [`create_theme_effective(self)`](/slides/python-net/pt/aspose.slides.charts/chart/create_theme_effective/#) | Retorna um tema efetivo para este gráfico. |

### Ver também
* classe [`Chart`](/slides/python-net/pt/aspose.slides.charts/chart)
* classe [`GraphicalObject`](/slides/python-net/pt/aspose.slides/graphicalobject)
* classe [`Shape`](/slides/python-net/pt/aspose.slides/shape)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)