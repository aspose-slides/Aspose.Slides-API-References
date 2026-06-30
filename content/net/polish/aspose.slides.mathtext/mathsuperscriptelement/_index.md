---
title: MathSuperscriptElement
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Określa obiekt indeksu górnego, który składa się z podstawy oraz zmniejszonego indeksu górnego umieszczonego powyżej i po prawej stronie
type: docs
weight: 9000
url: /pl/aspose.slides.mathtext/mathsuperscriptelement/
---
## MathSuperscriptElement klasa

Określa obiekt indeksu górnego, który składa się z podstawy i zmniejszonego indeksu górnego umieszczonego powyżej i po prawej stronie

```csharp
public sealed class MathSuperscriptElement : BaseScript, IMathSuperscriptElement
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [MathSuperscriptElement](mathsuperscriptelement)(IMathElement, IMathElement) | Inicjalizuje nową instancję klasy MathSuperscriptElement. |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Argument podstawy |
| [Superscript](../../aspose.slides.mathtext/mathsuperscriptelement/superscript) { get; } | Indeks górny |

## Metody

| Nazwa | Opis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ustawia znak akcentu (znak na górze tego elementu) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Wykonuje określoną funkcję używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Wykonuje określoną funkcję jednoparametrową, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Wykonuje określoną funkcję używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Wykonuje określoną funkcję używając tej instancji jako argumentu oraz podanego dodatkowego argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Wykonuje określoną funkcję używając tej instancji jako argumentu oraz podanego dodatkowego argumentu |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tworzy ułamek określonego typu z tym licznikiem i podanym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tworzy ułamek określonego typu z tym licznikiem i podanym mianownikiem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Otacza element matematyczny nawiasem |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub inne znaki ramkowe |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Wykonuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Wykonuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [GetChildren](../../aspose.slides.mathtext/mathsuperscriptelement/getchildren)() | Pobiera elementy potomne |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Tworzy całkę bez granic |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Tworzy całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Tworzy całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMMathElement, IMathElement, MathLimitLocations) | Tworzy całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Tworzy całkę |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Łączy element matematyczny i tworzy blok matematyczny |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tworzy operator N-arny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tworzy operator N-arny |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Ustawia kreskę na górze tego elementu |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Ustawia dolną granicę |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Ustawia dolną granicę |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tworzy indeks dolny |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tworzy indeks dolny |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMMathElement) | Tworzy indeks dolny i górny po lewej stronie |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tworzy indeks dolny i górny po lewej stronie |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMMathElement, IMMathElement) | Tworzy indeks dolny i górny po prawej stronie |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tworzy indeks dolny i górny po prawej stronie |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMMathElement) | Tworzy indeks górny |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tworzy indeks górny |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMMathElement) | Ustawia górną granicę |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Ustawia górną granicę |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umieszcza ten element w ramce |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umieszcza ten element w ramce |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umieszcza ten element w niewidzialnym pudełku (grupowaniu logicznym), które służy do grupowania komponentów równania lub innego fragmentu tekstu matematycznego. Obiekt w pudełku może (na przykład) pełnić rolę emulatora operatora z punktem wyrównania lub bez niego, służyć jako punkt łamania linii lub być grupowany w taki sposób, aby nie dopuszczać do łamania linii wewnątrz. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umieszcza w pionowej tablicy |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Ustawia kreskę na dole tego elementu |

### Przykłady

Przykład:

```csharp
[C#]
MathSuperscriptElement superscriptElement = new MathematicalText("N").SetSuperscript("i");
```

### Zobacz także

* klasa [BaseScript](../basescript)
* interfejs [IMathSuperscriptElement](../imathsuperscriptelement)
* przestrzeń nazw [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->