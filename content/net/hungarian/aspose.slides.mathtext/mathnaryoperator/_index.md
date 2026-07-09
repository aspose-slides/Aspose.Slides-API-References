---
title: MathNaryOperator
second_title: Aspose.Sildes .NET API hivatkozás
description: Megad egy N-áris matematikai objektumot, például Summation és Integral. Operátorból, egy alapelemről vagy operandusról, valamint opcionális felső és alsó határból áll. N-áris operátorok példái: Summation, Union, Intersection, Integral
type: docs
weight: 8870
url: /hu/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator osztály

N-áris matematikai objektumot határoz meg, például összeadást és integrált. Operátorból, egy alapelemből (vagy operandusból) és opcionális felső és alsó határból áll. N-áris operátorok példái: Összegzés, Unió, Metszet, Integrál

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | Új példányt hoz létre a MathNaryOperator osztályból. |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | Új példányt hoz létre a MathNaryOperator osztályból. |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | Új példányt hoz létre a MathNaryOperator osztályból. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | Alapargumentum |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | Az operátor karakter függőlegesen nő, hogy megfeleljen az operandus magasságának |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | Alsó index elrejtése |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | Felső index elrejtése |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | A határok (alsó és felső index) helye |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | N-áris operátor karakter, például: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | Alsó index argumentum, például integrál esetén az alsó határ beállítása |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | Felső index argumentum, például integrál esetén a felső határ beállítása |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Akcentusjel (a karakter a elem tetején) beállítása |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | A megadott függvény meghívása ezzel a példánnyal argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | A megadott függvény meghívása ezzel a példánnyal argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | A megadott függvény meghívása ezzel a példánnyal argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | A megadott függvény meghívása ezzel a példánnyal és a megadott további argumentummal |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | A megadott függvény meghívása ezzel a példánnyal és a megadott további argumentummal |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tört létre ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tört létre ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | A megadott típusú tört létrehozása ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | A megadott típusú tört létrehozása ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Matematikai elemet zárójelek közé helyez |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Matematikai elemet a megadott karakterek közé helyez, például zárójelek vagy más keretező karakterek |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Függvényt hív meg egy argumentummal, a példányt a függvény nevének használva |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Függvényt hív meg egy argumentummal, a példányt a függvény nevének használva |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | Gyermekelemek lekérése |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Elem elhelyezése egy csoportba alsó kapcsos zárójelettel |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Elem elhelyezése egy csoportba csoportosító karakterrel, például alsó kapcsos zárójel vagy más |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Integrál létrehozása határok nélkül |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrál létrehozása |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrál létrehozása |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrál létrehozása |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrál létrehozása |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Matematikai elemet összekapcsol és matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematikai szöveget összekapcsol és matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-áris operátor létrehozása |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-áris operátor létrehozása |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Vízszintes vonalat helyez az elem tetejére |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Matematikai gyököt ad meg a megadott fokozatból a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Matematikai gyököt ad meg a megadott fokozatból a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határ megadása |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határ megadása |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó index létrehozása |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó index létrehozása |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Alsó és felső index bal oldalon létrehozása |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Alsó és felső index bal oldalon létrehozása |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Alsó és felső index jobb oldalon létrehozása |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Alsó és felső index jobb oldalon létrehozása |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső index létrehozása |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső index létrehozása |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határ megadása |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határ megadása |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Elem elhelyezése egy keretdobozban |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Elem elhelyezése egy keretdobozban |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Elem elhelyezése egy nem vizuális dobozban (logikai csoportosítás), amelyet egy egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. A dobozos objektum (például) operátor emulátorként szolgálhat igazítási ponttal vagy anélkül, vonaltörés pontként, vagy úgy csoportosítható, hogy ne engedje meg a sortöréseket benne. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges sorba helyezés |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Vízszintes vonalat helyez az elem aljára |

### Példák

Példa:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathNaryOperator](../imathnaryoperator)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->