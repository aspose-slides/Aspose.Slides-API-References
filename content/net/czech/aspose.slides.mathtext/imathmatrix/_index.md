---
title: IMathMatrix
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Definuje objekt Matrix, který se skládá z podřízených prvků uspořádaných v jednom nebo více řádcích a sloupcích. Je důležité poznamenat, že matice nemají vestavěné oddělovače. Pro umístění matice do závorek byste měli použít objekt oddělovače IMathDelimiter. Null argumenty lze použít k vytvoření mezer v maticích.
type: docs
weight: 8360
url: /cs/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix rozhraní

Definuje objekt Matrix, který se skládá z podřízených prvků uspořádaných v jednom nebo více řádcích a sloupcích. Je důležité poznamenat, že matice nemají vestavěné oddělovače. Pro umístění matice do závorek byste měli použít objekt oddělovače (IMathDelimiter). Null argumenty lze použít k vytvoření mezer v maticích.

```csharp
public interface IMathMatrix : IMathElement
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Umožňuje získat základní rozhraní IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Určuje svislé zarovnání vzhledem k okolnímu textu. Možné hodnoty jsou top, bottom a center. Výchozí: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Počet sloupců v matici |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Hodnota vodorovného rozestupu mezi sloupci matice; pokud je ColumnGapRule nastaven na 3 ("Exactly"), jednotka je interpretována jako twipy (1/20 bodu). Pokud je ColumnGapRule nastaven na 4 ("Multiple"), jednotka je interpretována jako počet 0.5 em kroků. V ostatních případech je ignorována. Výchozí: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Typ vodorovného rozestupu mezi sloupci matice; jednotky vodorovného rozestupu mohou být ems nebo points (uloženy jako twipy). Výchozí: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Skryje zástupné znaky pro prázdné prvky matice. Výchozí: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Prvky matice |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Minimální šířka sloupce v twipech (1/20 bodu). Rozestup mezery (také nazývaný “Column Gap” nebo “Gap Width”) se přičítá k MinColumnWidth pro určení celkového rozestupu sloupců matice (vzdálenost mezi stejnými hranami různých sloupců). Výchozí: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Počet řádků v matici |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Hodnota svislého rozestupu mezi řádky matice; pokud je RowGapRule nastaven na 3 ("Exactly"), jednotka je interpretována jako twipy (1/20 bodu). Pokud je RowGapRule nastaven na 4 ("Multiple"), jednotka je interpretována jako poloviční řádky. Výchozí: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Typ svislého rozestupu mezi řádky matice; jednotky svislého rozestupu mohou být lines nebo points (uloženy jako twipy). Výchozí: SingleSpacingGap (0) |

## Metody

| Název | Popis |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Odstraní zadaný sloupec |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Odstraní zadaný řádek |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Získá vodorovné zarovnání zadaného sloupce |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Vloží nový sloupec za zadaný. Na začátku jsou všechny prvky v novém sloupci null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Vloží nový sloupec před zadaný. Na začátku jsou všechny prvky v novém sloupci null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Vloží nový řádek za zadaný. Na začátku jsou všechny prvky v novém řádku null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Vloží nový řádek před zadaný. Na začátku jsou všechny prvky v novém řádku null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Nastaví vodorovné zarovnání zadaného sloupce |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Nastaví vodorovné zarovnání zadaných sloupců |

### Příklady

Příklad:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Viz také

* rozhraní [IMathElement](../imathelement)
* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->