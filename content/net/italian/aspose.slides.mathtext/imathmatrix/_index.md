---
title: IMathMatrix
second_title: Riferimento API Aspose.Sildes per .NET
description: Specifica l'oggetto Matrix composto da elementi figli disposti in una o più righe e colonne. È importante notare che le matrici non hanno delimitatori incorporati. Per inserire la matrice tra parentesi è necessario utilizzare l'oggetto delimitatore IMathDelimiter. È possibile utilizzare argomenti null per creare spazi vuoti nelle matrici.
type: docs
weight: 8360
url: /it/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interfaccia

Specifica l'oggetto Matrix, costituito da elementi figli disposti in una o più righe e colonne. È importante notare che le matrici non hanno delimitatori incorporati. Per inserire la matrice tra parentesi è necessario utilizzare l'oggetto delimitatore (IMathDelimiter). È possibile utilizzare argomenti null per creare spazi vuoti nelle matriche.

```csharp
public interface IMathMatrix : IMathElement
```

## Proprietà

| Name | Description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Consente di ottenere l'interfaccia IMathElement di base [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Specifica l'allineamento verticale rispetto al testo circostante. I valori possibili sono top, bottom e center. Predefinito: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Numero di colonne nella matrice |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Il valore della spaziatura orizzontale tra le colonne di una matrice; se ColumnGapRule è impostato su 3 (\"Exactly\"), l'unità è interpretata come twips (1/20 di punto) se ColumnGapRule è impostato su 4 (\"Multiple\"), l'unità è interpretata come numero di incrementi di 0,5 em. In altri casi viene ignorato. Predefinito: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere ems o points (memorizzati come twips). Predefinito: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Nasconde i segnaposto per gli elementi di matrice vuoti Predefinito: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Elementi della matrice |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Larghezza minima della colonna in twips (1/20 di punto) La spaziatura dell'interruzione (nota anche come “Column Gap” o “Gap Width”) è aggiunta a MinColumnWidth per determinare la spaziatura totale delle colonne della matrice (distanza tra gli stessi bordi delle diverse colonne). Predefinito: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Numero di righe nella matrice |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato su 3 (\"Exactly\"), l'unità è interpretata come twips (1/20 di punto) se RowGapRule è impostato su 4 (\"Multiple\"), l'unità è interpretata come mezze linee. Predefinito: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere lines o points (memorizzati come twips). Predefinito: SingleSpacingGap (0) |

## Metodi

| Name | Description |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Elimina la colonna specificata |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Elimina la riga specificata |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Ottiene l'allineamento orizzontale della colonna specificata |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Inserisce una nuova colonna dopo quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Inserisce una nuova colonna prima di quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Inserisce una nuova riga dopo quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Inserisce una nuova riga prima di quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Imposta l'allineamento orizzontale della colonna specificata |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Imposta l'allineamento orizzontale delle colonne specificate |

### Esempi

Esempio:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Vedi anche

* interfaccia [IMathElement](../imathelement)
* spazio dei nomi [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->