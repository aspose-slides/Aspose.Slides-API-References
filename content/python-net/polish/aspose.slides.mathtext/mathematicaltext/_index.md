---
title: MathematicalText class
second_title: Aspose.Slides dla Pythona via .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText klasa

Tekst matematyczny

**Dziedziczenie:**[`MathematicalText`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext) → [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)

Typ MathematicalText udostępnia następujące elementy:

## Konstruktorzy

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/__init__/#) | Domyślny konstruktor (tworzy wartość String.Empty) |
| [`__init__(self, math_symbol)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/__init__/#char) | Tworzy MathText z pojedynczym symbolem |
| [`__init__(self, math_text)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/__init__/#str) | Tworzy MathematicalText z tekstu |
| [`__init__(self, math_text, portion_format)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/__init__/#str-iportionformat) | Tworzy MathematicalText z tekstu i ustawień formatowania |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`value`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/value/) | Wartość tekstowa |
| [`format`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/format/) | Właściwości formatowania tekstu |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/join/#imathelement) | Łączy element matematyczny i tworzy blok matematyczny |
| [`join(self, math_text)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/join/#str) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/divide/#imathelement) | Tworzy ułamek z tym liczebnikiem i podanym mianownikiem |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/divide/#str) | Tworzy ułamek z tym liczebnikiem i podanym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/divide/#imathelement-mathfractiontypes) | Tworzy ułamek określonego typu z tym liczebnikiem i podanym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/divide/#str-mathfractiontypes) | Tworzy ułamek określonego typu z tym liczebnikiem i podanym mianownikiem |
| [`enclose(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/enclose/#) | Otacza element matematyczny nawiasami |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/enclose/#char-char) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/function/#imathelement) | Przyjmuje funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/function/#str) | Przyjmuje funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#imathelement) | Przyjmuje określoną funkcję używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#str) | Przyjmuje określoną funkcję używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsofoneargument) | Przyjmuje określoną funkcję używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Przyjmuje określoną funkcję używając tej instancji jako argumentu oraz dodatkowego argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Przyjmuje określoną funkcję używając tej instancji jako argumentu oraz dodatkowego argumentu |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/set_subscript/#imathelement) | Tworzy indeks dolny |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/set_subscript/#str) | Tworzy indeks dolny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/set_superscript/#imathelement) | Tworzy indeks górny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/set_superscript/#str) | Tworzy indeks górny |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#str-str) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tworzy indeks dolny i górny po lewej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#str-str) | Tworzy indeks dolny i górny po lewej stronie |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/radical/#imathelement) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/radical/#str) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#imathelement) | Przyjmuje górny limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#str) | Przyjmuje górny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#imathelement) | Przyjmuje dolny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#str) | Przyjmuje dolny limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tworzy operator N-arny |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-str-str) | Tworzy operator N-arny |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement) | Przyjmuje całkę |
| [`integral(self, integral_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes) | Przyjmuje całkę bez limitów |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str) | Przyjmuje całkę |
| [`group(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/group/#) | Umieszcza ten element w grupie używając dolnego nawiasu klamrowego |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/group/#char-mathtopbotpositions-mathtopbotpositions) | Umieszcza ten element w grupie używając znaku grupowania, takiego jak dolny nawias klamrowy lub inny |
| [`to_border_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/to_border_box/#) | Umieszcza ten element w ramce |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umieszcza ten element w ramce |
| [`to_math_array(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/to_math_array/#) | Umieszcza w pionowej tablicy |
| [`accent(self, accent_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/accent/#char) | Ustawia znak akcentu (znak nad tym elementem) |
| [`overbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/overbar/#) | Ustawia kreskę nad tym elementem |
| [`underbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/underbar/#) | Ustawia kreskę pod tym elementem |
| [`to_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/to_box/#) | Umieszcza ten element w niewidzialnej ramce (logiczne grupowanie) <br/>            które służy do grupowania składników równania lub innego wystąpienia tekstu matematycznego.<br/>            Obiekt w ramce może (na przykład) pełnić rolę emulatora operatora z punktem wyrównania lub bez niego, <br/>            służyć jako punkt przerwania linii lub być grupowany tak, aby nie pozwalać na łamanie linii wewnątrz. |
| [`get_children(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/get_children/#) |  |

### Zobacz także
* klasa [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)
* klasa [`MathematicalText`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)