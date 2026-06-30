---
title: MathBar
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Określa funkcję kreski składającą się z argumentu bazowego oraz kreski górnej lub dolnej
type: docs
weight: 8550
url: /pl/aspose.slides.mathtext/mathbar/
---
## MathBar klasa

Określa funkcję kreski, składającą się z argumentu bazowego oraz kreski górnej lub dolnej

```csharp
public sealed class MathBar : MathElementBase, IMathBar
```

## Konstruktorzy

| Name | Description |
| --- | --- |
| [MathBar](mathbar#constructor)(IMathElement) | Inicjalizuje MathBar z nadkreśleniem (pozycja Górna) |
| [MathBar](mathbar#constructor_1)(IMathElement, MathTopBotPositions) | Inicjalizuje MathBar z określoną pozycją |

## Właściwości

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathbar/base) { get; } | Argument bazowy |
| [Position](../../aspose.slides.mathtext/mathbar/position) { get; set; } | Pozycja linii kreski. Domyślnie: Top |

## Metody

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ustawia znak akcentu (znak na górze tego elementu) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz podanego dodatkowego argumentu |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz podanego dodatkowego argumentu |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Umieszcza element matematyczny w nawiasach |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Umieszcza element matematyczny w określonych znakach, takich jak nawiasy lub inne znaki otaczające |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [GetChildren](../../aspose.slides.mathtext/mathbar/getchildren)() | Pobiera elementy potomne |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Przyjmuje całkę bez granic |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMMathElement, MathLimitLocations) | Przyjmuje całkę |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Przyjmuje całkę |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Łączy element matematyczny i tworzy blok matematyczny |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Tworzy operator N-arny |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Tworzy operator N-arny |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Ustawia kreskę na górze tego elementu |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Określa pierwiastek matematyczny danej stopnia z podanego argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Określa pierwiastek matematyczny danej stopnia z podanego argumentu. |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umieszcza ten element w niewidzialnym pudełku (logiczne grupowanie), które służy do grupowania komponentów równania lub innego fragmentu tekstu matematycznego. Obiekt w ramce może (na przykład) służyć jako emulator operatora z lub bez punktu wyrównania, jako punkt podziału linii lub być grupowany tak, aby nie pozwalał na podziały linii wewnątrz. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umieszcza w pionowej tablicy |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Ustawia kreskę na dole tego elementu |

### Przykłady

Example:

```csharp
[C#]
MathBar mathBar = new MathBar(new MathematicalText("x"));
```

### Zobacz także

* klasa [MathElementBase](../mathelementbase)
* interfejs [IMathBar](../imathbar)
* przestrzeń nazw [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->