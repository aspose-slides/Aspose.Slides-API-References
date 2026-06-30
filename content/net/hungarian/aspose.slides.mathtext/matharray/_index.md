---
title: MathArray
second_title: Aspose.Sildes .NET API referenciához
description: Függőleges egyenletekből vagy bármely matematikai objektumból álló tömböt határoz meg
type: docs
weight: 8530
url: /hu/aspose.slides.mathtext/matharray/
---
## MathArray osztály

Függőleges egyenletekből vagy bármely matematikai objektumból álló tömböt határoz meg

```csharp
public sealed class MathArray : MathElementBase, IMathArray
```

## Constructors

| Name | Description |
| --- | --- |
| [MathArray](matharray#constructor_1)(IEnumerable&lt;IMathElement&gt;) | Létrehoz egy matematikai tömböt, és elhelyezi benne a megadott elemeket |
| [MathArray](matharray#constructor)(IMathElement) | Létrehoz egy matematikai tömböt, és elhelyezi benne a megadott elemet |

## Properties

| Name | Description |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/matharray/arguments) { get; } | A tömb elemeinek halmaza |
| [BaseJustification](../../aspose.slides.mathtext/matharray/basejustification) { get; set; } | Megadja a tömb elhelyezkedését a környező szöveghez képest. A tömbön kívüli szöveg alulra, felülre vagy középre igazítható a tömb objektumhoz képest. Alapértelmezett érték: Center |
| [MaximumDistribution](../../aspose.slides.mathtext/matharray/maximumdistribution) { get; set; } | Maximum terjesztés. Ha igaz, a tömb a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességére terjed. |
| [ObjectDistribution](../../aspose.slides.mathtext/matharray/objectdistribution) { get; set; } | Objektum terjesztés. Ha igaz, a tömb tartalma a tömb objektum maximális szélességére terjed. |
| [RowSpacing](../../aspose.slides.mathtext/matharray/rowspacing) { get; set; } | Sorok közti távolság a tömbben. Csak akkor használatos, ha a RowSpacingRule 3-ra van állítva. Ebben az esetben a mértékegység pont, vagy Multiple esetén fél sor. Alapértelmezett: 0 |
| [RowSpacingRule](../../aspose.slides.mathtext/matharray/rowspacingrule) { get; set; } | A tömb elemei közötti függőleges távolság típusa. Alapértelmezett: SingleLineGap |

## Methods

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy ékezetet (karakter a elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | A megadott függvényt használja, a példányt argumentumként átadva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | A megadott függvényt használja, a példányt argumentumként átadva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | A megadott függvényt használja, a példányt argumentumként átadva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | A megadott függvényt használja, a példányt argumentumként átadva, valamint egy további argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | A megadott függvényt használja, a példányt argumentumként átadva, valamint egy további argumentumot |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelek közé tesz egy matematikaelemet |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Zárójelek vagy más karakterek közé tesz egy matematikaelemet |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Függvényt hoz létre egy argumentummal, a példányt a függvény nevének használva |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Függvényt hoz létre egy argumentummal, a példányt a függvény nevének használva |
| [GetChildren](../../aspose.slides.mathtext/matharray/getchildren)() | Gyermekelemek lekérése |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi alsó kapcsos zárójelek segítségével |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójelek vagy más karakter használatával |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | A határolók nélküli integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Egy matematikai elemet egyesít, és matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Egy matematikai szöveget egyesít, és matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-értelmű operátort hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-értelmű operátort hoz létre |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Felső vonalat helyez az elem tetejére |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Meghatározza a matematikai gyököt a megadott fokozatban a megadott argumentumból |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Meghatározza a matematikai gyököt a megadott fokozatban a megadott argumentumból |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határérték felvétele |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határérték felvétele |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó index (subscript) létrehozása |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó index (subscript) létrehozása |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon al- és felső indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon al- és felső indexet hoz létre |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon al- és felső indexet hoz létre |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon al- és felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső index (superscript) létrehozása |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső index (superscript) létrehozása |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határérték felvétele |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határérték felvétele |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet nem vizuális dobozban helyezi (logikai csoportosítás), amelyet egyenletek vagy egyéb matematikai szövegrészek komponenseinek csoportosítására használnak. Egy keretes objektum például szolgálhat operátor emulátorként igazítási pont nélkül vagy ponttal, vonaltörés pontként, vagy úgy csoportosítható, hogy ne engedélyezze a sorok megtörését. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Alsó vonalat helyez az elem aljára |

### Examples

Példa:

```csharp
[C#]
MathArray mathArray = new MathArray(new MathematicalText("item1"));
```

### See Also

* class [MathElementBase](../mathelementbase)
* interface [IMathArray](../imatharray)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->