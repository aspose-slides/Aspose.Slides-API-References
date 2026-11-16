---
title: MathBox
second_title: Aspose.Sildes .NET API Referencia
description: Megadja a matematikai elem logikai dobozolását és csomagolását. Például egy dobozolt objektum szolgálhat operátor-emulátorként igazítási ponttal vagy anélkül, szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedélyezzen sortöréseket a belsejében. Például az operátort dobozni kell a sortörések megelőzése érdekében.
type: docs
weight: 8650
url: /hu/aspose.slides.mathtext/mathbox/
---
## MathBox osztály

Megadja a matematikai elem logikai dobozolását (csomagolását). Például egy dobozolt objektum szolgálhat operátor-emulátorként igazítási ponttal vagy anélkül, szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedélyezzen sortöréseket belül. Például a \"==\" operátort dobozni kell a sortörések megelőzése érdekében.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Inicializálja a MathBox-ot a megadott elemmel argumentumként. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Ha igaz, ez az operátor-emulátor igazítási pontként szolgál; vagyis a többi egyenletben meghatározott igazítási pontok ehhez igazíthatók. Alapértelmezett: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Alapargumentum |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differential Ha igaz, a doboz differenciálként működik (például 𝑑𝑥 a integrandusban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciálhoz. Alapértelmezett: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicit break megadja, van-e sortörés a Box objektum elején, így a sor a doboz objektum elején törik. Megadja az előző sorban lévő operátor számát a matematikai szövegben, amelyet az aktuális sor igazítási pontjaként kell használni. Lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit sortörés) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break Ez a tulajdonság határozza meg a "unbreakable" (törhetetlen) tulajdonságot az objektumdobozon. Ha igaz, sortörés nem fordulhat elő a dobozon belül. Ez fontos lehet több bináris operátorból álló operátor-emulátorok esetén. Ha ez az elem nincs megadva, a dobozon belül előfordulhatnak törések. Alapértelmezett: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator. Ha igaz, a doboz és tartalma egyetlen operátorként viselkedik és örökli az operátor tulajdonságait. Ez azt jelenti, például, hogy a karakter szolgálhat sortörés pontként és igazítható más operátorokhoz. Az Operator Emulator-okat gyakran használják, amikor egy vagy több glif kombinálódik egy operátor létrehozásához, például a '=='. Alapérték: false |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy ékezetet (karakter az elem tetején). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megadott függvényt hív meg, amely a példányt használja argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megadott függvényt hív meg, amely a példányt használja argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megadott függvényt hív meg, amely a példányt használja argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megadott függvényt hív meg, amely a példányt argumentumként és egy megadott további argumentumot használ. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megadott függvényt hív meg, amely a példányt argumentumként és egy megadott további argumentumot használ. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy törtet a megadott típusban ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy törtet a megadott típusban ezzel a számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelek közé tesz egy matematikai elemet. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Zárójelek vagy más karakterek közé tesz egy matematikai elemet a megadott karakterekkel. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Megkap egy argumentumfüggvényt, ahol ez a példány a függvény neve. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Megkap egy argumentumfüggvényt, ahol ez a példány a függvény neve. |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Lekéri a gyermekelemeket. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elem alul levő kapcsos zárójel használatával csoportba helyezi. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elem csoportba helyezi a megadott csoportosító karakterrel, például alul levő kapcsos zárójel vagy más karakter. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Megkapja a határolás nélküli integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Megkapja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Megkapja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Megkapja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Megkapja az integrált. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet és matematikai blokkot hoz létre. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget és matematikai blokkot hoz létre. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-értékű operátort. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-értékű operátort. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Beállít egy vonalat az elem tetején. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja az adott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja az adott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Felveszi az alsó határt. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Felveszi az alsó határt. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Létrehoz alsó indexet. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Létrehoz alsó indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon hoz létre alsó és felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Létrehoz felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Létrehoz felső indexet. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felveszi a felső határt. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felveszi a felső határt. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet keretdobozba helyezi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet keretdobozba helyezi. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem vizuális dobozba (logikai csoportosításba) helyezi, amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy dobozolt objektum például szolgálhat operátor-emulátorként igazítási ponttal vagy anélkül, szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedélyezzen sortöréseket a belsejében. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Beállít egy vonalat az elem alján. |

### Példák

Példa:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathBox](../imathbox)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->