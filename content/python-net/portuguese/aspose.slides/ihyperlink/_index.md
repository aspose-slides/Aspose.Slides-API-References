---
title: IHyperlink class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ihyperlink/
---
## IHyperlink classe

Representa um hyperlink.

O tipo IHyperlink expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`action_type`](/slides/python-net/pt/aspose.slides/ihyperlink/action_type/) | Retorna o tipo da ação de HyperLinkEx.<br/>            Somente leitura [`HyperlinkActionType`](/slides/python-net/pt/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/pt/aspose.slides/ihyperlink/external_url/) | Especifica a URL externa<br/>            Se esta propriedade não for None, então a propriedade TargetSlide será None.<br/>            Somente leitura **str**. |
| [`external_url_original`](/slides/python-net/pt/aspose.slides/ihyperlink/external_url_original/) | Representa um hyperlink que está definido para esta porção sem considerar o conteúdo real da porção.<br/>            <br/>            O PowerPoint se comporta de forma específica para links e seu texto correspondente em uma porção. Ele permite criar texto para o hyperlink na forma de uma URL válida, diferente do endereço real do link. Neste caso, ao visualizar o link na janela de edição, ele será alterado para coincidir com a porção de texto. Esta propriedade representa o valor original do hyperlink. |
| [`target_slide`](/slides/python-net/pt/aspose.slides/ihyperlink/target_slide/) | Se o HyperlinkEx direciona para um slide específico, retorna esse slide.<br/>            Se a propriedade não for None, então a propriedade ExternalUrl será None.<br/>            Somente leitura [`ISlide`](/slides/python-net/pt/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/pt/aspose.slides/ihyperlink/target_frame/) | Retorna o quadro dentro do frameset HTML pai para o alvo do hyperlink pai quando este existir.<br/>            Leitura/gravação **str**. |
| [`tooltip`](/slides/python-net/pt/aspose.slides/ihyperlink/tooltip/) | Retorna a string que pode ser exibida em uma interface de usuário associada ao hyperlink pai.<br/>            Leitura/gravação **str**. |
| [`history`](/slides/python-net/pt/aspose.slides/ihyperlink/history/) | Determina se o alvo do hyperlink pai deve ser adicionado a uma lista de hyperlinks visualizados quando for invocado.<br/>            Leitura/gravação **bool**. |
| [`highlight_click`](/slides/python-net/pt/aspose.slides/ihyperlink/highlight_click/) | Determina se o hyperlink deve ser destacado ao clicar.<br/>            Leitura/gravação **bool**. |
| [`stop_sound_on_click`](/slides/python-net/pt/aspose.slides/ihyperlink/stop_sound_on_click/) | Determina se o som deve ser interrompido ao clicar no hyperlink.<br/>            Leitura/gravação **bool**. |
| [`sound`](/slides/python-net/pt/aspose.slides/ihyperlink/sound/) | Representa o som sendo reproduzido pelo hyperlink.<br/>            Leitura/gravação [`IAudio`](/slides/python-net/pt/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/pt/aspose.slides/ihyperlink/color_source/) | Representa a origem da cor do hyperlink - seja estilos ou formato da porção.<br/>            Leitura/gravação [`HyperlinkColorSource`](/slides/python-net/pt/aspose.slides/hyperlinkcolorsource). |

## Métodos

| Method | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/pt/aspose.slides/ihyperlink/equals/#ihyperlink) | Determina se as duas instâncias de Hyperlink são iguais. |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)