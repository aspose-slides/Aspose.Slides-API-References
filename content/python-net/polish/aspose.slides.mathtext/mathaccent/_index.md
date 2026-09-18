---
title: MathAccent class
second_title: Aspose.Slides dla Pythona przez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathaccent/
---
## MathAccent klasa

Określa funkcję akcentu, składającą się z podstawy i łączącego znaku diakrytycznego  
Przykład: 𝑎́

**Dziedziczenie:**[`MathAccent`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)

Typ MathAccent udostępnia następujące członki:

## Konstruktorzy

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | Tworzy akcent matematyczny stosowany do określonego elementu matematycznego z domyślną wartością znaku akcentu |
| [`__init__(self, element, accent_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | Tworzy akcent matematyczny stosowany do określonego elementu matematycznego |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`base`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/base/) | Argument, do którego zastosowano akcent |
| [`character`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/character/) | Znak akcentu<br/>            Wartość powinna mieścić się w zakresie (U+0300–U+036F) lub (U+20D0–U+20EF)<br/>            Wartość domyślna: Łączący akcent daszka (U+0302) |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/join/#imathelement) | Łączy element matematyczny i tworzy blok matematyczny |
| [`join(self, math_text)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/join/#str) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/divide/#imathelement) | Tworzy ułamek o tym liczniku i określonym mianowniku |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/divide/#str) | Tworzy ułamek o tym liczniku i określonym mianowniku |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | Tworzy ułamek określonego typu o tym liczniku i określonym mianowniku |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | Tworzy ułamek określonego typu o tym liczniku i określonym mianowniku |
| [`enclose(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/enclose/#) | Umieszcza element matematyczny w nawiasach |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/enclose/#char-char) | Umieszcza element matematyczny w określonych znakach, takich jak nawiasy lub inne znaki ramkowe |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/function/#imathelement) | Tworzy funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/function/#str) | Tworzy funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | Używa określonej funkcji, korzystając z tej instancji jako argumentu |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | Używa określonej funkcji, korzystając z tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | Używa określonej funkcji, korzystając z tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Używa określonej funkcji, korzystając z tej instancji jako argumentu i dodatkowego określonego argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Używa określonej funkcji, korzystając z tej instancji jako argumentu i dodatkowego określonego argumentu |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | Tworzy indeks dolny |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/set_subscript/#str) | Tworzy indeks dolny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | Tworzy indeks górny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/set_superscript/#str) | Tworzy indeks górny |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tworzy indeks dolny i górny po lewej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | Tworzy indeks dolny i górny po lewej stronie |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/radical/#imathelement) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/radical/#str) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | Przyjmuje górny limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | Przyjmuje górny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | Przyjmuje dolny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | Przyjmuje dolny limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tworzy operator N-arny |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | Tworzy operator N-arny |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | Przyjmuje całkę |
| [`integral(self, integral_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | Przyjmuje całkę bez limitów |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | Przyjmuje całkę |
| [`group(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/group/#) | Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [`to_border_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/to_border_box/#) | Umieszcza ten element w ramce obramowania |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umieszcza ten element w ramce obramowania |
| [`to_math_array(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/to_math_array/#) | Umieszcza w pionowej macierzy |
| [`accent(self, accent_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/accent/#char) | Ustawia znak akcentu (znak nad tym elementem) |
| [`overbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/overbar/#) | Ustawia pasek na górze tego elementu |
| [`underbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/underbar/#) | Ustawia pasek na dole tego elementu |
| [`to_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/to_box/#) | Umieszcza ten element w niewizualnym polu (grupowanie logiczne) <br/>            które służy do grupowania składników równania lub innego fragmentu tekstu matematycznego.<br/>            Obiekt w polu może (na przykład) działać jako emulator operatora z punktem wyrównania lub bez niego, <br/>            służyć jako punkt podziału wiersza lub być grupowany w taki sposób, aby nie zezwalać na podziały wierszy wewnątrz. |
| [`get_children(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/get_children/#) | Pobiera elementy potomne |


### Zobacz także
* klasa [`MathAccent`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent)
* klasa [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)