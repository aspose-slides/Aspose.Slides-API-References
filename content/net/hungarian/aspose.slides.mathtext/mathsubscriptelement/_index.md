---
title: MathSubscriptElement
second_title: Aspose.Sildes .NET API referenciája
description: Megadja az alsó index objektumot, amely egy alapból és egy kisebb méretű, alulra és jobbra elhelyezett alsó indexből áll.
type: docs
weight: 8980
url: /hu/aspose.slides.mathtext/mathsubscriptelement/
---
## MathSubscriptElement osztály

Megadja az alsó index objektumot, amely egy alapból és egy kisebb méretű, alulra és jobbra elhelyezett alsó indexből áll.

```csharp
public sealed class MathSubscriptElement : BaseScript, IMathSubscriptElement
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathSubscriptElement](mathsubscriptelement)(IMathElement, IMathElement) | Inicializál egy új példányt a MathSubscriptElement osztályból. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Alap argumentum |
| [Subscript](../../aspose.slides.mathtext/mathsubscriptelement/subscript) { get; } | Alsóindex |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akcentusjelet (a karaktert az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megkapja a megadott függvényt, amely ezt az példányt argumentumként használja |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megkapja a megadott függvényt, amely ezt az példányt argumentumként használja |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megkapja a megadott függvényt, amely ezt az példányt argumentumként használja |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megkapja a megadott függvényt, amely ezt az példányt argumentumként és a megadott további argumentumot használja |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megkapja a megadott függvényt, amely ezt az példányt argumentumként és a megadott további argumentumot használja |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Egy matematikai elemet zárójelbe helyez |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Egy matematikai elemet a megadott karakterek közé helyez, például zárójelek vagy egyéb karakterek közé |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Megkap egy argumentumfüggvényt, amely ezt a példányt a függvény nevének használja |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Megkap egy argumentumfüggvényt, amely ezt a példányt a függvény nevének használja |
| [GetChildren](../../aspose.slides.mathtext/mathsubscriptelement/getchildren)() | Lekéri a gyermekelemeket |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi, az alsó kapcsos zárójelet használva |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Az integrált határok nélkül veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Egy matematikai elemet összevon és egy matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematikai szöveget összekapcsol és egy matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-áris operátort hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-áris operátort hoz létre |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Egy vonalat helyez az elem tetejére |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határt vesz |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határt vesz |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt vesz |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt vesz |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi, amely egyenlet vagy egyéb matematikai szöveg komponenseinek csoportosítására szolgál. Egy dobozba helyezett objektum például operátor emulátorként szolgálhat igazítási pont nélkül vagy ponttal, sorbontási pontként működhet, vagy úgy csoportosítható, hogy ne engedélyezzen sorbontást |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Egy vonalat helyez az elem aljára |

### Példák

Példa:

```csharp
[C#]
MathSubscriptElement subscriptElement = new MathematicalText("N").SetSubscript("i");
```

### Lásd még

* osztály [BaseScript](../basescript)
* interfész [IMathSubscriptElement](../imathsubscriptelement)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->