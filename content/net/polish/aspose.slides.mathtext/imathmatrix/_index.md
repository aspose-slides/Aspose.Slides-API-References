---
title: IMathMatrix
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Określa obiekt Matrix składający się z elementów podrzędnych ułożonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych ograniczników. Aby umieścić macierz w nawiasach, należy użyć obiektu ogranicznika IMathDelimiter. Argumenty null mogą być użyte do tworzenia przerw w macierzach.
type: docs
weight: 8340
url: /pl/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interfejs

Określa obiekt Matrix, składający się z elementów podrzędnych ułożonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych ograniczników. Aby umieścić macierz w nawiasach, należy użyć obiektu ogranicznika (IMathDelimiter). Argumenty null mogą być użyte do tworzenia przerw w macierzach.

```csharp
public interface IMathMatrix : IMathElement
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Umożliwia pobranie bazowego interfejsu IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Określa pionowe wyrównanie względem otaczającego tekstu. Dostępne wartości to top, bottom i center. Domyślne: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Liczba kolumn w macierzy |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 (\"Exactly\"), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 (\"Multiple\"), jednostka jest interpretowana jako liczba 0.5-krotnych jednostek em. W innych przypadkach ignorowane. Domyślne: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Typ poziomego odstępu między kolumnami macierzy; jednostki poziomego odstępu mogą być em lub points (przechowywane jako twips). Domyślne: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Ukrywa symbole zastępcze dla pustych elementów macierzy. Domyślne: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Elementy macierzy |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Minimalna szerokość kolumny w twips (1/20 punktu). Odstęp (nazywany także „Column Gap” lub „Gap Width”) jest dodawany do MinColumnWidth w celu określenia całkowitego odstępu kolumn macierzy (odległość między tymi samymi krawędziami różnych kolumn). Domyślne: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Liczba wierszy w macierzy |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 (\"Exactly\"), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli RowGapRule ma wartość 4 (\"Multiple\"), jednostka jest interpretowana jako pół-linii. Domyślne: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Typ pionowego odstępu między wierszami macierzy; jednostki pionowego odstępu mogą być lines lub points (przechowywane jako twips). Domyślne: SingleSpacingGap (0) |

## Metody

| Nazwa | Opis |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Usuwa określoną kolumnę |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Usuwa określony wiersz |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Pobiera poziome wyrównanie określonej kolumny |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Wstawia nową kolumnę po określonej. Początkowo wszystkie elementy w nowej kolumnie są null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Wstawia nową kolumnę przed określoną. Początkowo wszystkie elementy w nowej kolumnie są null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Wstawia nowy wiersz po określonym. Początkowo wszystkie elementy w nowym wierszu są null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Wstawia nowy wiersz przed określonym. Początkowo wszystkie elementy w nowym wierszu są null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Ustawia poziome wyrównanie określonej kolumny |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Ustawia poziome wyrównanie określonych kolumn |

### Przykłady

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Zobacz także

* interfejs [IMathElement](../imathelement)
* przestrzeń nazw [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->