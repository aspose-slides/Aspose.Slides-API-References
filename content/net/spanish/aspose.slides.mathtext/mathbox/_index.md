---
title: MathBox
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica el encuadre lógico empaquetado del elemento matemático. Por ejemplo un objeto encuadrado puede servir como un emulador de operador con o sin un punto de alineación servir como un punto de interrupción de línea o agruparse para no permitir saltos de línea within. Por ejemplo el operador  debe estar encuadrado para evitar saltos de línea.
type: docs
weight: 7910
url: /es/aspose.slides.mathtext/mathbox/
---
## MathBox class

Especifica el encuadre lógico (empaquetado) del elemento matemático. Por ejemplo, un objeto encuadrado puede servir como un emulador de operador con o sin un punto de alineación, servir como un punto de interrupción de línea o agruparse para no permitir saltos de línea within. Por ejemplo, el operador "==" debe estar encuadrado para evitar saltos de línea.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Inicializa MathBox con el elemento especificado como argumento |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Cuando es verdadero, este emulador de operador sirve como punto de alineación; es decir, puntos de alineación designados en otras ecuaciones se pueden alinear con él. Valor predeterminado: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Argumento base |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Diferencial Cuando es verdadero, el cuadro actúa como un diferencial (p. ej., 𝑑𝑥 en un integrando) y recibe el espacio horizontal adecuado para el diferencial matemático. Valor predeterminado: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Salto explícito especifica si hay un salto de línea al comienzo del objeto de cuadro, tal que la línea se ajusta al comienzo del objeto de cuadro. Especifica el número del operador en la línea anterior de texto matemático que se utilizará como el punto de alineación para la línea actual de texto matemático valores posibles: 1..255 Predeterminado: 0 (sin corte explícito) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Sin interrupción Esta propiedad especifica la propiedad "irrompible" en el cuadro del objeto. Cuando es verdadero, no se pueden producir saltos de línea dentro del cuadro. Esto puede ser importante para los emuladores de operadores que constan de más de un operador binario. Cuando no se especifica este elemento, pueden producirse rupturas dentro del cuadro. Valor predeterminado: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Emulador de operador. Cuando es verdadero, el cuadro y su contenido se comportan como un solo operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto para un salto de línea y puede alinearse con otros operadores. Los emuladores de operadores se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '==' . Valor por defecto: false |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Establece un acento (un carácter en la parte superior de este elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Toma la función especificada utilizando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Toma la función especificada utilizando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Toma la función especificada utilizando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Toma la función especificada utilizando esta instancia como argumento y el argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Toma la función especificada utilizando esta instancia como argumento y el argumento adicional especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Encierra un elemento matemático entre paréntesis |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Encierra un elemento matemático en caracteres específicos como paréntesis u otros caracteres como framing |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Toma una función de un argumento usando esta instancia como el nombre de función |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Toma una función de un argumento usando esta instancia como el nombre de función |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Obtener elementos secundarios |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Coloca este elemento en un grupo usando un corchete inferior |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento en un grupo usando un carácter de agrupación como corchete inferior u otro |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Toma la integral sin límites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Toma la integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Une un elemento matemático y forma un bloque matemático |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Une un texto matemático y forma un bloque matemático |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operador N-ario |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crea un operador N-ario |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Establece una barra en la parte superior de este elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
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
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Pone en una matriz vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Establece una barra en la parte inferior de este elemento |

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Ver también

* class [MathElementBase](../mathelementbase)
* interface [IMathBox](../imathbox)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
