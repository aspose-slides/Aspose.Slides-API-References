---
title: MathBorderBox
second_title: Referência da API Aspose.Sildes para .NET
description: Desenha uma borda retangular ou outra ao redor do IMathElement.
type: docs
weight: 8590
url: /pt/aspose.slides.mathtext/mathborderbox/
---
## classe MathBorderBox

Desenha um retângulo ou alguma outra borda ao redor do IMathElement.

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | Cria um elemento MathBorderBox com borda retangular |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | Cria um elemento MathBorderBox |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | Argumento base |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | Ocultar Borda Inferior (padrão é false) - especifica o estado oculto ou visível da borda inferior da caixa de borda. |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | Ocultar Borda Esquerda (padrão é false) - especifica o estado oculto ou visível da borda esquerda da caixa de borda. |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | Ocultar Borda Direita (padrão é false) - especifica o estado oculto ou visível da borda direita da caixa de borda. |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | Ocultar Borda Superior (padrão é false) - especifica o estado oculto ou visível da borda superior da caixa de borda. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | Riscado de Baixo-Esquerda para Alto-Direita (padrão é false). Especifica o estado oculto ou visível de uma linha diagonal riscada do canto inferior esquerdo ao canto superior direito da caixa de borda. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | Riscado Horizontal (padrão é false) - especifica o estado oculto ou visível de uma linha horizontal riscada. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | Riscado de Alto-Esquerda para Baixo-Direita (padrão é false). Especifica o estado oculto ou visível de uma linha diagonal riscada do canto superior esquerdo ao canto inferior direito da caixa de borda. |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | Riscado Vertical (padrão é false) - especifica o estado oculto ou visível de uma linha vertical riscada. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Define um acento (um caractere no topo deste elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Utiliza a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Utiliza a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Utiliza a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Aplica a função especificada usando esta instância como argumento e o argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Aplica a função especificada usando esta instância como argumento e o argumento adicional especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Cria uma fração com este numerador e o denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Cria uma fração com este numerador e o denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Envolve um elemento matemático entre parênteses |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Envolve um elemento matemático nos caracteres especificados, como parênteses ou outros caracteres como moldura |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Aplica uma função de um argumento usando esta instância como nome da função |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Aplica uma função de um argumento usando esta instância como nome da função |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | Obtém os elementos filhos |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Coloca este elemento em um grupo usando uma chave inferior |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento em um grupo usando um caractere de agrupamento, como chave inferior ou outro |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Aplica a integral sem limites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Aplica a integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Aplica a integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Aplica a integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Aplica a integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Une um elemento matemático e forma um bloco matemático |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Une um texto matemático e forma um bloco matemático |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Cria um operador N-ário |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Cria um operador N-ário |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Define uma barra no topo deste elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Obtém limite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Obtém limite inferior |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Cria subscrito |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Cria subscrito |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à esquerda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Cria subscrito e sobrescrito à esquerda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à direita |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Cria subscrito e sobrescrito à direita |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Cria sobrescrito |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Cria sobrescrito |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Obtém limite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Obtém limite superior |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Coloca este elemento em uma caixa de borda |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento em uma caixa de borda |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento em uma caixa não visual (agrupamento lógico) usada para agrupar componentes de uma equação ou outra instância de texto matemático. Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha ou ser agrupado de forma a não permitir quebras de linha dentro dele. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Coloca em um array vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Define uma barra na parte inferior deste elemento |

### Exemplos

Exemplo:

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### Veja também

* classe [MathElementBase](../mathelementbase)
* interface [IMathBorderBox](../imathborderbox)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->