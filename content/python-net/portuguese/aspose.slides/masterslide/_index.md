---
title: MasterSlide class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/masterslide/
---
## MasterSlide classe

Representa um slide mestre em uma apresentação.

**Herança:**[`MasterSlide`](/slides/python-net/pt/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/pt/aspose.slides/baseslide)

O tipo MasterSlide expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`shapes`](/slides/python-net/pt/aspose.slides/masterslide/shapes/) | Retorna as formas de um slide.<br/>            Somente leitura [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pt/aspose.slides/masterslide/controls/) | Retorna a coleção de controles ActiveX em um slide.<br/>            Somente leitura [`IControlCollection`](/slides/python-net/pt/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pt/aspose.slides/masterslide/name/) | Retorna ou define o nome de um slide mestre.<br/>            Leitura/gravação **str**. |
| [`slide_id`](/slides/python-net/pt/aspose.slides/masterslide/slide_id/) | Retorna o ID de um slide.<br/>            Somente leitura **int**. |
| [`custom_data`](/slides/python-net/pt/aspose.slides/masterslide/custom_data/) | Retorna os dados personalizados do slide.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pt/aspose.slides/masterslide/timeline/) | Retorna o objeto da linha do tempo de animação.<br/>            Somente leitura [`IAnimationTimeLine`](/slides/python-net/pt/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pt/aspose.slides/masterslide/slide_show_transition/) | Retorna o objeto Transition que contém informações sobre<br/>            como o slide especificado avança durante a apresentação.<br/>            Somente leitura [`ISlideShowTransition`](/slides/python-net/pt/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pt/aspose.slides/masterslide/background/) | Retorna o plano de fundo do slide.<br/>            Somente leitura [`IBackground`](/slides/python-net/pt/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pt/aspose.slides/masterslide/hyperlink_queries/) | Fornece fácil acesso aos hyperlinks contidos.<br/>            Somente leitura [`IHyperlinkQueries`](/slides/python-net/pt/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pt/aspose.slides/masterslide/show_master_shapes/) | Especifica se as formas no slide mestre devem ser mostradas nos slides ou não.<br/>            Para o próprio slide mestre esta propriedade sempre retorna `false`.<br/>            Leitura/gravação **bool**. |
| [`presentation`](/slides/python-net/pt/aspose.slides/masterslide/presentation/) | Retorna a interface IPresentation.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/pt/aspose.slides/masterslide/header_footer_manager/) | Retorna o gerenciador HeaderFooter do slide mestre.<br/>            Somente leitura [`IMasterSlideHeaderFooterManager`](/slides/python-net/pt/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/pt/aspose.slides/masterslide/title_style/) | Retorna o estilo do texto de título.<br/>            Somente leitura [`ITextStyle`](/slides/python-net/pt/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/pt/aspose.slides/masterslide/body_style/) | Retorna o estilo do texto do corpo.<br/>            Somente leitura [`ITextStyle`](/slides/python-net/pt/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/pt/aspose.slides/masterslide/other_style/) | Retorna o estilo de outro texto.<br/>            Somente leitura [`ITextStyle`](/slides/python-net/pt/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/pt/aspose.slides/masterslide/layout_slides/) | Retorna a coleção de slides de layout filho para este slide mestre.<br/>            Somente leitura [`IMasterLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/pt/aspose.slides/masterslide/preserve/) | Determina se o mestre correspondente é excluído quando todos os slides que seguem esse mestre são excluídos.<br/>            Observação: Aspose.Slides nunca removerá um mestre não usado por conta própria; para remover mestres não usados, chame **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            Leitura/gravação **bool**. |
| [`has_depending_slides`](/slides/python-net/pt/aspose.slides/masterslide/has_depending_slides/) | Retorna verdadeiro se existir ao menos um slide que dependa deste slide mestre.<br/>            Somente leitura **bool**. |
| [`theme_manager`](/slides/python-net/pt/aspose.slides/masterslide/theme_manager/) | Retorna o gerenciador de tema.<br/>            Somente leitura [`IMasterThemeManager`](/slides/python-net/pt/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/pt/aspose.slides/masterslide/drawing_guides/) | Retorna uma coleção de guias de desenho para o slide mestre.<br/>            Somente leitura [`IDrawingGuidesCollection`](/slides/python-net/pt/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/pt/aspose.slides/masterslide/slide/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pt/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Une execuções com a mesma formatação em todos os parágrafos de todas as formas aceitáveis. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pt/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Une execuções com a mesma formatação em todos os parágrafos em todas as formas aceitáveis. |
| [`equals(self, slide)`](/slides/python-net/pt/aspose.slides/masterslide/equals/#ibaseslide) | Determina se as duas instâncias IBaseSlide são iguais.<br/>            O valor retornado é calculado com base na estrutura do slide e no conteúdo estático.<br/>            Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., forem iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo o valor da data atual no Marcador de Data. |
| [`create_theme_effective(self)`](/slides/python-net/pt/aspose.slides/masterslide/create_theme_effective/#) | Retorna um tema efetivo para este slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pt/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Encontra a primeira ocorrência de uma forma com o texto alternativo especificado. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/pt/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Cria um novo slide mestre com base no atual, aplicando um tema externo a ele e aplica o slide mestre criado a todos os slides dependentes. |
| [`get_depending_slides(self)`](/slides/python-net/pt/aspose.slides/masterslide/get_depending_slides/#) | Retorna um array com todos os slides que dependem deste slide mestre. |

### Veja Também
* classe [`BaseSlide`](/slides/python-net/pt/aspose.slides/baseslide)
* classe [`MasterSlide`](/slides/python-net/pt/aspose.slides/masterslide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)