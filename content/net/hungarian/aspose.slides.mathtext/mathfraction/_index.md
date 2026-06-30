---
title: MathFraction
second_title: Aspose.Sildes .NET API referenciája
description: Megadja a tört objektumot, amely egy számlálóból és egy nevezőből áll, és egy törtvonallal van elválasztva. A törtvonal lehet vízszintes vagy átlós a tört tulajdonságaitól függően. A törtobjektumot a stack függvény ábrázolására is használják, amely egy elemet a másik fölé helyez, anélkül, hogy törtvonala lenne.
type: docs
weight: 8670
url: /hu/aspose.slides.mathtext/mathfraction/
---
## MathFraction osztály

Megadja a tört objektumot, amely egy számlálóból és egy nevezőből áll, amelyeket egy törtvonallal választ el. A törtvonal lehet vízszintes vagy átlós, a tört tulajdonságaitól függően. A tört objektumot a stack függvény ábrázolására is használják, amely egy elemet a másik fölé helyez, törtvonal nélkül.

```csharp
public sealed class MathFraction : MathElementBase, IMathFraction
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathFraction](mathfraction#constructor)(IMathElement, IMathElement) | Létrehozza a 'Bar' típusú MathFraction-t a megadott számlálóval és nevezővel |
| [MathFraction](mathfraction#constructor_1)(IMathElement, IMathElement, MathFractionTypes) | Létrehozza a MathFraction-t a megadott számlálóval, nevezővel és típussal |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Denominator](../../aspose.slides.mathtext/mathfraction/denominator) { get; } | Nevező |
| [FractionType](../../aspose.slides.mathtext/mathfraction/fractiontype) { get; set; } | Tört típus Alapértelmezett: Bar |
| [Numerator](../../aspose.slides.mathtext/mathfraction/numerator) { get; } | Számláló |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy ékezetjelet (karakter az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Alkalmazza a megadott függvényt, ezt a példányt argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Alkalmazza a megadott függvényt, ezt a példányt argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Alkalmazza a megadott függvényt, ezt a példányt argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Alkalmazza a megadott függvényt, ezt a példányt argumentumként használva, és a megadott további argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Alkalmazza a megadott függvényt, ezt a példányt argumentumként használva, és a megadott további argumentumot |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehozza a törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehozza a törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehozza a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehozza a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Közelez egy matematikai elemet zárójelek közé |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Közelez egy matematikai elemet megadott karakterekkel, például zárójelekkel vagy más keretező karakterekkel |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Alkalmaz egy argumentumfüggvényt, ez a példány a függvény neve |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Alkalmaz egy argumentumfüggvényt, ez a példány a függvény neve |
| [GetChildren](../../aspose.slides.mathtext/mathfraction/getchildren)() | Gyermekelemek lekérése |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Elhelyezi ezt az elemet egy csoportba, alsó kapcsos zárójel használatával |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Elhelyezi ezt az elemet egy csoportba, csoportosító karakterrel, például alsó kapcsos zárójellel vagy más |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Integrál határok nélkül |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrált vesz |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrált vesz |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrált vesz |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrált vesz |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet és egy matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget és egy matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehozza az N-áris operátort |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehozza az N-áris operátort |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Felső vonalat helyez el az elem tetején |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alulhatárt vesz |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alulhatárt vesz |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Létrehozza az alsó indexet |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Létrehozza az alsó indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon létrehozza az alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon létrehozza az alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon létrehozza az alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon létrehozza az alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Létrehozza a felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Létrehozza a felső indexet |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt vesz |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt vesz |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Elhelyezi ezt az elemet egy keretdobozba |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Elhelyezi ezt az elemet egy keretdobozba |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Elhelyezi ezt az elemet egy nincs látható dobozba (logikai csoportosítás), amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy keretezett objektum például szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, sorbreak pontként, vagy úgy csoportosítható, hogy ne engedélyezze a sortöréseket benne. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Alsó vonalat helyez el az elem alján |

### Példák

Example:

```csharp
[C#]
MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathFraction](../imathfraction)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->