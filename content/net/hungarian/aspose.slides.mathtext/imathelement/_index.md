---
title: IMathElement
second_title: Aspose.Sildes .NET API referenciája
description: Bármely matematikai elem alapinterfésze, például tört, matematikai szöveg, függvény, több elemet tartalmazó kifejezés stb.
type: docs
weight: 8230
url: /hu/aspose.slides.mathtext/imathelement/
---
## IMathElement interfész

Alapértelmezett interfész bármely matematikai elemhez: tört, matematikai szöveg, függvény, többszörös elemekkel rendelkező kifejezés stb

```csharp
public interface IMathElement
```

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Beállít egy ékezetjelzőt (egy karakter az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Megkapja a megadott függvényt, amelyet ez a példány argumentumként használ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Megkapja a megadott függvényt, amelyet ez a példány argumentumként használ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Megkapja a megadott függvényt, amelyet ez a példány argumentumként használ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Megkapja a megadott függvényt, amelyet ez a példány argumentumként használ, és a megadott további argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Megkapja a megadott függvényt, amelyet ez a példány argumentumként használ, és a megadott további argumentumot |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Körbezár egy matematikai elemet zárójelbe |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Körbezárja ezt az elemet a megadott karakterekkel, például zárójelek vagy más karakterek |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Létrehoz egy függvényt az argumentummal, ahol a függvény neve ez a példány |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Létrehoz egy függvényt az argumentummal, ahol a függvény neve ez a példány |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Visszaadja a gyermekelemeket |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | A(z) alsó kapcsos zárójelet használva csoportba helyezi ezt az elemet |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | A(z) alsó kapcsos zárójelet vagy más csoportosító karaktert használva csoportba helyezi ezt az elemet |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Megkapja az integrált korlátok nélkül |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Megkapja az integrált |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Megkapja az integrált |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Megkapja az integrált |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Megkapja az integrált |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Összekapcsol egy matematikai elemet és matematikai blokkot hoz létre |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Összekapcsol egy matematikai szöveget és matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áris operátort |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áris operátort |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Beállít egy vonalat ennek az elemnek a tetején |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Megkapja az alsó határt |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Megkapja az alsó határt |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Létrehoz alsó indexet |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Létrehoz alsó indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Baloldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Baloldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobboldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Jobboldalon hoz létre alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Létrehoz felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Létrehoz felső indexet |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Megkapja a felső határt |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Megkapja a felső határt |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Ezt az elemet keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Ezt az elemet keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Ezt az elemet nem látható dobozba (logikai csoportosítás) helyezi, amelyet egy egyenlet vagy más matematikai szöveg részeinek csoportosítására használnak. Egy dobozba helyezett objektum például szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedjen sortörést benne. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Beállít egy vonalat ennek az elemnek az alján |

### Példák

Példa:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Lásd még

* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->