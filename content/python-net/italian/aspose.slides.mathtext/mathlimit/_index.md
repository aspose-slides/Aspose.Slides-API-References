---
title: MathLimit class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathlimit/
---
## MathLimit classe

Specifica l'oggetto Limit, costituito da testo sulla linea di base e testo di dimensioni ridotte immediatamente sopra o sotto di esso.

**Eredità:**[`MathLimit`](/slides/python-net/it/aspose.slides.mathtext/mathlimit) → [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)

Il tipo MathLimit espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, base_arg, limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement-bool) | Inizializza una nuova istanza della classe MathLimit. |
| [`__init__(self, base_arg, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement) | Inizializza una nuova istanza della classe MathLimit con limite inferiore |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`base`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/base/) | Argomento base |
| [`limit`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/limit/) | Argomento limite |
| [`upper_limit`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/upper_limit/) | Specifica il limite superiore o inferiore |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/join/#imathelement) | Unisce un elemento matematico e forma un blocco matematico |
| [`join(self, math_text)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/join/#str) | Unisce un testo matematico e forma un blocco matematico |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/divide/#imathelement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/divide/#str) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/divide/#imathelement-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/divide/#str-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`enclose(self)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/enclose/#) | Raccoglie un elemento matematico tra parentesi |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/enclose/#char-char) | Raccoglie un elemento matematico in caratteri specificati, come parentesi o altri caratteri come cornice |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/function/#imathelement) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/function/#str) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/as_argument_of_function/#imathelement) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/as_argument_of_function/#str) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsofoneargument) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prende la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prende la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/set_subscript/#imathelement) | Crea un pedice |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/set_subscript/#str) | Crea un pedice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/set_superscript/#imathelement) | Crea un apice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/set_superscript/#str) | Crea un apice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#str-str) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea pedice e apice a sinistra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#str-str) | Crea pedice e apice a sinistra |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/radical/#imathelement) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/radical/#str) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/set_upper_limit/#imathelement) | Prende il limite superiore |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/set_upper_limit/#str) | Prende il limite superiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/set_lower_limit/#imathelement) | Prende il limite inferiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/set_lower_limit/#str) | Prende il limite inferiore |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operatore N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-str-str) | Crea un operatore N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement) | Prende l'integrale |
| [`integral(self, integral_type)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes) | Prende l'integrale senza limiti |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str) | Prende l'integrale |
| [`group(self)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/group/#) | Colloca questo elemento in un gruppo usando una parentesi graffa inferiore |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/group/#char-mathtopbotpositions-mathtopbotpositions) | Colloca questo elemento in un gruppo usando un carattere di raggruppamento, come una parentesi graffa inferiore o altro |
| [`to_border_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/to_border_box/#) | Colloca questo elemento in un riquadro bordato |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Colloca questo elemento in un riquadro bordato |
| [`to_math_array(self)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/to_math_array/#) | Inserisce in un array verticale |
| [`accent(self, accent_character)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/accent/#char) | Imposta un segno di accento (un carattere sopra questo elemento) |
| [`overbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/overbar/#) | Imposta una barra sopra questo elemento |
| [`underbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/underbar/#) | Imposta una barra sotto questo elemento |
| [`to_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/to_box/#) | Colloca questo elemento in una scatola non visiva (raggruppamento logico) <br/>            usata per raggruppare componenti di un'equazione o altra istanza di testo matematico.<br/>            Un oggetto in scatola può (ad esempio) fungere da emulatore di operatore con o senza punto di allineamento, <br/>            fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga al suo interno. |
| [`get_children(self)`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/get_children/#) | Ottiene gli elementi figli |


### Vedi anche
* classe [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)
* classe [`MathLimit`](/slides/python-net/it/aspose.slides.mathtext/mathlimit)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)