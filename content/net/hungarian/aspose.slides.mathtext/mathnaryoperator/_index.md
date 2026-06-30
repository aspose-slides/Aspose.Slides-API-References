---
title: MathNaryOperator
second_title: Aspose.Sildes .NET API referencia
description: Megad egy N-áris matematikai objektumot, például Summation és Integral. Egy operátorból, egy bázisból vagy operandusból és opcionális felső és alsó határból áll. N-áris operátorok példái: Summation, Union, Intersection, Integral
type: docs
weight: 8850
url: /hu/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator osztály

Megad egy N-áris matematikai objektumot, például Summation és Integral. Egy operátorból, egy bázisból (vagy operandusból) és opcionális felső és alsó határból áll. Az N-áris operátorok példái: Summation, Union, Intersection, Integral

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | Inicializál egy új példányt a MathNaryOperator osztályban. |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | Inicializál egy új példányt a MathNaryOperator osztályban. |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | Inicializál egy új példányt a MathNaryOperator osztályban. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | Alap argumentum |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | Az operátor karakter függőlegesen nő, hogy megegyezzen az operandusa magasságával |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | Alsó index elrejtése |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | Felső index elrejtése |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | A határok helye (alsó és felső index) |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | N-áris operátor karakter, például: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | Megad egy alsó index argumentumot, amely például integrál esetén beállítja az alsó határt |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | Megad egy felső index argumentumot, amely például integrál esetén beállítja a felső határt |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Akcentusjelet állít be (egy karakter az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | A megadott függvényt használja, a példányt argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | A megadott függvényt használja, a példányt argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | A megadott függvényt használja, a példányt argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | A megadott függvényt használja, a példányt argumentumként és a megadott további argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | A megadott függvényt használja, a példányt argumentumként és a megadott további argumentumot |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezen számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezen számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Egy matematikai elemet zárójelekbe helyez |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Egy matematikai elemet megadott karakterekbe zár, például zárójelekbe vagy más keretező karakterekbe |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Az argumentum függvényét veszi, a példányt függvényneveként használva |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Az argumentum függvényét veszi, a példányt függvényneveként használva |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | Gyermekelemeket kap |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi, alsó kapcsos zárójelet használva |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportoló karakterrel, például alsó kapcsos zárójel vagy más karakter |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Az integrált korlátok nélkül veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Egy matematikai elemet összekapcsol és egy matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Egy matematikai szöveget összekapcsol és egy matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áris operátort |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áris operátort |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Az elem tetejére vonalat helyez |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határt vesz |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határt vesz |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Balra hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Balra hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobbra hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobbra hoz létre alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt vesz |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt vesz |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretdobozba helyezi a megadott logikai értékekkel |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy dobozos objektum például operátor emulátorként szolgálhat, vonaltöréspontként vagy úgy csoportosítható, hogy ne engedélyezze a sorok törését benne. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Az elem aljára vonalat helyez |

### Példák

Példa:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### Tovább olvasnivaló

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathNaryOperator](../imathnaryoperator)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->