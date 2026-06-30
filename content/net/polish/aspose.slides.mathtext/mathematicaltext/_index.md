---
title: MathematicalText
second_title: Aspose.Sildes dla .NET – Odniesienie API
description: Tekst matematyczny
type: docs
weight: 9040
url: /pl/aspose.slides.mathtext/mathematicaltext/
---
## Klasa MathematicalText

Tekst matematyczny

```csharp
public sealed class MathematicalText : MathElementBase, IMathematicalText
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [MathematicalText](mathematicaltext#constructor)() | Domyślny konstruktor (tworzy wartość String.Empty) |
| [MathematicalText](mathematicaltext#constructor_1)(char) | Tworzy MathText z pojedynczym symbolem |
| [MathematicalText](mathematicaltext#constructor_2)(string) | Tworzy MathematicalText z tekstu |
| [MathematicalText](mathematicaltext#constructor_3)(string, IPortionFormat) | Tworzy MathematicalText z tekstu i ustawień formatu |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Format](../../aspose.slides.mathtext/mathematicaltext/format) { get; } | Właściwości formatowania tekstu |
| [Value](../../aspose.slides.mathtext/mathematicaltext/value) { get; set; } | Wartość tekstu |

## Metody

| Nazwa | Opis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ustawia znak akcentu (znak nad tym elementem) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Przyjmuje określoną funkcję, używając tego wystąpienia jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Przyjmuje określoną funkcję, używając tego wystąpienia jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Przyjmuje określoną funkcję, używając tego wystąpienia jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Przyjmuje określoną funkcję, używając tego wystąpienia jako argumentu oraz określony dodatkowy argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Przyjmuje określoną funkcję, używając tego wystąpienia jako argumentu oraz określony dodatkowy argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Otacza element matematyczny nawiasami |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub inne znaki |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Przyjmuje funkcję argumentu, używając tego wystąpienia jako nazwy funkcji |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Przyjmuje funkcję argumentu, używając tego wystąpienia jako nazwy funkcji |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umieszcza ten element w grupie przy użyciu dolnego klamry |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolna klamra lub inny |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Przyjmuje całkę bez granic |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Przyjmuje całkę |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Łączy element matematyczny i tworzy blok matematyczny |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tworzy operator N-arny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tworzy operator N-arny |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Ustawia kreskę na górze tego elementu |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Określa pierwiastek matematyczny określonego stopnia z podanego argumentu |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Określa pierwiastek matematyczny określonego stopnia z podanego argumentu |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Przyjmuje dolną granicę |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Przyjmuje dolną granicę |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Tworzy indeks dolny |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Tworzy indeks dolny |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po lewej stronie |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Tworzy indeks dolny i górny po lewej stronie |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Tworzy indeks dolny i górny po prawej stronie |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Tworzy indeks dolny i górny po prawej stronie |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Tworzy indeks górny |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Tworzy indeks górny |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Przyjmuje górną granicę |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Przyjmuje górną granicę |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umieszcza ten element w ramce |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umieszcza ten element w ramce |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umieszcza ten element w niewidzialnym pudełku (grupowanie logiczne), które służy do grupowania składników równania lub innego fragmentu tekstu matematycznego. Obiekt w pudełku może (na przykład) pełnić rolę emulatora operatora z punktem wyrównania lub bez, służyć jako punkt podziału linii lub być grupowany w taki sposób, aby nie zezwalał na podziały linii wewnątrz. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Układa w pionowej macierzy |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Ustawia kreskę na dole tego elementu |

### Przykłady

Przykład:

```csharp
[C#]
MathematicalText mathText = new MathematicalText("x+y");
```

### Zobacz także

* klasa [MathElementBase](../mathelementbase)
* interfejs [IMathematicalText](../imathematicaltext)
* przestrzeń nazw [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->