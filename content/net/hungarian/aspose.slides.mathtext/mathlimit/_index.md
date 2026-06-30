---
title: MathLimit
second_title: Aspose.Sildes .NET API Referencia
description: Megadja a Limit objektumot, amely a vonal alapján lévő szöveget és azt közvetlenül fölötte vagy alatta elhelyezkedő, kisebb méretű szöveget tartalmazza.
type: docs
weight: 8800
url: /hu/aspose.slides.mathtext/mathlimit/
---
## MathLimit osztály

Megadja a Limit objektumot, amely a vonal alatti szöveget és az azonnal fölötte vagy alatta elhelyezkedő, kisebb méretű szöveget tartalmazza.

```csharp
public sealed class MathLimit : MathElementBase, IMathLimit
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathLimit](mathlimit#constructor)(IMathElement, IMathElement) | Új példányt hoz létre a MathLimit osztályból alsó határral |
| [MathLimit](mathlimit#constructor_1)(IMathElement, IMathElement, bool) | Új példányt hoz létre a MathLimit osztályból. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathlimit/base) { get; } | Alap argumentum |
| [Limit](../../aspose.slides.mathtext/mathlimit/limit) { get; } | Határ argumentum |
| [UpperLimit](../../aspose.slides.mathtext/mathlimit/upperlimit) { get; set; } | Megadja a felső vagy alsó határt |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Akcentusjelet (karaktert az elem tetején) állít be |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megadott függvényt alkalmaz, ahol ez az példány az argumentum |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megadott függvényt alkalmaz, ahol ez az példány az argumentum |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megadott függvényt alkalmaz, ahol ez az példány az argumentum |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megadott függvényt alkalmaz, ahol ez az példány az argumentum, és egy megadott további argumentum |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megadott függvényt alkalmaz, ahol ez az példány az argumentum, és egy megadott további argumentum |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Törtet hoz létre ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Törtet hoz létre ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | A megadott típusú törtet hoz létre ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | A megadott típusú törtet hoz létre ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Matematikai elemet zárójelek közé tesz |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Matematikai elemet a megadott karakterek közé zárja, például zárójelek vagy egyéb keret karakterek |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Argumentum függvényt hoz létre, ahol ez az példány a függvény neve |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Argumentum függvényt hoz létre, ahol ez az példány a függvény neve |
| [GetChildren](../../aspose.slides.mathtext/mathlimit/getchildren)() | Gyermekelemeket kap |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi alsó kapcsos zárójel használatával |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi a megadott csoportosító karakterrel, például alsó kapcsos zárójel vagy egyéb |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Integrált vesz fel határok nélkül |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrált vesz fel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrált vesz fel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrált vesz fel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrált vesz fel |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Matematikai elemet kapcsol össze és matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematikai szöveget kapcsol össze és matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-áris operátort hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-áris operátort hoz létre |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Vonalat helyez az elem tetejére |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határt vesz fel |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határt vesz fel |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt vesz fel |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt vesz fel |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretmezőbe helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretmezőbe helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy dobozba helyezett objektum például szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, szolgálhat sorvágási pontként, vagy úgy csoportosítható, hogy ne engedélyezze a sorok törését benne. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Vonalat helyez az elem aljára |

### Példák

Példa:

```csharp
[C#]
MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("𝑛→∞"));
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathLimit](../imathlimit)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->