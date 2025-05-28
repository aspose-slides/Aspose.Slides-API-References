---
title: MathNaryOperator
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica un objeto matemático N-ario como Suma e Integral. Consiste en un operador, una base o operando y límites superiores e inferiores opcionales. Ejemplos de operadores N-arios son Suma, Unión, Intersección, Integral
type: docs
weight: 8610
url: /es/aspose.slides.mathtext/mathnaryoperator/
---

## Clase MathNaryOperator

Especifica un objeto matemático N-ario, como Suma e Integral. Consiste en un operador, una base (o operando) y límites superiores e inferiores opcionales. Ejemplos de operadores N-arios son: Suma, Unión, Intersección, Integral

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | Inicializa una nueva instancia de la clase MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | Inicializa una nueva instancia de la clase MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | Inicializa una nueva instancia de la clase MathNaryOperator. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | Argumento base |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | El carácter del operador crece verticalmente para coincidir con la altura de su operando |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | Ocultar subíndice |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | Ocultar superíndice |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | La ubicación de los límites (subíndice y superíndice) |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | Carácter del operador N-ario Por ejemplo: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | Especifica un argumento de subíndice que, por ejemplo, en el caso de un integral, establece el límite inferior |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | Especifica un argumento de superíndice que, por ejemplo, en el caso de un integral, establece el límite superior |

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
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Encierra un elemento matemático entre paréntesis |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Encierra un elemento matemático entre caracteres especificados como paréntesis u otros caracteres para enmarcar |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Toma una función de un argumento usando esta instancia como nombre de función |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Toma una función de un argumento usando esta instancia como nombre de función |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | Obtiene los elementos hijos |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Coloca este elemento en un grupo utilizando una llave de cierre inferior |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento en un grupo utilizando un carácter de agrupación como una llave de cierre inferior u otro |
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
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Toma el límite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Toma el límite inferior |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crea subíndice |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crea subíndice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea subíndice y superíndice a la izquierda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crea subíndice y superíndice a la izquierda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea subíndice y superíndice a la derecha |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crea subíndice y superíndice a la derecha |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crea superíndice |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crea superíndice |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Toma el límite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Toma el límite superior |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Coloca este elemento en un cuadro de borde |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento en un cuadro de borde |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento en una caja no visual (agrupación lógica) que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto en caja puede (por ejemplo) servir como un emulador de operador con o sin un punto de alineación, servir como un punto de salto de línea, o agruparse de tal modo que no se permita saltos de línea dentro. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Coloca en una matriz vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Establece una barra en la parte inferior de este elemento |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### Ver también

* clase [MathElementBase](../mathelementbase)
* interfaz [IMathNaryOperator](../imathnaryoperator)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->