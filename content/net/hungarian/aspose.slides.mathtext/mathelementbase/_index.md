---
title: MathElementBase
second_title: Aspose.Sildes .NET API referencia
description: Alap osztály az IMathElement számára, amely a minden örökölt osztályra jellemző néhány metódus megvalósítását tartalmazza. Csak belső használatra. Az örökölt osztálynak IMathElementnek kell lennie.
type: docs
weight: 8660
url: /hu/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase osztály

Alap osztály az IMathElement számára, amely a minden örökölt osztályra jellemző néhány metódus megvalósítását tartalmazza. Csak belső használatra. Az örökölt osztálynak IMMathElementnek kell lennie.

```csharp
public abstract class MathElementBase : IMathElement
```

## Módszerek

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akcentus jelet (egy karaktert ezen elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | Megadott függvényt hív meg, amely ezt az példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Megadott függvényt hív meg, amely ezt az példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | Megadott függvényt hív meg, amely ezt az példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Megadott függvényt hív meg, amely ezt az példányt használja argumentumként, és egy megadott további argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Megadott függvényt hív meg, amely ezt az példányt használja argumentumként, és egy megadott további argumentumot |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | Körülvesz egy matematikai elemet zárójelekbe |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | Körülvesz egy matematikai elemet a megadott karakterekkel, például zárójelek vagy más keretező karakterek |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | Megadott argumentumfüggvényt vesz, amely ezt az példányt használja függvénynévként |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | Megadott argumentumfüggvényt vesz, amely ezt az példányt használja függvénynévként |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | Ezt az elemet egy csoportba helyezi, az alsó kapcsos zárójel használatával |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Ezt az elemet egy csoportba helyezi, egy csoportosító karakter, például alsó kapcsos zárójel vagy más segítségével |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | Megkapja az integrált limitek nélkül |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Végrehajt egy integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | Végrehajt egy integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Végrehajt egy integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Végrehajt egy integrált |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | Összekapcsol egy matematikai elemet és létrehoz egy matematikai blokkot |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | Összekapcsol egy matematikai szöveget és létrehoz egy matematikai blokkot |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-operandus operátort |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-operandus operátort |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Beállít egy vonalat ennek az elemnek a tetején |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | Megadja a megadott fokú matematikai gyökeret a meghatározott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | Megadja a megadott fokú matematikai gyökeret a meghatározott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | Megkapja az alsó határt |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | Megkapja az alsó határt |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | Létrehoz alsó indexet |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | Létrehoz alsó indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon létrehoz alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Bal oldalon létrehoz alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | Létrehoz felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | Létrehoz felső indexet |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | Megkapja a felső határt |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | Megkapja a felső határt |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | Ezt az elemet egy keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Ezt az elemet egy keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Ezt az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy keretezett objektum (például) szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, szolgálhat sorvágás pontként, vagy úgy csoportosítható, hogy ne engedje meg a sortöréseket belül. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Beállít egy vonalat ennek az elemnek az alján |

### Lásd még

* interfész [IMathElement](../imathelement)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->