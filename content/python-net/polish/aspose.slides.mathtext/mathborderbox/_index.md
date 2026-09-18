---
title: MathBorderBox class
second_title: Aspose.Slides dla Pythona poprzez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox klasa

Rysuje prostokątną lub inną ramkę wokół elementu IMathElement.

**Dziedziczenie:**[`MathBorderBox`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)

Typ MathBorderBox udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | Tworzy element MathBorderBox z prostokątną ramką |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | Tworzy element MathBorderBox |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`base`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/base/) | Argument bazowy |
| [`hide_top`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/hide_top/) | Ukryj górną krawędź (wartość domyślna to false) – określa, czy górna krawędź ramki jest ukryta czy widoczna. |
| [`hide_bottom`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/hide_bottom/) | Ukryj dolną krawędź (wartość domyślna to false) – określa, czy dolna krawędź ramki jest ukryta czy widoczna. |
| [`hide_left`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/hide_left/) | Ukryj lewą krawędź (wartość domyślna to false) – określa, czy lewa krawędź ramki jest ukryta czy widoczna. |
| [`hide_right`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/hide_right/) | Ukryj prawą krawędź (wartość domyślna to false) – określa, czy prawa krawędź ramki jest ukryta czy widoczna. |
| [`strikethrough_horizontal`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | Przekreślenie poziome (wartość domyślna to false) – określa, czy pozioma linia przekreślenia jest ukryta czy widoczna. |
| [`strikethrough_vertical`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | Przekreślenie pionowe (wartość domyślna to false) – określa, czy pionowa linia przekreślenia jest ukryta czy widoczna. |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | Przekreślenie od lewego dolnego do prawego górnego (wartość domyślna to false).<br/>            Określa, czy przekreślona linia ukośna od lewego dolnego rogu do prawego górnego rogu ramki jest ukryta czy widoczna. |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | Przekreślenie od lewego górnego do prawego dolnego (wartość domyślna to false).<br/>            Określa, czy przekreślona linia ukośna od lewego górnego rogu do prawego dolnego rogu ramki jest ukryta czy widoczna. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/join/#imathelement) | Łączy element matematyczny i tworzy blok matematyczny |
| [`join(self, math_text)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/join/#str) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | Tworzy ułamek z tym liczebnikiem i określonym mianownikiem |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/divide/#str) | Tworzy ułamek z tym liczebnikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | Tworzy ułamek określonego typu z tym liczebnikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | Tworzy ułamek określonego typu z tym liczebnikiem i określonym mianownikiem |
| [`enclose(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/enclose/#) | Otacza element matematyczny nawiasami |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/function/#imathelement) | Tworzy funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/function/#str) | Tworzy funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | Używa określonej funkcji, wykorzystując tę instancję jako argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | Używa określonej funkcji, wykorzystując tę instancję jako argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | Używa określonej funkcji, wykorzystując tę instancję jako argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Używa określonej funkcji, wykorzystując tę instancję jako argument oraz dodatkowy określony argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Używa określonej funkcji, wykorzystując tę instancję jako argument oraz dodatkowy określony argument |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | Tworzy indeks dolny |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | Tworzy indeks dolny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | Tworzy indeks górny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | Tworzy indeks górny |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tworzy indeks dolny i górny po lewej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | Tworzy indeks dolny i górny po lewej stronie |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/radical/#str) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | Pobiera górną granicę |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | Pobiera górną granicę |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | Pobiera dolną granicę |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | Pobiera dolną granicę |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tworzy operator N-arny |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | Tworzy operator N-arny |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Pobiera całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | Pobiera całkę |
| [`integral(self, integral_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | Pobiera całkę bez granic |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Pobiera całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | Pobiera całkę |
| [`group(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/group/#) | Umieszcza ten element w grupie, używając dolnego nawiasu klamrowego |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Umieszcza ten element w grupie, używając znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [`to_border_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/to_border_box/#) | Umieszcza ten element w ramce |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umieszcza ten element w ramce |
| [`to_math_array(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/to_math_array/#) | Umieszcza w pionowej tablicy |
| [`accent(self, accent_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/accent/#char) | Ustawia znak akcentu (znak nad tym elementem) |
| [`overbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/overbar/#) | Ustawia pasek nad tym elementem |
| [`underbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/underbar/#) | Ustawia pasek pod tym elementem |
| [`to_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/to_box/#) | Umieszcza ten element w niewidzialnej ramce (grupowanie logiczne) <br/>            której używa się do grupowania elementów równania lub innego fragmentu tekstu matematycznego.<br/>            Obiekt w ramce może (na przykład) służyć jako emulator operatora z punktem wyrównania lub bez niego, <br/>            służyć jako punkt podziału wiersza lub być grupowany w taki sposób, aby nie dopuszczać do podziału wierszy wewnątrz. |
| [`get_children(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/get_children/#) | Pobiera elementy potomne |


### Zobacz także
* klasa [`MathBorderBox`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox)
* klasa [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)