---
title: MathGroupingCharacter class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter classe

Specifica un simbolo di raggruppamento sopra o sotto un'espressione, solitamente per evidenziare la relazione tra gli elementi

**Inheritance:**[`MathGroupingCharacter`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)

Il tipo MathGroupingCharacter espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | Inizializza una nuova istanza della classe MathGroupingCharacter <br/>            con il carattere di raggruppamento predefinito U+23DF (Parentesi graffa inferiore) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | Inizializza una nuova istanza della classe MathGroupingCharacter. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`base`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/base/) | argomento base |
| [`character`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/character/) | Carattere di raggruppamento<br/>            Valore predefinito: U+23DF (Parentesi graffa inferiore) |
| [`position`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/position/) | Posizione del carattere di raggruppamento.<br/>            Predefinito: Bottom |
| [`vertical_justification`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | Giustificazione verticale del carattere di gruppo.<br/>            Specifica l'allineamento dell'oggetto rispetto alla linea di base.<br/>            Ad esempio, quando il carattere di gruppo è sopra l'oggetto, <br/>            VerticalJustification di Top indica che la parte superiore dell'oggetto cade sulla linea di base;<br/>            quando VerticalJustification è impostato su Bottom, la parte inferiore dell'oggetto è sulla linea di base<br/>            Predefinito: Bottom per Position=Top, e Top per Position=Bottom |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | Unisce un elemento matematico e forma un blocco matematico |
| [`join(self, math_text)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | Unisce un testo matematico e forma un blocco matematico |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`enclose(self)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | Racchiude un elemento matematico tra parentesi |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | Racchiude un elemento matematico in caratteri specificati come parentesi o altri caratteri come cornice |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | Prende una funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | Prende una funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | Prende una funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prende una funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prende una funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | Crea pedice |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | Crea pedice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | Crea apice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | Crea apice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea pedice e apice a sinistra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | Crea pedice e apice a sinistra |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | Prende limite superiore |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | Prende limite superiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | Prende limite inferiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | Prende limite inferiore |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operatore N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | Crea un operatore N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | Prende l'integrale |
| [`integral(self, integral_type)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | Prende l'integrale senza limiti |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | Prende l'integrale |
| [`group(self)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/group/#) | Inserisce questo elemento in un gruppo usando una parentesi graffa inferiore |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | Inserisce questo elemento in un gruppo usando un carattere di raggruppamento come la parentesi graffa inferiore o un altro |
| [`to_border_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | Inserisce questo elemento in una cornice |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Inserisce questo elemento in una cornice |
| [`to_math_array(self)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | Inserisce in un array verticale |
| [`accent(self, accent_character)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | Imposta un segno di accento (un carattere sopra questo elemento) |
| [`overbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | Imposta una barra sulla parte superiore di questo elemento |
| [`underbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | Imposta una barra sulla parte inferiore di questo elemento |
| [`to_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | Inserisce questo elemento in una casella non visiva (raggruppamento logico) <br/>            che è usata per raggruppare componenti di un'equazione o altra istanza di testo matematico.<br/>            Un oggetto incorniciato può (ad esempio) servire da emulatore di operatore con o senza un punto di allineamento, <br/>            servire da punto di interruzione di linea, o essere raggruppato in modo da non permettere interruzioni di linea al suo interno. |
| [`get_children(self)`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | Ottiene gli elementi figli |

### Vedi anche
* classe [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)
* classe [`MathGroupingCharacter`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)