---
title: IMathElement
second_title: Aspose.Sildes a .NET API referencia
description: Bármely matematikai elem, például tört, matematikai szöveg, függvény, több elemet tartalmazó kifejezés alap interfésze
type: docs
weight: 8210
url: /hu/aspose.slides.mathtext/imathelement/
---
## IMathElement interfész

Alap interfész minden matematikai elemhez: tört, matematikai szöveg, függvény, több elemet tartalmazó kifejezés stb.

```csharp
public interface IMathElement
```

## Módszerek

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Beállít egy ékezetjelet (egy karakter az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Megkap egy megadott függvényt, ahol ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Megkap egy megadott függvényt, ahol ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Megkap egy megadott függvényt, ahol ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Megkap egy megadott függvényt, ahol ezt a példányt használja argumentumként, valamint egy megadott további argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Megkap egy megadott függvényt, ahol ezt a példányt használja argumentumként, valamint egy megadott további argumentumot |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Zárójelbe tesz egy matematikai elemet |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Ezt az elemet megadott karakterek közé helyezi, például zárójelek vagy más keretező karakterek |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Megkap egy argumentumfüggvényt, ahol ezt a példányt használja függvénynévként |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Megkap egy argumentumfüggvényt, ahol ezt a példányt használja függvénynévként |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Lekéri a gyermekelemeket |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Ezt az elemet egy csoportba helyezi, alullevő kapcsos zárójel használatával |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Ezt az elemet egy csoportba helyezi, egy csoportosító karakter használatával, például alulkapcsos zárójel vagy más |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Az integrált határok nélkül veszi |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Összevon egy matematikai elemet és matematikai blokkot hoz létre |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Összevon egy matematikai szöveget és matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-árnyalatos operátort |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-árnyalatos operátort |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Ezen elem tetejére vonalat helyez |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Alulhatárt vesz fel |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Alulhatárt vesz fel |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Alsó indexet hoz létre |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Alsó indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon alsó- és felső indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Bal oldalon alsó- és felső indexet hoz létre |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon alsó- és felső indexet hoz létre |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Jobb oldalon alsó- és felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Felső indexet hoz létre |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Felső határt vesz fel |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Felső határt vesz fel |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Ezt az elemet egy keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Ezt az elemet egy keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Ezt az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy dobozba helyezett objektum például operátor emulátorként szolgálhat igazítási ponttal vagy anélkül, sorvágó pontként működhet, vagy úgy csoportosítható, hogy ne engedje meg a sorok törését benne. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Ezen elem aljára vonalat helyez |

### Példák

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Lásd még

* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->