---
title: IMathElement
second_title: Aspose.Sildes .NET API referencia
description: Bármely matematikai elem – tört, matematikai szöveg, függvény vagy több elemből álló kifejezés – alapeső interfésze
type: docs
weight: 8250
url: /hu/aspose.slides.mathtext/imathelement/
---
## IMathElement interfész

Alap interfész minden matematikai elemhez: tört, matematikai szöveg, függvény, több elemből álló kifejezés stb

```csharp
public interface IMathElement
```

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Beállít egy hangsúlyjelet (egy karakter az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | A megadott függvényt veszi, ezt a példányt argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | A megadott függvényt veszi, ezt a példányt argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | A megadott függvényt veszi, ezt a példányt argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | A megadott függvényt veszi, ezt a példányt argumentumként és a megadott további argumentumot használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | A megadott függvényt veszi, ezt a példányt argumentumként és a megadott további argumentumot használva |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Zárójelek közé helyezi a matematikai elemet |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | A megadott karakterekbe (például zárójelek vagy más karakterek) helyezi ezt az elemet |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Az argumentum függvényét veszi, ezt a példányt a függvény nevének tekintve |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Az argumentum függvényét veszi, ezt a példányt a függvény nevének tekintve |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Lekéri a gyermekelemeket |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Ezt az elemet egy csoportba helyezi, alul kapcsos zárójelet használva |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Ezt az elemet egy csoportba helyezi egy csoportosító karakter segítségével, például alul kapcsos zárójel vagy más |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Az integrált veszi korlátok nélkül |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMMathElement, IMathElement) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Egy matematikai elemet egyesít, és egy matematikai blokkot hoz létre |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Egy matematikai szöveget egyesít, és egy matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-ary operátort |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-ary operátort |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Beállít egy sávot az elem tetejére |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Megadja az adott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Megadja az adott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Az alsó határt veszi |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Az alsó határt veszi |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Alsó indexet hoz létre |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Alsó indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Felső indexet hoz létre |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | A felső határt veszi |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | A felső határt veszi |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Ezt az elemet egy keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Ezt az elemet egy keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Ezt az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. A dobozba helyezett objektum (például) szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, vonaltörés pontként, vagy úgy csoportosítható, hogy ne engedje meg a vonaltöréseket. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Beállít egy sávot az elem aljára |

### Példák

Példa:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Lásd még

* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->