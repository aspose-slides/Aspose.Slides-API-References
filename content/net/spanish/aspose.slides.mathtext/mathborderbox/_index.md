---
title: MathBorderBox
second_title: Referencia de la API de Aspose.Slides para .NET
description: Dibuja un borde rectangular u otro alrededor del IMathElement.
type: docs
weight: 8350
url: /es/aspose.slides.mathtext/mathborderbox/
---

## Clase MathBorderBox

Dibuja un borde rectangular u otro alrededor del IMathElement.

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | Crea el elemento MathBorderBox con borde rectangular |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | Crea el elemento MathBorderBox |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | Argumento base |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | Ocultar borde inferior (el valor predeterminado es falso) - especifica el estado oculto o visible del borde inferior del cuadro de borde. |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | Ocultar borde izquierdo (el valor predeterminado es falso) - especifica el estado oculto o visible del borde izquierdo del cuadro de borde. |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | Ocultar borde derecho (el valor predeterminado es falso) - especifica el estado oculto o visible del borde derecho del cuadro de borde. |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | Ocultar borde superior (el valor predeterminado es falso) - especifica el estado oculto o visible del borde superior del cuadro de borde. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | Tachar de abajo a la izquierda a arriba a la derecha (el valor predeterminado es falso). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina inferior izquierda hasta la esquina superior derecha del cuadro de borde. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | Tachar horizontal (el valor predeterminado es falso) - especifica el estado oculto o visible de una línea horizontal tachada. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | Tachar de arriba a la izquierda a abajo a la derecha (el valor predeterminado es falso). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina superior izquierda hasta la esquina inferior derecha del cuadro de borde. |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | Tachar vertical (el valor predeterminado es falso) - especifica el estado oculto o visible de una línea vertical tachada. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Toma la función especificada usando esta instancia como el argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Toma la función especificada usando esta instancia como el argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Toma la función especificada usando esta instancia como el argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Toma la función especificada usando esta instancia como el argumento y el argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Toma la función especificada usando esta instancia como el argumento y el argumento adicional especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Enclaustra un elemento matemático entre paréntesis |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Enclaustra un elemento matemático en los caracteres especificados, como paréntesis u otros caracteres como marco |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Toma una función de un argumento usando esta instancia como el nombre de la función |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Toma una función de un argumento usando esta instancia como el nombre de la función |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | Obtiene elementos hijos |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Coloca este elemento en un grupo usando una llave de apertura inferior |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento en un grupo usando un carácter de agrupamiento como llave de apertura inferior u otro |
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
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Especifica la raíz matemática del grado dado desde el argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Especifica la raíz matemática del grado dado desde el argumento especificado. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Toma el límite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Toma el límite inferior |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crea un subíndice |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crea un subíndice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea subíndice y superíndice a la izquierda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crea subíndice y superíndice a la izquierda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea subíndice y superíndice a la derecha |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crea subíndice y superíndice a la derecha |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crea un superíndice |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crea un superíndice |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Toma el límite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Toma el límite superior |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Coloca este elemento en un cuadro de borde |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento en un cuadro de borde |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento en una caja no visual (agrupamiento lógico) que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto en caja puede (por ejemplo) servir como un emulador de operador con o sin un punto de alineación, servir como un punto de quiebre de línea, o ser agrupado de manera que no permita quiebres de línea dentro. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Pone en un arreglo vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Establece una barra en la parte inferior de este elemento |

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### Véase También

* clase [MathElementBase](../mathelementbase)
* interfaz [IMathBorderBox](../imathborderbox)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->