---
title: MathBlock class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathblock/
---
## MathBlock classe

Specifica un'istanza di testo matematico contenuta all'interno di un MathParagraph e che inizia su una propria linea.
            Tutte le zone matematiche, incluse equazioni, espressioni, array di equazioni o espressioni e formule sono rappresentate da blocco matematico.

**Eredità:**[`MathBlock`](/slides/python-net/it/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)

Il tipo MathBlock espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/__init__/#) | Inizializza una nuova istanza della classe MathBlock. |
| [`__init__(self, math_element)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Crea un nuovo blocco matematico e inserisce l'elemento specificato al suo interno |
| [`__init__(self, math_elements)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`count`](/slides/python-net/it/aspose.slides.mathtext/mathblock/count/) | Ottiene il numero di elementi matematici figli effettivamente contenuti nella collezione.<br/>            Sola lettura **int**. |
| [`is_read_only`](/slides/python-net/it/aspose.slides.mathtext/mathblock/is_read_only/) | Restituisce false perché la collezione di elementi figli può essere modificata. |

Ottiene o imposta IMathElement all'indice specificato.

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides.mathtext/mathblock/__getitem__/) | L'indice basato su zero dell'elemento |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/join/#imathelement) | Unisce un elemento matematico a questo blocco matematico |
| [`join(self, math_text)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/join/#str) | Unisce un testo matematico a questo blocco matematico |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/divide/#imathelement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/divide/#str) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/enclose/#char-char) | Racchiude gli elementi figli di questo blocco in caratteri specificati come parentesi o altri caratteri come cornice |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Racchiude gli elementi figli di questo blocco in caratteri specificati come parentesi o altri come cornice<br/>            e delimita con un carattere separatore |
| [`enclose(self)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/enclose/#) | Racchiude un elemento matematico tra parentesi |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/function/#imathelement) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/function/#str) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prende la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prende la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Crea un pedice |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/set_subscript/#str) | Crea un pedice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Crea un apice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/set_superscript/#str) | Crea un apice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea pedice e apice a sinistra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Crea pedice e apice a sinistra |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/radical/#imathelement) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/radical/#str) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Prende il limite superiore |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Prende il limite superiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Prende il limite inferiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Prende il limite inferiore |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operatore N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Crea un operatore N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Prende l'integrale |
| [`integral(self, integral_type)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Prende l'integrale senza limiti |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Prende l'integrale |
| [`group(self)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/group/#) | Colloca questo elemento in un gruppo usando una parentesi graffa inferiore |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Colloca questo elemento in un gruppo usando un carattere di raggruppamento come una parentesi graffa inferiore o un altro |
| [`to_border_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/to_border_box/#) | Colloca questo elemento in una cornice |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Colloca questo elemento in una cornice |
| [`to_math_array(self)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/to_math_array/#) | Mette gli elementi figli in un array verticale |
| [`accent(self, accent_character)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/accent/#char) | Imposta un segno diacritico (un carattere sopra questo elemento) |
| [`overbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/overbar/#) | Imposta una barra sopra questo elemento |
| [`underbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/underbar/#) | Imposta una barra sotto questo elemento |
| [`to_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/to_box/#) | Colloca questo elemento in una scatola non visiva (raggruppamento logico) <br/>            che è usata per raggruppare componenti di un'equazione o altra istanza di testo matematico.<br/>            Un oggetto incapsulato può (ad esempio) fungere da emulatore di operatore con o senza un punto di allineamento, <br/>            fungere da punto di interruzione di linea, o essere raggruppato in modo da non consentire interruzioni di linea al suo interno. |
| [`get_children(self)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/get_children/#) | Ottiene gli elementi figli |
| [`add(self, item)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/add/#imathelement) | Aggiunge un elemento matematico alla fine della collezione. |
| [`clear(self)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/clear/#) | Rimuove tutti gli elementi dalla collezione. |
| [`contains(self, item)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/contains/#imathelement) | Determina se la collezione contiene un valore specifico. |
| [`copy_to(self, array, array_index)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Copia in un array specificato. |
| [`remove(self, item)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/remove/#imathelement) | Rimuove la prima occorrenza di un oggetto specifico dalla collezione. |
| [`index_of(self, item)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Determina l'indice di un elemento matematico specifico nella collezione. |
| [`insert(self, index, item)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Inserisce un MathElement nella collezione all'indice specificato. |
| [`remove_at(self, index)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/remove_at/#int) | Rimuove l'elemento all'indice specificato della collezione. |
| [`join_block(self, other)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Unisce un altro blocco matematico a questo |
| [`delimit(self, separator_character)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/delimit/#char) | Delimita gli elementi figli con un carattere separatore (senza le parentesi) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/it/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Salva il contenuto di questo [`MathBlock`](/slides/python-net/it/aspose.slides.mathtext/mathblock) come MathML |

### Vedi anche
* classe [`MathBlock`](/slides/python-net/it/aspose.slides.mathtext/mathblock)
* classe [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)