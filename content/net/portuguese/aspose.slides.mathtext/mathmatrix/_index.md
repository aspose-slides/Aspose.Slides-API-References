---
title: MathMatrix
second_title: Referência da API Aspose.Sildes para .NET
description: Especifica o objeto Matrix constituído por elementos filhos dispostos em uma ou mais linhas e colunas. É importante observar que matrizes não possuem delimitadores incorporados. Para colocar a matriz entre colchetes, você deve usar o objeto delimitador IMathDelimiter. Argumentos nulos podem ser usados para criar lacunas nas matrizes.
type: docs
weight: 8830
url: /pt/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix classe

Especifica o objeto Matrix, constituído por elementos filhos dispostos em uma ou mais linhas e colunas. É importante observar que matrizes não possuem delimitadores incorporados. Para colocar a matriz entre colchetes, você deve usar o objeto delimitador (IMathDelimiter). Argumentos nulos podem ser usados para criar lacunas nas matrizes.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Inicializa uma nova instância da classe MathMatrix. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Especifica o alinhamento vertical em relação ao texto ao redor. Valores possíveis: top, bottom e center. Padrão: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Número de colunas na matriz |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Valor do espaçamento horizontal entre colunas da matriz; se ColumnGapRule for 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto). Se ColumnGapRule for 4 ("Multiple"), a unidade é interpretada como número de incrementos de 0,5 em. Em outros casos, ignorado. Padrão: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Tipo do espaçamento horizontal entre colunas da matriz; unidades podem ser ems ou points (armazenados como twips). Padrão: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Oculta os espaços reservados para elementos vazios da matriz. Padrão: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Elemento da matriz |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Largura mínima da coluna em twips (1/20 de ponto). O espaçamento de lacuna (também chamado “Column Gap” ou “Gap Width”) é adicionado ao MinColumnWidth para determinar o espaçamento total de coluna da matriz (distância entre as mesmas bordas de colunas diferentes). Padrão: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Número de linhas na matriz |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Valor do espaçamento vertical entre linhas da matriz; se RowGapRule for 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto). Se RowGapRule for 4 ("Multiple"), a unidade é interpretada como meia-linha. Padrão: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Tipo do espaçamento vertical entre linhas da matriz; unidades podem ser lines ou points (armazenados como twips). Padrão: SingleSpacingGap (0) |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Define um acento (um caractere acima deste elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Aplica a função especificada usando esta instância como argumento e o argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Aplica a função especificada usando esta instância como argumento e o argumento adicional especificado |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Exclui a coluna especificada |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Exclui a linha especificada |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Cria uma fração com este numerador e denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Cria uma fração com este numerador e denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Envolve um elemento matemático entre parênteses |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres de enquadramento |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Aplica uma função de um argumento usando esta instância como nome da função |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Aplica uma função de um argumento usando esta instância como nome da função |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Obtém os elementos filhos |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Obtém o alinhamento horizontal da coluna especificada |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Coloca este elemento em um grupo usando uma chave curva inferior |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento em um grupo usando um caractere de agrupamento como chave curva inferior ou outro |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Insere uma nova coluna após a especificada. Inicialmente todos os elementos da nova coluna são nulos. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Insere uma nova coluna antes da especificada. Inicialmente todos os elementos da nova coluna são nulos. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Insere uma nova linha após a especificada. Inicialmente todos os elementos da nova linha são nulos. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Insere uma nova linha antes da especificada. Inicialmente todos os elementos da nova linha são nulos. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Insere a integral sem limites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Insere a integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Insere a integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Insere a integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Insere a integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Une um elemento matemático e forma um bloco matemático |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Une um texto matemático e forma um bloco matemático |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Cria um operador N-ário |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Cria um operador N-ário |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Define uma barra no topo deste elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Define o alinhamento horizontal da coluna especificada |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Define o alinhamento horizontal das colunas especificadas |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Aplica limite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Aplica limite inferior |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Cria subscrito |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Cria subscrito |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à esquerda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Cria subscrito e sobrescrito à esquerda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à direita |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Cria subscrito e sobrescrito à direita |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Cria sobrescrito |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Cria sobrescrito |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Aplica limite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Aplica limite superior |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Coloca este elemento em uma caixa de borda |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento em uma caixa de borda |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento em uma caixa não visual (agrupamento lógico) usado para agrupar componentes de uma equação ou outro texto matemático. Um objeto em caixa pode (por exemplo) servir como emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha, ou ser agrupado de modo a não permitir quebras de linha internas. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Insere em um arranjo vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Define uma barra na base deste elemento |

### Exemplos

Exemplo:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Veja Também

* classe [MathElementBase](../mathelementbase)
* interface [IMathMatrix](../imathmatrix)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->