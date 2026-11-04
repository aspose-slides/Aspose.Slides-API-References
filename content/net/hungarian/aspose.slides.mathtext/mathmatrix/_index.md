---
title: MathMatrix
second_title: Aspose.Sildes .NET API referenciája
description: Meghatározza a Matrix objektumot, amely gyermekelemekből áll, és egy vagy több sorba és oszlopba van rendezve. Fontos megjegyezni, hogy a mátrixoknak nincsenek beépített határolójaik. A mátrix zárójelbe helyezéséhez a határoló objektumot, az IMathDelimiter-t kell használni. Null argumentumokkal rések hozhatók létre a mátrixokban.
type: docs
weight: 8870
url: /hu/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix osztály

A Matrix objektumot határozza meg, amely gyermekelemekből áll, és egy vagy több sorba és oszlopba rendeződik. Fontos megjegyezni, hogy a mátrixoknak nincsenek beépített határolójeleik. A mátrix zárójelbe helyezéséhez a határoló objektumot (IMathDelimiter) kell használni. Null argumentumokkal rést hozhatunk létre a mátrixokban.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Új MathMatrix osztálypéldányt hoz létre. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Megadja a függőleges igazítást a környező szöveghez képest. Lehetséges értékek: top, bottom és center. Alapértelmezett: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | A mátrixban lévő oszlopok száma |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule 3-ra ("Exactly") van beállítva, akkor az egységet twip-ként (pont 1/20-a) értelmezi; ha a ColumnGapRule 4-re ("Multiple") van beállítva, akkor az egységet 0,5 em lépésként értelmezi. Más esetekben figyelmen kívül hagyja. Alapértelmezett: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság mértékegysége lehet em vagy point (twip-ben tárolva). Alapértelmezett: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Elrejti az üres mátrixelemek helyőrzőit. Alapértelmezett: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | A mátrix eleme |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | A minimális oszlopszélesség twip-ben (pont 1/20-a). A hézag távolság (más néven “Column Gap” vagy “Gap Width”) a MinColumnWidth-hez adódik, hogy meghatározza a teljes Matrix Column Spacing-et (a különböző oszlopok azonos élei közti távolság). Alapértelmezett: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | A mátrix sorainak száma |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-ra ("Exactly") van beállítva, akkor az egységet twip-ként (pont 1/20-a) értelmezi; ha a RowGapRule 4-re ("Multiple") van beállítva, akkor az egységet fél sorként értelmezi. Alapértelmezett: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság mértékegysége sor vagy point (twip-ben tárolva). Alapértelmezett: SingleSpacingGap (0) |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Akcentusjelet állít be (karakter a elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | A megadott függvényt veszi, a példányt az argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | A megadott függvényt veszi, a példányt az argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | A megadott függvényt veszi, a példányt az argumentumként használva |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | A megadott függvényt veszi, a példányt argumentumként használja, és a megadott további argumentumot is |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | A megadott függvényt veszi, a példányt argumentumként használja, és a megadott további argumentumot is |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Törli a megadott oszlopot |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Törli a megadott sort |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelbe helyezi a matematikai elemet |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | A megadott karakterek közé helyezi a matematikai elemet, mint például zárójelek vagy más keretező karakterek |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | A példányt függvényneveként használva egy argumentumfüggvényt vesz |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | A példányt függvényneveként használva egy argumentumfüggvényt vesz |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Lekéri a gyermekelemeket |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Lekéri a megadott oszlop vízszintes igazítását |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet alulra ívelt zárójel segítségével csoportba helyezi |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakter, például alulra ívelt zárójel vagy más segítségével |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Új oszlopot szúr be a megadott után. Kezdetben az új oszlop összes eleme null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Új oszlopot szúr be a megadott előtt. Kezdetben az új oszlop összes eleme null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Új sort szúr be a megadott után. Kezdetben az új sor összes eleme null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Új sort szúr be a megadott előtt. Kezdetben az új sor összes eleme null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Az integrált határok nélkül veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMMathElement, IMathElement) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet, és egy matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget, és egy matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áramú operátort |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áramú operátort |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Felső vonalat helyez az elemre |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyökeret a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyökeret a megadott argumentumból. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Beállítja a megadott oszlop vízszintes igazítását |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Beállítja a megadott oszlopok vízszintes igazítását |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Az alsó határt veszi |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Az alsó határt veszi |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon létrehoz egy alsó és egy felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon létrehoz egy alsó és egy felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobbra hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobbra hoz létre alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | A felső határt veszi |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | A felső határt veszi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak. A dobozos objektum (például) operátor emulátorként szolgálhat igazítási ponttal vagy anélkül, sorvége jelként vagy úgy csoportosítható, hogy ne engedjen sortörést a belsejében. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Alsó vonalat helyez az elemre |

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