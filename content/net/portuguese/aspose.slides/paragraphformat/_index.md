---
title: ParagraphFormat
second_title: Aspose.Sildes for .NET Referência da API
description: Esta classe contém as propriedades de formatação de parágrafo. Ao contrário de IParagraphFormatEffectiveData./iparagraphformateffectivedata, todas as propriedades desta classe são graváveis.
type: docs
weight: 9310
url: /pt/aspose.slides/paragraphformat/
---
## ParagraphFormat classe

Esta classe contém as propriedades de formatação de parágrafo. Ao contrário de [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), todas as propriedades desta classe são graváveis.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Inicializa uma nova instância da classe [`ParagraphFormat`](../paragraphformat). |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Retorna ou define o alinhamento de texto em um parágrafo sem herança. Leitura/gravação [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obter a interface base IPresentationComponent. Somente leitura [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Retorna ou define o tamanho padrão da tabulação sem herança. Leitura/gravação Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Determina se a quebra de linha East Asian é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Retorna ou define o alinhamento da fonte em um parágrafo sem herança. Leitura/gravação [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Determina se a pontuação suspensa é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Retorna ou define a indentação da primeira linha/Indentação suspensa do parágrafo sem herança. A indentação suspensa pode ser definida com valores negativos. Leitura/gravação Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Determina se a quebra de linha Latin é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Retorna ou define a margem esquerda em um parágrafo sem herança. Leitura/gravação Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Retorna ou define a margem direita em um parágrafo sem herança. Leitura/gravação Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Determina se a escrita da direita para a esquerda é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Retorna ou define a quantidade de espaço após a última linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ter. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leitura/gravação Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Retorna ou define a quantidade de espaço antes da primeira linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ter. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leitura/gravação Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Retorna ou define a quantidade de espaço entre linhas base em um parágrafo. Valor positivo significa porcentagem, negativo – tamanho em pontos. Nenhuma herança aplicada. Leitura/gravação Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Retorna as tabulações de um parágrafo. Nenhuma herança aplicada. Somente leitura [`ITabCollection`](../itabcollection). |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara com o objeto especificado. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Obtém os dados de formatação de parágrafo efetivos com a herança aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retorna o código hash. |

### Observações

Esta classe é usada para devolver e manipular as propriedades de formatação de parágrafo definidas para o parágrafo específico. Isso significa que nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você receberá valores que significam “indefinido”.

Para obter os valores efetivos dos parâmetros de formatação, incluindo os herdados, você precisa usar o método [`GetEffective`](./geteffective) que retorna uma instância [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Ver Também

* classe [PVIObject](../pviobject)
* interface [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interface [IParagraphFormat](../iparagraphformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->