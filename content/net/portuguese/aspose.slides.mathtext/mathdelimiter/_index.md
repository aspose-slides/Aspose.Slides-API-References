---
title: MathDelimiter
second_title: Aspose.Sildes para .NET Referência da API
description: Especifica o objeto delimitador composto de caracteres de abertura e fechamento, como parênteses, chaves, colchetes e barras verticais, e um ou mais elementos matemáticos internos separados por um caractere especificado. Exemplos 2 2x7C2
type: docs
weight: 8630
url: /pt/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter classe

Especifica o objeto delimitador, constituído por caracteres de abertura e fechamento (como parênteses, chaves, colchetes e barras verticais), e um ou mais elementos matemáticos internos, separados por um caractere especificado. Exemplos: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Inicializa MathDelimiter com o elemento especificado como argumento base único |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Um ou mais elementos matemáticos separados por caracteres delimitadores |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Delimiter Beginning Character especifica o caractere delimitador de início, ou de abertura. Delimitadores matemáticos são caracteres de fechamento como parênteses, colchetes e chaves. O padrão: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Especifica o formato dos delimitadores no objeto delimitador. Quando é MathDelimiterShape.Centered, os delimitadores são centralizados em torno do eixo matemático do texto e ainda são ajustados para caber na altura total de seu conteúdo. Quando é MathDelimiterShape.Match, sua altura e formato são alterados para corresponder exatamente ao conteúdo. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimiter Ending Character especifica o caractere delimitador de fim, ou de fechamento. Delimitadores matemáticos são caracteres de fechamento como parênteses, colchetes e chaves. O padrão: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Especifica o crescimento de BeginningCharacter, SeparatorCharacter e EndingCharacter. Quando true, os delimitadores crescem verticalmente para combinar com a altura do operando. O valor padrão é true. |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimiter Separator Character especifica o caractere que separa argumentos no objeto delimitador. O padrão: '&#x7C;'. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Define uma marca de acento (um caractere no topo deste elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Aplica a função especificada usando esta instância como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Aplica a função especificada usando esta instância como argumento e o argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Aplica a função especificada usando esta instância como argumento e o argumento adicional especificado |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Delimita argumentos usando o caractere delimitador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Cria uma fração com este numerador e o denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Cria uma fração com este numerador e o denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e o denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e o denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Envolve um elemento matemático em parênteses |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como enquadramento |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Aplica uma função de um argumento usando esta instância como nome da função |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Aplica uma função de um argumento usando esta instância como nome da função |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Obtém elementos filhos |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Coloca este elemento em uma caixa de contorno |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento em uma caixa de contorno |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento em uma caixa não visual (agrupamento lógico) usada para agrupar componentes de uma equação ou outra instância de texto matemático. Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha, ou ser agrupado de modo a não permitir quebras de linha dentro dele. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Insere em um arranjo vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Define uma barra na parte inferior deste elemento |

### Exemplos

Exemplo:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### Veja Também

* classe [MathElementBase](../mathelementbase)
* interface [IMathDelimiter](../imathdelimiter)
* espaço de nomes [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->