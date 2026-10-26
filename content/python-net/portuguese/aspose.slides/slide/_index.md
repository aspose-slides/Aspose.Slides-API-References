---
title: Slide class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/slide/
---
## Classe Slide

Representa um slide em uma apresentação.

**Inheritance:**[`Slide`](/slides/python-net/pt/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/pt/aspose.slides/baseslide)

O tipo Slide expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`shapes`](/slides/python-net/pt/aspose.slides/slide/shapes/) | Retorna as formas de um slide.<br/>            Somente leitura [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pt/aspose.slides/slide/controls/) | Retorna a coleção de controles ActiveX em um slide.<br/>            Somente leitura [`IControlCollection`](/slides/python-net/pt/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pt/aspose.slides/slide/name/) | Retorna ou define o nome de um slide.<br/>            Leitura/gravação **str**. |
| [`slide_id`](/slides/python-net/pt/aspose.slides/slide/slide_id/) | Retorna o ID de um slide.<br/>            Somente leitura **int**. |
| [`custom_data`](/slides/python-net/pt/aspose.slides/slide/custom_data/) | Retorna os dados personalizados do slide.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pt/aspose.slides/slide/timeline/) | Retorna o objeto da linha de tempo de animação.<br/>            Somente leitura [`IAnimationTimeLine`](/slides/python-net/pt/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pt/aspose.slides/slide/slide_show_transition/) | Retorna o objeto Transition que contém informações sobre<br/>            como o slide especificado avança durante a apresentação.<br/>            Somente leitura [`ISlideShowTransition`](/slides/python-net/pt/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pt/aspose.slides/slide/background/) | Retorna o plano de fundo do slide.<br/>            Somente leitura [`IBackground`](/slides/python-net/pt/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pt/aspose.slides/slide/hyperlink_queries/) | Fornece acesso fácil aos hyperlinks contidos.<br/>            Somente leitura [`IHyperlinkQueries`](/slides/python-net/pt/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pt/aspose.slides/slide/show_master_shapes/) | Especifica se as formas no slide mestre devem ser mostradas nos slides ou não.<br/>            Leitura/gravação **bool**. |
| [`presentation`](/slides/python-net/pt/aspose.slides/slide/presentation/) | Retorna a interface IPresentation.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/pt/aspose.slides/slide/header_footer_manager/) | Retorna o gerenciador HeaderFooter do slide.<br/>            Somente leitura [`ISlideHeaderFooterManager`](/slides/python-net/pt/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/pt/aspose.slides/slide/theme_manager/) | Retorna o gerenciador de tema de sobrescrita.<br/>            Somente leitura [`IOverrideThemeManager`](/slides/python-net/pt/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/pt/aspose.slides/slide/slide_number/) | Retorna o número de um slide.<br/>            O índice do slide na coleção [`Presentation.slides`](/slides/python-net/pt/aspose.slides/presentation/slides) é sempre igual a SlideNumber - Presentation.FirstSlideNumber.<br/>            Leitura/gravação **int**. |
| [`hidden`](/slides/python-net/pt/aspose.slides/slide/hidden/) | Determina se o slide especificado está oculto durante a apresentação.<br/>            Leitura/gravação **bool**. |
| [`layout_slide`](/slides/python-net/pt/aspose.slides/slide/layout_slide/) | Retorna ou define o layout do slide atual.<br/>            Leitura/gravação [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/pt/aspose.slides/slide/notes_slide_manager/) | Permite acessar o slide de notas, adicioná-lo e removê-lo.<br/>            Somente leitura [`INotesSlideManager`](/slides/python-net/pt/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/pt/aspose.slides/slide/slide/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pt/aspose.slides/slide/join_portions_with_same_formatting/#) | Une sequências com a mesma formatação em todos os parágrafos em todas as formas aceitáveis. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pt/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Une sequências com a mesma formatação em todos os parágrafos em todas as formas aceitáveis. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/slide/get_image/#float-float) | Retorna um objeto Thumbnail Image com dimensionamento personalizado. |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/slide/get_image/#) | Retorna um objeto Thumbnail Image (20% do tamanho real). |
| [`get_image(self, image_size)`](/slides/python-net/pt/aspose.slides/slide/get_image/#asposeslidessize) | Retorna um objeto Thumbnail Image com tamanho especificado. |
| [`get_image(self, options)`](/slides/python-net/pt/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Retorna um objeto de imagem tiff Thumbnail com parâmetros especificados. |
| [`get_image(self, options)`](/slides/python-net/pt/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Retorna um objeto Thumbnail Image. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Retorna um objeto Thumbnail Image com dimensionamento personalizado. |
| [`get_image(self, options, image_size)`](/slides/python-net/pt/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Retorna um objeto Thumbnail Image com tamanho especificado. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/slide/write_as_svg/#iorawiobase) | Salva o conteúdo do slide como um arquivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva o conteúdo do slide como um arquivo SVG. |
| [`equals(self, slide)`](/slides/python-net/pt/aspose.slides/slide/equals/#ibaseslide) | Determina se as duas instâncias de IBaseSlide são iguais.<br/>            O valor retornado é calculado com base na estrutura do slide e no conteúdo estático.<br/>            Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações etc. forem iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId, nem conteúdo dinâmico, como o valor da data atual em um Placeholder de Data. |
| [`create_theme_effective(self)`](/slides/python-net/pt/aspose.slides/slide/create_theme_effective/#) | Retorna um tema efetivo para este slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pt/aspose.slides/slide/find_shape_by_alt_text/#str) | Encontra a primeira ocorrência de uma forma com o texto alternativo especificado. |
| [`write_as_emf(self, stream)`](/slides/python-net/pt/aspose.slides/slide/write_as_emf/#iorawiobase) | Salva o conteúdo do slide como um arquivo EMF. |
| [`remove(self)`](/slides/python-net/pt/aspose.slides/slide/remove/#) | Remove o slide da apresentação. |
| [`reset(self)`](/slides/python-net/pt/aspose.slides/slide/reset/#) | Redefine a posição, tamanho e formatação de cada forma que possui um protótipo no LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/pt/aspose.slides/slide/get_slide_comments/#icommentauthor) | Retorna todos os comentários do slide adicionados por um autor específico. |

### Veja também
* classe [`BaseSlide`](/slides/python-net/pt/aspose.slides/baseslide)
* classe [`Slide`](/slides/python-net/pt/aspose.slides/slide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)