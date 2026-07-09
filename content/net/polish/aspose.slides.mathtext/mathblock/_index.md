---
title: MathBlock
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Określa instancję tekstu matematycznego znajdującą się w elemencie MathParagraph i rozpoczynającą się w osobnym wierszu. Wszystkie obszary matematyczne, w tym równania, wyrażenia, tablice równań lub wyrażeń oraz formuły, są reprezentowane przez blok matematyczny.
type: docs
weight: 8590
url: /pl/aspose.slides.mathtext/mathblock/
---
## MathBlock klasa

Specyfikuje instancję tekstu matematycznego, który znajduje się w MathParagraph i rozpoczyna się w osobnym wierszu. Wszystkie obszary matematyczne, w tym równania, wyrażenia, tablice równań lub wyrażeń oraz formuły są reprezentowane przez blok matematyczny.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktory

| Name | Description |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Inicjalizuje nową instancję klasy MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Tworzy nowy blok matematyczny i umieszcza w nim określone elementy. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Tworzy nowy blok matematyczny i umieszcza w nim określony element. |

## Właściwości

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Zwraca liczbę elementów matematycznych podrzędnych faktycznie zawartych w kolekcji. Tylko do odczytu Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Zwraca false, ponieważ kolekcja elementów podrzędnych może być modyfikowana. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Zwraca lub ustawia IMathElement pod podanym indeksem. |

## Metody

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ustawia znak akcentu (znak nad tym elementem). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Dodaje element matematyczny na koniec kolekcji. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu i określonego dodatkowego argumentu. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu i określonego dodatkowego argumentu. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Usuwa wszystkie elementy z kolekcji. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Określa, czy kolekcja zawiera określoną wartość. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Kopiuje do określonej tablicy. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Oddziela elementy podrzędne znakiem separatora (bez nawiasów). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tworzy ułamek z tym liczownikiem i określonym mianownikiem. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tworzy ułamek z tym liczownikiem i określonym mianownikiem. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tworzy ułamek określonego typu z tym liczownikiem i określonym mianownikiem. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tworzy ułamek określonego typu z tym liczownikiem i określonym mianownikiem. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Otacza element matematyczny nawiasami. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Otacza elementy podrzędne tego bloku określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramkę. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Otacza elementy podrzędne tego bloku określonymi znakami, takimi jak nawiasy lub innymi jako ramkę i oddziela znakiem separatora. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Pobiera elementy podrzędne. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umieszcza ten element w grupie przy użyciu dolnego klamrowego nawiasu. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umieszcza ten element w grupie przy użyciu znaku grupowania, takiego jak dolny klamrowy nawias lub inny. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Określa indeks określonego elementu matematycznego w kolekcji. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Wstawia MathElement do kolekcji pod podanym indeksem. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Przyjmuje całkę bez granic. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Przyjmuje całkę. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Przyjmuje całkę. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Przyjmuje całkę. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Przyjmuje całkę. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Łączy element matematyczny z tym blokiem matematycznym. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Łączy tekst matematyczny z tym blokiem matematycznym. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Łączy inny blok matematyczny z tym. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tworzy operator N-arny. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tworzy operator N-arny. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Ustawia kreskę na górze tego elementu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Usuwa element pod podanym indeksem w kolekcji. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Przyjmuje dolną granicę. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Przyjmuje dolną granicę. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tworzy indeks dolny. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tworzy indeks dolny. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po lewej stronie. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tworzy indeks dolny i górny po lewej stronie. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po prawej stronie. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tworzy indeks dolny i górny po prawej stronie. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Tworzy indeks górny. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tworzy indeks górny. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Przyjmuje górną granicę. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Przyjmuje górną granicę. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umieszcza ten element w ramce. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umieszcza ten element w ramce. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umieszcza ten element w niewidzialnym pudełku (grupowaniu logicznym), które służy do grupowania składników równania lub innego fragmentu tekstu matematycznego. Obiekt w pudełku może (na przykład) działać jako emulator operatora z punktem wyrównania lub bez niego, służyć jako punkt podziału linii lub być grupowany w taki sposób, aby nie zezwalać na podziały linii wewnątrz. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Umieszcza elementy podrzędne w pionowej tablicy. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Ustawia kreskę na dole tego elementu. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Zapisuje zawartość tego [`MathBlock`](../mathblock) jako MathML. |

### Przykłady

Przykład:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Zobacz także

* klasa [MathElementBase](../mathelementbase)
* interfejs [IMathBlock](../imathblock)
* przestrzeń nazw [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->