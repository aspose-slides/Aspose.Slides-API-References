---
title: MathBox
second_title: Referência da API Aspose.Sildes para .NET
description: Especifica o empacotamento lógico (boxing) de elemento matemático. Por exemplo, um objeto encapsulado pode servir como um emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha ou ser agrupado de forma a não permitir quebras de linha dentro dele. Por exemplo, o operador deve ser encapsulado para impedir quebras de linha.
type: docs
weight: 8610
url: /pt/aspose.slides.mathtext/mathbox/
---
## classe MathBox

Especifica o empacotamento lógico (boxing) de elemento matemático. Por exemplo, um objeto encapsulado pode servir como um emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha ou ser agrupado de forma a não permitir quebras de linha dentro dele. Por exemplo, o operador “==” deve ser encapsulado para impedir quebras de linha.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Inicializa MathBox com o elemento especificado como argumento |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Quando true, este emulador de operador serve como ponto de alinhamento; ou seja, pontos de alinhamento designados em outras equações podem ser alinhados com ele. Padrão: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Argumento base |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Diferencial Quando true, a caixa atua como um diferencial (por exemplo, 𝑑𝑥 em um integrando) e recebe o espaçamento horizontal apropriado para o diferencial matemático. Padrão: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Quebra explícita especifica se há uma quebra de linha no início do objeto Box, de modo que a linha seja quebrada no início da caixa. Especifica o número do operador na linha anterior de texto matemático que será usado como ponto de alinhamento para a linha atual de texto matemático. valores possíveis: 1..255 Padrão: 0 (sem quebra explícita) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Sem quebra Esta propriedade define a propriedade “inquebrável” na caixa do objeto. Quando true, nenhuma quebra de linha pode ocorrer dentro da caixa. Isso pode ser importante para emuladores de operador que consistem em mais de um operador binário. Quando este elemento não é especificado, quebras podem ocorrer dentro da caixa. Padrão: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Emulador de Operador. Quando true, a caixa e seu conteúdo comportam-se como um único operador e herdam as propriedades de um operador. Isto significa, por exemplo, que o caractere pode servir como ponto de quebra de linha e pode ser alinhado a outros operadores. Emuladores de Operador são frequentemente usados quando um ou mais glifos se combinam para formar um operador, como ‘==’. Valor padrão: false |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Define uma marca de acento (um caractere acima deste elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Recebe a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Recebe a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Recebe a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Recebe a função especificada usando esta instância como argumento e argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Recebe a função especificada usando esta instância como argumento e argumento adicional especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Cria uma fração com este numerador e denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Cria uma fração com este numerador e denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Envolve um elemento matemático entre parênteses |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Recebe uma função de um argumento usando esta instância como nome da função |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Recebe uma função de um argumento usando esta instância como nome da função |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Obtém elementos filhos |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Coloca este elemento em um grupo usando uma chave chata inferior |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento em um grupo usando um caractere de agrupamento, como chave chata inferior ou outro |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Recebe a integral sem limites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Recebe a integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Recebe a integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Recebe a integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Recebe a integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Junta um elemento matemático e forma um bloco matemático |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Junta um texto matemático e forma um bloco matemático |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Cria um operador N-ário |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Cria um operador N-ário |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Define uma barra no topo deste elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Especifica a raiz matemática do grau fornecido a partir do argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Especifica a raiz matemática do grau fornecido a partir do argumento especificado. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Recebe limite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Recebe limite inferior |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Cria subscrito |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Cria subscrito |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à esquerda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Cria subscrito e sobrescrito à esquerda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à direita |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Cria subscrito e sobrescrito à direita |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Cria sobrescrito |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Cria sobrescrito |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Recebe limite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Recebe limite superior |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Coloca este elemento em uma caixa de borda |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento em uma caixa de borda |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento em uma caixa não visual (agrupamento lógico) usada para agrupar componentes de uma equação ou outra instância de texto matemático. Um objeto encapsulado pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha ou ser agrupado de forma a não permitir quebras de linha dentro dele. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Insere em um array vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Define uma barra na parte inferior deste elemento |

### Exemplos

Exemplo:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Veja Também

* classe [MathElementBase](../mathelementbase)
* interface [IMathBox](../imathbox)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->