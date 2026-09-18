---
title: MathGroupingCharacter class
second_title: Aspose.Slides dla Pythona poprzez .NET Odwołanie API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter klasa

Określa znak grupowania nad lub pod wyrażeniem, zazwyczaj aby podkreślić zależność między elementami

**Dziedziczenie:**[`MathGroupingCharacter`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)

typ MathGroupingCharacter udostępnia następujące członki:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | Inicjalizuje nową instancję klasy MathGroupingCharacter <br/>            z domyślnym znakiem grupowania U+23DF (BOTTOM CURLY BRACKET) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | Inicjalizuje nową instancję klasy MathGroupingCharacter. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`base`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/base/) | Argument bazowy |
| [`character`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/character/) | Znak grupowania<br/>            Wartość domyślna: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/position/) | Pozycja znaku grupowania.<br/>            Domyślnie: Bottom |
| [`vertical_justification`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | Pionowe wyrównanie znaku grupowania.<br/>            Określa wyrównanie obiektu względem linii bazowej.<br/>            Na przykład, gdy znak grupowania znajduje się nad obiektem, <br/>            VerticalJustification ustawione na Top oznacza, że górna krawędź obiektu leży na linii bazowej;<br/>            gdy VerticalJustification jest ustawione na Bottom, dolna krawędź obiektu leży na linii bazowej<br/>            Domyślnie: Bottom dla Position=Top oraz Top dla Position=Bottom |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | Łączy element matematyczny i tworzy blok matematyczny |
| [`join(self, math_text)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | Tworzy ułamek z tym liczebnikiem i określonym mianownikiem |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | Tworzy ułamek z tym liczebnikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | Tworzy ułamek określonego typu z tym liczebnikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | Tworzy ułamek określonego typu z tym liczebnikiem i określonym mianownikiem |
| [`enclose(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | Otacza element matematyczny nawiasami |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | Tworzy funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | Tworzy funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | Używa określonej funkcji, używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | Używa określonej funkcji, używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | Używa określonej funkcji, używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Używa określonej funkcji, używając tej instancji jako argumentu i określonego dodatkowego argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Używa określonej funkcji, używając tej instancji jako argumentu i określonego dodatkowego argumentu |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | Tworzy indeks dolny |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | Tworzy indeks dolny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | Tworzy indeks górny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | Tworzy indeks górny |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tworzy indeks dolny i górny po lewej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | Tworzy indeks dolny i górny po lewej stronie |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | Określa pierwiastek matematyczny danej stopnia z podanego argumentu. |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | Określa pierwiastek matematyczny danej stopnia z podanego argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | Ustawia górny limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | Ustawia górny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | Ustawia dolny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | Ustawia dolny limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tworzy operator N-arny |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | Tworzy operator N-arny |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tworzy całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | Tworzy całkę |
| [`integral(self, integral_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | Tworzy całkę bez granic |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tworzy całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | Tworzy całkę |
| [`group(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/group/#) | Umieszcza ten element w grupie używając dolnego nawiasu klamrowego |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | Umieszcza ten element w grupie używając znaku grupowania, takiego jak dolny nawias klamrowy lub inny |
| [`to_border_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | Umieszcza ten element w ramce |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umieszcza ten element w ramce |
| [`to_math_array(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | Umieszcza w pionowej tablicy |
| [`accent(self, accent_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | Ustawia znak akcentu (znak nad tym elementem) |
| [`overbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | Ustawia kreskę na górze tego elementu |
| [`underbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | Ustawia kreskę na dole tego elementu |
| [`to_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | Umieszcza ten element w niewidzialnym pudełku (grupowanie logiczne) <br/>            które służy do grupowania składników równania lub innego fragmentu tekstu matematycznego.<br/>            Obiekt w pudełku może (na przykład) pełnić rolę emulatora operatora z punktem wyrównania lub bez niego, <br/>            służyć jako punkt podziału linii lub być grupowany w taki sposób, aby nie zezwalać na podziały linii wewnątrz. |
| [`get_children(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | Pobiera elementy podrzędne |

### Zobacz także
* klasa [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)
* klasa [`MathGroupingCharacter`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)