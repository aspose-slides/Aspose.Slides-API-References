---
title: MathBlock
second_title: Referência da API Aspose.Sildes para .NET
description: Especifica uma instância de texto matemático que está contida dentro de um MathParagraph e começa em sua própria linha. Todas as zonas matemáticas, incluindo equações, expressões, matrizes de equações ou expressões e fórmulas, são representadas por um bloco matemático.
type: docs
weight: 8570
url: /pt/aspose.slides.mathtext/mathblock/
---
## classe MathBlock

Especifica uma instância de texto matemático que está contida dentro de um MathParagraph e começa em sua própria linha. Todas as zonas matemáticas, incluindo equações, expressões, matrizes de equações ou expressões e fórmulas são representadas por um bloco matemático.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Inicializa uma nova instância da classe MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Cria um novo bloco matemático e coloca os elementos especificados nele. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Cria um novo bloco matemático e coloca o elemento especificado nele. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Obtém o número de elementos matemáticos filho realmente contidos na coleção. Int32 somente leitura. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Retorna false porque a coleção de elementos filho pode ser modificada. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Obtém ou define IMathElement no índice especificado. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Define uma marca de acento (um caractere no topo deste elemento). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Adiciona um elemento matemático ao final da coleção. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Utiliza a função especificada usando esta instância como argumento. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Utiliza a função especificada usando esta instância como argumento. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Utiliza a função especificada usando esta instância como argumento. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Aplica a função especificada usando esta instância como argumento e o argumento adicional especificado. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Aplica a função especificada usando esta instância como argumento e o argumento adicional especificado. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Remove todos os elementos da coleção. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Determina se a coleção contém um valor específico. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Copia para a matriz especificada. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Delimita os elementos filho com o caractere separador (sem os colchetes). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Cria uma fração com este numerador e o denominador especificado. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Cria uma fração com este numerador e o denominador especificado. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e o denominador especificado. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Cria uma fração do tipo especificado com este numerador e o denominador especificado. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Envolve um elemento matemático entre parênteses. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Envolve os elementos filho deste bloco em caracteres especificados, como parênteses ou outros caracteres como moldura. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Envolve os elementos filho deste bloco em caracteres especificados, como parênteses ou outros, como moldura e delimita com um caractere separador. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Aplica uma função de um argumento usando esta instância como nome da função. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Aplica uma função de um argumento usando esta instância como nome da função. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Obtém os elementos filhos. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Coloca este elemento em um grupo usando uma chave inferior. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento em um grupo usando um caractere de agrupamento, como uma chave inferior ou outro. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Determina o índice de um elemento matemático específico na coleção. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Insere um MathElement na coleção no índice especificado. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Aplica a integral sem limites. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Aplica a integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Aplica a integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Aplica a integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Aplica a integral. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Une um elemento matemático a este bloco matemático. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Une um texto matemático a este bloco matemático. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Une outro bloco matemático a este. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMMathElement, IMathElement) | Cria um operador N-ário. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Cria um operador N-ário. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Define uma barra no topo deste elemento. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Remove o elemento no índice especificado da coleção. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Obtém o limite inferior. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Obtém o limite inferior. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Cria subscrito. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Cria subscrito. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à esquerda. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Cria subscrito e sobrescrito à esquerda. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Cria subscrito e sobrescrito à direita. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Cria subscrito e sobrescrito à direita. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Cria sobrescrito. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Cria sobrescrito. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Obtém o limite superior. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Obtém o limite superior. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Coloca este elemento em uma caixa de borda. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento em uma caixa de borda. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento em uma caixa não visual (agrupamento lógico) que é usada para agrupar componentes de uma equação ou outra instância de texto matemático. Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha ou ser agrupado de forma a não permitir quebras de linha dentro. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Coloca os elementos filho em uma matriz vertical. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Define uma barra na parte inferior deste elemento. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Salva o conteúdo deste [`MathBlock`](../mathblock) como MathML. |

### Exemplos

Exemplo:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Veja Também

* classe [MathElementBase](../mathelementbase)
* interface [IMathBlock](../imathblock)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->