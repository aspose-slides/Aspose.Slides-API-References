---
title: MathMatrix
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Określa obiekt Matrix składający się z elementów podrzędnych rozmieszczonych w jednym lub wielu wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych ograniczników. Aby umieścić macierz w nawiasach, należy użyć obiektu delimiter IMathDelimiter. Argumenty null mogą być użyte do tworzenia przerw w macierzach.
type: docs
weight: 8830
url: /pl/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix klasa

Określa obiekt Matrix, składający się z elementów podrzędnych rozmieszczonych w jednym lub wielu wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych ograniczników. Aby umieścić macierz w nawiasach, należy użyć obiektu delimiter (IMathDelimiter). Argumenty null mogą być użyte do tworzenia przerw w macierzach.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Konstruktorzy

| Name | Description |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Inicjalizuje nową instancję klasy MathMatrix. |

## Właściwości

| Name | Description |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Określa pionowe wyrównanie względem otaczającego tekstu. Dostępne wartości to top, bottom i center. Domyślna: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Liczba kolumn w macierzy |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Wartość odstępu poziomego między kolumnami macierzy; jeśli ColumnGapRule jest ustawione na 3 (\"Exactly\"), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli ColumnGapRule jest ustawione na 4 (\"Multiple\"), jednostka jest interpretowana jako liczba pół-emów. W innych przypadkach ignorowane. Domyślnie: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Typ odstępu poziomego między kolumnami macierzy; jednostki odstępu poziomego mogą być em lub punktami (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Ukrywa symbole zastępcze dla pustych elementów macierzy. Domyślnie: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Element macierzy |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Minimalna szerokość kolumny w twypach (1/20 punktu). Odstęp pomiędzy kolumnami (określany także jako „Column Gap” lub „Gap Width”) jest dodawany do MinColumnWidth, aby określić całkowity odstęp między kolumnami macierzy (odległość między takimi samymi krawędziami różnych kolumn). Domyślnie: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Liczba wierszy w macierzy |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Wartość odstępu pionowego między wierszami macierzy; jeśli RowGapRule jest ustawione na 3 (\"Exactly\"), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli RowGapRule jest ustawione na 4 (\"Multiple\"), jednostka jest interpretowana jako połowa linii. Domyślnie: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Typ odstępu pionowego między wierszami macierzy; jednostki odstępu pionowego mogą być liniami lub punktami (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0) |

## Metody

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ustawia znak akcentu (znak nad tym elementem) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz dodatkowego określonego argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz dodatkowego określonego argumentu |
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
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Pobiera wyrównanie poziome określonej kolumny |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Wstawia nową kolumnę po określonej. Początkowo wszystkie elementy w nowej kolumnie są null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Wstawia nową kolumnę przed określoną. Początkowo wszystkie elementy w nowej kolumnie są null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Wstawia nowy wiersz po określonym. Początkowo wszystkie elementy w nowym wierszu są null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Wstawia nowy wiersz przed określonym. Początkowo wszystkie elementy w nowym wierszu są null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Przyjmuje całkę bez limitów |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Przyjmuje całkę |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Łączy element matematyczny i tworzy blok matematyczny |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tworzy operator n-arny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tworzy operator n-arny |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Ustawia kreskę na górze tego elementu |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Określa pierwiastek matematyczny danej stopnia z podanego argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Określa pierwiastek matematyczny danej stopnia z podanego argumentu. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Ustawia wyrównanie poziome określonej kolumny |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Ustawia wyrównanie poziome określonych kolumn |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Przyjmuje limit dolny |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Przyjmuje limit dolny |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tworzy indeks dolny |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tworzy indeks dolny |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po lewej stronie |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tworzy indeks dolny i górny po lewej stronie |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po prawej stronie |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tworzy indeks dolny i górny po prawej stronie |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Tworzy indeks górny |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tworzy indeks górny |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Przyjmuje limit górny |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Przyjmuje limit górny |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umieszcza ten element w ramce |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umieszcza ten element w ramce |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umieszcza ten element w nie-wizualnym pudełku (logiczne grupowanie), które służy do grupowania elementów równania lub innego fragmentu tekstu matematycznego. Obiekt w pudełku może (na przykład) pełnić rolę emulatora operatora z punktem wyrównania lub bez niego, służyć jako punkt podziału linii lub być grupowany tak, aby nie zezwalać na podziały linii wewnątrz. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umieszcza w pionowej tablicy |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Ustawia kreskę na dole tego elementu |

### Przykłady

Przykład:

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