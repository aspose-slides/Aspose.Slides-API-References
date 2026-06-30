---
title: MathematicalText
second_title: Aspose.Sildes .NET API referenciája
description: Matematikai szöveg
type: docs
weight: 9040
url: /hu/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText osztály

Matematikai szöveg

```csharp
public sealed class MathematicalText : MathElementBase, IMathematicalText
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathematicalText](mathematicaltext#constructor)() | Alapértelmezett konstruktor (létrehozza a String.Empty értéket) |
| [MathematicalText](mathematicaltext#constructor_1)(char) | MathText létrehozása egyetlen szimbólummal |
| [MathematicalText](mathematicaltext#constructor_2)(string) | MathematicalText létrehozása szövegből |
| [MathematicalText](mathematicaltext#constructor_3)(string, IPortionFormat) | MathematicalText létrehozása szövegből és formázási beállításokból |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Format](../../aspose.slides.mathtext/mathematicaltext/format) { get; } | Szöveg formázási tulajdonságok |
| [Value](../../aspose.slides.mathtext/mathematicaltext/value) { get; set; } | Szöveg értéke |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ékezetjel beállítása (karakter az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megadott függvényt használ az aktuális példányt argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megadott függvényt használ az aktuális példányt argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megadott függvényt használ az aktuális példányt argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megadott függvényt használ az aktuális példányt argumentumként, és egy megadott további argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megadott függvényt használ az aktuális példányt argumentumként, és egy megadott további argumentumot |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tört létrehozása a jelenlegi számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tört létrehozása a jelenlegi számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | A megadott típusú tört létrehozása a jelenlegi számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | A megadott típusú tört létrehozása a jelenlegi számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Matematikai elemet zárójelek közé helyez |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Matematikai elemet megadott karakterek (például zárójelek vagy más karakterek) közé keretezi |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Függvényt kap argumentumból, az aktuális példányt függvényneveként használva |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Függvényt kap argumentumból, az aktuális példányt függvényneveként használva |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Alsó kapcsos zárójelet használva csoportba helyezi ezt az elemet |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Határok nélküli integrált vesz fel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrált vesz fel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrált vesz fel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrált vesz fel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrált vesz fel |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Matematikai elemet csatlakoztat, és matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematikai szöveget csatlakoztat, és matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-áris operátort hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-áris operátort hoz létre |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Vonalat helyez az elem tetejére |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határvonalat vesz fel |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határvonalat vesz fel |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon alsó- és felsőindexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon alsó- és felsőindexet hoz létre |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon alsó- és felsőindexet hoz létre |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon alsó- és felsőindexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határvonalat vesz fel |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határvonalat vesz fel |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretes dobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretes dobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet nem vizuális dobozba (logikai csoportosítás) helyezi, amely egyenlet vagy más matematikai szöveg komponenseinek csoportosítására szolgál. Egy dobozobjektum például operátorémulátorként használható igazítási ponttal vagy anélkül, sortöréspontként, vagy úgy csoportosítható, hogy ne engedje a sorok tördelését. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Vonalat helyez az elem aljára |

### Példák

Példa:

```csharp
[C#]
MathematicalText mathText = new MathematicalText("x+y");
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathematicalText](../imathematicaltext)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->