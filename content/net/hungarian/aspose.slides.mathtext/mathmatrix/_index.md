---
title: MathMatrix
second_title: Aspose.Sildes .NET API-referencia
description: Megadja a Matrix objektumot, amely gyermekelemekből áll, amelyek egy vagy több sorban és oszlopban vannak elrendezve. Fontos megjegyezni, hogy a mátrixok nem rendelkeznek beépített határolókkal. A mátrixot zárójelekbe helyezni a delimiter objektum, az IMathDelimiter használatával kell. Null argumentumokkal hézagok hozhatók létre a mátrixokban.
type: docs
weight: 8830
url: /hu/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix osztály

Megadja a Matrix objektumot, amely gyermekelemekből áll, amelyek egy vagy több sorban és oszlopban vannak elrendezve. Fontos megjegyezni, hogy a mátrixok nem rendelkeznek beépített határolókkal. A mátrix zárójelekbe helyezéséhez a delimiter objektumot (IMathDelimiter) kell használni. Null argumentumokkal hézagok hozhatók létre a mátrixokban.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Új MathMatrix példányt inicializál. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Megadja a függőleges igazítást a környező szöveghez képest. Lehetséges értékek: top, bottom, és center. Alapértelmezett: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | A mátrix oszlopainak száma |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule 3-ra („Exactly”) van állítva, a mértékegység twip (1/20 pont). Ha a ColumnGapRule 4-re („Multiple”) van állítva, a mértékegység 0,5-es em lépések száma. Egyéb esetben figyelmen kívül hagyott. Alapértelmezett: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság egysége lehet em vagy point (twip-ként tárolva). Alapértelmezett: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Elrejti az üres mátrixelemek helyőrzőit. Alapértelmezett: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | A mátrix eleme |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Minimum oszlopszélesség twip-ben (1/20 pont). A hézag (más néven „Column Gap” vagy „Gap Width”) a MinColumnWidth-hez adódik, hogy megkapjuk a teljes mátrix oszloptávolságot (különböző oszlopok azonos széle közti távolság). Alapértelmezett: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | A mátrix sorainak száma |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-ra („Exactly”) van állítva, a mértékegység twip (1/20 pont). Ha a RowGapRule 4-re („Multiple”) van állítva, a mértékegység fél-sor. Alapértelmezett: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság egysége lehet line vagy point (twip-ként tárolva). Alapértelmezett: SingleSpacingGap (0) |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Akcentusjelet (a elem tetején megjelenő karaktert) állít be |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | A megadott függvényt a példányt argumentumként használva hajtja végre |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | A megadott függvényt a példányt argumentumként használva hajtja végre |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | A megadott függvényt a példányt argumentumként használva hajtja végre |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | A megadott függvényt a példányt argumentumként használva hajtja végre és a megadott további argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | A megadott függvényt a példányt argumentumként használva hajtja végre és a megadott további argumentumot |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | A megadott oszlopot törli |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | A megadott sort törli |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz a megadott típusú törtet a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz a megadott típusú törtet a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Egy matematikai elemet zárójelekbe helyez |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Egy matematikai elemet a megadott karakterekkel, például zárójelekkel vagy egyéb keretező karakterekkel helyez körül |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Az argumentum függvényét a példányt függvénynevének használatával veszi |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Az argumentum függvényét a példányt függvénynevének használatával veszi |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Gyermekelemeket ad vissza |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | A megadott oszlop vízszintes igazítását adja vissza |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy alsó szögletes zárójelekből álló csoportba helyezi |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó szögletes zárójel vagy más karakter |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Új oszlopot szúr be a megadott után; kezdetben az új oszlop elemei null értékűek. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Új oszlopot szúr be a megadott előtt; kezdetben az új oszlop elemei null értékűek. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Új sort szúr be a megadott után; kezdetben az új sor elemei null értékűek. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Új sort szúr be a megadott előtt; kezdetben az új sor elemei null értékűek. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | A határolók nélküli integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Matematikai elemet összekapcsol és matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematikai szöveget összekapcsol és matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary operátort hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary operátort hoz létre |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | A elem tetejére vonalat helyez |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | A megadott fokú matematikai gyököt a megadott argumentumból állítja elő |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | A megadott fokú matematikai gyököt a megadott argumentumból állítja elő |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | A megadott oszlop vízszintes igazítását állítja be |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | A megadott oszlopok vízszintes igazítását állítja be |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határértéket vesz |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határértéket vesz |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határértéket vesz |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határértéket vesz |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keret-dobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keret-dobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem-visualis dobozba (logikai csoportosításba) helyezi, amelyet egyenletek vagy egyéb matematikai szövegek komponenseinek csoportosítására használnak. Egy keretezett objektum például operátor-szimulátorként működhet igazítási ponttal vagy anélkül, vonaltörés-pontként szolgálhat, vagy úgy csoportosítható, hogy ne engedélyezi a sorok tördelését. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbé rendezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Az elem aljára vonalat helyez |

### Példák

Példa:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathMatrix](../imathmatrix)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->