---
title: MathDelimiter class
second_title: Aspose.Slides dla Pythona poprzez .NET referencja API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter klasa

Określa obiekt delimitera, składający się z znaków otwierających i zamykających (takich jak nawiasy okrągłe, klamry, nawiasy kwadratowe i kreski pionowe) oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem.  
Przykłady: (𝑥2); [𝑥2|𝑦2]

**Dziedziczenie:**[`MathDelimiter`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)

Typ MathDelimiter udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Inicjalizuje MathDelimiter z określonym elementem jako jedynym argumentem bazowym |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`arguments`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/arguments/) | Jeden lub więcej elementów matematycznych oddzielonych znakami delimitera |
| [`beginning_character`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character określa początkowy, czyli otwierający, znak delimitera. <br/>            Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy okrągłe, kwadratowe i klamry.<br/>            Domyślnie: '('. |
| [`separator_character`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie delimitera. <br/>            Domyślnie: '\|'. |
| [`ending_character`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character określa końcowy, czyli zamykający, znak delimitera. <br/>            Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy okrągłe, kwadratowe i klamry.<br/>            Domyślnie: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Gdy true, delimitery rosną pionowo, aby dopasować się do wysokości swojego operandu.<br/>            Domyślna wartość to true |
| [`delimiter_shape`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Określa kształt delimiterów w obiekcie delimitera. <br/>            Gdy jest MathDelimiterShape.Centered, delimitery są wyśrodkowane wokół osi matematycznej tekstu <br/>            i nadal dopasowywane, aby obejmowały całą wysokość ich zawartości.<br/>            Gdy jest MathDelimiterShape.Match, ich wysokość i kształt są zmieniane, aby dokładnie dopasować się do zawartości. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Łączy element matematyczny i tworzy blok matematyczny |
| [`join(self, math_text)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/join/#str) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/divide/#str) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka |
| [`enclose(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/enclose/#) | Otacza element matematyczny w nawiasie |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Tworzy funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/function/#str) | Tworzy funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Używa określonej funkcji, traktując tę instancję jako argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Używa określonej funkcji, traktując tę instancję jako argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Używa określonej funkcji, traktując tę instancję jako argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Używa określonej funkcji, traktując tę instancję jako argument oraz określony dodatkowy argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Używa określonej funkcji, traktując tę instancję jako argument oraz określony dodatkowy argument |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Tworzy indeks dolny |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Tworzy indeks dolny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Tworzy indeks górny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Tworzy indeks górny |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tworzy indeks dolny i górny po lewej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Tworzy indeks dolny i górny po lewej stronie |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/radical/#str) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Ustawia granicę górną |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Ustawia granicę górną |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Ustawia granicę dolną |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Ustawia granicę dolną |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tworzy operator N-arny |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Tworzy operator N-arny |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Oblicza całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Oblicza całkę |
| [`integral(self, integral_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Oblicza całkę bez granic |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Oblicza całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Oblicza całkę |
| [`group(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/group/#) | Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [`to_border_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Umieszcza ten element w ramce |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umieszcza ten element w ramce |
| [`to_math_array(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Umieszcza w pionowej macierzy |
| [`accent(self, accent_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/accent/#char) | Ustawia znak akcentu (znak na górze tego elementu) |
| [`overbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/overbar/#) | Ustawia kreskę nad tym elementem |
| [`underbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/underbar/#) | Ustawia kreskę pod tym elementem |
| [`to_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/to_box/#) | Umieszcza ten element w niewizualnym pudełku (grupowanie logiczne) <br/>            które służy do grupowania składników równania lub innego fragmentu tekstu matematycznego.<br/>            Obiekt w pudełku może (na przykład) pełnić rolę emulatora operatora z punktem wyrównania lub bez niego, <br/>            pełnić funkcję punktu podziału linii lub być grupowany w sposób uniemożliwiający podziały linii wewnątrz. |
| [`delimit(self, separator_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Oddziela argumenty przy użyciu określonego znaku delimitera |
| [`get_children(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/get_children/#) | Pobiera elementy potomne |

### Zobacz także
* klasa [`MathDelimiter`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter)
* klasa [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)