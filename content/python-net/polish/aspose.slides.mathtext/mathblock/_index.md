---
title: MathBlock class
second_title: Aspose.Slides dla Pythona w wersji .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathblock/
---
## MathBlock klasa

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line.
            All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

**Dziedziczenie:**[`MathBlock`](/slides/python-net/pl/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)

The MathBlock type exposes the following members:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/__init__/#) | Inicjalizuje nową instancję klasy MathBlock. |
| [`__init__(self, math_element)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Tworzy nowy blok matematyczny i umieszcza w nim określony element |
| [`__init__(self, math_elements)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`count`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/count/) | Zwraca liczbę elementów matematycznych podrzędnych faktycznie zawartych w kolekcji.<br/>            Tylko do odczytu **int**. |
| [`is_read_only`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/is_read_only/) | Zwraca false, ponieważ kolekcję elementów podrzędnych można modyfikować. |

Pobiera lub ustawia IMathElement pod określonym indeksem.

## Indeksator

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/__getitem__/) | Indeks zerowy elementu |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/join/#imathelement) | Łączy element matematyczny z tym blokiem matematycznym |
| [`join(self, math_text)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/join/#str) | Łączy tekst matematyczny z tym blokiem matematycznym |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/divide/#imathelement) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/divide/#str) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/enclose/#char-char) | Otacza elementy podrzędne tego bloku określonymi znakami, takimi jak nawiasy lub inne znaki jako ramkę |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Otacza elementy podrzędne tego bloku określonymi znakami, takimi jak nawiasy lub inne jako ramkę<br/>            i oddziela znakiem separatora |
| [`enclose(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/enclose/#) | Otacza element matematyczny w nawiasach |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/function/#imathelement) | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/function/#str) | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz określony dodatkowy argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz określony dodatkowy argument |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Tworzy indeks dolny |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/set_subscript/#str) | Tworzy indeks dolny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Tworzy indeks górny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/set_superscript/#str) | Tworzy indeks górny |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tworzy indeks dolny i górny po lewej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Tworzy indeks dolny i górny po lewej stronie |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/radical/#imathelement) | Określa pierwiastek matematyczny stopnia podanego z określonego argumentu. |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/radical/#str) | Określa pierwiastek matematyczny stopnia podanego z określonego argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Przyjmuje granicę górną |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Przyjmuje granicę górną |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Przyjmuje granicę dolną |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Przyjmuje granicę dolną |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tworzy operator N-arny |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Tworzy operator N-arny |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Przyjmuje całkę |
| [`integral(self, integral_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Przyjmuje całkę bez granic |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Przyjmuje całkę |
| [`group(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/group/#) | Umieszcza ten element w grupie używając dolnego nawiasu klamrowego |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Umieszcza ten element w grupie używając znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [`to_border_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/to_border_box/#) | Umieszcza ten element w ramce |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umieszcza ten element w ramce |
| [`to_math_array(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/to_math_array/#) | Umieszcza elementy podrzędne w pionowej tablicy |
| [`accent(self, accent_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/accent/#char) | Ustawia znak akcentu (znak nad tym elementem) |
| [`overbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/overbar/#) | Ustawia kreskę na górze tego elementu |
| [`underbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/underbar/#) | Ustawia kreskę na dole tego elementu |
| [`to_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/to_box/#) | Umieszcza ten element w niewidzialnej ramce (grupowanie logiczne) <br/>            która jest używana do grupowania składników równania lub innego przykładu tekstu matematycznego.<br/>            Obiekt w ramce może (na przykład) służyć jako emulator operatora z punktem wyrównania lub bez niego, <br/>            służyć jako punkt podziału linii lub być grupowany w taki sposób, aby nie dopuszczać do podziału linii wewnątrz. |
| [`get_children(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/get_children/#) | Pobiera elementy podrzędne |
| [`add(self, item)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/add/#imathelement) | Dodaje element matematyczny na koniec kolekcji. |
| [`clear(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/clear/#) | Usuwa wszystkie elementy z kolekcji. |
| [`contains(self, item)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/contains/#imathelement) | Określa, czy kolekcja zawiera określoną wartość. |
| [`copy_to(self, array, array_index)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Kopiuje do określonej tablicy. |
| [`remove(self, item)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/remove/#imathelement) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [`index_of(self, item)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Określa indeks określonego elementu matematycznego w kolekcji. |
| [`insert(self, index, item)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Wstawia MathElement do kolekcji pod określonym indeksem. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/remove_at/#int) | Usuwa element pod określonym indeksem w kolekcji. |
| [`join_block(self, other)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Łączy kolejny blok matematyczny z tym |
| [`delimit(self, separator_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/delimit/#char) | Oddziela elementy podrzędne znakiem separatora (bez nawiasów) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Zapisuje zawartość tego [`MathBlock`](/slides/python-net/pl/aspose.slides.mathtext/mathblock) jako MathML |

### Zobacz także
* klasa [`MathBlock`](/slides/python-net/pl/aspose.slides.mathtext/mathblock)
* klasa [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)