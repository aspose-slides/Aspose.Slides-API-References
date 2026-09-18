---
title: IBaseSlide class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ibaseslide/
---
## IBaseSlide classe

Representa dados comuns para todos os tipos de slide.

O tipo IBaseSlide expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/pt/aspose.slides/ibaseslide/shapes/) | Retorna as formas de um slide.<br/>            Somente leitura [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pt/aspose.slides/ibaseslide/controls/) | Retorna a coleção de controles ActiveX em um slide.<br/>            Somente leitura [`IControlCollection`](/slides/python-net/pt/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pt/aspose.slides/ibaseslide/name/) | Retorna ou define o nome de um slide.<br/>            Leitura/gravação **str**. |
| [`slide_id`](/slides/python-net/pt/aspose.slides/ibaseslide/slide_id/) | Retorna o ID de um slide.<br/>            Somente leitura **int**. |
| [`custom_data`](/slides/python-net/pt/aspose.slides/ibaseslide/custom_data/) | Retorna os dados personalizados do slide.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pt/aspose.slides/ibaseslide/timeline/) | Retorna o objeto de linha do tempo de animação.<br/>            Somente leitura [`IAnimationTimeLine`](/slides/python-net/pt/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pt/aspose.slides/ibaseslide/slide_show_transition/) | Retorna o objeto TransitionEx que contém informações sobre<br/>            como o slide especificado avança durante uma apresentação.<br/>            Somente leitura [`ISlideShowTransition`](/slides/python-net/pt/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pt/aspose.slides/ibaseslide/background/) | Retorna o plano de fundo do slide.<br/>            Somente leitura [`IBackground`](/slides/python-net/pt/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pt/aspose.slides/ibaseslide/hyperlink_queries/) | Fornece acesso fácil aos hyperlinks contidos.<br/>            Somente leitura [`IHyperlinkQueries`](/slides/python-net/pt/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pt/aspose.slides/ibaseslide/show_master_shapes/) | Especifica se as formas no slide mestre devem ser mostradas nos slides ou não.<br/>            Para o próprio slide mestre, esta propriedade sempre retorna `false`.<br/>            Leitura/gravação **bool**. |
| [`slide`](/slides/python-net/pt/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/ibaseslide/presentation/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pt/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Encontra a primeira ocorrência de uma forma com o texto alternativo especificado. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pt/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Mescla execuções com a mesma formatação em todos os parágrafos em todas as formas aceitáveis. |
| [`equals(self, slide)`](/slides/python-net/pt/aspose.slides/ibaseslide/equals/#ibaseslide) | Determina se as duas instâncias de IBaseSlide são iguais.<br/>            O valor retornado é calculado com base na estrutura do slide e no conteúdo estático.<br/>            Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., são iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo o valor da data atual no espaço reservado de data. |
| [`create_theme_effective(self)`](/slides/python-net/pt/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### Ver Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)