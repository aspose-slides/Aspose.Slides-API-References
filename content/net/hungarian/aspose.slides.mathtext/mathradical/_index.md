---
title: MathRadical
second_title: Aspose.Sildes .NET API referencia
description: Megadja a gyökfüggvényt, amely egy alapelemből és egy opcionális kitevőből áll. A gyökobjektus példája .
type: docs
weight: 8920
url: /hu/aspose.slides.mathtext/mathradical/
---
## MathRadical osztály

Meghatározza a gyökfüggvényt, amely egy alapból és egy opcionális kitevőből áll. A gyök objektum példája √𝑥.

```csharp
public sealed class MathRadical : MathElementBase, IMathRadical
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathRadical](mathradical)(IMathElement, IMathElement) | Új példányt hoz létre a MathRadical osztályból. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathradical/base) { get; } | Alap argumentum |
| [Degree](../../aspose.slides.mathtext/mathradical/degree) { get; } | Kitevő argumentum |
| [HideDegree](../../aspose.slides.mathtext/mathradical/hidedegree) { get; set; } | Elrejti a kitevőt. Ha true, a kitevő nem jelenik meg, például √𝑥 |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy ékezetjelzést (egy karakter az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megkapja a megadott függvényt, amelynek argumentumaként ezt a példányt használja |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megkapja a megadott függvényt, amelynek argumentumaként ezt a példányt használja |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megkapja a megadott függvényt, amelynek argumentumaként ezt a példányt használja |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megkapja a megadott függvényt, amelynek argumentumaként ezt a példányt, valamint a megadott további argumentumot használja |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megkapja a megadott függvényt, amelynek argumentumaként ezt a példányt, valamint a megadott további argumentumot használja |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Egy matematikai elemet zárójelek közé helyez |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Egy matematikai elemet a megadott karakterek közé helyez, például zárójelek vagy más keretező karakterek |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Megkap egy argumentumfüggvényt, melynek függvényneveként ezt a példányt használja |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Megkap egy argumentumfüggvényt, melynek függvényneveként ezt a példányt használja |
| [GetChildren](../../aspose.slides.mathtext/mathradical/getchildren)() | Lekéri a gyermekelemeket |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakter segítségével, például alsó kapcsos zárójel vagy más |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Megkapja az integrált határok nélkül |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Megkapja az integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Megkapja az integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Megkapja az integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Megkapja az integrált |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet és egy matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget és egy matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áris operátort |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áris operátort |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Beállít egy vonalat az elem tetejére |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Meghatározza a megadott kitevőből származó matematikai gyököt a megadott argumentumból |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Meghatározza a megadott kitevőből származó matematikai gyököt a megadott argumentumból |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Megkapja az alsó határt |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Megkapja az alsó határt |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Létrehoz alsó indexet |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Létrehoz alsó indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Létrehoz felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Létrehoz felső indexet |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Megkapja a felső határt |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Megkapja a felső határt |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak. Egy keretezett objektum például szolgálhat operátor emulátorként igazítási pont nélkül, vonaltörés pontként, vagy úgy csoportosítható, hogy ne engedje meg a sortörést belül. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Beállít egy vonalat az elem aljára |

### Példák

Példa:

```csharp
[C#]
MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathRadical](../imathradical)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->