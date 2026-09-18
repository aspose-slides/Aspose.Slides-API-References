---
title: MathLimit class
second_title: Aspose.Slides dla Pythona przez .NET - Referencja API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathlimit/
---
## MathLimit klasa

Określa obiekt Limit, składający się z tekstu na linii podstawowej oraz tekstu o zmniejszonym rozmiarze umieszczonego bezpośrednio powyżej lub poniżej.

**Dziedziczenie:**[`MathLimit`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit) → [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)

Typ MathLimit udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, base_arg, limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement-bool) | Inicjalizuje nową instancję klasy MathLimit. |
| [`__init__(self, base_arg, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement) | Inicjalizuje nową instancję klasy MathLimit z dolnym limitem |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`base`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/base/) | Argument podstawowy |
| [`limit`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/limit/) | Argument limitu |
| [`upper_limit`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/upper_limit/) | Określa górny lub dolny limit |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/join/#imathelement) | Łączy element matematyczny i tworzy blok matematyczny |
| [`join(self, math_text)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/join/#str) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/divide/#imathelement) | Tworzy ułamek z tym liczebnikiem i określonym mianownikiem |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/divide/#str) | Tworzy ułamek z tym liczebnikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/divide/#imathelement-mathfractiontypes) | Tworzy ułamek określonego typu z tym liczebnikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/divide/#str-mathfractiontypes) | Tworzy ułamek określonego typu z tym liczebnikiem i określonym mianownikiem |
| [`enclose(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/enclose/#) | Otacza element matematyczny nawiasem |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/enclose/#char-char) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/function/#imathelement) | Przyjmuje funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/function/#str) | Przyjmuje funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/as_argument_of_function/#imathelement) | Przyjmuje określoną funkcję używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/as_argument_of_function/#str) | Przyjmuje określoną funkcję używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsofoneargument) | Przyjmuje określoną funkcję używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Przyjmuje określoną funkcję używając tej instancji jako argumentu oraz określony dodatkowy argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Przyjmuje określoną funkcję używając tej instancji jako argumentu oraz określony dodatkowy argument |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/set_subscript/#imathelement) | Tworzy indeks dolny |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/set_subscript/#str) | Tworzy indeks dolny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/set_superscript/#imathelement) | Tworzy indeks górny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/set_superscript/#str) | Tworzy indeks górny |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#str-str) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tworzy indeks dolny i górny po lewej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#str-str) | Tworzy indeks dolny i górny po lewej stronie |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/radical/#imathelement) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/radical/#str) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/set_upper_limit/#imathelement) | Przyjmuje górny limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/set_upper_limit/#str) | Przyjmuje górny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/set_lower_limit/#imathelement) | Przyjmuje dolny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/set_lower_limit/#str) | Przyjmuje dolny limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tworzy operator N-arny |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-str-str) | Tworzy operator N-arny |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement) | Przyjmuje całkę |
| [`integral(self, integral_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes) | Przyjmuje całkę bez limitów |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str) | Przyjmuje całkę |
| [`group(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/group/#) | Umieszcza ten element w grupie przy użyciu dolnego klamrowego nawiasu |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/group/#char-mathtopbotpositions-mathtopbotpositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny klamrowy nawias lub inny |
| [`to_border_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/to_border_box/#) | Umieszcza ten element w ramce |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umieszcza ten element w ramce |
| [`to_math_array(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/to_math_array/#) | Umieszcza w pionowej macierzy |
| [`accent(self, accent_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/accent/#char) | Ustawia znak akcentu (znak nad tym elementem) |
| [`overbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/overbar/#) | Ustawia kreskę nad tym elementem |
| [`underbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/underbar/#) | Ustawia kreskę pod tym elementem |
| [`to_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/to_box/#) | Umieszcza ten element w niewizualnym pudełku (grupowanie logiczne) <br/>            które jest używane do grupowania składników równania lub innego fragmentu tekstu matematycznego.<br/>            Obiekt w pudełku może (na przykład) służyć jako emulator operatora z punktem wyrównania lub bez niego, <br/>            służyć jako punkt przerwania linii lub być grupowany w sposób uniemożliwiający przerwy wierszy wewnątrz. |
| [`get_children(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/get_children/#) | Pobierz elementy potomne |


### Zobacz również
* klasa [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)
* klasa [`MathLimit`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)