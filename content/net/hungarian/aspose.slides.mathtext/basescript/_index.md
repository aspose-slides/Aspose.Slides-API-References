---
title: BaseScript
second_title: Aspose.Sildes .NET API Referenciája
description: Matematikai szkript
type: docs
weight: 8050
url: /hu/aspose.slides.mathtext/basescript/
---
## BaseScript osztály

Matematikai szkript

```csharp
public abstract class BaseScript : MathElementBase
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Alap argumentum |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy ékezetet (karakter az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Elfogadja a megadott függvényt, amely ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Elfogadja a megadott függvényt, amely ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Elfogadja a megadott függvényt, amely ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Elfogadja a megadott függvényt, amely ezt a példányt használja argumentumként, és a megadott további argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Elfogadja a megadott függvényt, amely ezt a példányt használja argumentumként, és a megadott további argumentumot |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy törtet a megadott típusban ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy törtet a megadott típusban ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Körbezárja a matematikai elemet zárójelekbe |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Körbezár egy matematikai elemet megadott karakterekkel, például zárójelekbe vagy más karakterekbe |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Elfogad egy argumentumfüggvényt, amely ezt a példányt használja függvénynévként |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Elfogad egy argumentumfüggvényt, amely ezt a példányt használja függvénynévként |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi alsó kapcsos zárójel használatával |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más karakter |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Elfogadja az integrált határok nélkül |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Elfogadja az integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Elfogadja az integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Elfogadja az integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Elfogadja az integrált |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet és matematikai blokká alakítja |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget és matematikai blokká alakítja |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áris operátort |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áris operátort |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Beállít egy vonalat az elem tetejére |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Elfogadja az alsó határt |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Elfogadja az alsó határt |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Létrehoz alsó indexet |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Létrehoz alsó indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon létrehoz alsó- és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon létrehoz alsó- és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon létrehoz alsó- és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon létrehoz alsó- és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Létrehoz felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Létrehoz felső indexet |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Elfogadja a felső határt |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Elfogadja a felső határt |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egy egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak. Egy dobozos objektum például szolgálhat operátor emulátorként, igazítási ponttal vagy anélkül, sorvége jelként, vagy úgy csoportosítható, hogy ne engedje meg a sortöréseket benne. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Beállít egy vonalat az elem aljára |

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->