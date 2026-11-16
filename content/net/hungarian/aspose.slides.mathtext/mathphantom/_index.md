---
title: MathPhantom
second_title: Aspose.Sildes .NET API hivatkozás
description: Egy fantom matematikai objektum (<m:phant>) képvisel, amely befolyásolja a gyermekelem elrendezését anélkül, hogy feltétlenül megjelenítené azt. A fantom elrejtheti az alapkifejezést, miközben megőrzi a szélességét, magasságát vagy mélységét a képletek igazításához vagy helyfoglaláshoz. A láthatóságot és a geometriai viselkedést olyan tulajdonságok szabályozzák, mint a Show, ZeroWid, ZeroAsc, ZeroDesc és a Transp.
type: docs
weight: 8940
url: /hu/aspose.slides.mathtext/mathphantom/
---
## MathPhantom osztály

Egy fantom matematikai objektum (<m:phant>) reprezentál, amely befolyásolja a gyermekelem elrendezését anélkül, hogy feltétlenül megjelenítené azt. A fantom elrejtheti az alapkifejezését, miközben megőrzi a szélességét, magasságát vagy mélységét a képletek igazításához vagy helyfoglaláshoz. A láthatóságot és a geometriai viselkedést olyan tulajdonságok szabályozzák, mint a Show, ZeroWid, ZeroAsc, ZeroDesc és a Transp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | Új példányt hoz létre a [`MathPhantom`](../mathphantom) osztályból a megadott almath elem használatával. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | Alap argumentum |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | Értéket kap vagy állít be, amely jelzi, hogy az alapelem megjelenik-e. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | Értéket kap vagy állít be, amely jelzi, hogy a fantom átlátszó-e az osztályalapú térköz szabályokhoz. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | Értéket kap vagy állít be, amely jelzi, hogy az alapelem felemelkedése (alapvonal feletti magasság) legyen-e nulla. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | Értéket kap vagy állít be, amely jelzi, hogy az alapelem süllyedése (alapvonal alatti mélység) legyen-e nulla. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | Értéket kap vagy állít be, amely jelzi, hogy az alapelem szélessége legyen-e nulla. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akcentusjelzőt (egy karakter az elem tetején). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megadott függvényt vesz, amely ezt a példányt használja argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megadott függvényt vesz, amely ezt a példányt használja argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megadott függvényt vesz, amely ezt a példányt használja argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megadott függvényt vesz, amely ezt a példányt argumentumként és a megadott további argumentumot használja. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megadott függvényt vesz, amely ezt a példányt argumentumként és a megadott további argumentumot használja. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Egy matematikai elemet zárójelek közé helyez. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Virtuálisan egy matematikai elemet megadott karakterek közé helyez, például zárójelek vagy más karakterek keretezésként. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Megad egy argumentumfüggvényt, amely ezt a példányt használja függvénynévként. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Megad egy argumentumfüggvényt, amely ezt a példányt használja függvénynévként. |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | Visszaadja a gyermekelemeket. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakter, például alsó kapcsos zárójel vagy más, használatával. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Integrált vesz korlátok nélkül. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrált vesz. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrált vesz. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrált vesz. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrált vesz. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Virtuálisan egy matematikai elemet összekapcsol és matematikai blokkot hoz létre. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Virtuálisan matematikai szöveget összekapcsol és matematikai blokkot hoz létre. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-áris operátort hoz létre. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-áris operátort hoz létre. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Egy vonalat helyez ennek az elemnek a tetejére. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határt vesz. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határt vesz. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon alsó és felső indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon alsó és felső indexet hoz létre. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon alsó és felső indexet hoz létre. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon alsó és felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt vesz. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt vesz. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretes dobozba helyezi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretes dobozba helyezi. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy dobozos objektum például operátor emulátorként szolgálhat igazítási ponttal vagy anélkül, sorvége pontként, vagy úgy csoportosítható, hogy ne engedje meg a sortörést. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Virtuálisan egy függőleges tömbbe helyezi. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Egy vonalat helyez ennek az elemnek az aljára. |

### Példák

Példa:

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // Elrejti a tartalmat
phantom.ZeroWidth = false;     // Megőrzi a szélességet
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathPhantom](../imathphantom)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->