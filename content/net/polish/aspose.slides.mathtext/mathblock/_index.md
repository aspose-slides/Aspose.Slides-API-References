---
title: MathBlock
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Określa wystąpienie tekstu matematycznego, które znajduje się w MathParagraph i zaczyna się w osobnej linii. Wszystkie strefy matematyczne, w tym równania, wyrażenia, tablice równań lub wyrażeń oraz formuły, są reprezentowane przez blok matematyczny.
type: docs
weight: 8570
url: /pl/aspose.slides.mathtext/mathblock/
---
## MathBlock klasa

Określa wystąpienie tekstu matematycznego, które znajduje się w MathParagraph i rozpoczyna się w osobnej linii. Wszystkie strefy matematyczne, w tym równania, wyrażenia, tablice równań lub wyrażeń oraz formuły, są reprezentowane przez blok matematyczny.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Inicjalizuje nową instancję klasy MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Tworzy nowy blok matematyczny i umieszcza w nim określone elementy. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Tworzy nowy blok matematyczny i umieszcza w nim określony element. |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Zwraca liczbę elementów matematycznych potomnych faktycznie zawartych w kolekcji. Tylko do odczytu Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Zwraca false, ponieważ kolekcję elementów potomnych można modyfikować. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Pobiera lub ustawia IMathElement pod określonym indeksem. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ustawia znak akcentu (znak nad tym elementem). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Dodaje element matematyczny na koniec kolekcji. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Wykonuje określoną funkcję, używając tej instancji jako argumentu. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Wykonuje określoną funkcję, używając tej instancji jako argumentu. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Wykonuje określoną funkcję, używając tej instancji jako argumentu. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Wykonuje określoną funkcję, używając tej instancji jako argumentu i podanego dodatkowego argumentu. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Wykonuje określoną funkcję, używając tej instancji jako argumentu i podanego dodatkowego argumentu. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Usuwa wszystkie elementy z kolekcji. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Określa, czy kolekcja zawiera określoną wartość. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Kopiuje do określonej tablicy. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Oddziela elementy potomne znakiem separatora (bez nawiasów). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tworzy ułamek z tym licznikiem i określonym mianownikiem. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tworzy ułamek z tym licznikiem i określonym mianownikiem. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Otacza element matematyczny nawiasami. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Otacza elementy potomne tego bloku określonymi znakami, takimi jak nawiasy lub inne znaki jako ramki. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Otacza elementy potomne tego bloku określonymi znakami, takimi jak nawiasy lub inne, jako ramki i oddziela je znakiem separatora. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Wykonuje funkcję argumentu, używając tej instancji jako nazwy funkcji. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Wykonuje funkcję argumentu, używając tej instancji jako nazwy funkcji. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Pobiera elementy potomne. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Określa indeks określonego elementu matematycznego w kolekcji. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Wstawia MathElement do kolekcji pod określonym indeksem. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Oblicza całkę bez granic. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Oblicza całkę. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Oblicza całkę. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Oblicza całkę. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Oblicza całkę. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Łączy element matematyczny z tym blokiem matematycznym. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Łączy tekst matematyczny z tym blokiem matematycznym. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Łączy inny blok matematyczny z tym. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tworzy operator N-argumentowy. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tworzy operator N-argumentowy. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Ustawia kreskę na górze tego elementu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Określa pierwiastek matematyczny danej stopni z określonego argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Określa pierwiastek matematyczny danej stopni z określonego argumentu. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Usuwa element pod określonym indeksem kolekcji. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Pobiera dolną granicę. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Pobiera dolną granicę. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tworzy indeks dolny. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tworzy indeks dolny. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po lewej stronie. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tworzy indeks dolny i górny po lewej stronie. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po prawej stronie. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tworzy indeks dolny i górny po prawej stronie. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Tworzy indeks górny. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tworzy indeks górny. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Pobiera górną granicę. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Pobiera górną granicę. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umieszcza ten element w ramce. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umieszcza ten element w ramce. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umieszcza ten element w niewidzialnym pudełku (logiczne grupowanie), które służy do grupowania składników równania lub innego fragmentu tekstu matematycznego. Obiekt w ramce może (na przykład) pełnić rolę emulacji operatora z punktem wyrównania lub bez niego, służyć jako punkt łamania linii lub być grupowany tak, aby nie dopuszczać do łamania linii w jego wnętrzu. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Układa elementy potomne w pionowej macierzy. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Ustawia kreskę na dole tego elementu. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Zapisuje zawartość tego [`MathBlock`](../mathblock) jako MathML. |

### Przykłady

Przykład:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Zobacz również

* klasa [MathElementBase](../mathelementbase)
* interfejs [IMathBlock](../imathblock)
* przestrzeń nazw [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->