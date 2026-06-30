---
title: MathBorderBox
second_title: Aspose.Sildes .NET API hivatkozás
description: Téglalap vagy más típusú keretet rajzol az IMathElement köré.
type: docs
weight: 8590
url: /hu/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox osztály

Téglalap vagy más típusú keretet rajzol az IMathElement köré.

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | Létrehozza a MathBorderBox elemet téglalap alakú kerettel |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | Létrehozza a MathBorderBox elemet |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | Alap argumentum |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | Az alsó él elrejtése (az alapértelmezett hamis) – meghatározza a keretdoboz alsó élének rejtett vagy látható állapotát. |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | A bal él elrejtése (az alapértelmezett hamis) – meghatározza a keretdoboz bal élének rejtett vagy látható állapotát. |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | A jobb él elrejtése (az alapértelmezett hamis) – meghatározza a keretdoboz jobb élének rejtett vagy látható állapotát. |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | A felső él elrejtése (az alapértelmezett hamis) – meghatározza a keretdoboz felső élének rejtett vagy látható állapotát. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | Áthúzás bal alsó saroktól jobb felső sarokig (az alapértelmezett hamis). Meghatározza a keretdoboz bal alsó saroktól jobb felső sarokig íródó áthúzási átló rejtett vagy látható állapotát. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | Vízszintes áthúzás (az alapértelmezett hamis) – meghatározza egy vízszintes áthúzási vonal rejtett vagy látható állapotát. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | Áthúzás bal felső saroktól jobb alsó sarokig (az alapértelmezett hamis). Meghatározza a keretdoboz bal felső saroktól jobb alsó sarokig íródó áthúzási átló rejtett vagy látható állapotát. |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | Függőleges áthúzás (az alapértelmezett hamis) – meghatározza egy függőleges áthúzási vonal rejtett vagy látható állapotát. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy hangsúlyjelet (az elem tetején lévő karaktert) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megadott függvényt alkalmaz, amely az aktuális példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megadott függvényt alkalmaz, amely az aktuális példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megadott függvényt alkalmaz, amely az aktuális példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megadott függvényt alkalmaz, amely az aktuális példányt használja argumentumként, valamint a megadott további argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megadott függvényt alkalmaz, amely az aktuális példányt használja argumentumként, valamint a megadott további argumentumot |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet, amelynek számlálója ez, a nevezője pedig a megadott |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet, amelynek számlálója ez, a nevezője pedig a megadott |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy megadott típusú törtet, amelynek számlálója ez, a nevezője pedig a megadott |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy megadott típusú törtet, amelynek számlálója ez, a nevezője pedig a megadott |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelek közé helyezi a matematikai elemet |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Körülveszi a matematikai elemet megadott karakterekkel, például zárójelek vagy más keret karakterek |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Argumentumfüggvényt vesz fel, ahol az aktuális példány a függvény neve |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Argumentumfüggvényt vesz fel, ahol az aktuális példány a függvény neve |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | Gyermekelemek lekérése |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Elhelyezi ezt az elemet egy csoportba, alul kapcsos zárójel használatával |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Elhelyezi ezt az elemet egy csoportba, egy csoportosító karakter, például alul kapcsos zárójel vagy más használatával |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Vesz egy integrált korlátok nélkül |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Vesz egy integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Vesz egy integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Vesz egy integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Vesz egy integrált |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet, és matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget, és matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áris operátort |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áris operátort |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Felső vonalat helyez az elem tetejére |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott argumentum adott fokú matematikai gyökerét |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott argumentum adott fokú matematikai gyökerét |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határt vesz |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határt vesz |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Létrehoz alsó indexet |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Létrehoz alsó indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Létrehoz felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Létrehoz felső indexet |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt vesz |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt vesz |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egy egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak. A dobozos objektum például operátor emulátorként működhet igazítási ponttal vagy anélkül, sorbre törés pontként szolgálhat, vagy úgy csoportosítható, hogy ne engedélyezze a sorok törését benne. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Alsó vonalat helyez az elem aljára |

### Példák

Példa:

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathBorderBox](../imathborderbox)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->