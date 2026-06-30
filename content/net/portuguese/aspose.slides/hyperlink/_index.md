---
title: Hyperlink
second_title: Referência da API Aspose.Sildes para .NET
description: Representa um hyperlink.
type: docs
weight: 5100
url: /pt/aspose.slides/hyperlink/
---
## Hyperlink classe

Representa um hyperlink.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Cria uma instância de um hyperlink que aponta para um slide específico. Observação: o hyperlink criado deve ser atribuído a algum objeto da mesma apresentação, caso contrário o link será salvo como NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Cria uma instância de um hyperlink. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Cria uma instância de um hyperlink usando outro hyperlink como fonte, sobrescrevendo propriedades secundárias. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Retorna um hyperlink que encerra a apresentação. Somente leitura [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Retorna um hyperlink para o primeiro slide da apresentação. Somente leitura [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Retorna um hyperlink para o último slide da apresentação. Somente leitura [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Retorna um hyperlink para o último slide visualizado. Somente leitura [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Retorna um hyperlink especial "play mediafile". Usado em AudioFrame e VideoFrame. Somente leitura [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Retorna um hyperlink para o próximo slide. Somente leitura [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Retorna um hyperlink especial "do nothing". Somente leitura [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Retorna um hyperlink para o slide anterior. Somente leitura [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Retorna o tipo da ação do Hyperlink. Somente leitura [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obter a interface base IPresentationComponent. Somente leitura [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Representa a origem da cor do hyperlink - estilos ou formato da porção. Leitura/gravação [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Especifica o URL externo. Somente leitura String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Representa um hyperlink que está definido para esta porção sem considerar o conteúdo real da porção. O PowerPoint se comporta de forma específica para links e seu texto correspondente em uma porção. Permite criar texto para o hyperlink na forma de um URL válido, diferente do endereço real do link. Nesse caso, ao visualizar o link na janela de edição, ele será alterado para corresponder à porção de texto. Esta propriedade representa o valor original do hyperlink. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Determina se o hyperlink deve ser destacado ao clicar. Leitura/gravação Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Determina se o destino do hyperlink pai deve ser adicionado a uma lista de hyperlinks visualizados quando for invocado. Leitura/gravação Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Representa o som reproduzido pelo hyperlink. Leitura/gravação [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Determina se o som deve ser interrompido ao clicar no hyperlink. Leitura/gravação Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Retorna o quadro dentro do frameset HTML pai para o destino do hyperlink pai quando existir. Leitura/gravação String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Se o Hyperlink apontar para um slide específico, retorna esse slide. Somente leitura [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Retorna a string que pode ser exibida em uma interface de usuário como associada ao hyperlink pai. Leitura/gravação String. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Determina se as duas instâncias de Hyperlink são iguais. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Determina se as duas instâncias de Hyperlink são iguais. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Funciona como uma função hash para um tipo específico, adequada para uso em algoritmos de hashing e estruturas de dados como uma tabela hash. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Testa dois hyperlinks para igualdade. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Testa dois hyperlinks para desigualdade. |

### Veja também

* classe [PVIObject](../pviobject)
* interface [IHyperlink](../ihyperlink)
* espaço de nomes [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->