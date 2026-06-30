---
title: MathSuperscriptElement
second_title: Aspose.Sildes .NET API referencia
description: Megadja a felső index objektumot, amely egy alapból és egy kisebb méretű felső indexből áll, amely az alap fölött és jobbra helyezkedik el
type: docs
weight: 9000
url: /hu/aspose.slides.mathtext/mathsuperscriptelement/
---
## MathSuperscriptElement osztály

Meghatározza a felső index objektumot, amely egy alapból és egy kisebb méretű felső indexből áll, amely az alap fölött és jobbra helyezkedik el.

```csharp
public sealed class MathSuperscriptElement : BaseScript, IMathSuperscriptElement
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathSuperscriptElement](mathsuperscriptelement)(IMathElement, IMathElement) | Inicializál egy új példányt a MathSuperscriptElement osztályból. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Alap argumentum |
| [Superscript](../../aspose.slides.mathtext/mathsuperscriptelement/superscript) { get; } | Felső index |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akcentusjelet (egy karakter az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megkapja a megadott függvényt, amely ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megkapja a megadott függvényt, amely ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megkapja a megadott függvényt, amely ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megkapja a megadott függvényt, amely ezt a példányt használja argumentumként és a megadott további argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megkapja a megadott függvényt, amely ezt a példányt használja argumentumként és a megadott további argumentumot |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelek közé helyez egy matematikai elemet |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Zárójelekkel vagy más karakterekkel keretezi a matematikai elemet |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Az argumentum függvényét veszi, amely ezt a példányt használja függvénynévként |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Az argumentum függvényét veszi, amely ezt a példányt használja függvénynévként |
| [GetChildren](../../aspose.slides.mathtext/mathsuperscriptelement/getchildren)() | Lekéri a gyermek elemeket |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet alulra helyezett kapcsos zárójel segítségével egy csoportba helyezi |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alulra helyezett kapcsos zárójellel vagy más karakterrel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Az integrált határok nélkül veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet és egy matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematikai szöveget kapcsol össze és egy matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-értékű operátort |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-értékű operátort |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Az elem tetejére vonalat helyez |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Az alsó határt veszi |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Az alsó határt veszi |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Létrehoz alindexet |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Létrehoz alindexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Balra helyez al- és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Balra helyez al- és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobbra helyez al- és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobbra helyez al- és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Létrehoz felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Létrehoz felső indexet |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | A felső határt veszi |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | A felső határt veszi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretes dobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretes dobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi, amelyet egy egyenlet vagy egyéb matematikai szöveg összetevőinek csoportosítására használnak. Egy keretezett objektum például szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedjen sortörést belül. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Az elem aljára vonalat helyez |

### Példák

Példa:

```csharp
[C#]
MathSuperscriptElement superscriptElement = new MathematicalText("N").SetSuperscript("i");
```

### Lásd még

* osztály [BaseScript](../basescript)
* interfész [IMathSuperscriptElement](../imathsuperscriptelement)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->