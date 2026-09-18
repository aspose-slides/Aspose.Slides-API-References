---
title: MathNaryOperator class
second_title: Aspose.Slides dla Pythona poprzez .NET – referencja API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator klasa

Określa n-ary obiekt matematyczny, taki jak Sumowanie i Całka.  
Składa się z operatora, bazy (lub operandu) oraz opcjonalnych górnych i dolnych limitów.  
Przykłady operatorów n-arnych to: Sumowanie, Suma, Przecięcie, Całka

**Dziedziczenie:**[`MathNaryOperator`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)

Typ MathNaryOperator udostępnia następujące elementy:

## Konstruktorzy

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | Inicjalizuje nową instancję klasy MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | Inicjalizuje nową instancję klasy MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | Inicjalizuje nową instancję klasy MathNaryOperator. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`base`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/base/) | Argument bazowy |
| [`subscript`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/subscript/) | Określa argument indeksu dolnego, który na przykład w przypadku całki ustawia dolny limit |
| [`superscript`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/superscript/) | Określa argument indeksu górnego, który na przykład w przypadku całki ustawia górny limit |
| [`operator`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/operator/) | Znak operatora n-ary<br/>            Na przykład: '∑', '∫' |
| [`limit_location`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/limit_location/) | Lokalizacja limitów (indeks dolny i górny) |
| [`grow_to_match_operand_height`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | Znak operatora rośnie pionowo, aby dopasować się do wysokości operandów |
| [`hide_subscript`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | Ukryj indeks dolny |
| [`hide_superscript`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | Ukryj indeks górny |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | Łączy element matematyczny i tworzy blok matematyczny |
| [`join(self, math_text)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/join/#str) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/divide/#str) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [`enclose(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/enclose/#) | Otacza element matematyczny nawiasami |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | Tworzy funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/function/#str) | Tworzy funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz określonego dodatkowego argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz określonego dodatkowego argumentu |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | Tworzy indeks dolny |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | Tworzy indeks dolny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | Tworzy indeks górny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | Tworzy indeks górny |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tworzy indeks dolny i górny po lewej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | Tworzy indeks dolny i górny po lewej stronie |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | Określa pierwiastek matematyczny danej stopnia z określonego argumentu. |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/radical/#str) | Określa pierwiastek matematyczny danej stopnia z określonego argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | Przyjmuje górny limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | Przyjmuje górny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | Przyjmuje dolny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | Przyjmuje dolny limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tworzy operator N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | Tworzy operator N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | Przyjmuje całkę |
| [`integral(self, integral_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | Przyjmuje całkę bez limitów |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | Przyjmuje całkę |
| [`group(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/group/#) | Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [`to_border_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | Umieszcza ten element w ramce |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umieszcza ten element w ramce |
| [`to_math_array(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | Umieszcza w pionowej tablicy |
| [`accent(self, accent_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/accent/#char) | Ustawia znak akcentu (znak nad tym elementem) |
| [`overbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/overbar/#) | Ustawia kreskę na górze tego elementu |
| [`underbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/underbar/#) | Ustawia kreskę na dole tego elementu |
| [`to_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/to_box/#) | Umieszcza ten element w niewidzialnym pudełku (grupowanie logiczne) <br/>            które służy do grupowania komponentów równania lub innego fragmentu tekstu matematycznego.<br/>            Obiekt w pudełku może (na przykład) służyć jako emulator operatora z punktem wyrównania lub bez niego, <br/>            służyć jako punkt łamania linii lub być grupowany w sposób uniemożliwiający łamanie linii wewnątrz. |
| [`get_children(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/get_children/#) | Pobiera elementy podrzędne |

### Zobacz także
* klasa [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)
* klasa [`MathNaryOperator`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)