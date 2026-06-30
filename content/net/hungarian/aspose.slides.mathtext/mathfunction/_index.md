---
title: MathFunction
second_title: Aspose.Sildes a .NET API hivatkozás
description: Megad egy argumentum függvényét.
type: docs
weight: 8700
url: /hu/aspose.slides.mathtext/mathfunction/
---
## MathFunction osztály

Specifies a function of an argument.

```csharp
public sealed class MathFunction : MathElementBase, IMathFunction
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathFunction](mathfunction#constructor)(IMathElement, IMathElement) | Inicializál egy új példányt a MathFunction osztályból. |
| [MathFunction](mathfunction#constructor_1)(string, IMathElement) | Inicializál egy új példányt a MathFunction osztályból. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathfunction/base) { get; } | Függvény argumentuma |
| [Name](../../aspose.slides.mathtext/mathfunction/name) { get; } | Függvény neve Például a függvénynevek a sin és a cos |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy ékezetjelet (egy karakter az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megadott függvényt használ, amelynek argumentuma ez a példány. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megadott függvényt használ, amelynek argumentuma ez a példány. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megadott függvényt használ, amelynek argumentuma ez a példány. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megadott függvényt használ, amelynek argumentuma ez a példány, valamint egy megadott további argumentum. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megadott függvényt használ, amelynek argumentuma ez a példány, valamint egy megadott további argumentum. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy törtet a megadott típusban ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy törtet a megadott típusban ezzel a számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelez egy matematikai elemet. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Zárójelez egy matematikai elemet a megadott karakterekkel, például zárójelek vagy más karakterek keretezésére. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Egy argumentumfüggvényt vesz fel, amelynek függvényneve ez a példány. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Egy argumentumfüggvényt vesz fel, amelynek függvényneve ez a példány. |
| [GetChildren](../../aspose.slides.mathtext/mathfunction/getchildren)() | Lekéri a gyermekelemeket. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Egy alsó kapcsos záróval csoportba helyezi ezt az elemet. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Csoportba helyezi ezt az elemet egy csoportosító karakter segítségével, például alsó kapcsos záróval vagy más karakterrel. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Megkapja az integrált korlátok nélkül. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Megkapja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Megkapja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Megkapja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Megkapja az integrált. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet és egy matematikai blokkot hoz létre. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget és egy matematikai blokkot hoz létre. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áris operátort. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áris operátort. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Felső vonalat helyez az elem tetejére. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Megveszi az alsó határt. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Megveszi az alsó határt. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Létrehoz alsó indexet. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Létrehoz alsó indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon létrehoz alsó és felső indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon létrehoz alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon létrehoz alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon létrehoz alsó és felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Létrehoz felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Létrehoz felső indexet. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Megveszi a felső határt. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Megveszi a felső határt. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Ezt az elemet egy keretdobozba helyezi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Ezt az elemet egy keretdobozba helyezi. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Ezt az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi, amelyet egy egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy dobozos objektum például szolgálhat operátor emulátoraként igazítási pont nélkül vagy ponttal, szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedje meg a sortöréseket benne. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Alsó vonalat helyez az elem aljára. |

### Példák

Example:

```csharp
[C#]
MathFunction func = new MathFunction("sin", new MathematicalText("x"));
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathFunction](../imathfunction)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->