---
title: OleObjectFrame class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/oleobjectframe/
---
## OleObjectFrame classe

Representa um objeto OLE em um slide.

**Inheritance:**[`OleObjectFrame`](/slides/python-net/pt/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/pt/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/pt/aspose.slides/shape)

O tipo OleObjectFrame expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides/oleobjectframe/is_text_holder/) | Determina se a forma é TextHolder_PPT.<br/>            Somente leitura **bool**. |
| [`placeholder`](/slides/python-net/pt/aspose.slides/oleobjectframe/placeholder/) | Retorna o placeholder de uma forma. Retorna None se a forma não tem placeholder.<br/>            Somente leitura [`IPlaceholder`](/slides/python-net/pt/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/pt/aspose.slides/oleobjectframe/custom_data/) | Retorna os dados personalizados da forma.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/pt/aspose.slides/oleobjectframe/raw_frame/) | Retorna ou define as propriedades brutas da moldura da forma.<br/>            Leitura/Escrita [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/pt/aspose.slides/oleobjectframe/frame/) | Retorna ou define as propriedades da moldura da forma.<br/>            Leitura/Escrita [`IShapeFrame`](/slides/python-net/pt/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/pt/aspose.slides/oleobjectframe/line_format/) | Retorna o objeto LineFormat que contém as propriedades de formatação de linha para uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não têm propriedades de linha.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/oleobjectframe/three_d_format/) | Retorna o objeto ThreeDFormat que contém as propriedades de efeito 3D para uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não têm propriedades 3D.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides/oleobjectframe/effect_format/) | Retorna o objeto EffectFormat que contém os efeitos de pixel aplicados a uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não têm propriedades de efeito.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides/oleobjectframe/fill_format/) | Retorna o objeto FillFormat que contém as propriedades de formatação de preenchimento para uma forma.<br/>            Nota: pode retornar None para certos tipos de formas que não têm propriedades de preenchimento.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/oleobjectframe/hyperlink_click/) | Retorna ou define o hyperlink definido para clique do mouse.<br/>            Leitura/Escrita [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Retorna ou define o hyperlink definido para passar o mouse sobre.<br/>            Leitura/Escrita [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/oleobjectframe/hyperlink_manager/) | Retorna o gerenciador de hyperlink.<br/>            Somente leitura [`IHyperlinkManager`](/slides/python-net/pt/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/pt/aspose.slides/oleobjectframe/hidden/) | Determina se a forma está oculta.<br/>            Leitura/Escrita **bool**. |
| [`z_order_position`](/slides/python-net/pt/aspose.slides/oleobjectframe/z_order_position/) | Retorna a posição de uma forma na ordem Z.<br/>            Shapes[0] retorna a forma mais ao fundo da ordem Z,<br/>            e Shapes[Shapes.Count - 1] retorna a forma mais ao frente da ordem Z.<br/>            Somente leitura **int**. |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides/oleobjectframe/connection_site_count/) | Retorna o número de pontos de conexão na forma.<br/>            Somente leitura **int**. |
| [`rotation`](/slides/python-net/pt/aspose.slides/oleobjectframe/rotation/) | Retorna ou define o número de graus que a forma especificada é rotacionada ao redor do eixo Z.<br/>            Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário.<br/>            Leitura/Escrita **float**. |
| [`x`](/slides/python-net/pt/aspose.slides/oleobjectframe/x/) | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/Escrita **float**. |
| [`y`](/slides/python-net/pt/aspose.slides/oleobjectframe/y/) | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos.<br/>            Leitura/Escrita **float**. |
| [`width`](/slides/python-net/pt/aspose.slides/oleobjectframe/width/) | Obtém ou define a largura da forma, medida em pontos.<br/>            Leitura/Escrita **float**. |
| [`height`](/slides/python-net/pt/aspose.slides/oleobjectframe/height/) | Obtém ou define a altura da forma, medida em pontos.<br/>            Leitura/Escrita **float**. |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides/oleobjectframe/black_white_mode/) | Propriedade que especifica como uma forma será renderizada no modo de exibição em preto e branco.<br/>            Leitura/Escrita [`BlackWhiteMode`](/slides/python-net/pt/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/pt/aspose.slides/oleobjectframe/unique_id/) | Retorna um identificador interno, com escopo de apresentação, destinado ao uso por complementos ou outro código.<br/>            Como este valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado<br/>            como uma chave única persistente.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.office_interop_shape_id`](/slides/python-net/pt/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides/oleobjectframe/office_interop_shape_id/) | Retorna um identificador único com escopo de slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código interop referencie a forma de forma confiável a partir de qualquer ponto no documento.<br/>            Somente leitura **int**.<br/>            Veja também [`Shape.unique_id`](/slides/python-net/pt/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/pt/aspose.slides/oleobjectframe/alternative_text/) | Retorna ou define o texto alternativo associado a uma forma.<br/>            Leitura/Escrita **str**. |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides/oleobjectframe/alternative_text_title/) | Retorna ou define o título do texto alternativo associado a uma forma.<br/>            Leitura/Escrita **str**. |
| [`name`](/slides/python-net/pt/aspose.slides/oleobjectframe/name/) | Retorna ou define o nome de uma forma.<br/>            Não pode ser None. Use uma string vazia se necessário.<br/>            Leitura/Escrita **str**. |
| [`is_decorative`](/slides/python-net/pt/aspose.slides/oleobjectframe/is_decorative/) | Obtém ou define a opção 'Marcar como decorativo'<br/>            Leitura/Escrita **bool**. |
| [`shape_lock`](/slides/python-net/pt/aspose.slides/oleobjectframe/shape_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IGraphicalObjectLock`](/slides/python-net/pt/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/pt/aspose.slides/oleobjectframe/is_grouped/) | Determina se a forma está agrupada.<br/>            Somente leitura **bool**. |
| [`parent_group`](/slides/python-net/pt/aspose.slides/oleobjectframe/parent_group/) | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna None.<br/>            Somente leitura [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/pt/aspose.slides/oleobjectframe/slide/) | Retorna o slide pai de uma forma.<br/>            Somente leitura [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pt/aspose.slides/oleobjectframe/presentation/) | Retorna a apresentação pai de um slide.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/pt/aspose.slides/oleobjectframe/graphical_object_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IGraphicalObjectLock`](/slides/python-net/pt/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/pt/aspose.slides/oleobjectframe/substitute_picture_format/) | Retorna o objeto de propriedades de preenchimento de imagem OleObject.<br/>            Somente leitura [`IPictureFillFormat`](/slides/python-net/pt/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/pt/aspose.slides/oleobjectframe/substitute_picture_title/) | Retorna ou define o título do ícone OleObject.<br/>            Leitura/Escrita **str**. |
| [`object_name`](/slides/python-net/pt/aspose.slides/oleobjectframe/object_name/) | Retorna ou define o nome de um objeto.<br/>            Leitura/Escrita **str**. |
| [`object_prog_id`](/slides/python-net/pt/aspose.slides/oleobjectframe/object_prog_id/) | Retorna o ProgID de um objeto.<br/>            Somente leitura **str**. |
| [`link_file_name`](/slides/python-net/pt/aspose.slides/oleobjectframe/link_file_name/) | Retorna o caminho completo para um arquivo vinculado. O nome de arquivo curto será usado.<br/>            Somente leitura **str**. |
| [`link_path_long`](/slides/python-net/pt/aspose.slides/oleobjectframe/link_path_long/) | Retorna o caminho completo para um arquivo vinculado. O nome de arquivo longo será usado.<br/>            Leitura/Escrita **str**. |
| [`link_path_relative`](/slides/python-net/pt/aspose.slides/oleobjectframe/link_path_relative/) | Retorna o caminho relativo para um arquivo vinculado, se presente, caso contrário retorna uma string vazia.<br/>             Somente leitura **str**. |
| [`embedded_file_label`](/slides/python-net/pt/aspose.slides/oleobjectframe/embedded_file_label/) | Retorna o nome de arquivo do objeto OLE incorporado |
| [`embedded_file_name`](/slides/python-net/pt/aspose.slides/oleobjectframe/embedded_file_name/) | Retorna o caminho do objeto OLE incorporado |
| [`embedded_data`](/slides/python-net/pt/aspose.slides/oleobjectframe/embedded_data/) | Obtém ou define informações sobre dados OLE incorporados.<br/>            Leitura/Escrita [`IOleEmbeddedDataInfo`](/slides/python-net/pt/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/pt/aspose.slides/oleobjectframe/is_object_icon/) | Determina se um objeto é visível como ícone.<br/>            Leitura/Escrita **bool**. |
| [`is_object_link`](/slides/python-net/pt/aspose.slides/oleobjectframe/is_object_link/) | Determina se um objeto está vinculado a um arquivo externo.<br/>            Somente leitura **bool**. |
| [`update_automatic`](/slides/python-net/pt/aspose.slides/oleobjectframe/update_automatic/) | Determina se o objeto incorporado vinculado é atualizado automaticamente quando a apresentação é aberta ou impressa.<br/>            Leitura/Escrita **bool**. |

## Métodos

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/oleobjectframe/get_image/#) | Retorna a miniatura da forma.<br/>            O tipo ShapeThumbnailBounds.Shape de limites da miniatura da forma é usado por padrão. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Retorna a miniatura da forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Salva o conteúdo da Forma como arquivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva o conteúdo da Forma como arquivo SVG. |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides/oleobjectframe/remove_placeholder/#) | Define que esta forma não é um placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides/oleobjectframe/get_base_placeholder/#) | Retorna uma forma placeholder básica (forma do layout e/ou do slide mestre da qual a forma atual é herdada).<br/>            Retorna None se a forma atual não for herdada. |
| [`get_visual_bounds(self)`](/slides/python-net/pt/aspose.slides/oleobjectframe/get_visual_bounds/#) | Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/pt/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Define informações sobre dados OLE incorporados.<br/>            <br/>            Este método altera as propriedades do objeto para refletir os novos dados e <br/>            define a flag IsObjectLink como false, indicando que o objeto OLE está incorporado. |

### Veja Também
* classe [`GraphicalObject`](/slides/python-net/pt/aspose.slides/graphicalobject)
* classe [`OleObjectFrame`](/slides/python-net/pt/aspose.slides/oleobjectframe)
* classe [`Shape`](/slides/python-net/pt/aspose.slides/shape)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)