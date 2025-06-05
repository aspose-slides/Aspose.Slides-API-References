---
title: IMathElement
second_title: Referencia de la API de Aspose.Slides para .NET
description: Interfaz base de cualquier elemento matemático fracción, texto matemático, función, expresión con múltiples elementos, etc.
type: docs
weight: 7980
url: /es/aspose.slides.mathtext/imathelement/
---

## Interfaz IMathElement

Interfaz base de cualquier elemento matemático: fracción, texto matemático, función, expresión con múltiples elementos, etc.

```csharp
public interface IMathElement
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Toma la función especificada usando esta instancia como el argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Toma la función especificada usando esta instancia como el argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Toma la función especificada usando esta instancia como el argumento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Toma la función especificada usando esta instancia como el argumento y el argumento adicional especificado |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Toma la función especificada usando esta instancia como el argumento y el argumento adicional especificado |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Crea una fracción con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Enclava un elemento matemático entre paréntesis |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Enclava este elemento en caracteres especificados como paréntesis u otros caracteres como marco |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Toma una función de un argumento usando esta instancia como el nombre de la función |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Toma una función de un argumento usando esta instancia como el nombre de la función |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Obtiene elementos hijos |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Coloca este elemento en un grupo usando una llave de cierre inferior |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Coloca este elemento en un grupo usando un carácter de agrupación como una llave de cierre inferior u otro |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Toma la integral sin límites |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Toma la integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Toma la integral |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Une un elemento matemático y forma un bloque matemático |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Une un texto matemático y forma un bloque matemático |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operador N-ario |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Crea un operador N-ario |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Establece una barra en la parte superior de este elemento |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Especifica la raíz matemática del grado dado del argumento especificado. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Especifica la raíz matemática del grado dado del argumento especificado. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Toma el límite inferior |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Toma el límite inferior |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Crea un subíndice |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Crea un subíndice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea un subíndice y un superíndice a la izquierda |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Crea un subíndice y un superíndice a la izquierda |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea un subíndice y un superíndice a la derecha |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Crea un subíndice y un superíndice a la derecha |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Crea un superíndice |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Crea un superíndice |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Toma el límite superior |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Toma el límite superior |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Coloca este elemento en un border-box |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Coloca este elemento en un border-box |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Coloca este elemento en una caja no visual (agrupación lógica) que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático. Un objeto en caja puede (por ejemplo) servir como un emulador de operador con o sin un punto de alineación, servir como un punto de quiebre de línea, o estar agrupado de tal manera que no permita quiebres de línea dentro. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Coloca en un arreglo vertical |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Establece una barra en la parte inferior de este elemento |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Ver También

* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->