---
title: Table class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/table/
---
## classe Table

Representa uma tabela em um slide.

**Inheritance:**[`Table`](/slides/python-net/pt/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/pt/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pt/aspose.slides/shape)

O tipo Table expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides/table/is_text_holder/) | Determina se a forma é TextHolder_PPT.<br/>            Somente leitura **bool**. |
| [`placeholder`](/slides/python-net/pt/aspose.slides/table/placeholder/) | Retorna o placeholder de uma forma. Retorna None se a forma não tem placeholder.<br/>            Somente leitura [`IPlaceholder`](/slides/python-net/pt/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pt/aspose.slides/table/custom_data/) | Retorna os dados personalizados da forma.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pt/aspose.slides/table/raw_frame/) | Retorna ou define as propriedades da moldura bruta da forma.<br/>            Leitura/Gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pt/aspose.slides/table/frame/) | Retorna ou define as propriedades da moldura da forma.<br/>            Leitura/Gravação [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pt/aspose.slides/table/line_format/) | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não possuem propriedades de linha.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/table/three_d_format/) | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3d para uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não possuem propriedades 3d.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides/table/effect_format/) | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não possuem propriedades de efeito.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides/table/fill_format/) | Retorna um objeto TableFormat.FillFormat contendo a formatação de preenchimento para a Table.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/table/hyperlink_click/) | Retorna ou define o hyperlink definido para clique do mouse.<br/>            Leitura/Gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/table/hyperlink_mouse_over/) | Retorna ou define o hyperlink definido para passar o mouse sobre.<br/>            Leitura/Gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/table/hyperlink_manager/) | Retorna o gerenciador de hyperlinks.<br/>            Somente leitura [`IHyperlinkManager`](/slides/python-net/pt/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pt/aspose.slides/table/hidden/) | Determina se a forma está oculta.<br/>            Leitura/Gravação **bool**. |
| [`z_order_position`](/slides/python-net/pt/aspose.slides/table/z_order_position/) | Retorna a posição de uma forma na ordem z.<br/>            Shapes[0] retorna a forma no fundo da ordem z,<br/>            e Shapes[Shapes.Count - 1] retorna a forma na frente da ordem z.<br/>            Somente leitura **int**. |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides/table/connection_site_count/) | Retorna o número de pontos de conexão na forma.<br/>            Somente leitura **int**. |
| [`rotation`](/slides/python-net/pt/aspose.slides/table/rotation/) | Retorna ou define o número de graus que a forma especificada está rotacionada em torno do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário.<br/>            Leitura/Gravação **float**. |
| [`x`](/slides/python-net/pt/aspose.slides/table/x/) | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/Gravação **float**. |
| [`y`](/slides/python-net/pt/aspose.slides/table/y/) | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/Gravação **float**. |
| [`width`](/slides/python-net/pt/aspose.slides/table/width/) | Obtém ou define a largura da forma, medida em pontos.<br/>            Leitura/Gravação **float**. |
| [`height`](/slides/python-net/pt/aspose.slides/table/height/) | Obtém ou define a altura da forma, medida em pontos.<br/>            Leitura/Gravação **float**. |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides/table/black_white_mode/) | Propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco..<br/>            Leitura/Gravação [`BlackWhiteMode`](/slides/python-net/pt/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pt/aspose.slides/table/unique_id/) | Retorna um identificador interno, de escopo de apresentação, destinado ao uso por complementos ou outro código.<br/>            Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.office_interop_shape_id`](/slides/python-net/pt/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides/table/office_interop_shape_id/) | Retorna um identificador único de escopo de slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código interop referencie a forma de forma confiável a partir de qualquer lugar no documento.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.unique_id`](/slides/python-net/pt/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pt/aspose.slides/table/alternative_text/) | Retorna ou define o texto alternativo associado a uma forma.<br/>            Leitura/Gravação **str**. |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides/table/alternative_text_title/) | Retorna ou define o título do texto alternativo associado a uma forma.<br/>            Leitura/Gravação **str**. |
| [`name`](/slides/python-net/pt/aspose.slides/table/name/) | Retorna ou define o nome de uma forma.<br/>            Deve não ser None. Use string vazia se necessário.<br/>            Leitura/Gravação **str**. |
| [`is_decorative`](/slides/python-net/pt/aspose.slides/table/is_decorative/) | Obtém ou define a opção 'Marcar como decorativo'<br/>            Leitura/Gravação **bool**. |
| [`shape_lock`](/slides/python-net/pt/aspose.slides/table/shape_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IGraphicalObjectLock`](/slides/python-net/pt/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pt/aspose.slides/table/is_grouped/) | Determina se a forma está agrupada.<br/>            Somente leitura **bool**. |
| [`parent_group`](/slides/python-net/pt/aspose.slides/table/parent_group/) | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna None.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pt/aspose.slides/table/slide/) | Retorna o slide pai de uma forma.<br/>            Somente leitura [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pt/aspose.slides/table/presentation/) | Retorna a apresentação pai de um slide.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pt/aspose.slides/table/graphical_object_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IGraphicalObjectLock`](/slides/python-net/pt/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/pt/aspose.slides/table/rows/) | Retorna a coleção de linhas.<br/>            Somente leitura [`IRowCollection`](/slides/python-net/pt/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/pt/aspose.slides/table/columns/) | Retorna a coleção de colunas.<br/>            Somente leitura [`IColumnCollection`](/slides/python-net/pt/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/pt/aspose.slides/table/table_format/) | Retorna o objeto TableFormat que contém propriedades de formatação para esta tabela.<br/>            Somente leitura [`ITableFormat`](/slides/python-net/pt/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/pt/aspose.slides/table/style_preset/) | Obtém ou define o estilo de tabela interno.<br/>            Leitura/Gravação [`TableStylePreset`](/slides/python-net/pt/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/pt/aspose.slides/table/right_to_left/) | Determina se a tabela tem ordem de leitura da direita para a esquerda.<br/>            Leitura/Gravação **bool**. |
| [`first_row`](/slides/python-net/pt/aspose.slides/table/first_row/) | Determina se a primeira linha de uma tabela deve ser desenhada com formatação especial.<br/>            Leitura/Gravação **bool**. |
| [`first_col`](/slides/python-net/pt/aspose.slides/table/first_col/) | Determina se a primeira coluna de uma tabela deve ser desenhada com formatação especial.<br/>            Leitura/Gravação **bool**. |
| [`last_row`](/slides/python-net/pt/aspose.slides/table/last_row/) | Determina se a última linha de uma tabela deve ser desenhada com formatação especial.<br/>            Leitura/Gravação **bool**. |
| [`last_col`](/slides/python-net/pt/aspose.slides/table/last_col/) | Determina se a última coluna de uma tabela deve ser desenhada com formatação especial.<br/>            Leitura/Gravação **bool**. |
| [`horizontal_banding`](/slides/python-net/pt/aspose.slides/table/horizontal_banding/) | Determina se as linhas pares devem ser desenhadas com formatação diferente.<br/>            Leitura/Gravação **bool**. |
| [`vertical_banding`](/slides/python-net/pt/aspose.slides/table/vertical_banding/) | Determina se as colunas pares devem ser desenhadas com formatação diferente.<br/>            Leitura/Gravação **bool**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/table/get_image/#) | Retorna a miniatura da forma.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type é usado por padrão. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Retorna a miniatura da forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/table/write_as_svg/#iorawiobase) | Salva o conteúdo da Shape como arquivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva o conteúdo da Shape como arquivo SVG. |
| [`set_text_format(self, source)`](/slides/python-net/pt/aspose.slides/table/set_text_format/#iportionformat) | Define propriedades de formato de porção definidas para todas as porções de células da tabela. |
| [`set_text_format(self, source)`](/slides/python-net/pt/aspose.slides/table/set_text_format/#iparagraphformat) | Define propriedades de formato de parágrafo definidas para todos os parágrafos das células da tabela. |
| [`set_text_format(self, source)`](/slides/python-net/pt/aspose.slides/table/set_text_format/#itextframeformat) | Define propriedades de formato de quadro de texto definidas para todos os quadros de texto das células da tabela. |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides/table/remove_placeholder/#) | Define que esta forma não é um placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides/table/add_placeholder/#iplaceholder) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides/table/get_base_placeholder/#) | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada).<br/>            Retorna None se a forma atual não for herdada. |
| [`get_visual_bounds(self)`](/slides/python-net/pt/aspose.slides/table/get_visual_bounds/#) | Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/pt/aspose.slides/table/merge_cells/#icell-icell-bool) | Mescla células vizinhas. |

### Veja Também
* classe [`GraphicalObject`](/slides/python-net/pt/aspose.slides/graphicalobject)
* classe [`Shape`](/slides/python-net/pt/aspose.slides/shape)
* classe [`Table`](/slides/python-net/pt/aspose.slides/table)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)