---
title: MathMatrix
second_title: Aspose.Sildes dla .NET odniesienie API
description: Określa obiekt Matrix składający się z elementów podrzędnych rozmieszczonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych ograniczników. Aby umieścić macierz w nawiasach, należy użyć obiektu ogranicznika IMathDelimiter. Argumenty o wartości null mogą być używane do tworzenia przerw w macierzach.
type: docs
weight: 8870
url: /pl/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix klasa

Określa obiekt Matrix, składający się z elementów podrzędnych rozmieszczonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych ograniczników. Aby umieścić macierz w nawiasach, należy użyć obiektu ogranicznika (IMathDelimiter). Argumenty o wartości null można używać do tworzenia przerw w macierzach.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Inicjalizuje nową instancję klasy MathMatrix. |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Określa pionowe wyrównanie względem otaczającego tekstu. Dostępne wartości to top, bottom i center. Domyślnie: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Liczba kolumn w macierzy |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 (\"Exactly\"), jednostka jest interpretowana jako twip (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 (\"Multiple\"), jednostka jest interpretowana jako liczba 0,5-kroków em. W innych przypadkach ignorowane. Domyślnie: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Typ poziomego odstępu między kolumnami macierzy; jednostki poziomego odstępu mogą być em lub punkty (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Ukrywa miejsca wypełniające dla pustych elementów macierzy. Domyślnie: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Element macierzy |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Minimalna szerokość kolumny w twipach (1/20 punktu). Odstęp (oznaczany także jako „Column Gap” lub „Gap Width”) jest dodawany do MinColumnWidth w celu określenia całkowitego odstępu kolumn macierzy (odległość między takimi samymi krawędziami różnych kolumn). Domyślnie: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Liczba wierszy w macierzy |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 (\"Exactly\"), jednostka jest interpretowana jako twip (1/20 punktu). Jeśli RowGapRule ma wartość 4 (\"Multiple\"), jednostka jest interpretowana jako półlinii. Domyślnie: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Typ pionowego odstępu między wierszami macierzy; jednostki pionowego odstępu mogą być liniami lub punktami (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0) |

## Metody

| Nazwa | Opis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ustawia znak akcentu (znak nad tym elementem) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu i dodatkowego określonego argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu i dodatkowego określonego argumentu |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Usuwa określoną kolumnę |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Usuwa określony wiersz |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tworzy ułamek z tym liczebnikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tworzy ułamek z tym liczebnikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tworzy ułamek określonego typu z tym liczebnikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tworzy ułamek określonego typu z tym liczebnikiem i określonym mianownikiem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Otacza element matematyczny nawiasami |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub inne znaki ramkowe |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Pobiera elementy podrzędne |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Pobiera poziome wyrównanie określonej kolumny |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umieszcza ten element w grupie przy użyciu dolnego ukośnika klamrowego |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny ukośnik klamrowy lub inny |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Wstawia nową kolumnę po określonej. Początkowo wszystkie elementy w nowej kolumnie są null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Wstawia nową kolumnę przed określoną. Początkowo wszystkie elementy w nowej kolumnie są null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Wstawia nowy wiersz po określonym. Początkowo wszystkie elementy w nowym wierszu są null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Wstawia nowy wiersz przed określonym. Początkowo wszystkie elementy w nowym wierszu są null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Przyjmuje całkę bez granic |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Przyjmuje całkę |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Łączy element matematyczny i tworzy blok matematyczny |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tworzy operator n-arny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tworzy operator n-arny |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Ustawia kreskę na górze tego elementu |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Określa pierwiastek matematyczny danego stopnia z podanego argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Określa pierwiastek matematyczny danego stopnia z podanego argumentu. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Ustawia poziome wyrównanie określonej kolumny |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Ustawia poziome wyrównanie określonych kolumn |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Przyjmuje dolny limit |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Przyjmuje dolny limit |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tworzy indeks dolny |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tworzy indeks dolny |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po lewej stronie |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tworzy indeks dolny i górny po lewej stronie |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po prawej stronie |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tworzy indeks dolny i górny po prawej stronie |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Tworzy indeks górny |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tworzy indeks górny |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Przyjmuje górny limit |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Przyjmuje górny limit |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umieszcza ten element w ramce |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umieszcza ten element w ramce |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umieszcza ten element w nie-wizualnym pudełku (logiczne grupowanie) używanym do grupowania składników równania lub innego fragmentu tekstu matematycznego. Obiekt w ramce może (na przykład) służyć jako emulacja operatora z lub bez punktu wyrównania, jako punkt podziału linii lub być grupowany w taki sposób, aby nie dopuszczać do podziałów linii wewnątrz. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umieszcza w pionowej tablicy |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Ustawia kreskę na dole tego elementu |

### Przykłady

Example:

```csharp
[C#]
IMMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Zobacz także

* klasa [MathElementBase](../mathelementbase)
* interfejs [IMathMatrix](../imathmatrix)
* przestrzeń nazw [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->