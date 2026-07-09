---
title: MathBlock
second_title: Referencia de API de Aspose.Sildes para .NET
description: Especifica una instancia de texto matemático que se encuentra dentro de un MathParagraph y comienza en su propia línea. Todas las zonas matemáticas, incluidas ecuaciones, expresiones, matrices de ecuaciones o expresiones y fórmulas, están representadas por un bloque matemático.
type: docs
weight: 8590
url: /es/aspose.slides.mathtext/mathblock/
---
## Clase MathBlock

Especifica una instancia de texto matemático que se encuentra dentro de un MathParagraph y comienza en su propia línea. Todas las zonas matemáticas, incluidas ecuaciones, expresiones, matrices de ecuaciones o expresiones y fórmulas, están representadas por un bloque matemático.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Inicializa una nueva instancia de la clase MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Crea un nuevo bloque matemático y coloca los elementos especificados en él |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Crea un nuevo bloque matemático y coloca el elemento especificado en él |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Obtiene el número de elementos matemáticos secundarios realmente contenidos en la colección. Sólo lectura Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Devuelve false porque la colección de elementos secundarios se puede modificar. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Obtiene o establece IMathElement en el índice especificado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Añade un elemento matemático al final de la colección. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Aplica la función especificada usando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Aplica la función especificada usando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Aplica la función especificada usando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Aplica la función especificada usando esta instancia como argumento y el argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Aplica la función especificada usando esta instancia como argumento y el argumento adicional especificado |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Elimina todos los elementos de la colección. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Determina si la colección contiene un valor específico. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Copia a la matriz especificada. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Delimita los elementos secundarios con el carácter separador (sin los corchetes) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Encierra un elemento matemático entre paréntesis |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Encierra los elementos secundarios de este bloque en los caracteres especificados, como paréntesis u otros caracteres como marco |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Encierra los elementos secundarios de este bloque en los caracteres especificados, como paréntesis u otros, y los delimita con un carácter separador |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Aplica una función de un argumento usando esta instancia como nombre de la función |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Aplica una función de un argumento usando esta instancia como nombre de la función |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Obtiene los elementos secundarios |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Coloca este elemento en un grupo usando una llave curva inferior |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento en un grupo usando un carácter de agrupación, como una llave curva inferior u otro |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Determina el índice de un elemento matemático específico en la colección. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Inserta un MathElement en la colección en el índice especificado. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Obtiene la integral sin límites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Obtiene la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Obtiene la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Obtiene la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Obtiene la integral |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Une un elemento matemático con este bloque matemático |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Une un texto matemático con este bloque matemático |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Une otro bloque matemático con este |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operador N-ario |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crea un operador N-ario |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Establece una barra en la parte superior de este elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Elimina la primera aparición de un objeto específico de la colección. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Elimina el elemento en el índice especificado de la colección. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Obtiene el límite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Obtiene el límite inferior |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crea subíndice |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crea subíndice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea subíndice y superíndice a la izquierda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crea subíndice y superíndice a la izquierda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea subíndice y superíndice a la derecha |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crea subíndice y superíndice a la derecha |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crea superíndice |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crea superíndice |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Obtiene el límite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Obtiene el límite superior |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Coloca este elemento en un cuadro con borde |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento en un cuadro con borde |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento en un cuadro no visual (agrupación lógica) que se usa para agrupar componentes de una ecuación u otro texto matemático. Un objeto en caja puede (por ejemplo) servir como emulador de operador con o sin punto de alineación, servir como punto de salto de línea, o agruparse de modo que no se permitan saltos de línea dentro. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Coloca los elementos secundarios en una matriz vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Establece una barra en la parte inferior de este elemento |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Guarda el contenido de este [`MathBlock`](../mathblock) como MathML |

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Ver también

* clase [MathElementBase](../mathelementbase)
* interfaz [IMathBlock](../imathblock)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->