---
title: MathSuperscriptElement class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.mathtext/mathsuperscriptelement/
---
## MathSuperscriptElement classe

Specifies the superscript object, which consists of a base 
            and a reduced-size superscript placed above and to the right

**Inheritance:**[`MathSuperscriptElement`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement) → [`BaseScript`](/slides/python-net/it/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)

The MathSuperscriptElement type exposes the following members:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, base_arg, super_script)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/__init__/#imathelement-imathelement) | Inizializza una nuova istanza della classe MathSuperscriptElement. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`base`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/base/) | Base argument |
| [`superscript`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/superscript/) | Superscript |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/join/#imathelement) | Unisce un elemento matematico e forma un blocco matematico |
| [`join(self, math_text)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/join/#str) | Unisce un testo matematico e forma un blocco matematico |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/divide/#str) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/divide/#str-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`enclose(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/enclose/#) | Racchiude un elemento matematico tra parentesi |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/enclose/#char-char) | Racchiude un elemento matematico in caratteri specificati come parentesi o altri caratteri come cornice |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/function/#imathelement) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/function/#str) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#imathelement) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#str) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prende la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prende la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#imathelement) | Crea pedice |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#str) | Crea pedice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#imathelement) | Crea apice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#str) | Crea apice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea pedice e apice a sinistra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | Crea pedice e apice a sinistra |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/radical/#imathelement) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/radical/#str) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#imathelement) | Prende limite superiore |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#str) | Prende limite superiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#imathelement) | Prende limite inferiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#str) | Prende limite inferiore |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operatore N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | Crea un operatore N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Prende l'integrale |
| [`integral(self, integral_type)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes) | Prende l'integrale senza limiti |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str) | Prende l'integrale |
| [`group(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/group/#) | Colloca questo elemento in un gruppo usando una parentesi graffa inferiore |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Colloca questo elemento in un gruppo usando un carattere di raggruppamento come parentesi graffa inferiore o altro |
| [`to_border_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#) | Colloca questo elemento in una casella bordata |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Colloca questo elemento in una casella bordata |
| [`to_math_array(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/to_math_array/#) | Inserisce in un array verticale |
| [`accent(self, accent_character)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/accent/#char) | Imposta un segno diacritico (un carattere sopra questo elemento) |
| [`overbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/overbar/#) | Imposta una barra sulla parte superiore di questo elemento |
| [`underbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/underbar/#) | Imposta una barra sulla parte inferiore di questo elemento |
| [`to_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/to_box/#) | Colloca questo elemento in una scatola non visiva (raggruppamento logico) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [`get_children(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/get_children/#) | Ottieni gli elementi figli |


### Vedi anche
* classe [`BaseScript`](/slides/python-net/it/aspose.slides.mathtext/basescript)
* classe [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)
* classe [`MathSuperscriptElement`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)