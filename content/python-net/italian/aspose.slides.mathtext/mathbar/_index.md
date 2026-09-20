---
title: MathBar class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathbar/
---
## MathBar classe

Specifica la funzione barra, composta da un argomento base e una barra superiore o inferiore

**Inheritance:**[`MathBar`](/slides/python-net/it/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)

Il tipo MathBar espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/__init__/#imathelement) | Inizializza MathBar con overbar (Top position) |
| [`__init__(self, element, position)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | Inizializza MathBar con posizione specificata |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`base`](/slides/python-net/it/aspose.slides.mathtext/mathbar/base/) | Argomento base |
| [`position`](/slides/python-net/it/aspose.slides.mathtext/mathbar/position/) | Posizione della linea di barra. <br/>            Default: Top |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/join/#imathelement) | Unisce un elemento matematico e forma un blocco matematico |
| [`join(self, math_text)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/join/#str) | Unisce un testo matematico e forma un blocco matematico |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/divide/#imathelement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/divide/#str) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`enclose(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/enclose/#) | Racchiude un elemento matematico tra parentesi |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/enclose/#char-char) | Racchiude un elemento matematico in caratteri specificati, come parentesi o altri caratteri di inquadramento |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/function/#imathelement) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/function/#str) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prende la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prende la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | Crea pedice |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/set_subscript/#str) | Crea pedice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | Crea apice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/set_superscript/#str) | Crea apice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea pedice e apice a sinistra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | Crea pedice e apice a sinistra |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/radical/#imathelement) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/radical/#str) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | Prende limite superiore |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | Prende limite superiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | Prende limite inferiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | Prende limite inferiore |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operatore N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | Crea un operatore N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | Prende l'integrale |
| [`integral(self, integral_type)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | Prende l'integrale senza limiti |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | Prende l'integrale |
| [`group(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/group/#) | Posiziona questo elemento in un gruppo usando una parentesi graffa inferiore |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | Posiziona questo elemento in un gruppo usando un carattere di raggruppamento come la parentesi graffa inferiore o altro |
| [`to_border_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/to_border_box/#) | Posiziona questo elemento in un riquadro |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Posiziona questo elemento in un riquadro |
| [`to_math_array(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/to_math_array/#) | Inserisce in una matrice verticale |
| [`accent(self, accent_character)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/accent/#char) | Imposta un segno di accento (un carattere sopra questo elemento) |
| [`overbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/overbar/#) | Imposta una barra sopra questo elemento |
| [`underbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/underbar/#) | Imposta una barra sotto questo elemento |
| [`to_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/to_box/#) | Posiziona questo elemento in una casella non visiva (raggruppamento logico) <br/>            che è usata per raggruppare componenti di un'equazione o altra istanza di testo matematico.<br/>            Un oggetto incapsulato può (ad esempio) fungere da emulatore di operatore con o senza punto di allineamento, <br/>            fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga al suo interno. |
| [`get_children(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbar/get_children/#) | Ottieni gli elementi figli |

### Vedi anche
* classe [`MathBar`](/slides/python-net/it/aspose.slides.mathtext/mathbar)
* classe [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)