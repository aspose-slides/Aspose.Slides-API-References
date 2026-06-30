---
title: MathGroupingCharacter
second_title: Aspose.Sildes .NET API-referencia
description: Megad egy csoportosító szimbólumot egy kifejezés felett vagy alatt, általában az elemek közötti kapcsolat kiemelésére
type: docs
weight: 8740
url: /hu/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter osztály

Megad egy csoportosító szimbólumot a kifejezés felett vagy alatt, általában az elemek közötti kapcsolat kiemelésére

```csharp
public sealed class MathGroupingCharacter : MathElementBase, IMathGroupingCharacter
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathGroupingCharacter](mathgroupingcharacter#constructor)(IMathElement) | Létrehoz egy új MathGroupingCharacter példányt az alapértelmezett csoportosító karakterrel U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter](mathgroupingcharacter#constructor_1)(IMathElement, char, MathTopBotPositions, MathTopBotPositions) | Létrehoz egy új MathGroupingCharacter példányt. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathgroupingcharacter/base) { get; } | Alap argumentum |
| [Character](../../aspose.slides.mathtext/mathgroupingcharacter/character) { get; set; } | Csoportosító karakter Alapértelmezett érték: U+23DF (BOTTOM CURLY BRACKET) |
| [Position](../../aspose.slides.mathtext/mathgroupingcharacter/position) { get; set; } | A csoportosító karakter pozíciója. Alapértelmezett: Bottom |
| [VerticalJustification](../../aspose.slides.mathtext/mathgroupingcharacter/verticaljustification) { get; set; } | A csoportosító karakter függőleges igazítása. Megadja az objektum igazítását az alapvonalhoz képest. Például, ha a csoportosító karakter az objektum felett van, a VerticalJustification értéke Top jelzi, hogy az objektum teteje az alapvonalon van; ha a VerticalJustification értéke Bottom, akkor az objektum alja az alapvonalon van. Alapértelmezett: Bottom a Position=Top esetén, és Top a Position=Bottom esetén |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy hangsúlyjelet (egy karakter az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | A megadott függvényt azonnal meghívja, amely ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | A megadott függvényt azonnal meghívja, amely ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | A megadott függvényt azonnal meghívja, amely ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | A megadott függvényt azonnal meghívja, amely ezt a példányt használja argumentumként, illetve egy további argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | A megadott függvényt azonnal meghívja, amely ezt a példányt használja argumentumként, illetve egy további argumentumot |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy adott típusú törtet a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy adott típusú törtet a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelek közé helyezi a matematikai elemet |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Zárójelek vagy egyéb karakterek közé helyezi a matematikai elemet, keretezve |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | A függvény nevét ezt a példányt használja argumentumnak |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | A függvény nevét ezt a példányt használja argumentumnak |
| [GetChildren](../../aspose.slides.mathtext/mathgroupingcharacter/getchildren)() | Gyermekelemek lekérése |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy alsó kapcsos zárójelcsoportba helyezi |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi a megadott csoportosító karakter használatával, például alsó kapcsos zárójelek vagy más karakterek |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | A határértékek nélküli integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Matematikai elemet csatlakoztat és matematikai blokkoká alakít |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematikai szöveget csatlakoztat és matematikai blokkoká alakít |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-áris operátort hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-áris operátort hoz létre |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Felső vonalat helyez az elem tetejére |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határérték |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határérték |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Balra helyezi a alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Balra helyezi a alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobbra helyezi a alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobbra helyezi a alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határérték |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határérték |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy szegélydobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy szegélydobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak. Egy doboz objektum például szolgálhat operátor emulátorként igazítási pont nélkül vagy azzal, vagy lehet sorvége pont, vagy úgy csoportosítható, hogy ne engedje meg a sortörést benne. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Alulra vonalat helyez az elem aljára |

### Példák

Példa:

```csharp
[C#]
MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathGroupingCharacter](../imathgroupingcharacter)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->