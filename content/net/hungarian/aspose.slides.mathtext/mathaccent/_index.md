---
title: MathAccent
second_title: Aspose.Sildes .NET API hivatkozása
description: Meghatározza a hangsúly függvényt, amely egy alapból és egy kombináló diakritikus jelből áll. Példa: ́
type: docs
weight: 8510
url: /hu/aspose.slides.mathtext/mathaccent/
---
## MathAccent osztály

Meghatározza a hangsúlyozási funkciót, amely egy alapból és egy kombináló diakritikus jelből áll. Példa: 𝑎́

```csharp
public sealed class MathAccent : MathElementBase, IMathAccent
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathAccent](mathaccent#constructor)(IMathElement) | Létrehoz egy matematikai hangsúlyt, amely a megadott matematikai elemhez alkalmazódik az alapértelmezett hangsúlykarakter értékkel. |
| [MathAccent](mathaccent#constructor_1)(IMathElement, char) | Létrehoz egy matematikai hangsúlyt, amely a megadott matematikai elemhez alkalmazódik. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathaccent/base) { get; } | Az argumentum, amelyhez a hangsúly alkalmazva lett. |
| [Character](../../aspose.slides.mathtext/mathaccent/character) { get; set; } | Hangsúlykarakter. Az értéknek a (U+0300–U+036F) vagy (U+20D0–U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Kombináló körző hangsúly (U+0302). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy hangsúlyjelet (egy karakter, amely az elem tetején jelenik meg). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | A megadott függvényt veszi, az aktuális példányt használva argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | A megadott függvényt veszi, az aktuális példányt használva argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | A megadott függvényt veszi, az aktuális példányt használva argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | A megadott függvényt veszi, az aktuális példányt használja argumentumként, valamint a megadott további argumentumot. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | A megadott függvényt veszi, az aktuális példányt használja argumentumként, valamint a megadott további argumentumot. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Közé zár egy matematikai elemet zárójelbe. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Közé zár egy matematikai elemet a megadott karakterekkel, például zárójellel vagy más karakterekkel keretezve. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Az argumentum függvényét veszi, az aktuális példányt használva függvényneveként. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Az argumentum függvényét veszi, az aktuális példányt használva függvényneveként. |
| [GetChildren](../../aspose.slides.mathtext/mathaccent/getchildren)() | Lekéri a gyermekelemeket. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójelekkel vagy más karakterrel. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Az integrált veszi határok nélkül. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összevon egy matematikai elemet és létrehoz egy matematikai blokkot. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összevon egy matematikai szöveget és létrehoz egy matematikai blokkot. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áramú operátort. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áramú operátort. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Feltűz egy vonalat az elem tetejére. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Az alsó határt veszi. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Az alsó határt veszi. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Balra hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Balra hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobbra hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobbra hoz létre alsó és felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | A felső határt veszi. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | A felső határt veszi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretdobozba helyezi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretdobozba helyezi. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy dobozba helyezett objektum például operátor emulátorként szolgálhat igazítási ponttal vagy anélkül, sorvége pontként működhet, vagy úgy csoportosítható, hogy ne engedélyezze a sorok törését benne. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Feltűz egy vonalat az elem aljára. |

### Példák

```csharp
[C#]
IMathElement baseElement = new MathematicalText("x");
MathAccent accent = new MathAccent(baseElement, '~');
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathAccent](../imathaccent)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->