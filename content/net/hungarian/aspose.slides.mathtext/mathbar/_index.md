---
title: MathBar
second_title: Aspose.Sildes .NET API hivatkozás
description: Meghatározza a vonal függvényt, amely egy alapargumentumból és egy felül vagy alul elhelyezett vonalból áll.
type: docs
weight: 8550
url: /hu/aspose.slides.mathtext/mathbar/
---
## MathBar osztály

Meghatározza a vonal függvényt, amely egy alapargumentumból és egy felül vagy alul elhelyezett vonalból áll.

```csharp
public sealed class MathBar : MathElementBase, IMathBar
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathBar](mathbar#constructor)(IMathElement) | Inicializálja a MathBar-t felső vonallal (Felső pozíció) |
| [MathBar](mathbar#constructor_1)(IMathElement, MathTopBotPositions) | Inicializálja a MathBar-t a megadott pozícióval |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathbar/base) { get; } | Alapargumentum |
| [Position](../../aspose.slides.mathtext/mathbar/position) { get; set; } | A vonal helye. Alapértelmezett: Felső |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akcentusjelzőt (egy karakter a elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Alkalmazza a megadott függvényt, ennek példányát argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Alkalmazza a megadott függvényt, ennek példányát argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Alkalmazza a megadott függvényt, ennek példányát argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Alkalmazza a megadott függvényt, ennek példányát argumentumként, valamint a megadott további argumentumot használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Alkalmazza a megadott függvényt, ennek példányát argumentumként, valamint a megadott további argumentumot használva |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Körbezár egy matematikai elemet zárójelek közé |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Körbezár egy matematikai elemet a megadott karakterekkel, például zárójelekkel vagy más keretező karakterekkel |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Alkalmazza az argumentum függvényét, ennek példányát függvénynévként használva |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Alkalmazza az argumentum függvényét, ennek példányát függvénynévként használva |
| [GetChildren](../../aspose.slides.mathtext/mathbar/getchildren)() | Lekéri a gyermekelemeket |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Ezt az elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Ezt az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójelez vagy más karakterrel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Alkalmazza a korlátok nélküli integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Alkalmazza az integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Alkalmazza az integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Alkalmazza az integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Alkalmazza az integrált |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet és egy matematikai blokká alakítja |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget és egy matematikai blokká alakítja |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-értékű operátort |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-értékű operátort |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Felső vonalat helyez az elem tetejére |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Lekéri az alsó határt |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Lekéri az alsó határt |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Létrehoz alsó indekset |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Létrehoz alsó indekset |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalra létrehoz alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalra létrehoz alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalra létrehoz alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalra létrehoz alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Létrehoz felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Létrehoz felső indexet |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Lekéri a felső határt |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Lekéri a felső határt |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy szegélyes dobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy szegélyes dobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amely az egyenlet vagy más matematikai szöveg komponenseinek csoportosítására szolgál. Egy dobozos objektum (például) operátorosémként használható igazítási ponttal vagy anélkül, sorvége jelzőként funkcionálhat, vagy úgy csoportosítható, hogy ne engedélyezze a sortöréseket belül. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömböt helyez be |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Alsó vonalat helyez az elem aljára |

### Példák

Példa:

```csharp
[C#]
MathBar mathBar = new MathBar(new MathematicalText("x"));
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathBar](../imathbar)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->