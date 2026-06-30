---
title: MathNaryOperator
second_title: Referência de API Aspose.Sildes para .NET
description: Especifica um objeto matemático N-ário, como Somatório e Integral. Consiste em um operador, uma base ou operando e limites superior e inferior opcionais. Exemplos de operadores N-ários são Somatório, União, Interseção e Integral.
type: docs
weight: 8850
url: /pt/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator classe

Especifica um objeto matemático N-ário, como Somatório e Integral. Consiste em um operador, uma base (ou operando) e limites superior e inferior opcionais. Exemplos de operadores N-ários são: Somatório, União, Interseção, Integral

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | Inicializa uma nova instância da classe MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | Inicializa uma nova instância da classe MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | Inicializa uma nova instância da classe MathNaryOperator. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | Argumento base |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | O caractere do operador cresce verticalmente para combinar com a altura do operando |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | Ocultar subscrito |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | Ocultar sobrescrito |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | A localização dos limites (subscrito e sobrescrito) |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | Caractere do operador N-ário. Por exemplo: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | Especifica um argumento subscrito que, por exemplo, no caso de uma integral, define o limite inferior |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | Especifica um argumento sobrescrito que, por exemplo, no caso de uma integral, define o limite superior |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Define um acento (um caractere na parte superior deste elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Aplica a função especificada usando esta instância como argumento e o argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Aplica a função especificada usando esta instância como argumento e o argumento adicional especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Cria uma fração com este numerador e o denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Cria uma fração com este numerador e o denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e o denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e o denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Envolve um elemento matemático entre parênteses |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Utiliza uma função de um argumento usando esta instância como nome da função |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Utiliza uma função de um argumento usando esta instância como nome da função |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | Obtém os elementos filhos |
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
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Define uma barra na parte superior deste elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Define limite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Define limite inferior |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Cria subscrito |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Cria subscrito |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à esquerda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Cria subscrito e sobrescrito à esquerda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à direita |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Cria subscrito e sobrescrito à direita |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Cria sobrescrito |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Cria sobrescrito |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Define limite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Define limite superior |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Coloca este elemento em uma caixa de borda |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento em uma caixa de borda |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento em uma caixa não visual (agrupamento lógico) que é usada para agrupar componentes de uma equação ou outra instância de texto matemático. Um objeto em caixa pode (por exemplo) servir como emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha, ou ser agrupado de modo a não permitir quebras de linha dentro dele. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Coloca em um array vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Define uma barra na parte inferior deste elemento |

### Exemplos

Exemplo:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### Veja Também

* classe [MathElementBase](../mathelementbase)
* interface [IMathNaryOperator](../imathnaryoperator)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->