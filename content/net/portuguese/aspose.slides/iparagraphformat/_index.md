---
title: IParagraphFormat
second_title: Aspose.Sildes para .NET Referência da API
description: Esta classe contém as propriedades de formatação de parágrafo. Ao contrário de IParagraphFormatEffectiveData./iparagraphformateffectivedata, todas as propriedades desta classe são graváveis.
type: docs
weight: 6590
url: /pt/aspose.slides/iparagraphformat/
---
## IParagraphFormat interface

Esta classe contém as propriedades de formatação de parágrafo. Ao contrário de [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), todas as propriedades desta classe são graváveis.

```csharp
public interface IParagraphFormat
```

## Propriedades

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Retorna ou define o alinhamento de texto em um parágrafo sem herança. Leitura/gravação [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Retorna o formato de marcadores do parágrafo. Somente leitura [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Retorna o formato de porção padrão de um parágrafo. Nenhuma herança aplicada. Somente leitura [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Retorna ou define o tamanho de tabulação padrão sem herança. Leitura/gravação Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Retorna ou define a profundidade do parágrafo. Valor 0 significa valor indefinido. Leitura/gravação Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Determina se a quebra de linha oriental é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Retorna ou define o alinhamento de fonte em um parágrafo sem herança. Leitura/gravação [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Determina se a pontuação pendente é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Retorna ou define o recuo da primeira linha/recúo pendente do parágrafo sem herança. O recuo pendente pode ser definido com valores negativos. Leitura/gravação Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Determina se a quebra de linha latina é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Retorna ou define a margem esquerda em um parágrafo sem herança. Leitura/gravação Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Retorna ou define a margem direita em um parágrafo sem herança. Leitura/gravação Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Determina se a escrita da direita para a esquerda é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Retorna ou define a quantidade de espaço após a última linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ter. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leitura/gravação Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Retorna ou define a quantidade de espaço antes da primeira linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ter. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leitura/gravação Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Retorna ou define a quantidade de espaço entre linhas de base em um parágrafo. Valor positivo significa porcentagem, negativo – tamanho em pontos. Nenhuma herança aplicada. Leitura/gravação Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Retorna as tabulações de um parágrafo. Nenhuma herança aplicada. Somente leitura [`ITabCollection`](../itabcollection). |

## Métodos

| Name | Description |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Obtém os dados efetivos de formatação de parágrafo com a herança aplicada. |

### Observações

Esta classe é usada para retornar e manipular as propriedades de formatação de parágrafo definidas para o parágrafo específico. Isso significa que nenhuma herança é aplicada ao obter valores, portanto na maioria dos casos você receberá valores que significam “indefinido”.

Para obter os valores efetivos dos parâmetros de formatação, incluindo os herdados, você precisa usar o método [`GetEffective`](./geteffective) que retorna uma instância [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Ver também

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->