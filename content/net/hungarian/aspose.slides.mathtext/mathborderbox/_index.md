---
title: MathBorderBox
second_title: Aspose.Sildes .NET-hez API referenciája
description: Téglalap vagy más típusú keretet rajzol az IMathElement köré.
type: docs
weight: 8610
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
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | MathBorderBox elemet hoz létre téglalap alakú kerettel |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | MathBorderBox elemet hoz létre |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | Alap argumentum |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | Alsó él elrejtése (alapértelmezett: false) – megadja a keret doboz alsó élének rejtett vagy látható állapotát. |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | Bal él elrejtése (alapértelmezett: false) – megadja a keret doboz bal élének rejtett vagy látható állapotát. |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | Jobb él elrejtése (alapértelmezett: false) – megadja a keret doboz jobb élének rejtett vagy látható állapotát. |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | Felső él elrejtése (alapértelmezett: false) – megadja a keret doboz felső élének rejtett vagy látható állapotát. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | Áthúzás bal alsó saroktól jobb felső sarokig (alapértelmezett: false). Megadja a keret doboz bal alsó sarokból jobb felső sarokba vezető átlós áthúzási vonal rejtett vagy látható állapotát. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | Vízszintes áthúzás (alapértelmezett: false) – megadja a vízszintes áthúzási vonal rejtett vagy látható állapotát. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | Áthúzás bal felső saroktól jobb alsó sarokig (alapértelmezett: false). Megadja a keret doboz bal felső sarokból jobb alsó sarokba vezető átlós áthúzási vonal rejtett vagy látható állapotát. |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | Függőleges áthúzás (alapértelmezett: false) – megadja a függőleges áthúzási vonal rejtett vagy látható állapotát. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Accentus jelet állít be (karakter az elem tetején). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | A megadott függvényt veszi, ennek példányát argumentumként használva. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | A megadott függvényt veszi, ennek példányát argumentumként használva. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | A megadott függvényt veszi, ennek példányát argumentumként használva. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | A megadott függvényt veszi, ennek példányát argumentumként és a megadott további argumentumot használva. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | A megadott függvényt veszi, ennek példányát argumentumként és a megadott további argumentumot használva. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Törtet hoz létre a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Törtet hoz létre a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | A megadott típusú törtet hoz létre a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | A megadott típusú törtet hoz létre a számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Matematikai elemet zár be zárójelbe. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Matematikai elemet zár be a megadott karakterekkel, például zárójelek vagy egyéb karakterek közé. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Az argumentum függvényét veszi, ennek példányát a függvény nevének használva. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Az argumentum függvényét veszi, ennek példányát a függvény nevének használva. |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | Gyermekelemeket kap. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi alul lévő kapcsos zárójel használatával. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alul lévő kapcsos zárójelet vagy másikat. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Integrált vesz fel korlátok nélkül. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrált vesz fel. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrált vesz fel. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrált vesz fel. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrált vesz fel. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Matematikai elemet egyesít és matematikai blokkot alkot. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematikai szöveget egyesít és matematikai blokkot alkot. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-áris operátort hoz létre. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-áris operátort hoz létre. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Vonalat helyez az elem tetejére. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a specifikált argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a specifikált argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határt vesz. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határt vesz. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó- és felső indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon hoz létre alsó- és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó- és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon hoz létre alsó- és felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt vesz. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt vesz. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet keret dobozba helyezi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet keret dobozba helyezi. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet nem vizuális dobozba (logikai csoportosítás) helyezi, amely egyenlet vagy más matematikai szöveg komponenseinek csoportosítására szolgál. Egy dobozban lévő objektum például operátor emulátorként használható igazítási ponttal vagy anélkül, vonaltörés pontként, vagy úgy csoportosítható, hogy ne engedje a sortörést. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Vonalat helyez az elem aljára. |

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