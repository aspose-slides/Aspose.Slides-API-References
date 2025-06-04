---
title: MathBox
second_title: Aspose.Slid es para .NET API Reference
description: Especifica el empaquetado lógico de elementos matemáticos. Por ejemplo, un objeto enmarcado puede servir como un emulador de operador con o sin un punto de alineación, servir como un punto de salto de línea o ser agrupado de tal manera que no permita saltos de línea dentro. Por ejemplo, el operador "==" debería estar enmarcado para evitar saltos de línea.
type: docs
weight: 8370
url: /es/aspose.slides.mathtext/mathbox/
---

## MathBox class

Especifica el empaquetado lógico (packaging) de elementos matemáticos. Por ejemplo, un objeto enmarcado puede servir como un emulador de operador con o sin un punto de alineación, servir como un punto de salto de línea, o ser agrupado de tal manera que no se permitan saltos de línea dentro. Por ejemplo, el operador "==" debería estar enmarcado para prevenir saltos de línea.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Constructors

| Nombre | Descripción |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Inicializa MathBox con el elemento especificado como argumento |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Cuando es verdadero, este emulador de operador sirve como un punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. Predeterminado: falso |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Argumento base |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Diferencial Cuando es verdadero, la caja actúa como un diferencial (por ejemplo, 𝑑𝑥 en un integrando), y recibe el espaciado horizontal adecuado para el diferencial matemático. Predeterminado: falso |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Un salto explícito especifica si hay un salto de línea al inicio del objeto Box, de tal manera que la línea se envuelve al inicio del objeto box. Especifica el número del operador en la línea anterior de texto matemático que se utilizará como punto de alineación para la línea actual de texto matemático. valores posibles: 1..255 Predeterminado: 0 (sin salto explícito) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Sin ruptura Esta propiedad especifica la propiedad "no rompible" en el objeto box. Cuando es verdadero, no pueden ocurrir saltos de línea dentro de la caja. Esto puede ser importante para emuladores de operadores que consisten en más de un operador binario. Cuando este elemento no se especifica, pueden ocurrir rupturas dentro de la caja. Predeterminado: verdadero |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Emulador de operador. Cuando es verdadero, la caja y su contenido se comportan como un solo operador e heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como un punto para un salto de línea y puede alinearse con otros operadores. Los emuladores de operadores se utilizan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: falso |

## Methods

| Nombre | Descripción |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Toma la función especificada utilizando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Toma la función especificada utilizando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Toma la función especificada utilizando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Toma la función especificada utilizando esta instancia como argumento y el argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Toma la función especificada utilizando esta instancia como argumento y el argumento adicional especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Encierra un elemento matemático entre paréntesis |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Encierra un elemento matemático en caracteres específicos como paréntesis u otros caracteres como marco |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Toma una función de un argumento utilizando esta instancia como el nombre de la función |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Toma una función de un argumento utilizando esta instancia como el nombre de la función |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Obtiene elementos hijos |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Coloca este elemento en un grupo utilizando una llave de cierre inferior |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento en un grupo utilizando un carácter de agrupamiento como llave de cierre inferior u otro |
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
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Especifica la raíz matemática del grado dado del argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Especifica la raíz matemática del grado dado del argumento especificado. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Toma un límite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Toma un límite inferior |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crea un subíndice |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crea un subíndice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea un subíndice y un superíndice a la izquierda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crea un subíndice y un superíndice a la izquierda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea un subíndice y un superíndice a la derecha |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crea un subíndice y un superíndice a la derecha |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crea un superíndice |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crea un superíndice |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Toma un límite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Toma un límite superior |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Coloca este elemento en un border-box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento en un border-box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento en una caja no visual (agrupación lógica) que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto enmarcado puede (por ejemplo) servir como un emulador de operador con o sin un punto de alineación, servir como un punto de salto de línea, o ser agrupado de tal manera que no se permiten saltos de línea dentro. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Pone en un arreglo vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Establece una barra en la parte inferior de este elemento |

### Examples

Ejemplo:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### See Also

* class [MathElementBase](../mathelementbase)
* interface [IMathBox](../imathbox)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->