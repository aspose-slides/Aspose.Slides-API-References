---
title: IMasterSlide class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/imasterslide/
---
## IMasterSlide classe

Representa um slide mestre em uma apresentação.

O tipo IMasterSlide expõe os seguintes membros:

## Propriedades

| Property | Descrição |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/pt/aspose.slides/imasterslide/header_footer_manager/) | Retorna o gerenciador HeaderFooter do slide mestre.<br/>            Somente leitura [`IMasterSlideHeaderFooterManager`](/slides/python-net/pt/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/pt/aspose.slides/imasterslide/title_style/) | Retorna o estilo de um texto de título.<br/>            Somente leitura [`ITextStyle`](/slides/python-net/pt/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/pt/aspose.slides/imasterslide/body_style/) | Retorna o estilo de um texto de corpo.<br/>            Somente leitura [`ITextStyle`](/slides/python-net/pt/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/pt/aspose.slides/imasterslide/other_style/) | Retorna o estilo de outro texto.<br/>            Somente leitura [`ITextStyle`](/slides/python-net/pt/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/pt/aspose.slides/imasterslide/layout_slides/) | Retorna a coleção de slides de layout filho para este slide mestre.<br/>            Somente leitura [`IMasterLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/pt/aspose.slides/imasterslide/preserve/) | Determina se o mestre correspondente é excluído quando todos os<br/>            slides que seguem esse mestre são excluídos.<br/>            Observação: Aspose.Slides nunca removerá nenhum mestre não usado por conta própria,<br/>            para realmente remover mestres não usados chame **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            Leitura/gravação **bool**. |
| [`has_depending_slides`](/slides/python-net/pt/aspose.slides/imasterslide/has_depending_slides/) | Retorna true se existir ao menos um slide que dependa deste slide mestre.<br/>            Somente leitura **bool**. |
| [`drawing_guides`](/slides/python-net/pt/aspose.slides/imasterslide/drawing_guides/) | Retorna uma coleção de guias de desenho para o slide mestre.<br/>            Somente leitura [`IDrawingGuidesCollection`](/slides/python-net/pt/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/pt/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/pt/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/pt/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/pt/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/pt/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/pt/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/pt/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/pt/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/pt/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/pt/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/pt/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/pt/aspose.slides/imasterslide/theme_manager/) |  |

## Métodos

| Method | Descrição |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/pt/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Cria um novo slide mestre baseado no atual, aplicando um tema externo a ele e aplica o slide mestre criado a todos os slides dependentes. |
| [`get_depending_slides(self)`](/slides/python-net/pt/aspose.slides/imasterslide/get_depending_slides/#) | Retorna um array com todos os slides que dependem deste slide mestre. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pt/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pt/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/pt/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/pt/aspose.slides/imasterslide/create_theme_effective/#) |  |

### Veja Também
* module [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)