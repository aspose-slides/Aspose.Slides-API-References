---
title: IMathMatrix
second_title: Aspose.Sildes voor .NET API-referentie
description: Specificeert het Matrix-object bestaande uit onderliggende elementen die in één of meer rijen en kolommen zijn gerangschikt. Het is belangrijk op te merken dat matrices geen ingebouwde delimiters hebben. Om de matrix tussen haakjes te plaatsen, moet je het delimiter object IMathDelimiter gebruiken. Null-argumenten kunnen worden gebruikt om gaten in matrices te creëren.
type: docs
weight: 8360
url: /nl/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interface

Specificeert het Matrix-object, bestaande uit onderliggende elementen die in één of meer rijen en kolommen zijn gerangschikt. Het is belangrijk op te merken dat matrices geen ingebouwde delimiters hebben. Om de matrix tussen haakjes te plaatsen, moet je het delimiter-object (IMathDelimiter) gebruiken. Null-argumenten kunnen worden gebruikt om gaten in matrices te creëren.

```csharp
public interface IMathMatrix : IMathElement
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Staat toe om de basis IMathElement-interface [`IMathElement`](../imathelement) op te halen |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Specificeert de verticale uitlijning ten opzichte van de omliggende tekst. Mogelijke waarden zijn top, bottom, en center. Standaard: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Aantal kolommen in de matrix |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | De waarde van de horizontale afstand tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 ("Exactly"), wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) Als de ColumnGapRule is ingesteld op 4 ("Multiple"), wordt de eenheid geïnterpreteerd als een aantal 0,5 em-stappen. In andere gevallen wordt genegeerd. Standaard: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Het type horizontale afstand tussen kolommen van een matrix; Horizontale afstandseenheden kunnen ems of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Verberg de tijdelijke aanduidingen voor lege matrixelementen Standaard: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Elementen van de matrix |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Minimum kolombreedte in twips (1/20e van een punt) De spatiëring (ook wel “Column Gap” of “Gap Width” genoemd) wordt toegevoegd aan de MinColumnWidth om de totale Matrix-kolomspatiëring (afstand tussen dezelfde randen van verschillende kolommen) te bepalen. Standaard: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Aantal rijen in de matrix |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | De waarde van de verticale afstand tussen rijen van een matrix; Als de RowGapRule is ingesteld op 3 ("Exactly"), wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) Als de RowGapRule is ingesteld op 4 ("Multiple"), wordt de eenheid geïnterpreteerd als halve lijnen. Standaard: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Het type verticale afstand tussen rijen van een matrix; Verticale afstandseenheden kunnen lijnen of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0) |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Verwijdert de opgegeven kolom |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Verwijdert de opgegeven rij |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Haalt de horizontale uitlijning op van de opgegeven kolom |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Voegt een nieuwe kolom in na de opgegeven. Initieel zijn alle elementen in de nieuwe kolom null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Voegt een nieuwe kolom in vóór de opgegeven. Initieel zijn alle elementen in de nieuwe kolom null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Voegt een nieuwe rij in na de opgegeven. Initieel zijn alle elementen in de nieuwe rij null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Voegt een nieuwe rij in vóór de opgegeven. Initieel zijn alle elementen in de nieuwe rij null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Stelt de horizontale uitlijning in van de opgegeven kolom |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Stelt de horizontale uitlijning in van de opgegeven kolommen |

### Voorbeelden

Voorbeeld:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Zie ook

* interface [IMathElement](../imathelement)
* naamruimte [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->