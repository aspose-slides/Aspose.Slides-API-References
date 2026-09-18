---
title: LayoutSlide class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/layoutslide/
---
## Classe LayoutSlide

Representa um slide de layout.

**Inheritance:**[`LayoutSlide`](/slides/python-net/pt/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/pt/aspose.slides/baseslide)

O tipo LayoutSlide expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/pt/aspose.slides/layoutslide/shapes/) | Retorna as formas de um slide.<br/>            Somente leitura [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pt/aspose.slides/layoutslide/controls/) | Retorna a coleção de controles ActiveX em um slide.<br/>            Somente leitura [`IControlCollection`](/slides/python-net/pt/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pt/aspose.slides/layoutslide/name/) | Retorna ou define o nome de um slide.<br/>            Leitura/gravação **str**. |
| [`slide_id`](/slides/python-net/pt/aspose.slides/layoutslide/slide_id/) | Retorna o ID de um slide.<br/>            Somente leitura **int**. |
| [`custom_data`](/slides/python-net/pt/aspose.slides/layoutslide/custom_data/) | Retorna os dados personalizados do slide.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pt/aspose.slides/layoutslide/timeline/) | Retorna o objeto da linha do tempo de animação.<br/>            Somente leitura [`IAnimationTimeLine`](/slides/python-net/pt/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pt/aspose.slides/layoutslide/slide_show_transition/) | Retorna o objeto Transition que contém informações sobre<br/>            como o slide especificado avança durante a apresentação.<br/>            Somente leitura [`ISlideShowTransition`](/slides/python-net/pt/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pt/aspose.slides/layoutslide/background/) | Retorna o plano de fundo do slide.<br/>            Somente leitura [`IBackground`](/slides/python-net/pt/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pt/aspose.slides/layoutslide/hyperlink_queries/) | Fornece acesso fácil a hiperlinks contidos.<br/>            Somente leitura [`IHyperlinkQueries`](/slides/python-net/pt/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pt/aspose.slides/layoutslide/show_master_shapes/) | Especifica se as formas no slide mestre devem ser mostradas nos slides ou não.<br/>            Leitura/gravação **bool**. |
| [`presentation`](/slides/python-net/pt/aspose.slides/layoutslide/presentation/) | Retorna a interface IPresentation.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/pt/aspose.slides/layoutslide/header_footer_manager/) | Retorna o gerenciador HeaderFooter do slide de layout.<br/>            Somente leitura [`ILayoutSlideHeaderFooterManager`](/slides/python-net/pt/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/pt/aspose.slides/layoutslide/placeholder_manager/) | Retorna o gerenciador de espaços reservados do slide de layout.<br/>            Somente leitura [`ILayoutPlaceholderManager`](/slides/python-net/pt/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/pt/aspose.slides/layoutslide/master_slide/) | Retorna ou define o slide mestre para um layout.<br/>            Leitura/gravação [`IMasterSlide`](/slides/python-net/pt/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/pt/aspose.slides/layoutslide/theme_manager/) | Retorna o gerenciador de tema sobrescrito.<br/>            Somente leitura [`IOverrideThemeManager`](/slides/python-net/pt/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/pt/aspose.slides/layoutslide/layout_type/) | Retorna o tipo de layout deste slide de layout.<br/>            Somente leitura [`SlideLayoutType`](/slides/python-net/pt/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/pt/aspose.slides/layoutslide/has_depending_slides/) | Retorna verdadeiro se existir ao menos um slide que dependa deste slide de layout.<br/>            Somente leitura **bool**. |
| [`drawing_guides`](/slides/python-net/pt/aspose.slides/layoutslide/drawing_guides/) | Retorna uma coleção de guias de desenho para o slide de layout.<br/>            Somente leitura [`IDrawingGuidesCollection`](/slides/python-net/pt/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/pt/aspose.slides/layoutslide/slide/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pt/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Mescla sequências com a mesma formatação em todos os parágrafos de todas as formas aceitáveis. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pt/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Mescla sequências com a mesma formatação em todos os parágrafos de todas as formas aceitáveis. |
| [`equals(self, slide)`](/slides/python-net/pt/aspose.slides/layoutslide/equals/#ibaseslide) | Determina se duas instâncias de IBaseSlide são iguais.<br/>            O valor retornado é calculado com base na estrutura do slide e no conteúdo estático.<br/>            Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., forem iguais. A comparação não considera valores de identificadores únicos, como SlideId, nem conteúdo dinâmico, como o valor da data atual em um placeholder de Data. |
| [`create_theme_effective(self)`](/slides/python-net/pt/aspose.slides/layoutslide/create_theme_effective/#) | Retorna um tema efetivo para este slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pt/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Encontra a primeira ocorrência de uma forma com o texto alternativo especificado. |
| [`remove(self)`](/slides/python-net/pt/aspose.slides/layoutslide/remove/#) | Remove o layout da apresentação. |
| [`get_depending_slides(self)`](/slides/python-net/pt/aspose.slides/layoutslide/get_depending_slides/#) | Retorna um array com todos os slides que dependem deste slide de layout. |


### Ver Também
* classe [`BaseSlide`](/slides/python-net/pt/aspose.slides/baseslide)
* classe [`LayoutSlide`](/slides/python-net/pt/aspose.slides/layoutslide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)