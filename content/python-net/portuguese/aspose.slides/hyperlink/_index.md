---
title: Hyperlink class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/hyperlink/
---
## classe Hyperlink

Representa um hyperlink.

**Herança:**[`Hyperlink`](/slides/python-net/pt/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/pt/aspose.slides/pviobject)

O tipo Hyperlink expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/pt/aspose.slides/hyperlink/__init__/#str) | Cria uma instância de um hyperlink. |
| [`__init__(self, slide)`](/slides/python-net/pt/aspose.slides/hyperlink/__init__/#islide) | Cria uma instância de um hyperlink que aponta para um slide específico.<br/>            Observação: o hyperlink criado deve ser atribuído a algum objeto da mesma apresentação, caso contrário o link será salvo como NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/pt/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Cria uma instância de um hyperlink usando outro hyperlink como origem, sobrescrevendo propriedades secundárias. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`no_action`](/slides/python-net/pt/aspose.slides/hyperlink/no_action/) | Retorna um hyperlink especial "do nothing".<br/>            Somente leitura [`Hyperlink`](/slides/python-net/pt/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/pt/aspose.slides/hyperlink/media/) | Retorna um hyperlink especial "play mediafile". Usado em AudioFrame e VideoFrame.<br/>            Somente leitura [`Hyperlink`](/slides/python-net/pt/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/pt/aspose.slides/hyperlink/next_slide/) | Retorna um hyperlink para o próximo slide.<br/>            Somente leitura [`Hyperlink`](/slides/python-net/pt/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/pt/aspose.slides/hyperlink/previous_slide/) | Retorna um hyperlink para o slide anterior.<br/>            Somente leitura [`Hyperlink`](/slides/python-net/pt/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/pt/aspose.slides/hyperlink/first_slide/) | Retorna um hyperlink para o primeiro slide da apresentação.<br/>            Somente leitura [`Hyperlink`](/slides/python-net/pt/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/pt/aspose.slides/hyperlink/last_slide/) | Retorna um hyperlink para o último slide da apresentação.<br/>            Somente leitura [`Hyperlink`](/slides/python-net/pt/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/pt/aspose.slides/hyperlink/last_vieved_slide/) | Retorna um hyperlink para o último slide visualizado.<br/>            Somente leitura [`Hyperlink`](/slides/python-net/pt/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/pt/aspose.slides/hyperlink/end_show/) | Retorna um hyperlink que encerra a apresentação.<br/>            Somente leitura [`Hyperlink`](/slides/python-net/pt/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/pt/aspose.slides/hyperlink/action_type/) | Retorna o tipo da ação do Hyperlink.<br/>            Somente leitura [`HyperlinkActionType`](/slides/python-net/pt/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/pt/aspose.slides/hyperlink/external_url/) | Especifica a URL externa.<br/>            Somente leitura **str**. |
| [`target_slide`](/slides/python-net/pt/aspose.slides/hyperlink/target_slide/) | Se o Hyperlink tiver como alvo um slide específico, retorna esse slide.<br/>            Somente leitura [`ISlide`](/slides/python-net/pt/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/pt/aspose.slides/hyperlink/external_url_original/) | Representa um hyperlink definido para esta porção independentemente do conteúdo real da porção.<br/>            <br/>            O PowerPoint se comporta de forma específica para links e seu texto correspondente em uma porção. Ele permite criar texto para o hyperlink na forma de uma URL válida, diferente do endereço real do link. Nesse caso, ao visualizar o link na janela de edição, ele será alterado para coincidir com a porção de texto. Esta propriedade representa o valor original do hyperlink. |
| [`target_frame`](/slides/python-net/pt/aspose.slides/hyperlink/target_frame/) | Retorna o frame dentro do frameset HTML pai para o alvo<br/>            do hyperlink pai quando este existe.<br/>            Leitura/gravação **str**. |
| [`tooltip`](/slides/python-net/pt/aspose.slides/hyperlink/tooltip/) | Retorna a string que pode ser exibida em uma interface de usuário<br/>            como associada ao hyperlink pai.<br/>            Leitura/escrita **str**. |
| [`history`](/slides/python-net/pt/aspose.slides/hyperlink/history/) | Determina se o alvo do hyperlink pai deve ser adicionado<br/>            a uma lista de hyperlinks visualizados quando for invocado.<br/>            Leitura/escrita **bool**. |
| [`highlight_click`](/slides/python-net/pt/aspose.slides/hyperlink/highlight_click/) | Determina se o hyperlink deve ser destacado ao ser clicado.<br/>            Leitura/escrita **bool**. |
| [`stop_sound_on_click`](/slides/python-net/pt/aspose.slides/hyperlink/stop_sound_on_click/) | Determina se o som deve ser interrompido ao clicar no hyperlink.<br/>            Leitura/escrita **bool**. |
| [`sound`](/slides/python-net/pt/aspose.slides/hyperlink/sound/) | Representa o som em reprodução do hyperlink.<br/>            Leitura/escrita [`IAudio`](/slides/python-net/pt/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/pt/aspose.slides/hyperlink/color_source/) | Representa a origem da cor do hyperlink - estilos ou formato da porção.<br/>            Leitura/escrita [`HyperlinkColorSource`](/slides/python-net/pt/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/pt/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/hyperlink/presentation/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/pt/aspose.slides/hyperlink/equals/#ihyperlink) | Determina se as duas instâncias de Hyperlink são iguais. |


### Veja Também
* classe [`Hyperlink`](/slides/python-net/pt/aspose.slides/hyperlink)
* classe [`PVIObject`](/slides/python-net/pt/aspose.slides/pviobject)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)