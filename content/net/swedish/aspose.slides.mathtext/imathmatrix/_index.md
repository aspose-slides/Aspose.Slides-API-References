---
title: IMathMatrix
second_title: Aspose.Sildes för .NET API-referens
description: Specificerar Matrix-objektet som består av underordnade element placerade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda avgränsare. För att placera matrisen i hakparenteser bör du använda avgränsningsobjektet IMathDelimiter. Null-argument kan användas för att skapa luckor i matriser.
type: docs
weight: 8320
url: /sv/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix gränssnitt

Specificerar Matrix-objektet, bestående av underordnade element placerade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda avgränsare. För att placera matrisen i hakparenteser bör du använda avgränsningsobjektet (IMathDelimiter). Null-argument kan användas för att skapa luckor i matriser.

```csharp
public interface IMathMatrix : IMathElement
```

## Egenskaper

| Name | Description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Gör det möjligt att hämta bas-IMathElement-gränssnittet [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Anger vertikal justering i förhållande till omgivande text. Möjliga värden är top, bottom och center. Standard: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Antalet kolumner i matrisen |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Värdet för horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är satt till 3 ("Exactly") tolkas enheten som twips (1/20 av en punkt). Om ColumnGapRule är satt till 4 ("Multiple") tolkas enheten som antal 0.5 em-steg. Ignoreras i andra fall. Standard: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Typen av horisontellt avstånd mellan kolumner i en matris; Horisontella avståndsenheter kan vara ems eller points (lagrade som twips). Standard: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Döljer platshållare för tomma matrixelement. Standard: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Element i matrisen |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Minsta kolumnbredd i twips (1/20 av en punkt). Gap-avståndet (även kallat ”Column Gap” eller ”Gap Width”) läggs till MinColumnWidth för att bestämma total Matrix Column Spacing (avståndet mellan samma kanter på olika kolumner). Standard: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Antalet rader i matrisen |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Värdet för vertikalt avstånd mellan rader i en matris; Om RowGapRule är satt till 3 ("Exactly") tolkas enheten som twips (1/20 av en punkt). Om RowGapRule är satt till 4 ("Multiple") tolkas enheten som halva rader. Standard: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Typen av vertikalt avstånd mellan rader i en matris; Vertikala avståndsenheter kan vara lines eller points (lagrade som twips). Standard: SingleSpacingGap (0) |

## Metoder

| Name | Description |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Tar bort den angivna kolumnen |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Tar bort den angivna raden |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Hämtar horisontell justering för den angivna kolumnen |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Infogar en ny kolumn efter den angivna. Initialt är alla element i den nya kolumnen null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Infogar en ny kolumn före den angivna. Initialt är alla element i den nya kolumnen null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Infogar en ny rad efter den angivna. Initialt är alla element i den nya raden null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Infogar en ny rad före den angivna. Initialt är alla element i den nya raden null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Sätter horisontell justering för den angivna kolumnen |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Sätter horisontell justering för de angivna kolumnerna |

### Exempel

Exempel:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Se även

* gränssnitt [IMathElement](../imathelement)
* namnutrymme [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->