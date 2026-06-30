---
title: MathBox
second_title: Aspose.Slides .NET API-referencia
description: Meghatározza a matematikai elem logikai becsomagolását. Például egy becsomagolt objektum szolgálhat operátoremulátorként, legyen benne vagy ne legyen igazítási pont, szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedélyezzen sortöréseket. Például az operátort becsomagolni kell a sortörések elkerülése érdekében.
type: docs
weight: 8610
url: /hu/aspose.slides.mathtext/mathbox/
---
## MathBox osztály

Meghatározza a matematikai elem logikai becsomagolását (csomagolását). Például egy becsomagolt objektum szolgálhat operátoremulátorként, legyen benne vagy ne legyen igazítási pont, szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedélyezzen sortöréseket belül. Például a "==" operátort becsomagolni kell a sortörések elkerülése érdekében.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Inicializálja a MathBox-ot a megadott elemmel argumentumként |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Ha igaz, ez az operátoremulátor igazítási pontként működik; ez azt jelenti, hogy más egyenletekben kijelölt igazítási pontok ehhez igazíthatók. Alapértelmezett: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Alap argumentum |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differenciális Ha igaz, a doboz differenciálisként működik (például 𝑑𝑥 egy integrandusban), és megkapja a megfelelő vízszintes távolságot a matematikai differenciához. Alapértelmezett: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicit break meghatározza, hogy van-e sortörés a Box objektum elején, úgy hogy a sor a doboz elején törik. Megadja a korábbi sor matematikai szövegében lévő operátor számát, amely a jelenlegi sor matematikai szövegének igazítási pontjaként lesz használva. Lehetséges értékek: 1..255 Alapértelmezett: 0 (nincs explicit törés) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break Ez a tulajdonság meghatározza a „unbreakable” (törhetetlen) tulajdonságot az objektumdobozon. Ha igaz, akkor a dobozon belül nem fordulhat elő sortörés. Ez fontos lehet több bináris operátorból álló operátoremulátoroknál. Ha ez az elem nincs megadva, a dobozon belül előfordulhatnak törések. Alapértelmezett: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operátoremulátor. Ha igaz, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti, hogy például a karakter szolgálhat sortörés pontként, és igazítható más operátorokhoz. Az Operátoremulátorokat gyakran használják, amikor egy vagy több glif kombinálódik egy operátor létrehozásához, mint például a '=='. Alapértelmezett érték: false |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akszentjelet (egy karaktert az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megkapja a megadott függvényt, az aktuális példányt argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megkapja a megadott függvényt, az aktuális példányt argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megkapja a megadott függvényt, az aktuális példányt argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megkapja a megadott függvényt, az aktuális példányt argumentumként használva, valamint a megadott kiegészítő argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megkapja a megadott függvényt, az aktuális példányt argumentumként használva, valamint a megadott kiegészítő argumentumot |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelekbe veszi a matematikai elemet |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | A megadott karakterek közé (például zárójelek vagy más karakterek) keretezi a matematikai elemet |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Argumentumfüggvényt vesz, amelynek neve az aktuális példány |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Argumentumfüggvényt vesz, amelynek neve az aktuális példány |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Lekéri a gyermekelemeket |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi, alsó kapcsos zárójel használatával |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi, egy csoportosító karakter, például alsó kapcsos zárójel vagy más használatával |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Az integrált határak nélkül veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Egy matematikai elemet összekapcsol és egy matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Egy matematikai szöveget összekapcsol és matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áris operátort |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áris operátort |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Beállít egy vonalat az elem tetején |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határt vesz |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határt vesz |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Létrehoz alsó indexet |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Létrehoz alsó indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Létrehoz felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Létrehoz felső indexet |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt vesz |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt vesz |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak. Egy becsomagolt objektum (például) működhet operátoremulátorként, legyen benne vagy ne legyen igazítási pont, szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedélyezzen sortöréseket. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Az elem aljára egy vonalat helyez |

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