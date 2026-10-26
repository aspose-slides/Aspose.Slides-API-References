---
title: SlideUtil class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.util/slideutil/
---
## SlideUtil classe

Oferece métodos que ajudam a pesquisar formas e texto em uma apresentação.

O tipo SlideUtil expõe os seguintes membros:

## Métodos

| Método | Descrição |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/pt/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | Localiza forma por texto alternativo em uma apresentação PPTX. |
| [`find_shape(slide, alt_text)`](/slides/python-net/pt/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | Localiza forma por texto alternativo em um slide de uma apresentação PPTX. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/pt/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | Altera a posição de todas as formas no slide. Alinha as formas às margens ou à borda do slide<br/>            ou as alinha em relação umas às outras. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/pt/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | Altera a posição das formas selecionadas no slide. Alinha as formas às margens ou à borda do slide<br/>             ou as alinha em relação umas às outras. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/pt/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | Altera a posição de todas as formas dentro de um grupo de formas. Alinha as formas às margens ou à borda do slide<br/>            ou as alinha em relação umas às outras. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/pt/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | Altera a posição das formas selecionadas dentro de um grupo de formas. Alinha as formas às margens ou à borda do slide<br/>            ou as alinha em relação umas às outras. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/pt/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | Procura todas as formas no slide especificado que correspondam ao tipo de marcador fornecido. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/pt/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | Encontra e substitui texto na apresentação com o formato fornecido |
| [`get_all_text_boxes(slide)`](/slides/python-net/pt/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | Retorna todos os quadros de texto em um slide de uma apresentação PPTX. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/pt/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | Retorna todos os quadros de texto no slide especificado que contêm o texto fornecido. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/pt/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | Retorna todos os quadros de texto em uma apresentação PPTX. |
| [`to_save_format(format)`](/slides/python-net/pt/aspose.slides.util/slideutil/to_save_format/#sourceformat) | Converte o formato de arquivo de origem para o correspondente [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat). |

### Veja Também
* módulo [`aspose.slides.util`](/slides/python-net/pt/aspose.slides.util)
* biblioteca [`Aspose.Slides`](/slides/python-net)