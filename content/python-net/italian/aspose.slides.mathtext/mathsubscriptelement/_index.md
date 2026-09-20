---
title: MathSubscriptElement class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathsubscriptelement/
---
## MathSubscriptElement classe

Specifica l'elemento indice, che consiste in una base e un indice di dimensioni ridotte posizionato sotto e a destra.

**Eredità:**[`MathSubscriptElement`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement) → [`BaseScript`](/slides/python-net/it/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)

Il tipo MathSubscriptElement espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, base_arg, sub_script)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/__init__/#imathelement-imathelement) | Inizializza una nuova istanza della classe MathSubscriptElement. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`base`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/base/) | Argomento base |
| [`subscript`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/subscript/) | Indice |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/join/#imathelement) | Unisce un elemento matematico e forma un blocco matematico |
| [`join(self, math_text)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/join/#str) | Unisce un testo matematico e forma un blocco matematico |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/divide/#str) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/divide/#str-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`enclose(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/enclose/#) | Racchiude un elemento matematico tra parentesi |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/enclose/#char-char) | Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri di inquadramento |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/function/#imathelement) | Definisce una funzione di un argomento usando questa istanza come nome della funzione |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/function/#str) | Definisce una funzione di un argomento usando questa istanza come nome della funzione |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#imathelement) | Utilizza la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#str) | Utilizza la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Utilizza la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Utilizza la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Utilizza la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#imathelement) | Crea indice |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#str) | Crea indice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#imathelement) | Crea apice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#str) | Crea apice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea indice e apice a destra |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#str-str) | Crea indice e apice a destra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea indice e apice a sinistra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#str-str) | Crea indice e apice a sinistra |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/radical/#imathelement) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/radical/#str) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#imathelement) | Prende il limite superiore |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#str) | Prende il limite superiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#imathelement) | Prende il limite inferiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#str) | Prende il limite inferiore |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operatore N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-str-str) | Crea un operatore N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Prende l'integrale |
| [`integral(self, integral_type)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes) | Prende l'integrale senza limiti |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str) | Prende l'integrale |
| [`group(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/group/#) | Posiziona questo elemento in un gruppo usando una parentesi graffa inferiore |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Posiziona questo elemento in un gruppo usando un carattere di raggruppamento, come una parentesi graffa inferiore o altro |
| [`to_border_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#) | Posiziona questo elemento in una casella di delimitazione |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Posiziona questo elemento in una casella di delimitazione |
| [`to_math_array(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/to_math_array/#) | Inserisce in un array verticale |
| [`accent(self, accent_character)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/accent/#char) | Imposta un segno diacritico (un carattere sopra questo elemento) |
| [`overbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/overbar/#) | Imposta una barra sopra questo elemento |
| [`underbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/underbar/#) | Imposta una barra sotto questo elemento |
| [`to_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/to_box/#) | Posiziona questo elemento in una casella non visiva (raggruppamento logico) <br/>            che è usata per raggruppare componenti di un'equazione o di un altro testo matematico.<br/>            Un oggetto incassato può (ad esempio) servire come emulatore di operatore con o senza punto di allineamento, <br/>            servire come punto di interruzione di linea, oppure essere raggruppato in modo da non consentire interruzioni di linea al suo interno. |
| [`get_children(self)`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/get_children/#) | Ottieni gli elementi figli |

### Vedi anche
* classe [`BaseScript`](/slides/python-net/it/aspose.slides.mathtext/basescript)
* classe [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)
* classe [`MathSubscriptElement`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)