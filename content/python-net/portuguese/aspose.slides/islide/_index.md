---
title: ISlide class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/islide/
---
## classe ISlide

Representa um slide em uma apresentação.

O tipo ISlide expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/pt/aspose.slides/islide/header_footer_manager/) | Retorna o gerenciador HeaderFooter do slide.<br/>            Somente leitura [`ISlideHeaderFooterManager`](/slides/python-net/pt/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/pt/aspose.slides/islide/slide_number/) | Retorna um número de slide.<br/>            O índice do slide na coleção [`IPresentation.slides`](/slides/python-net/pt/aspose.slides/ipresentation/slides) é sempre igual a SlideNumber - 1.<br/>            Leitura/gravação **int**. |
| [`hidden`](/slides/python-net/pt/aspose.slides/islide/hidden/) | Determina se o slide especificado está oculto durante uma apresentação de slides.<br/>            Leitura/gravação **bool**. |
| [`layout_slide`](/slides/python-net/pt/aspose.slides/islide/layout_slide/) | Retorna ou define o slide de layout para o slide atual.<br/>            Leitura/gravação [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/pt/aspose.slides/islide/notes_slide_manager/) | Permite acessar o slide de notas, adicioná-lo e removê-lo.<br/>            Somente leitura [`INotesSlideManager`](/slides/python-net/pt/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/pt/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/pt/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/pt/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/pt/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/pt/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/pt/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/pt/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/pt/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/pt/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/pt/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/pt/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/pt/aspose.slides/islide/theme_manager/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/islide/get_image/#float-float) | Retorna um objeto de imagem com escala personalizada. |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/islide/get_image/#) | Retorna um objeto Thumbnail Image (20% do tamanho real). |
| [`get_image(self, image_size)`](/slides/python-net/pt/aspose.slides/islide/get_image/#asposeslidessize) | Retorna um objeto de imagem com tamanho especificado. |
| [`get_image(self, options)`](/slides/python-net/pt/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Retorna um objeto bitmap tiff Thumbnail com parâmetros especificados. |
| [`get_image(self, options)`](/slides/python-net/pt/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Retorna um objeto Thumbnail Bitmap. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Retorna um objeto Thumbnail Bitmap com escala personalizada. |
| [`get_image(self, options, image_size)`](/slides/python-net/pt/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Retorna um objeto Thumbnail Bitmap com tamanho especificado. |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/islide/write_as_svg/#iorawiobase) | Salva o conteúdo do slide como um arquivo SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva o conteúdo do slide como um arquivo SVG. |
| [`get_slide_comments(self, author)`](/slides/python-net/pt/aspose.slides/islide/get_slide_comments/#icommentauthor) | Retorna todos os comentários do slide adicionados por um autor específico. |
| [`write_as_emf(self, stream)`](/slides/python-net/pt/aspose.slides/islide/write_as_emf/#iorawiobase) | Salva o conteúdo do slide como um arquivo EMF. |
| [`remove(self)`](/slides/python-net/pt/aspose.slides/islide/remove/#) | Remove o slide da apresentação. |
| [`reset(self)`](/slides/python-net/pt/aspose.slides/islide/reset/#) | Redefine a posição, tamanho e formatação de cada forma que tem um protótipo no LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pt/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pt/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/pt/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/pt/aspose.slides/islide/create_theme_effective/#) |  |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)