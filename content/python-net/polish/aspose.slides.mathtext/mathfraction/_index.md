---
title: MathFraction class
second_title: Aspose.Slides dla Pythona przy użyciu .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathfraction/
---
## MathFraction klasa

Określa obiekt ułamka, składający się z licznika i mianownika oddzielonych kreską ułamkową.  
Kreska ułamkowa może być pozioma lub skośna, w zależności od właściwości ułamka.  
Obiekt ułamka jest również używany do reprezentacji funkcji stosu, która umieszcza jeden element nad drugim, bez kreski ułamkowej.

**Dziedziczenie:**[`MathFraction`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)

Typ MathFraction udostępnia następujące elementy:

## Konstruktorzy

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | Inicjalizuje MathFraction z podanym licznikiem, mianownikiem i typem |
| [`__init__(self, numerator, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | Inicjalizuje MathFraction typu 'Bar' z podanym licznikiem i mianownikiem |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`fraction_type`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/fraction_type/) | Typ ułamka<br/>            Domyślnie: Bar |
| [`numerator`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/numerator/) | Licznik |
| [`denominator`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/denominator/) | Mianownik |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/join/#imathelement) | Łączy element matematyczny i tworzy blok matematyczny |
| [`join(self, math_text)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/join/#str) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/divide/#imathelement) | Tworzy ułamek z tym licznikiem i podanym mianownikiem |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/divide/#str) | Tworzy ułamek z tym licznikiem i podanym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | Tworzy ułamek określonego typu z tym licznikiem i podanym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | Tworzy ułamek określonego typu z tym licznikiem i podanym mianownikiem |
| [`enclose(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/enclose/#) | Obejmuje element matematyczny nawiasem |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/enclose/#char-char) | Obejmuje element matematyczny określonymi znakami, takimi jak nawias lub inne znaki jako ramka |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/function/#imathelement) | Pobiera funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/function/#str) | Pobiera funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | Pobiera określoną funkcję używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | Pobiera określoną funkcję używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | Pobiera określoną funkcję używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Pobiera określoną funkcję używając tej instancji jako argumentu i dodatkowego argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Pobiera określoną funkcję używając tej instancji jako argumentu i dodatkowego argumentu |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | Tworzy indeks dolny |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/set_subscript/#str) | Tworzy indeks dolny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | Tworzy indeks górny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/set_superscript/#str) | Tworzy indeks górny |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tworzy indeks dolny i górny po lewej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | Tworzy indeks dolny i górny po lewej stronie |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/radical/#imathelement) | Określa pierwiastek matematyczny o danym stopniu z podanego argumentu. |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/radical/#str) | Określa pierwiastek matematyczny o danym stopniu z podanego argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | Pobiera górną granicę |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | Pobiera górną granicę |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | Pobiera dolną granicę |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | Pobiera dolną granicę |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tworzy operator N-arny |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | Tworzy operator N-arny |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Pobiera całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | Pobiera całkę |
| [`integral(self, integral_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | Pobiera całkę bez granic |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | Pobiera całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | Pobiera całkę |
| [`group(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/group/#) | Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [`to_border_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/to_border_box/#) | Umieszcza ten element w ramce |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umieszcza ten element w ramce |
| [`to_math_array(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/to_math_array/#) | Umieszcza w pionowej macierzy |
| [`accent(self, accent_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/accent/#char) | Ustawia znak akcentu (znak nad tym elementem) |
| [`overbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/overbar/#) | Ustawia kreskę na górze tego elementu |
| [`underbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/underbar/#) | Ustawia kreskę na dole tego elementu |
| [`to_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/to_box/#) | Umieszcza ten element w niewizualnym pudełku (grupowanie logiczne) <br/>            które jest używane do grupowania komponentów równania lub innego wystąpienia tekstu matematycznego.<br/>            Obiekt w ramce może (na przykład) służyć jako emulator operatora z lub bez punktu wyrównania, <br/>            służyć jako punkt przerwania linii lub być grupowany w taki sposób, aby nie zezwalać na przerwy wierszy wewnątrz. |
| [`get_children(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/get_children/#) | Pobiera elementy potomne |

### Zobacz także
* klasa [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)
* klasa [`MathFraction`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)