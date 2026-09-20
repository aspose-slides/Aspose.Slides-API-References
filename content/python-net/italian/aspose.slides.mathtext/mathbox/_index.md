---
title: MathBox class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathbox/
---
## MathBox classe

Specifica il incapsulamento logico (impacchettamento) di un elemento matematico.
            Ad esempio, un oggetto incapsulato può fungere da emulatore di operatore con o senza un punto di allineamento, 
            funge da punto di interruzione di linea, oppure può essere raggruppato in modo da non consentire interruzioni di linea al suo interno.
            Ad esempio, l'operatore "==" dovrebbe essere incapsulato per impedire interruzioni di linea.

**Ereditarietà:**[`MathBox`](/slides/python-net/it/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)

Il tipo MathBox espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Inizializza MathBox con l'elemento specificato come argomento |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`base`](/slides/python-net/it/aspose.slides.mathtext/mathbox/base/) | Argomento di base |
| [`operator_emulator`](/slides/python-net/it/aspose.slides.mathtext/mathbox/operator_emulator/) | Emulatore di operatore.<br/>            Quando è vero, la scatola e il suo contenuto si comportano come un singolo operatore e ereditano le proprietà di un operatore. <br/>            Ciò significa, ad esempio, che il carattere può fungere da punto per un'interruzione di linea e può essere allineato ad altri operatori.<br/>            Gli emulatori di operatori sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='.<br/>            Valore predefinito: false |
| [`no_break`](/slides/python-net/it/aspose.slides.mathtext/mathbox/no_break/) | Nessuna interruzione<br/>            Questa proprietà specifica la proprietà "unbreakable" (non rompibile) sulla scatola dell'oggetto. Quando è vero, nessuna interruzione di linea può verificarsi all'interno della scatola.<br/>            Ciò può essere importante per gli emulatori di operatori che consistono in più di un operatore binario. <br/>            Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno della scatola.<br/>            Predefinito: true |
| [`differential`](/slides/python-net/it/aspose.slides.mathtext/mathbox/differential/) | Differenziale<br/>            Quando è vero, la scatola agisce come un differenziale (ad esempio, 𝑑𝑥 in un integrando) e riceve la spaziatura orizzontale appropriata <br/>            spaziatura orizzontale per il differenziale matematico.<br/>            Predefinito: false |
| [`alignment_point`](/slides/python-net/it/aspose.slides.mathtext/mathbox/alignment_point/) | Quando è vero, questo emulatore di operatore funge da punto di allineamento; cioè, <br/>            i punti di allineamento designati in altre equazioni possono essere allineati con esso.<br/>            Predefinito: false |
| [`explicit_break`](/slides/python-net/it/aspose.slides.mathtext/mathbox/explicit_break/) | Interruzione esplicita specifica se esiste un'interruzione di linea all'inizio dell'oggetto Box, <br/>            in modo che la linea vada a capo all'inizio dell'oggetto box.<br/>            Specifica il numero dell'operatore sulla linea precedente del testo matematico che deve<br/>            essere usato come punto di allineamento per la linea corrente del testo matematico<br/>            valori possibili: 1..255<br/>            Predefinito: 0 (nessuna interruzione esplicita) |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/join/#imathelement) | Unisce un elemento matematico e forma un blocco matematico |
| [`join(self, math_text)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/join/#str) | Unisce un testo matematico e forma un blocco matematico |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/divide/#imathelement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/divide/#str) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`enclose(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/enclose/#) | Racchiude un elemento matematico tra parentesi |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/enclose/#char-char) | Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri di inquadratura |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/function/#imathelement) | Crea una funzione di un argomento utilizzando questa istanza come nome della funzione |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/function/#str) | Crea una funzione di un argomento utilizzando questa istanza come nome della funzione |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Utilizza la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Utilizza la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Utilizza la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Utilizza la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Utilizza la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Crea pedice |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/set_subscript/#str) | Crea pedice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Crea apice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/set_superscript/#str) | Crea apice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea pedice e apice a sinistra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Crea pedice e apice a sinistra |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/radical/#imathelement) | Specifica la radice matematica del grado indicato dall'argomento specificato. |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/radical/#str) | Specifica la radice matematica del grado indicato dall'argomento specificato. |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Prende il limite superiore |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Prende il limite superiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Prende il limite inferiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Prende il limite inferiore |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operatore N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | Crea un operatore N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | Prende l'integrale |
| [`integral(self, integral_type)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Prende l'integrale senza limiti |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | Prende l'integrale |
| [`group(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/group/#) | Posiziona questo elemento in un gruppo usando una graffa inferiore |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Posiziona questo elemento in un gruppo usando un carattere di raggruppamento come la graffa inferiore o un altro |
| [`to_border_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/to_border_box/#) | Posiziona questo elemento in una casella di contorno |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Posiziona questo elemento in una casella di contorno |
| [`to_math_array(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/to_math_array/#) | Inserisce in un array verticale |
| [`accent(self, accent_character)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/accent/#char) | Imposta un segno di accento (un carattere sopra questo elemento) |
| [`overbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/overbar/#) | Imposta una barra sopra questo elemento |
| [`underbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/underbar/#) | Imposta una barra sotto questo elemento |
| [`to_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/to_box/#) | Posiziona questo elemento in una scatola non visiva (raggruppamento logico) <br/>            che è usata per raggruppare componenti di un'equazione o di altra istanza di testo matematico.<br/>            Un oggetto incapsulato può (ad esempio) fungere da emulatore di operatore con o senza un punto di allineamento, <br/>            servire da punto di interruzione di linea, o essere raggruppato in modo da non consentire interruzioni di linea al suo interno. |
| [`get_children(self)`](/slides/python-net/it/aspose.slides.mathtext/mathbox/get_children/#) | Ottiene gli elementi figli |

### Vedi anche
* classe [`MathBox`](/slides/python-net/it/aspose.slides.mathtext/mathbox)
* classe [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)