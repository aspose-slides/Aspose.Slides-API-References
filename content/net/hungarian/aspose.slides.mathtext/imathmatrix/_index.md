---
title: IMathMatrix
second_title: Aspose.Sildes .NET API referencia
description: Megadja a Matrix objektumot, amely gyermekelemekből áll, és egy vagy több sorban és oszlopban helyezkedik el. Fontos megjegyezni, hogy a mátrixoknak nincsenek beépített határolóik. A mátrix zárójelek közé helyezéséhez a határolóobjektumot IMathDelimiter kell használni. Null argumentumokkal lehet hézagokat létrehozni a mátrixokban.
type: docs
weight: 8320
url: /hu/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interfész

Megadja a Matrix objektumot, amely gyermekelemekből áll, és egy vagy több sorban és oszlopban helyezkedik el. Fontos megjegyezni, hogy a mátrixoknak nincsenek beépített határolóik. A mátrix zárójelek közé helyezéséhez a határolóobjektumot (IMathDelimiter) kell használni. Null argumentumok használhatók a mátrixokban hézagok létrehozásához.

```csharp
public interface IMathMatrix : IMathElement
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Lehetővé teszi a base IMathElement interfész [`IMathElement`](../imathelement) lekérését |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Meghatározza a függőleges igazítást a környező szöveghez képest. Lehetséges értékek a top, bottom és center. Alapértelmezett: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | A mátrix oszlopainak száma |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule 3-ra („Exactly”) van állítva, akkor az egység twip (1/20 pont) formájában értelmeződik. Ha a ColumnGapRule 4-re („Multiple”) van állítva, akkor az egység 0,5 em lépésként értelmeződik. Egyéb esetekben figyelmen kívül marad. Alapértelmezett: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság egysége lehet em vagy pont (twipként tárolva). Alapértelmezett: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Elrejti az üres mátrixelemek helykitöltőit. Alapértelmezett: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | A mátrix elemei |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Minimum oszlopszélesség twipben (1/20 pont). A hézag (más néven „Column Gap” vagy „Gap Width”) a MinColumnWidth-hez adódik, meghatározva a teljes Matrix Column Spacing-et (a különböző oszlopok azonos élei közti távolság). Alapértelmezett: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | A mátrix sorainak száma |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-ra („Exactly”) van állítva, akkor az egység twip (1/20 pont) formájában értelmeződik. Ha a RowGapRule 4-re („Multiple”) van állítva, akkor az egység fél sor. Alapértelmezett: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság egysége lehet sor vagy pont (twipként tárolva). Alapértelmezett: SingleSpacingGap (0) |

## Módszerek

| Név | Leírás |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Törli a megadott oszlopot |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Törli a megadott sort |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Lekéri a megadott oszlop vízszintes igazítását |
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
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->