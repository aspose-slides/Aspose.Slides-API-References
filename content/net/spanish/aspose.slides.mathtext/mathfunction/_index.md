---
title: MathFunction
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica una función de un argumento.
type: docs
weight: 8460
url: /es/aspose.slides.mathtext/mathfunction/
---

## Clase MathFunction

Especifica una función de un argumento.

```csharp
public sealed class MathFunction : MathElementBase, IMathFunction
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MathFunction](mathfunction#constructor)(IMathElement, IMathElement) | Inicializa una nueva instancia de la clase MathFunction. |
| [MathFunction](mathfunction#constructor_1)(string, IMathElement) | Inicializa una nueva instancia de la clase MathFunction. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathfunction/base) { get; } | Argumento de la función |
| [Name](../../aspose.slides.mathtext/mathfunction/name) { get; } | Nombre de la función. Por ejemplo, los nombres de funciones son sin y cos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Toma la función especificada usando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Toma la función especificada usando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Toma la función especificada usando esta instancia como argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Toma la función especificada usando esta instancia como argumento y el argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Toma la función especificada usando esta instancia como argumento y el argumento adicional especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Enclava un elemento matemático entre paréntesis |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Enclava un elemento matemático en caracteres especificados como paréntesis u otros caracteres como marco |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [GetChildren](../../aspose.slides.mathtext/mathfunction/getchildren)() | Obtiene los elementos hijos |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Coloca este elemento en un grupo usando una llave de cierre inferior |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento en un grupo usando un carácter de agrupación como llave de cierre inferior u otro |
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
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Especifica la raíz matemática de un grado dado del argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Especifica la raíz matemática de un grado dado del argumento especificado. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Toma el límite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Toma el límite inferior |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crea un subíndice |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crea un subíndice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea un subíndice y un superíndice a la izquierda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crea un subíndice y un superíndice a la izquierda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea un subíndice y un superíndice a la derecha |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crea un subíndice y un superíndice a la derecha |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crea un superíndice |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crea un superíndice |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Toma el límite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Toma el límite superior |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Coloca este elemento en un border-box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento en un border-box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento en una caja no visual (agrupación lógica) que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto en caja puede (por ejemplo) servir como un emulador de operador con o sin un punto de alineación, servir como un punto de ruptura de línea, o estar agrupado de manera que no permita rupturas de línea dentro. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Coloca en un arreglo vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Establece una barra en la parte inferior de este elemento |

### Ejemplos

Ejemplo:

```csharp
[C#]
MathFunction func = new MathFunction("sin", new MathematicalText("x"));
```

### Véase También

* clase [MathElementBase](../mathelementbase)
* interfaz [IMathFunction](../imathfunction)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->