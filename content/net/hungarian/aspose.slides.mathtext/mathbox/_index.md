---
title: MathBox
second_title: "Aspose.Sildes .NET API Referenciája"
description: "Megadja a matematikai elem logikai dobozolását (csomagolását). Például egy dobozolt objektum szolgálhat operátor emulátorként egy igazítási ponttal vagy anélkül, szolgálhat sortörés-pontként, vagy csoportosítható úgy, hogy ne engedélyezze a sortöréseket belül. Például az operátort dobozni kell a sortörések megelőzése érdekében."
type: docs
weight: 8630
url: /hu/aspose.slides.mathtext/mathbox/
---
## MathBox osztály

Megadja a matematikai elem logikai dobozolását (csomagolását). Például egy dobozolt objektum szolgálhat operátor emulátorként egy igazítási ponttal vagy anélkül, szolgálhat sorvágás-pontként, vagy csoportosítható úgy, hogy ne engedélyezzen sortöréseket belül. Például a "==" operátort dobozni kell a sortörések megelőzése érdekében.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Inicializálja a MathBoxot a megadott elemmel argumentumként. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Ha igaz, ez az operátor emulátor igazítási pontként szolgál; vagyis a többi egyenletben kijelölt igazítási pontok ezzel igazíthatók. Alapértelmezett: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Alapargumentum |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differenciál. Ha igaz, a doboz differenciálként működik (pl. 𝑑𝑥 egy integrandusban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciál számára. Alapértelmezett: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicit break meghatározza, hogy van-e sortörés a Box objektum elején, így a sor a doboz objektum elején törik. Meghatározza az előző sor matematikai szövegében lévő operátor számát, amely a jelenlegi sor matematikai szövegének igazítási pontjaként szolgál. Lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit break) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break. Ez a tulajdonság meghatározza az objektum doboz „törhetetlen” tulajdonságát. Ha igaz, sortörés nem történhet a dobozon belül. Ez fontos lehet olyan operátor emulátoroknál, amelyek egynél több bináris operátorból állnak. Ha ez az elem nincs megadva, a dobozon belül sortörés lehetséges. Alapértelmezett: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operátor emulátor. Ha igaz, a doboz és tartalma egyetlen operátorként viselkedik, és örökli az operátor tulajdonságait. Ez azt jelenti, például, hogy a karakter szolgálhat sorvágó pontként és igazítható más operátorokhoz. Az operátor emulátorokat gyakran használják, amikor egy vagy több glif kombinálódik egy operátorra, például '=='. Alapértelmezett érték: false |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy ékezetjelzést (az elem tetején lévő karaktert). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megadja a megadott függvényt, amely ezt az példányt használja argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megadja a megadott függvényt, amely ezt az példányt használja argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megadja a megadott függvényt, amely ezt az példányt használja argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megadja a megadott függvényt, amely ezt az példányt és a megadott további argumentumot használja. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megadja a megadott függvényt, amely ezt az példányt és a megadott további argumentumot használja. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Körülvesz egy matematikai elemet zárójelbe. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Körülvesz egy matematikai elemet a megadott karakterekkel, például zárójelekkel vagy egyéb karakterekkel keretezésként. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Megad egy argumentumfüggvényt, amely ezt az példányt használja a függvény nevének. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Megad egy argumentumfüggvényt, amely ezt az példányt használja a függvény nevének. |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Lekéri a gyermek elemeket. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Elhelyezi az elemet egy csoportban, alsó kapcsos zárójel használatával. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Elhelyezi az elemet egy csoportban, egy csoportoló karakterrel, például alsó kapcsos zárójellel vagy másik karakterrel. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Megadja az integrált korlátok nélkül. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Megadja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Megadja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Megadja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Megadja az integrált. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet és létrehozza a matematikai blokkot. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget és létrehozza a matematikai blokkot. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áris operátort. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áris operátort. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Beállít egy vonalat az elem tetején. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Megadja az alsó határt. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Megadja az alsó határt. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Létrehoz alsó indexet. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Létrehoz alsó indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Létrehoz bal oldali alsó és felső indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Létrehoz bal oldali alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Létrehoz jobb oldali alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Létrehoz jobb oldali alsó és felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Létrehoz felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Létrehoz felső indexet. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Megadja a felső határt. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Megadja a felső határt. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Elhelyezi az elemet egy keretdobozban. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Elhelyezi az elemet egy keretdobozban. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Elhelyezi az elemet egy nem vizuális dobozban (logikai csoportosítás), amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy dobozolt objektum (például) szolgálhat operátor emulátorként egy igazítási ponttal vagy anélkül, szolgálhat sorvágó pontként, vagy csoportosítható úgy, hogy ne engedélyezzen sortöréseket. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Elhelyez egy függőleges tömböt. |
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