---
title: MathMatrix
second_title: Aspose.Sildes .NET API Referencia
description: Meghatározza a Matrix objektumot, amely gyermekelemekből áll, és egy vagy több sorban és oszlopban helyezkedik el. Fontos megjegyezni, hogy a mátrixoknak nincsenek beépített határolóik. A mátrixot a zárójelek közé helyezni a IMathDelimiter határolóobjektumot kell használni. Null argumentumok használhatók a mátrixokban hézagok létrehozásához.
type: docs
weight: 8850
url: /hu/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix osztály

Meghatározza a Matrix objektumot, amely gyermekelemekből áll és egy vagy több sorban és oszlopban helyezkedik el. Fontos megjegyezni, hogy a mátrixoknak nincsenek beépített határolóik. A mátrix zárójelek közé helyezéséhez a határoló objektumot (IMathDelimiter) kell használni. Null argumentumok használhatók a mátrixokban hézagok létrehozásához.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Új MathMatrix példányt hoz létre. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Meghatározza a függőleges igazítást a környező szöveghez képest. Lehetséges értékek: top, bottom, és center. Alapértelmezett: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | A mátrix oszlopainak száma |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | A mátrix oszlopai közötti vízszintes hézag értéke; ha a ColumnGapRule értéke 3 („Exactly”), akkor az egység twipként (1/20 pont) értelmeződik. Ha a ColumnGapRule értéke 4 („Multiple”), akkor az egység 0,5 em léptékek száma. Egyéb esetekben figyelmen kívül hagyott. Alapértelmezett: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | A mátrix oszlopai közötti vízszintes hézag típusa; a vízszintes hézag egysége lehet em vagy pont (twipként tárolva). Alapértelmezett: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Elrejti az üres mátrixelemek helyőrzőit. Alapértelmezett: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Mátrix eleme |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Minimális oszlopszélesség twipben (1/20 pont). A hézag (más néven „Column Gap” vagy „Gap Width”) hozzáadódik a MinColumnWidth-hez a teljes mátrix oszlopszélesség meghatározásához. Alapértelmezett: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | A mátrix sorainak száma |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | A mátrix sorai közötti függőleges hézag értéke; ha a RowGapRule értéke 3 („Exactly”), akkor az egység twipként (1/20 pont) értelmeződik. Ha a RowGapRule értéke 4 („Multiple”), akkor az egység fél sor. Alapértelmezett: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | A mátrix sorai közötti függőleges hézag típusa; a függőleges hézag egysége lehet sor vagy pont (twipként tárolva). Alapértelmezett: SingleSpacingGap (0) |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akcentus jelet (egy karakter az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | A megadott függvényt a példányt argumentumként használva veszi |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | A megadott függvényt a példányt argumentumként használva veszi |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | A megadott függvényt a példányt argumentumként használva veszi |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | A megadott függvényt a példányt argumentumként használva veszi, és egy további argumentumot ad meg |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | A megadott függvényt a példányt argumentumként használva veszi, és egy további argumentumot ad meg |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Törli a megadott oszlopot |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Törli a megadott sort |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Egy matematikai elemet zárójelbe helyez |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Egy matematikai elemet a megadott karakterekkel (például zárójelek vagy egyéb keret karakterek) veszi körül |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Egy argumentumfüggvényt hoz létre a példányt függvénynévként használva |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Egy argumentumfüggvényt hoz létre a példányt függvénynévként használva |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Gyermekelemeket kér le |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | A megadott oszlop vízszintes igazítását adja vissza |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi a megadott csoportkarakterrel, például alsó kapcsos zárójel vagy egyéb |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Új oszlopot szúr be a megadott után. Kezdetben az új oszlop minden eleme null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Új oszlopot szúr be a megadott elé. Kezdetben az új oszlop minden eleme null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Új sort szúr be a megadott után. Kezdetben az új sor minden eleme null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Új sort szúr be a megadott elé. Kezdetben az új sor minden eleme null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | A határolók nélküli integrált hoz létre |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrált hoz létre |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrált hoz létre |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrált hoz létre |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrált hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Egy matematikai elemet összekapcsol, és matematikai blokkot képez |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematikai szöveget kapcsol össze, és matematikai blokkot képez |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-értékű operátort hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-értékű operátort hoz létre |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | A elem tetejére vonalat helyez |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | A megadott argumentum adott fokú matematikai gyökét adja meg. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | A megadott argumentum adott fokú matematikai gyökét adja meg. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | A megadott oszlop vízszintes igazítását állítja be |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | A megadott oszlopok vízszintes igazítását állítja be |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határt ad meg |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határt ad meg |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Balra helyezi az alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Balra helyezi az alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobbra helyezi az alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobbra helyezi az alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt ad meg |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt ad meg |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg részeinek csoportosítására használnak. Egy dobozolt objektum például operátor emulátorként szolgálhat, sor törés pontként, vagy olyan módon csoportosítható, hogy ne legyenek sortörések benne. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Az elem aljára vonalat helyez |

### Példák

Példa:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Lásd még

* class [MathElementBase](../mathelementbase)
* interface [IMathMatrix](../imathmatrix)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->