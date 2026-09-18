---
title: MasterHandoutSlide class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide classe

Representa o slide mestre para folhetos.

**Herança:**[`MasterHandoutSlide`](/slides/python-net/pt/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/pt/aspose.slides/baseslide)

O tipo MasterHandoutSlide expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`shapes`](/slides/python-net/pt/aspose.slides/masterhandoutslide/shapes/) | Retorna as formas de um slide.<br/>            Somente leitura [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pt/aspose.slides/masterhandoutslide/controls/) | Retorna a coleção de controles ActiveX em um slide.<br/>            Somente leitura [`IControlCollection`](/slides/python-net/pt/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pt/aspose.slides/masterhandoutslide/name/) | Retorna ou define o nome de um slide.<br/>            Leitura/gravação **str**. |
| [`slide_id`](/slides/python-net/pt/aspose.slides/masterhandoutslide/slide_id/) | Retorna o ID de um slide.<br/>            Somente leitura **int**. |
| [`custom_data`](/slides/python-net/pt/aspose.slides/masterhandoutslide/custom_data/) | Retorna os dados personalizados do slide.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pt/aspose.slides/masterhandoutslide/timeline/) | Retorna o objeto da linha de tempo de animação.<br/>            Somente leitura [`IAnimationTimeLine`](/slides/python-net/pt/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pt/aspose.slides/masterhandoutslide/slide_show_transition/) | Retorna o objeto Transition que contém informações sobre<br/>            como o slide especificado avança durante a apresentação.<br/>            Somente leitura [`ISlideShowTransition`](/slides/python-net/pt/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pt/aspose.slides/masterhandoutslide/background/) | Retorna o plano de fundo do slide.<br/>            Somente leitura [`IBackground`](/slides/python-net/pt/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pt/aspose.slides/masterhandoutslide/hyperlink_queries/) | Fornece acesso fácil aos hiperlinks contidos.<br/>            Somente leitura [`IHyperlinkQueries`](/slides/python-net/pt/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pt/aspose.slides/masterhandoutslide/show_master_shapes/) | Especifica se as formas no slide mestre devem ser mostradas nos slides ou não.<br/>            Para o próprio slide mestre, esta propriedade sempre retorna `false`.<br/>            Leitura/gravação **bool**. |
| [`presentation`](/slides/python-net/pt/aspose.slides/masterhandoutslide/presentation/) | Retorna a interface IPresentation.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/pt/aspose.slides/masterhandoutslide/header_footer_manager/) | Retorna o gerenciador HeaderFooter do slide mestre de folhetos.<br/>            Somente leitura [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/pt/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/pt/aspose.slides/masterhandoutslide/theme_manager/) | Retorna o gerenciador de temas.<br/>            Somente leitura [`IMasterThemeManager`](/slides/python-net/pt/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/pt/aspose.slides/masterhandoutslide/drawing_guides/) | Retorna uma coleção de guias de desenho para o slide mestre de folhetos.<br/>            Somente leitura [`IDrawingGuidesCollection`](/slides/python-net/pt/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/pt/aspose.slides/masterhandoutslide/slide/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pt/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Une sequências com a mesma formatação em todos os parágrafos e em todas as formas aceitáveis. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pt/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Une sequências com a mesma formatação em todos os parágrafos e em todas as formas aceitáveis. |
| [`equals(self, slide)`](/slides/python-net/pt/aspose.slides/masterhandoutslide/equals/#ibaseslide) | Determina se as duas instâncias IBaseSlide são iguais.<br/>            O valor retornado é calculado com base na estrutura do slide e no conteúdo estático.<br/>            Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., forem iguais. A comparação não considera valores de identificadores únicos, como SlideId, nem conteúdo dinâmico, como o valor da data atual em um Placeholder de Data. |
| [`create_theme_effective(self)`](/slides/python-net/pt/aspose.slides/masterhandoutslide/create_theme_effective/#) | Retorna um tema efetivo para este slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pt/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Encontra a primeira ocorrência de uma forma com o texto alternativo especificado. |


### Veja Também
* classe [`BaseSlide`](/slides/python-net/pt/aspose.slides/baseslide)
* classe [`MasterHandoutSlide`](/slides/python-net/pt/aspose.slides/masterhandoutslide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)