---
title: IMathMatrix
second_title: Aspose.Slides .NET API hivatkozás
description: Megadja a Matrix objektumot, amely gyermekelemeket tartalmaz, egy vagy több sorban és oszlopban elrendezve. Fontos megjegyezni, hogy a mátrixok nem rendelkeznek beépített elválasztókkal. A mátrix zárójelek közé helyezéséhez a delimiter objektumot, az IMathDelimiter-t kell használni. Null argumentumokkal lehet hézagokat létrehozni a mátrixokban.
type: docs
weight: 8340
url: /hu/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interfész

Meghatározza a Matrix objektumot, amely gyermekelemeket tartalmaz, sorokban és oszlopokban elrendezve. Fontos megjegyezni, hogy a mátrixok nem rendelkeznek beépített elválasztókkal. A mátrix zárójelek közé helyezéséhez a delimiter objektumot (IMathDelimiter) kell használni. Null argumentumokkal lehet hézagokat létrehozni a mátrixokban.

```csharp
public interface IMathMatrix : IMathElement
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Lehetővé teszi a bazális IMathElement interfész lekérését [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Meghatározza a függőleges igazítást a környező szöveghez viszonyítva. Lehetséges értékek: top, bottom, és center. Alapértelmezett: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | A mátrix oszlopainak száma |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule 3-ra („Exactly”) van beállítva, akkor az egység twipként (pont 1/20-a) értelmeződik. Ha a RowGapRule 4-re („Multiple”) van beállítva, akkor az egység 0,5 em lépés számaként értelmeződik. Egyéb esetekben figyelmen kívül hagyják. Alapértelmezett: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság egységei lehetnek em vagy point (twipben tárolva). Alapértelmezett: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Elrejti az üres mátrixelemek helyőrzőit. Alapértelmezett: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | A mátrix elemei |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | A minimális oszlopszélesség twipben (pont 1/20-a). A hézag (más néven „Column Gap” vagy „Gap Width”) a MinColumnWidth-hez hozzáadva adja meg a teljes Matrix Column Spacing-et (a különböző oszlopok azonos élei közti távolság). Alapértelmezett: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | A mátrix sorainak száma |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-ra („Exactly”) van beállítva, akkor az egység twipként (pont 1/20-a) értelmeződik. Ha a RowGapRule 4-re („Multiple”) van beállítva, akkor az egység fél sorként értelmeződik. Alapértelmezett: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság egységei lehetnek sorok vagy pontok (twipben tárolva). Alapértelmezett: SingleSpacingGap (0) |

## Metódusok

| Név | Leírás |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Törli a megadott oszlopot |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Törli a megadott sort |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | A megadott oszlop vízszintes igazításának lekérése |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Új oszlop beszúrása a megadott után. Kezdetben az új oszlop összes eleme null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Új oszlop beszúrása a megadott előtt. Kezdetben az új oszlop összes eleme null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Új sor beszúrása a megadott után. Kezdetben az új sor összes eleme null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Új sor beszúrása a megadott előtt. Kezdetben az új sor összes eleme null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Beállítja a megadott oszlop vízszintes igazítását |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Beállítja a megadott oszlopok vízszintes igazítását |

### Példák

Példa:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Lásd még

* interfész [IMathElement](../imathelement)
* névtere [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->