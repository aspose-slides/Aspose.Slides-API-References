---
title: MathBox
second_title: Aspose.Sildes dla .NET Referencja API
description: Określa logiczne pakowanie elementu matematycznego. Na przykład obiekt w pudełku może służyć jako emulator operatora z punktem wyrównania lub bez niego, jako punkt przerwania wiersza lub być grupowany w taki sposób, aby nie zezwalać na przerwy wierszy wewnątrz. Na przykład operator powinien być umieszczony w pudełku, aby zapobiec przerwom wierszy.
type: docs
weight: 8610
url: /pl/aspose.slides.mathtext/mathbox/
---
## MathBox class

Określa logiczne pakowanie elementu matematycznego. Na przykład, obiekt w pudełku może służyć jako emulator operatora z punktem wyrównania lub bez niego, jako punkt przerwania linii lub być grupowany w taki sposób, aby nie zezwalać na przerwy wierszy wewnątrz. Na przykład operator "==" powinien być umieszczony w pudełku, aby zapobiec przerwom wierszy.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Constructors

| Nazwa | Opis |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Inicjalizuje MathBox przy użyciu podanego elementu jako argumentu |

## Properties

| Nazwa | Opis |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Gdy wartość true, ten emulator operatora pełni rolę punktu wyrównania; oznacza to, że wyznaczone punkty wyrównania w innych równaniach mogą być z nim wyrównane. Domyślnie: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Argument bazowy |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Różniczkowy. Gdy wartość true, pudełko działa jako różniczka (np. 𝑑𝑥 w całce) i otrzymuje odpowiednie odstępy poziome dla różniczki matematycznej. Domyślnie: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Przerwa explicite określa, czy na początku obiektu Box występuje przerwa wiersza, tak aby wiersz łamał się na początku tego obiektu. Określa liczbę operatora w poprzednim wierszu tekstu matematycznego, który ma być użyty jako punkt wyrównania dla bieżącego wiersza tekstu matematycznego. Możliwe wartości: 1..255. Domyślnie: 0 (brak przerwy explicite) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Brak przerwy. Ta właściwość określa właściwość „niełamiąca się” obiektu pudełka. Gdy wartość true, w obrębie pudełka nie mogą wystąpić przerwy wiersza. Może to być ważne dla emulatorów operatorów składających się z więcej niż jednego operatora binarnego. Gdy element nie jest określony, przerwy mogą wystąpić wewnątrz pudełka. Domyślnie: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Emulator operatora. Gdy wartość true, pudełko i jego zawartość zachowują się jak pojedynczy operator i dziedziczą właściwości operatora. Oznacza to na przykład, że znak może służyć jako punkt przerwania wiersza i może być wyrównany do innych operatorów. Emulatory operatorów są często używane, gdy jeden lub więcej glifów łączy się, tworząc operator, np. '=='. Domyślna wartość: false |

## Methods

| Nazwa | Opis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ustawia znak akcentu (znak nad tym elementem) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz podanego dodatkowego argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz podanego dodatkowego argumentu |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tworzy ułamek z tym licznikiem i podanym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tworzy ułamek z tym licznikiem i podanym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tworzy ułamek określonego typu z tym licznikiem i podanym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tworzy ułamek określonego typu z tym licznikiem i podanym mianownikiem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Otacza element matematyczny nawiasami |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub inne znaki ramkowe |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Pobiera elementy potomne |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Przyjmuje całkę bez granic |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Przyjmuje całkę |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Łączy element matematyczny i tworzy blok matematyczny |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tworzy operator N-arny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tworzy operator N-arny |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Umieszcza kreskę na górze tego elementu |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Przyjmuje niższą granicę |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Przyjmuje niższą granicę |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tworzy indeks dolny |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tworzy indeks dolny |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po lewej stronie |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tworzy indeks dolny i górny po lewej stronie |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po prawej stronie |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tworzy indeks dolny i górny po prawej stronie |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Tworzy indeks górny |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tworzy indeks górny |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Przyjmuje wyższą granicę |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Przyjmuje wyższą granicę |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umieszcza ten element w ramce |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umieszcza ten element w ramce |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umieszcza ten element w niewidzialnym pudełku (logiczne grupowanie), które służy do grupowania komponentów równania lub innego fragmentu tekstu matematycznego. Obiekt w pudełku może (na przykład) służyć jako emulator operatora z punktem wyrównania lub bez niego, jako punkt przerwania linii lub być grupowany w taki sposób, aby nie zezwalać na przerwy wierszy wewnątrz. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umieszcza w pionowej macierzy |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Umieszcza kreskę na dole tego elementu |

### Przykłady

Przykład:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Zobacz także

* klasa [MathElementBase](../mathelementbase)
* interfejs [IMathBox](../imathbox)
* przestrzeń nazw [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->