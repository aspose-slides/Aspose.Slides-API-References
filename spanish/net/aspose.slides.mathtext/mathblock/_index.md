---
title: MathBlock
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica una instancia de texto matemático contenido en un MathParagraph y comienza en su propia línea. Todas las zonas matemáticas incluidas ecuaciones expresiones matrices de ecuaciones o expresiones y fórmulas están representadas por bloques matemáticos.
type: docs
weight: 7870
url: /es/net/aspose.slides.mathtext/mathblock/
---
## MathBlock class

Especifica una instancia de texto matemático contenido en un MathParagraph y comienza en su propia línea. Todas las zonas matemáticas, incluidas ecuaciones, expresiones, matrices de ecuaciones o expresiones y fórmulas, están representadas por bloques matemáticos.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Inicializa una nueva instancia de la clase MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Crea un nuevo bloque matemático y coloca elementos específicos en él |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Crea un nuevo bloque matemático y coloca el elemento especificado en él |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Obtiene el número de elementos matemáticos secundarios realmente contenidos en la colección. Solo lecturaInt32 . |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Devuelve falso porque la colección de elementos secundarios se puede modificar. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Obtiene o establece IMathElement en el índice especificado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Establece un acento (un carácter en la parte superior de este elemento) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Agrega un elemento matemático al final de la colección. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Toma la función especificada utilizando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Toma la función especificada utilizando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Toma la función especificada utilizando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Toma la función especificada utilizando esta instancia como argumento y el argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Toma la función especificada utilizando esta instancia como argumento y el argumento adicional especificado |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Elimina todos los elementos de la colección. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Determina si la colección contiene un valor específico. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Copiar a la matriz especificada. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Delimita los elementos secundarios con carácter separador (sin los corchetes) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Encierra un elemento matemático entre paréntesis |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Encierra elementos secundarios de este bloque en caracteres específicos como paréntesis u otros caracteres como framing |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Encierra elementos secundarios de este bloque en caracteres específicos como paréntesis u otro como framing y delimita con un carácter separador |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Toma una función de un argumento usando esta instancia como el nombre de función |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Toma una función de un argumento usando esta instancia como el nombre de función |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Obtener elementos secundarios |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Coloca este elemento en un grupo usando un corchete inferior |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento en un grupo usando un carácter de agrupación como corchete inferior u otro |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Determina el índice de un elemento matemático específico en la colección. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Inserta un MathElement en la colección en el índice especificado. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Toma la integral sin límites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Toma la integral |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Une un elemento matemático con este bloque matemático |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Une un texto matemático con este bloque matemático |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Une otro bloque matemático con este |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operador N-ario |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crea un operador N-ario |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Establece una barra en la parte superior de este elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Elimina la primera aparición de un objeto específico de la colección. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Elimina el elemento en el índice especificado de la colección. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Toma límite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Toma límite inferior |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crea subíndice |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crea subíndice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea subíndice y superíndice a la izquierda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crea subíndice y superíndice a la izquierda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea subíndice y superíndice a la derecha |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crea subíndice y superíndice a la derecha |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crea superíndice |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crea superíndice |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Toma límite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Toma límite superior |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Coloca este elemento en un border-box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento en un border-box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento en un cuadro no visual (agrupación lógica) que se usa para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto encuadrado puede (por ejemplo) servir como un emulador de operador con o sin alineación punto, servir como un punto de salto de línea, o agruparse para no permitir saltos de línea dentro. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Pone elementos secundarios en una matriz vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Establece una barra en la parte inferior de este elemento |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Guarda el contenido de este[`MathBlock`](../mathblock) como MathML |

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Ver también

* class [MathElementBase](../mathelementbase)
* interface [IMathBlock](../imathblock)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
