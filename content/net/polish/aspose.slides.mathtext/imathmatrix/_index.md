---
title: IMathMatrix
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Określa obiekt Matrix składający się z elementów potomnych rozmieszczonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych delimiterów. Aby umieścić macierz w nawiasach, należy użyć obiektu delimiter IMathDelimiter. Argumenty null mogą być użyte do tworzenia przerw w macierzach.
type: docs
weight: 8320
url: /pl/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interfejs

Określa obiekt Matrix, składający się z elementów potomnych rozmieszczonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych delimiterów. Aby umieścić macierz w nawiasach, należy użyć obiektu delimiter (IMathDelimiter). Argumenty null mogą być użyte do tworzenia przerw w macierzach.

```csharp
public interface IMathMatrix : IMathElement
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Umożliwia pobranie podstawowego interfejsu IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Określa pionowe justowanie względem otaczającego tekstu. Dozwolone wartości to top, bottom i center. Domyślne: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Liczba kolumn w macierzy |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Wartość odstępu poziomego między kolumnami macierzy; jeśli ColumnGapRule jest ustawione na 3 („Exactly”), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli ColumnGapRule jest ustawione na 4 („Multiple”), jednostka jest interpretowana jako liczba przyrostów 0,5 em. W innych przypadkach ignorowane. Domyślne: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Typ odstępu poziomego między kolumnami macierzy; jednostki odstępu poziomego mogą być em lub points (przechowywane jako twipy). Domyślne: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Ukrywa symbole zastępcze dla pustych elementów macierzy. Domyślne: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Elementy macierzy |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Minimalna szerokość kolumny w twipach (1/20 punktu). Odstęp (zwany również „Column Gap” lub „Gap Width”) jest dodawany do MinColumnWidth, aby określić całkowity odstęp kolumn macierzy (odległość pomiędzy tymi samymi krawędziami różnych kolumn). Domyślne: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Liczba wierszy w macierzy |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Wartość odstępu pionowego między wierszami macierzy; jeśli RowGapRule jest ustawione na 3 („Exactly”), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli RowGapRule jest ustawione na 4 („Multiple”), jednostka jest interpretowana jako pół linii. Domyślne: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Typ odstępu pionowego między wierszami macierzy; jednostki odstępu pionowego mogą być lines lub points (przechowywane jako twipy). Domyślne: SingleSpacingGap (0) |

## Metody

| Nazwa | Opis |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Usuwa określoną kolumnę |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Usuwa określony wiersz |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Pobiera poziome wyrównanie określonej kolumny |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Wstawia nową kolumnę po wskazanej. Początkowo wszystkie elementy w nowej kolumnie są null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Wstawia nową kolumnę przed wskazaną. Początkowo wszystkie elementy w nowej kolumnie są null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Wstawia nowy wiersz po wskazanym. Początkowo wszystkie elementy w nowym wierszu są null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Wstawia nowy wiersz przed wskazanym. Początkowo wszystkie elementy w nowym wierszu są null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Ustawia poziome wyrównanie określonej kolumny |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Ustawia poziome wyrównanie określonych kolumn |

### Przykłady

Przykład:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Zobacz także

* interfejs [IMathElement](../imathelement)
* przestrzeń nazw [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->