---
title: IMathElement
second_title: Referência da API Aspose.Sildes para .NET
description: Interface base de qualquer elemento matemático, como fração, texto matemático, função, expressão com múltiplos elementos etc
type: docs
weight: 8210
url: /pt/aspose.slides.mathtext/imathelement/
---
## IMathElement interface

Interface base de qualquer elemento matemático: fração, texto matemático, função, expressão com múltiplos elementos etc

```csharp
public interface IMathElement
```

## Métodos

| Nome | Descrição |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Define uma marca de acento (um caractere no topo deste elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Aplica a função especificada usando esta instância como argumento e o argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Aplica a função especificada usando esta instância como argumento e o argumento adicional especificado |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Cria uma fração com este numerador e o denominador especificado |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Cria uma fração com este numerador e o denominador especificado |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e o denominador especificado |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e o denominador especificado |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Envolve um elemento matemático entre parênteses |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Envolve este elemento em caracteres especificados, como parênteses ou outros caracteres de moldura |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Usa esta instância como nome da função para uma função de um argumento |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Usa esta instância como nome da função para uma função de um argumento |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Obtém os elementos filhos |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Coloca este elemento em um grupo usando uma chave curva inferior |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento em um grupo usando um caractere de agrupamento, como chave curva inferior ou outro |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Aplica o integral sem limites |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Aplica o integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Aplica o integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Aplica o integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Aplica o integral |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Une um elemento matemático e forma um bloco matemático |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Une um texto matemático e forma um bloco matemático |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Cria um operador N-ário |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Cria um operador N-ário |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Define uma barra no topo deste elemento |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Especifica a raiz matemática do grau indicado a partir do argumento especificado |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Especifica a raiz matemática do grau indicado a partir do argumento especificado |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Define o limite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Define o limite inferior |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Cria um subscrito |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Cria um subscrito |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à esquerda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Cria subscrito e sobrescrito à esquerda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à direita |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Cria subscrito e sobrescrito à direita |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Cria um sobrescrito |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Cria um sobrescrito |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Define o limite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Define o limite superior |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Coloca este elemento em uma caixa de borda |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento em uma caixa de borda |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Coloca este elemento em uma caixa não visual (agrupamento lógico) usada para agrupar componentes de uma equação ou outro trecho de texto matemático. Um objeto encapsulado pode, por exemplo, servir como emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha ou ser agrupado de modo a impedir quebras de linha internas |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Insere em um arranjo vertical |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Define uma barra na parte inferior deste elemento |

### Exemplos

Exemplo:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Ver Também

* espaço de nomes [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->