---
title: MathFraction
second_title: Aspose.Sildes .NET API referencia
description: Megadja a tört objektumot, amely egy számlálóból és nevezőből áll, és egy törtvonal választja el őket. A törtvonal lehet vízszintes vagy átlós, a tört tulajdonságaitól függően. A tört objektumot a stack függvény ábrázolására is használják, amely egy elemet a másik fölé helyez, törtvonal nélkül.
type: docs
weight: 8690
url: /hu/aspose.slides.mathtext/mathfraction/
---
## MathFraction osztály

Megadja a tört objektumot, amely egy számlálóból és nevezőből áll, és egy törtvonal választja el őket. A törtvonal lehet vízszintes vagy átlós, a tört tulajdonságaitól függően. A tört objektumot a stack függvény ábrázolására is használják, amely egy elemet a másik fölé helyez, törtvonal nélkül.

```csharp
public sealed class MathFraction : MathElementBase, IMathFraction
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathFraction](mathfraction#constructor)(IMathElement, IMathElement) | Inicializál egy 'Bar' típusú MathFraction objektumot a megadott számlálóval és nevezővel |
| [MathFraction](mathfraction#constructor_1)(IMathElement, IMathElement, MathFractionTypes) | Inicializál egy MathFraction objektumot a megadott számlálóval, nevezővel és típussal |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Denominator](../../aspose.slides.mathtext/mathfraction/denominator) { get; } | Nevező |
| [FractionType](../../aspose.slides.mathtext/mathfraction/fractiontype) { get; set; } | Tört típus Alapértelmezett: Bar |
| [Numerator](../../aspose.slides.mathtext/mathfraction/numerator) { get; } | Számláló |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy ékezetjelzőt (egy karakter az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Végrehajtja a megadott függvényt, az aktuális példányt argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Végrehajtja a megadott egy argumentumos függvényt, az aktuális példányt argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Végrehajtja a megadott függvényt, az aktuális példányt argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Végrehajtja a megadott két argumentumos függvényt, az aktuális példányt első argumentumként, a megadott további argumentumot másodikként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Végrehajtja a megadott két argumentumos függvényt, az aktuális példányt első argumentumként, a megadott további argumentumot másodikként használva |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz a megadott típussal egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz a megadott típussal egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelez egy matematikai elemet |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Zárójelez egy matematikai elemet a megadott karakterekkel, például zárójelek vagy egyéb keretező karakterek |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Egy argumentumfüggvényt vesz, az aktuális példányt a függvényneveként használva |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Egy argumentumfüggvényt vesz, az aktuális példányt a függvényneveként használva |
| [GetChildren](../../aspose.slides.mathtext/mathfraction/getchildren)() | Lekéri a gyermekelemeket |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Csoportba helyezi ezt az elemet egy alsó kapcsos zárójelettel |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Csoportba helyezi ezt az elemet egy csoportosító karakterrel, például alsó kapcsos zárójelettel vagy egyébként |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | A határozatlan integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet és matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget és matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-értékű operátort |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-értékű operátort |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Felső vonalat helyez el ezen az elemen |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott argumentumból a megadott fokú matematikai gyököt |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott argumentumból a megadott fokú matematikai gyököt |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határértéket vesz |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határértéket vesz |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határértéket vesz |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határértéket vesz |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Egy keretdobozba helyezi ezt az elemet |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Egy keretdobozba helyezi ezt az elemet |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Egy nem vizuális (logikai csoportosító) dobozba helyezi ezt az elemet, amelyet egyenletek vagy más matematikai szöveg részeinek csoportosítására használnak. Egy doboz objektum például operátor emulátorként szolgálhat igazítási pont nélkül vagy ponttal, vonaltörés pontként funkcionálhat, vagy úgy csoportosítható, hogy ne engedélyezze a sorok megtörését benne. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Alsó vonalat helyez el ezen az elemen |

### Példák

Példa:

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