---
title: MathElementBase
second_title: Aspose.Slides para .NET API Reference
description: Clase base para IMathElement con la implementación de algunos métodos que son comunes a todas las clases heredadas. Solo para uso interno. La clase heredada debe ser IMathElement.
type: docs
weight: 8420
url: /es/aspose.slides.mathtext/mathelementbase/
---

## Clase MathElementBase

Clase base para IMathElement con la implementación de algunos métodos que son comunes a todas las clases heredadas. Solo para uso interno. La clase heredada debe ser IMathElement.

```csharp
public abstract class MathElementBase : IMathElement
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | Toma la función especificada utilizando esta instancia como el argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Toma la función especificada utilizando esta instancia como el argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | Toma la función especificada utilizando esta instancia como el argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Toma la función especificada utilizando esta instancia como el argumento y el argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Toma la función especificada utilizando esta instancia como el argumento y el argumento adicional especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | Enclava un elemento matemático entre paréntesis |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | Enclava un elemento matemático en caracteres especificados como paréntesis o otros caracteres como marco |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | Toma una función de un argumento utilizando esta instancia como el nombre de la función |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | Toma una función de un argumento utilizando esta instancia como el nombre de la función |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | Coloca este elemento en un grupo utilizando una llave de cierre inferior |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento en un grupo utilizando un carácter de agrupación como llave de cierre inferior u otro |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | Toma la integral sin límites |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Toma la integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | Une un elemento matemático y forma un bloque matemático |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | Une un texto matemático y forma un bloque matemático |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operador N-ario |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | Crea un operador N-ario |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Establece una barra en la parte superior de este elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | Establece el límite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | Establece el límite inferior |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | Crea un subíndice |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | Crea un subíndice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea un subíndice y un superíndice a la izquierda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Crea un subíndice y un superíndice a la izquierda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea un subíndice y un superíndice a la derecha |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Crea un subíndice y un superíndice a la derecha |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | Crea un superíndice |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | Crea un superíndice |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | Establece el límite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | Establece el límite superior |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | Coloca este elemento en un border-box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento en un border-box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Coloca este elemento en una caja no visual (agrupamiento lógico) que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto en caja puede (por ejemplo) servir como un emulador de operador con o sin un punto de alineación, servir como un punto de quiebre de línea, o estar agrupado de tal manera que no permita quiebres de línea dentro. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Coloca en un arreglo vertical |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Establece una barra en la parte inferior de este elemento |

### Ver También

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->