---
title: MathArray
second_title: Aspose.Sildes .NET API referenciája
description: Megad egy függőleges egyenletek vagy bármilyen matematikai objektumok tömbjét
type: docs
weight: 8550
url: /hu/aspose.slides.mathtext/matharray/
---
## MathArray osztály

Megadja a függőleges egyenletek vagy bármilyen matematikai objektumok tömbjét

```csharp
public sealed class MathArray : MathElementBase, IMathArray
```

## Konstruktorok

| Name | Description |
| --- | --- |
| [MathArray](matharray#constructor_1)(IEnumerable&lt;IMathElement&gt;) | Létrehoz egy matematikai tömböt, és elhelyezi benne a megadott elemeket |
| [MathArray](matharray#constructor)(IMathElement) | Létrehoz egy matematikai tömböt, és elhelyezi benne a megadott elemet |

## Tulajdonságok

| Name | Description |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/matharray/arguments) { get; } | A tömb elemeinek halmaza |
| [BaseJustification](../../aspose.slides.mathtext/matharray/basejustification) { get; set; } | Megadja a tömb igazítását a környező szöveghez képest. A tömbön kívüli szöveg a tömb objektum aljához, tetejéhez vagy közepéhez igazítható. Alapértelmezett érték: Center |
| [MaximumDistribution](../../aspose.slides.mathtext/matharray/maximumdistribution) { get; set; } | Maximum eloszlás. Ha igaz, a tömb a tartalmazó elem (oldal, oszlop, cella stb.) maximális szélességére lesz elosztva. |
| [ObjectDistribution](../../aspose.slides.mathtext/matharray/objectdistribution) { get; set; } | Objektum eloszlás. Ha igaz, a tömb tartalma a tömbobjektum maximális szélességére lesz elosztva. |
| [RowSpacing](../../aspose.slides.mathtext/matharray/rowspacing) { get; set; } | Tömb sorai közötti távolság. Csak akkor használható, ha a RowSpacingRule 3-ra van állítva. Ilyenkor a mértékegység pont, vagy ha Multiple, akkor fél sor. Alapértelmezett: 0 |
| [RowSpacingRule](../../aspose.slides.mathtext/matharray/rowspacingrule) { get; set; } | A tömb elemei közötti függőleges távolság típusa. Alapértelmezett: SingleLineGap |

## Metódusok

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy ékezetjelzést (egy karaktert az elem tetején). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megadott függvényt használ, ahol ez a példány az argumentum. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megadott függvényt használ, ahol ez a példány az argumentum. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megadott függvényt használ, ahol ez a példány az argumentum. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megadott függvényt használ, ahol ez a példány az argumentum, valamint egy megadott további argumentumot. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megadott függvényt használ, ahol ez a példány az argumentum, valamint egy megadott további argumentumot. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet, ahol ez a számláló és a megadott nevező. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet, ahol ez a számláló és a megadott nevező. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy megadott típusú törtet, ahol ez a számláló és a megadott nevező. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy megadott típusú törtet, ahol ez a számláló és a megadott nevező. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelekkel veszi körül a matematikai elemet. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Zárójeleket vagy megadott karaktereket használ a matematikai elem keretezéséhez. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Függvényt vesz fel egy argumentumra, ahol ez a példány a függvény neve. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Függvényt vesz fel egy argumentumra, ahol ez a példány a függvény neve. |
| [GetChildren](../../aspose.slides.mathtext/matharray/getchildren)() | Gyermekelemeket kap vissza. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi, alsó kapcsos zárójelet használva. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi, egy csoportosító karaktert használva, például alsó kapcsos zárójelet vagy más karaktert. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Az integrált veszi korlátok nélkül. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet, és egy matematikai blokkot alkot. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget, és egy matematikai blokkot alkot. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áramű operátort. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áramű operátort. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Az elem tetejére egy vonalat helyez. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Az alsó határt veszi. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Az alsó határt veszi. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon hoz létre alsó és felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | A felső határt veszi. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | A felső határt veszi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretes dobozba helyezi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretes dobozba helyezi. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy dobozban lévő objektum például operátor emulátorként funkcionálhat igazítási ponttal vagy anélkül, sortörés pontként szolgálhat, vagy úgy csoportosítható, hogy ne engedje a sortöréseket. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Az elem aljára egy vonalat helyez. |

### Példák

Példa:

```csharp
[C#]
MathArray mathArray = new MathArray(new MathematicalText("item1"));
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathArray](../imatharray)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->