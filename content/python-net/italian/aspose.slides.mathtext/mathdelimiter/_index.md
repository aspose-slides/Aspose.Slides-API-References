---
title: MathDelimiter class
second_title: Riferimento API di Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter classe

Specifica l'oggetto delimitatore, costituito da caratteri di apertura e chiusura (come parentesi, 
            graffe, parentesi quadre e barre verticali), e uno o più elementi matematici all'interno, separati da un carattere specificato.
            Esempi: (𝑥2); [𝑥2|𝑦2]

**Eredità:**[`MathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)

Il tipo MathDelimiter espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Inizializza MathDelimiter con l'elemento specificato come argomento base unico |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`arguments`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/arguments/) | Uno o più elementi matematici separati da caratteri delimitatori |
| [`beginning_character`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Il carattere di inizio delimitatore specifica il carattere delimitatore di apertura. <br/>            I delimitatori matematici sono caratteri di incapsulamento come parentesi, parentesi quadre e graffe.<br/>            Il valore predefinito: '(' |
| [`separator_character`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/separator_character/) | Il carattere separatore del delimitatore specifica il carattere che separa gli argomenti nell'oggetto delimitatore. <br/>            Il valore predefinito: '\|'. |
| [`ending_character`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/ending_character/) | Il carattere di fine delimitatore specifica il carattere delimitatore di chiusura. <br/>            I delimitatori matematici sono caratteri di incapsulamento come parentesi, parentesi quadre e graffe.<br/>            Il valore predefinito: ')' |
| [`grow_to_match_operand_height`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Quando true, i delimitatori crescono verticalmente per corrispondere all'altezza del loro operando.<br/>            Il valore predefinito è true |
| [`delimiter_shape`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Specifica la forma dei delimitatori nell'oggetto delimitatore. <br/>            Quando è MathDelimiterShape.Centered, i delimitatori sono centrati attorno all'asse matematico del testo matematico <br/>            e vengono adattati per coprire l'intera altezza del loro contenuto.<br/>            Quando è MathDelimiterShape.Match, la loro altezza e forma vengono modificate per corrispondere esattamente al contenuto. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Unisce un elemento matematico e forma un blocco matematico |
| [`join(self, math_text)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/join/#str) | Unisce un testo matematico e forma un blocco matematico |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/divide/#str) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`enclose(self)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/enclose/#) | Racchiude un elemento matematico tra parentesi |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri di inquadratura |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Accetta una funzione di un argomento usando questa istanza come nome della funzione |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/function/#str) | Accetta una funzione di un argomento usando questa istanza come nome della funzione |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Accetta la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Accetta la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Accetta la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Accetta la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Accetta la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Crea pedice |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Crea pedice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Crea apice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Crea apice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea pedice e apice a sinistra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Crea pedice e apice a sinistra |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/radical/#str) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Accetta limite superiore |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Accetta limite superiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Accetta limite inferiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Accetta limite inferiore |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operatore N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Crea un operatore N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Accetta l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Accetta l'integrale |
| [`integral(self, integral_type)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Accetta l'integrale senza limiti |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Accetta l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Accetta l'integrale |
| [`group(self)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/group/#) | Posiziona questo elemento in un gruppo usando una graffa inferiore |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Posiziona questo elemento in un gruppo usando un carattere di raggruppamento come una graffa inferiore o un altro |
| [`to_border_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Posiziona questo elemento in una scatola bordata |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Posiziona questo elemento in una scatola bordata |
| [`to_math_array(self)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Inserisce in un array verticale |
| [`accent(self, accent_character)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/accent/#char) | Imposta un segno di accento (un carattere sopra questo elemento) |
| [`overbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/overbar/#) | Imposta una barra sopra questo elemento |
| [`underbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/underbar/#) | Imposta una barra sotto questo elemento |
| [`to_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/to_box/#) | Posiziona questo elemento in una scatola non visiva (raggruppamento logico) <br/>            che è usata per raggruppare componenti di un'equazione o altra istanza di testo matematico.<br/>            Un oggetto incorniciato può (ad esempio) fungere da emulatore di operatore con o senza punto di allineamento, <br/>            fungere da punto di interruzione di riga, oppure essere raggruppato in modo da non permettere interruzioni di riga al suo interno. |
| [`delimit(self, separator_character)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Delimita gli argomenti usando il carattere delimitatore specificato |
| [`get_children(self)`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/get_children/#) | Ottiene gli elementi figli |


### Vedi anche
* classe [`MathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter)
* classe [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)