---
title: BaseSlide class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/baseslide/
---
## BaseSlide classe

Representa dados comuns para todos os tipos de slide.

O tipo BaseSlide expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`shapes`](/slides/python-net/pt/aspose.slides/baseslide/shapes/) | Retorna as formas de um slide.<br/>            Somente leitura [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pt/aspose.slides/baseslide/controls/) | Retorna a coleção de controles ActiveX em um slide.<br/>            Somente leitura [`IControlCollection`](/slides/python-net/pt/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pt/aspose.slides/baseslide/name/) | Retorna ou define o nome de um slide.<br/>            Leitura/gravação **str**. |
| [`slide_id`](/slides/python-net/pt/aspose.slides/baseslide/slide_id/) | Retorna o ID de um slide.<br/>            Somente leitura **int**. |
| [`custom_data`](/slides/python-net/pt/aspose.slides/baseslide/custom_data/) | Retorna os dados personalizados do slide.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pt/aspose.slides/baseslide/timeline/) | Retorna o objeto de linha do tempo de animação.<br/>            Somente leitura [`IAnimationTimeLine`](/slides/python-net/pt/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pt/aspose.slides/baseslide/slide_show_transition/) | Retorna o objeto Transition que contém informações sobre<br/>            como o slide especificado avança durante a apresentação.<br/>            Somente leitura [`ISlideShowTransition`](/slides/python-net/pt/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pt/aspose.slides/baseslide/background/) | Retorna o plano de fundo do slide.<br/>            Somente leitura [`IBackground`](/slides/python-net/pt/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pt/aspose.slides/baseslide/hyperlink_queries/) | Fornece acesso fácil aos hyperlinks contidos.<br/>            Somente leitura [`IHyperlinkQueries`](/slides/python-net/pt/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pt/aspose.slides/baseslide/show_master_shapes/) | Especifica se as formas no slide mestre devem ser mostradas nos slides ou não.<br/>            Para o próprio slide mestre esta propriedade sempre retorna `false`.<br/>            Leitura/gravação **bool**. |
| [`presentation`](/slides/python-net/pt/aspose.slides/baseslide/presentation/) | Retorna a interface IPresentation.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/pt/aspose.slides/baseslide/slide/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pt/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Une sequências com a mesma formatação em todos os parágrafos de todas as formas aceitáveis. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pt/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Une sequências com a mesma formatação em todos os parágrafos de todas as formas aceitáveis. |
| [`equals(self, slide)`](/slides/python-net/pt/aspose.slides/baseslide/equals/#ibaseslide) | Determina se as duas instâncias IBaseSlide são iguais.<br/>            O valor retornado é calculado com base na estrutura do slide e no conteúdo estático.<br/>            Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações etc. forem iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo o valor da data atual em um Placeholder de Data. |
| [`create_theme_effective(self)`](/slides/python-net/pt/aspose.slides/baseslide/create_theme_effective/#) | Retorna um tema efetivo para este slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pt/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Encontra a primeira ocorrência de uma forma com o texto alternativo especificado. |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)