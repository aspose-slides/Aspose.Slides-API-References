---
title: MathPhantom
second_title: Aspose.Sildes .NET API-referencia
description: Egy fantom matematikai objektumot (ltmphantgt) képvisel, amely befolyásolja gyermekeleme elrendezését anélkül, hogy feltétlenül megjelenítené azt. Egy fantom elrejtheti az alapkifejezését, miközben megőrzi a szélességét, magasságát vagy mélységét a képletek igazításához vagy hely lefoglalásához. A láthatóságot és a geometriai viselkedést olyan tulajdonságok szabályozzák, mint a Show, ZeroWid, ZeroAsc, ZeroDesc és a Transp.
type: docs
weight: 8900
url: /hu/aspose.slides.mathtext/mathphantom/
---
## MathPhantom osztály

Egy fantom matematikai objektum (&lt;m:phant&gt;) képvisel, amely befolyásolja a gyermekeleme elrendezését anélkül, hogy feltétlenül megjelenítené azt. Egy fantom elrejtheti az alapkifejezését, miközben megőrzi a szélességét, magasságát vagy mélységét a képletek igazításához vagy hely lefoglalásához. A láthatóságot és a geometriai viselkedést olyan tulajdonságok szabályozzák, mint a Show, ZeroWid, ZeroAsc, ZeroDesc és a Transp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## Konstruktorok

| Name | Description |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | Inicializál egy új példányt a [`MathPhantom`](../mathphantom) osztályból a megadott bázismatematikai elem használatával. |

## Tulajdonságok

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | Alap argumentum |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | Visszaad vagy beállít egy értéket, amely azt jelzi, hogy a báziselem megjelenik-e. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | Visszaad vagy beállít egy értéket, amely azt jelzi, hogy a fantom átlátszó-e az osztályalapú távolság szabályoknál. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | Visszaad vagy beállít egy értéket, amely azt jelzi, hogy a báziselem emelkedése (a vonal alatti magasság) nullaként legyen kezelve. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | Visszaad vagy beállít egy értéket, amely azt jelzi, hogy a báziselem süllyedése (a vonal alatti mélység) nullaként legyen kezelve. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | Visszaad vagy beállít egy értéket, amely azt jelzi, hogy a báziselem szélessége nullaként legyen kezelve. |

## Metódusok

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akcentusjelet (karaktert az elem tetején). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Alkalmazza a megadott függvényt, amely ezt a példányt argumentumként használja. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Alkalmazza a megadott függvényt, amely ezt a példányt argumentumként használja. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Alkalmazza a megadott függvényt, amely ezt a példányt argumentumként használja. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Alkalmazza a megadott függvényt, amely ezt a példányt argumentumként és a megadott további argumentumot használja. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Alkalmazza a megadott függvényt, amely ezt a példányt argumentumként és a megadott további argumentumot használja. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárja a matematikai elemet zárójelekbe. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Zárja a matematikai elemet megadott karakterek közé, például zárójelek vagy más karakterek. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Alkalmaz egy argumentumfüggvényt, ahol ez a példány a függvény neve. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Alkalmaz egy argumentumfüggvényt, ahol ez a példány a függvény neve. |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | Gyermekelemek lekérése. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elem elhelyezése egy csoportba alsó kapcsos zárójel használatával. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elem csoportba helyezése egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Kiszámítja az integrált határok nélkül. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Kiszámítja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Kiszámítja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Kiszámítja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Kiszámítja az integrált. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet, és matematikai blokkot hoz létre. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget, és matematikai blokkot hoz létre. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áris operátort. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áris operátort. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Beállít egy vonalat az elem tetejére. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Az alsó határ értéke. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Az alsó határ értéke. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Baloldali alsó és felső indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Baloldali alsó és felső indexet hoz létre. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobboldali alsó és felső indexet hoz létre. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobboldali alsó és felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | A felső határ értéke. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | A felső határ értéke. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elem elhelyezése egy keretes dobozban. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elem elhelyezése egy keretes dobozban. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elem elhelyezése egy nem vizuális dobozban (logikai csoportosítás), amelyet egy egyenlet vagy más matematikai szöveg elemeinek csoportosítására használnak. Egy keretezett objektum például szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, sorvége pontként, vagy úgy csoportosítható, hogy ne engedje a sortöréseket belül. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Beállít egy vonalat az elem aljára. |

### Példák

Example:

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // Elrejti a tartalmat
phantom.ZeroWidth = false;     // Megtartja a szélességet
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathPhantom](../imathphantom)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összegyűjtés [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->