---
title: IMathMatrix
second_title: Aspose.Sildes för .NET API-referens
description: Specificerar Matrix-objektet som består av underordnade element placerade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda avgränsare. För att placera matrisen i hakparenteserna bör du använda avgränsningsobjektet IMathDelimiter. Null-argument kan användas för att skapa luckor i matriser.
type: docs
weight: 8340
url: /sv/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix gränssnitt

Specificerar Matrix-objektet, bestående av underordnade element som placeras i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda avgränsare. För att placera matrisen i hakparenteser bör du använda avgränsningsobjektet (IMathDelimiter). Null-argument kan användas för att skapa luckor i matriser.

```csharp
public interface IMathMatrix : IMathElement
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Tillåter att hämta grundläggande IMathElement-gränssnitt [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Anger den vertikala justeringen i förhållande till omgivande text. Möjliga värden är top, bottom och center. Standard: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Antal kolumner i matrisen |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Värdet för horisontellt avstånd mellan kolumner i en matris; om ColumnGapRule är satt till 3 ("Exactly") tolkas enheten som twips (1/20 av en punkt) om ColumnGapRule är satt till 4 ("Multiple") tolkas enheten som antal 0,5-em-steg. I andra fall ignoreras det. Standard: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Typen av horisontellt avstånd mellan kolumner i en matris; horisontella avståndsenheter kan vara ems eller punkter (lagrade som twips). Standard: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Döljer platshållarna för tomma matriselement. Standard: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Element i matrisen |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Minimal kolumnbredd i twips (1/20 av en punkt). Gap-avståndet (även kallat “Column Gap” eller “Gap Width”) läggs till MinColumnWidth för att bestämma den totala matrisens kolumnavstånd (avståndet mellan samma kanter på olika kolumner). Standard: 0 |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Antal rader i matrisen |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Värdet för vertikalt avstånd mellan rader i en matris; om RowGapRule är satt till 3 ("Exactly") tolkas enheten som twips (1/20 av en punkt). Om RowGapRule är satt till 4 ("Multiple") tolkas enheten som halva rader. Standard: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Typen av vertikalt avstånd mellan rader i en matris; vertikala avståndsenheter kan vara rader eller punkter (lagrade som twips). Standard: SingleSpacingGap (0) |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Tar bort den angivna kolumnen |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Tar bort den angivna raden |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Hämtar den horisontella justeringen för den angivna kolumnen |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Infogar en ny kolumn efter den angivna. Initialt är alla element i den nya kolumnen null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Infogar en ny kolumn före den angivna. Initialt är alla element i den nya kolumnen null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Infogar en ny rad efter den angivna. Initialt är alla element i den nya raden null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Infogar en ny rad före den angivna. Initialt är alla element i den nya raden null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Ställer in den horisontella justeringen för den angivna kolumnen |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Ställer in den horisontella justeringen för de angivna kolumnerna |

### Exempel

Exempel:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Se även

* gränssnitt [IMathElement](../imathelement)
* namnrymd [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->