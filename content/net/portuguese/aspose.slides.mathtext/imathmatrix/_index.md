---
title: IMathMatrix
second_title: Aspose.Sildes para .NET Referência da API
description: Especifica o objeto Matrix composto por elementos filhos dispostos em uma ou mais linhas e colunas. É importante observar que as matrizes não possuem delimitadores incorporados. Para colocar a matriz entre colchetes, você deve usar o objeto delimitador IMathDelimiter. Argumentos nulos podem ser usados para criar lacunas nas matrizes.
type: docs
weight: 8320
url: /pt/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interface

Especifica o objeto Matrix, consistindo de elementos filhos dispostos em uma ou mais linhas e colunas. É importante observar que as matrizes não possuem delimitadores incorporados. Para colocar a matriz entre colchetes, você deve usar o objeto delimitador (IMathDelimiter). Argumentos nulos podem ser usados para criar lacunas nas matrizes.

```csharp
public interface IMathMatrix : IMathElement
```

## Propriedades

| Name | Description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Permite obter a interface base IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Especifica a justificativa vertical em relação ao texto circundante. Os valores possíveis são top, bottom, and center. Default: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Número de colunas na matriz |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | O valor do espaçamento horizontal entre colunas de uma matriz; Se a regra ColumnGapRule for 3 ("Exactly"), a unidade é interpretada como twips (1/20 de um ponto) Se a regra ColumnGapRule for 4 ("Multiple"), a unidade é interpretada como número de incrementos de 0.5 em. Em outros casos ignorado. Default: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | O tipo de espaçamento horizontal entre colunas de uma matriz; As unidades de espaçamento horizontal podem ser ems ou points (armazenados como twips). Default: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Oculta os marcadores de posição para elementos vazios da matriz Default: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Elementos da matriz |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Largura mínima da coluna em twips (1/20 de um ponto) O espaçamento de lacuna (também referido como “Column Gap” ou “Gap Width”) é adicionado ao MinColumnWidth para determinar o espaçamento total da coluna da matriz (distância entre as mesmas bordas de diferentes colunas). Default: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Número de linhas na matriz |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | O valor do espaçamento vertical entre linhas de uma matriz; Se a regra RowGapRule for 3 ("Exactly"), a unidade é interpretada como twips (1/20 de um ponto) Se a regra RowGapRule for 4 ("Multiple"), a unidade é interpretada como meia linha. Default: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | O tipo de espaçamento vertical entre linhas de uma matriz; As unidades de espaçamento vertical podem ser lines ou points (armazenados como twips). Default: SingleSpacingGap (0) |

## Métodos

| Name | Description |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Exclui a coluna especificada |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Exclui a linha especificada |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Obtém o alinhamento horizontal da coluna especificada |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Insere uma nova coluna após a especificada Inicialmente todos os elementos na nova coluna são nulos. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Insere uma nova coluna antes da especificada Inicialmente todos os elementos na nova coluna são nulos. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Insere uma nova linha após a especificada Inicialmente todos os elementos na nova linha são nulos. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Insere uma nova linha antes da especificada Inicialmente todos os elementos na nova linha são nulos. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Define o alinhamento horizontal da coluna especificada |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Define o alinhamento horizontal das colunas especificadas |

### Exemplos

Exemplo:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Veja Também

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->