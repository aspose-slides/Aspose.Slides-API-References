---
title: MathLimit
second_title: Aspose.Sildes .NET API referencia
description: Meghatározza a Limit objektumot, amely a kiinduló vonalon lévő szöveget és a közvetlenül fölötte vagy alatta lévő kicsinyített méretű szöveget tartalmazza.
type: docs
weight: 8840
url: /hu/aspose.slides.mathtext/mathlimit/
---
## MathLimit osztály

Megadja a Limit objektumot, amely a kiinduló vonalon lévő szöveget és a közvetlenül fölötte vagy alatta lévő kicsinyített méretű szöveget tartalmazza.

```csharp
public sealed class MathLimit : MathElementBase, IMathLimit
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathLimit](mathlimit#constructor)(IMathElement, IMathElement) | Új MathLimit osztálypéldányt hoz létre alsó határral |
| [MathLimit](mathlimit#constructor_1)(IMathElement, IMathElement, bool) | Új MathLimit osztálypéldányt hoz létre. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathlimit/base) { get; } | Alap argumentum |
| [Limit](../../aspose.slides.mathtext/mathlimit/limit) { get; } | Határ argumentum |
| [UpperLimit](../../aspose.slides.mathtext/mathlimit/upperlimit) { get; set; } | Megadja a felső vagy alsó határt |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akcentusjelet (a elem tetején lévő karakter). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megadott függvény, amely ezt a példányt argumentumként használja. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megadott függvény, amely ezt a példányt argumentumként használja. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megadott függvény, amely ezt a példányt argumentumként használja. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megadott függvény, amely ezt a példányt argumentumként és egy megadott további argumentumot használja. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megadott függvény, amely ezt a példányt argumentumként és egy megadott további argumentumot használja. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy meghatározott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy meghatározott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelek közé foglalja a matematikai elemet. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | A matematikai elemet megadott karakterekkel, például zárójelek vagy más karakterek közé foglalja. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Függvényt vesz, amely ezt a példányt függvénynevének használja. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Függvényt vesz, amely ezt a példányt függvénynevének használja. |
| [GetChildren](../../aspose.slides.mathtext/mathlimit/getchildren)() | Gyermekelemek lekérése. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet alsó kapcsos zárójellel csoportba helyezi. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet csoportba helyezi, csoportosító karaktert használva, például alsó kapcsos zárójelet vagy más karaktert. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Integrál, korlátok nélkül. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrál. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrál. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrál. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrál. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet és matematikai blokkot képez. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget és matematikai blokkot képez. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áris operátort. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áris operátort. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Vonalat helyez az elem tetejére. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határt vesz. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határt vesz. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon alsó és felső indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon alsó és felső indexet hoz létre. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon alsó és felső indexet hoz létre. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon alsó és felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt vesz. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt vesz. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet keretdobozba helyezi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet keretdobozba helyezi. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet nem vizuális dobozba (logikai csoportosítás) helyezi, amely egyenlet vagy más matematikai szöveg összetevőinek csoportosítására szolgál. Egy dobozba helyezett objektum (például) operátor-emulátorként használható igazítási ponttal vagy anélkül, sortörés pontként szolgálhat, vagy úgy csoportosítható, hogy ne engedjen sortöréseket belül. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömböt helyez be. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Vonalat helyez az elem aljára. |

### Példák

Example:

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