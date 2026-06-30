---
title: MathElementBase
second_title: Referência da API Aspose.Sildes para .NET
description: Classe base para IMathElement com a implementação de alguns métodos que são comuns a todas as classes herdadas. Apenas para uso interno. A classe herdada deve ser IMathElement.
type: docs
weight: 8660
url: /pt/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase classe

Classe base para IMathElement com a implementação de alguns métodos que são comuns a todas as classes herdadas. Somente para uso interno. A classe herdada deve ser IMathElement.

```csharp
public abstract class MathElementBase : IMathElement
```

## Métodos

| Nome | Descrição |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Define uma marca de acento (um caractere no topo deste elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Aplica a função especificada usando esta instância como argumento e argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Aplica a função especificada usando esta instância como argumento e argumento adicional especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | Cria uma fração com este numerador e denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | Cria uma fração com este numerador e denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | Envolve um elemento matemático em parênteses |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | Aplica uma função de um argumento usando esta instância como nome da função |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | Aplica uma função de um argumento usando esta instância como nome da função |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | Coloca este elemento em um grupo usando uma chave inferior |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento em um grupo usando um caractere de agrupamento, como chave inferior ou outro |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | Aplica a integral sem limites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Aplica a integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | Aplica a integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Aplica a integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Aplica a integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | Une um elemento matemático e forma um bloco matemático |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | Une um texto matemático e forma um bloco matemático |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Cria um operador N-ário |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | Cria um operador N-ário |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Define uma barra no topo deste elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | Especifica a raiz matemática do grau indicado a partir do argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | Especifica a raiz matemática do grau indicado a partir do argumento especificado. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | Define limite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | Define limite inferior |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | Cria subscrito |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | Cria subscrito |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à esquerda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Cria subscrito e sobrescrito à esquerda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à direita |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Cria subscrito e sobrescrito à direita |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | Cria sobrescrito |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | Cria sobrescrito |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | Define limite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | Define limite superior |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | Coloca este elemento em uma caixa de borda |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento em uma caixa de borda |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento em uma caixa não visual (agrupamento lógico) que é usada para agrupar componentes de uma equação ou outra instância de texto matemático. Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha ou ser agrupado de modo a não permitir quebras de linha internamente. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Coloca em um array vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Define uma barra na parte inferior deste elemento |

### Veja também

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->