---
title: MathDelimiter
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Określa obiekt delimitera składający się z znaków otwierających i zamykających, takich jak nawiasy, klamry, nawiasy kwadratowe i pionowe kreski, oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem. Przykłady 2 2x7C2
type: docs
weight: 8630
url: /pl/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter klasa

Określa obiekt delimitera, składający się z znaków otwierających i zamykających (takich jak nawiasy okrągłe, klamrowe, kwadratowe oraz pionowe kreski) oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem. Przykłady: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Inicjalizuje MathDelimiter określonym elementem jako pojedynczym argumentem bazowym |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Jeden lub więcej elementów matematycznych oddzielonych znakami delimitera |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Delimiter Beginning Character określa początkowy, czyli otwierający, znak delimitera. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślnie: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Określa kształt delimiterów w obiekcie delimitera. Gdy jest MathDelimiterShape.Centered, delimitery są wyśrodkowane wokół osi matematycznej tekstu i nadal mogą zostać dopasowane do całkowitej wysokości ich zawartości. Gdy jest MathDelimiterShape.Match, ich wysokość i kształt są zmieniane tak, aby dokładnie pasowały do ich zawartości. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimiter Ending Character określa końcowy, czyli zamykający, znak delimitera. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślnie: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy true, delimitery rosną pionowo, aby dopasować się do wysokości ich argumentu. Domyślna wartość to true |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie delimitera. Domyślnie: '&#x7C;'. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ustawia znak akcentu (znak na górze tego elementu) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz określonego dodatkowego argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz określonego dodatkowego argumentu |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Oddziela argumenty przy użyciu określonego znaku delimitera |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Otacza element matematyczny nawiasami |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub inne znaki, jako ramka |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Pobiera elementy potomne |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Przyjmuje całkę bez limitów |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Przyjmuje całkę |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Łączy element matematyczny i tworzy blok matematyczny |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tworzy operator N-arny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tworzy operator N-arny |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Ustawia kreskę na górze tego elementu |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Pobiera dolny limit |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Pobiera dolny limit |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tworzy indeks dolny |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tworzy indeks dolny |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po lewej stronie |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tworzy indeks dolny i górny po lewej stronie |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po prawej stronie |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tworzy indeks dolny i górny po prawej stronie |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Tworzy indeks górny |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tworzy indeks górny |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Pobiera górny limit |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Pobiera górny limit |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umieszcza ten element w ramce-pudełku |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umieszcza ten element w ramce-pudełku |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umieszcza ten element w nie-wizualnym pudełku (grupowaniu logicznym), które służy do grupowania komponentów równania lub innego fragmentu tekstu matematycznego. Obiekt w pudełku może (na przykład) pełnić rolę emulatora operatora z punktem wyrównania lub bez niego, służyć jako punkt podziału linii lub być grupowany w taki sposób, aby nie zezwalał na podziały linii wewnątrz. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umieszcza w pionowej tablicy |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Ustawia kreskę na dole tego elementu |

### Przykłady

Example:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### Zobacz także

* klasa [MathElementBase](../mathelementbase)
* interfejs [IMathDelimiter](../imathdelimiter)
* przestrzeń nazw [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* zestawienie [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->