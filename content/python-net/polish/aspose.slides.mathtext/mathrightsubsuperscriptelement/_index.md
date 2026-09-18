---
title: MathRightSubSuperscriptElement class
second_title: Aspose.Slides dla Pythona poprzez .NET - dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement klasa

Określa obiekt Sub-Superscript, który składa się z podstawy oraz indeksu dolnego i górnego umieszczonych po prawej stronie podstawy.

**Inheritance:**[`MathRightSubSuperscriptElement`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement) → [`BaseScript`](/slides/python-net/pl/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)

Typ MathRightSubSuperscriptElement udostępnia następujące członki:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, base_arg, sub_script, super_script)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/__init__/#imathelement-imathelement-imathelement) | Inicjalizuje nową instancję klasy MathRightSubSuperscriptElement. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`base`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/base/) | Argument podstawy |
| [`subscript`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript/) | Argument indeksu dolnego |
| [`superscript`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript/) | Argument indeksu górnego |
| [`align_scripts`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/align_scripts/) | Określa wyrównanie indeksu dolnego/górnego. <br/> Gdy wartość true, indeks dolny i górny są wyrównane poziomo względem siebie.<br/> Gdy wartość false, są dopasowywane (kerning) do kształtu podstawy.<br/> Domyślna wartość to false. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#imathelement) | Łączy element matematyczny i tworzy blok matematyczny |
| [`join(self, math_text)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#str) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement) | Tworzy ułamek z tym liczebnikiem i podanym mianownikiem |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str) | Tworzy ułamek z tym liczebnikiem i podanym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement-mathfractiontypes) | Tworzy ułamek określonego typu z tym liczebnikiem i podanym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str-mathfractiontypes) | Tworzy ułamek określonego typu z tym liczebnikiem i podanym mianownikiem |
| [`enclose(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#) | Otacza element matematyczny nawiasami |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#char-char) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub inne znaki jako ramka |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#imathelement) | Tworzy funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#str) | Tworzy funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#imathelement) | Używa określonej funkcji, wykorzystując tę instancję jako argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#str) | Używa określonej funkcji, wykorzystując tę instancję jako argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Używa określonej funkcji, wykorzystując tę instancję jako argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Używa określonej funkcji, wykorzystując tę instancję jako argument oraz podany dodatkowy argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Używa określonej funkcji, wykorzystując tę instancję jako argument oraz podany dodatkowy argument |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#imathelement) | Tworzy indeks dolny |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#str) | Tworzy indeks dolny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#imathelement) | Tworzy indeks górny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#str) | Tworzy indeks górny |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tworzy indeks dolny i górny po lewej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | Tworzy indeks dolny i górny po lewej stronie |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#imathelement) | Określa pierwiastek matematyczny danej stopnia z podanego argumentu. |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#str) | Określa pierwiastek matematyczny danej stopnia z podanego argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#imathelement) | Przyjmuje górny limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#str) | Przyjmuje górny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#imathelement) | Przyjmuje dolny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#str) | Przyjmuje dolny limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tworzy operator N-arny |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | Tworzy operator N-arny |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Przyjmuje całkę |
| [`integral(self, integral_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes) | Przyjmuje całkę bez limitów |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str) | Przyjmuje całkę |
| [`group(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#) | Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [`to_border_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#) | Umieszcza ten element w ramce |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umieszcza ten element w ramce |
| [`to_math_array(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_math_array/#) | Umieszcza w pionowej tablicy |
| [`accent(self, accent_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/accent/#char) | Ustawia znak akcentu (znak na górze tego elementu) |
| [`overbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/overbar/#) | Ustawia kreskę na górze tego elementu |
| [`underbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/underbar/#) | Ustawia kreskę na dole tego elementu |
| [`to_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_box/#) | Umieszcza ten element w niewidzialnym pudełku (grupowanie logiczne) <br/> które służy do grupowania elementów równania lub innego fragmentu tekstu matematycznego.<br/> Obiekt w pudełku może (na przykład) pełnić funkcję emulacji operatora z punktem wyrównania lub bez niego, <br/> służyć jako punkt podziału linii lub być grupowany w taki sposób, aby nie zezwalać na podziały linii wewnątrz. |
| [`get_children(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_children/#) | Pobiera elementy podrzędne |

### Zobacz także
* klasa [`BaseScript`](/slides/python-net/pl/aspose.slides.mathtext/basescript)
* klasa [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)
* klasa [`MathRightSubSuperscriptElement`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)