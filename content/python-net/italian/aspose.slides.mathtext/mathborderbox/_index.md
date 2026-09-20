---
title: MathBorderBox class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox classe

Disegna un bordo rettangolare o di altro tipo attorno all'IMathElement.

**Eredità:**[`MathBorderBox`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)

Il tipo MathBorderBox espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | Crea l'elemento MathBorderBox con bordo rettangolare |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | Crea l'elemento MathBorderBox |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`base`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/base/) | Argomento di base |
| [`hide_top`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/hide_top/) | Nascondi il bordo superiore (predefinito è false) - specifica lo stato nascosto o mostrato del bordo superiore della border box. |
| [`hide_bottom`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/hide_bottom/) | Nascondi il bordo inferiore (predefinito è false) - specifica lo stato nascosto o mostrato del bordo inferiore della border box. |
| [`hide_left`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/hide_left/) | Nascondi il bordo sinistro (predefinito è false) - specifica lo stato nascosto o mostrato del bordo sinistro della border box. |
| [`hide_right`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/hide_right/) | Nascondi il bordo destro (predefinito è false) - specifica lo stato nascosto o mostrato del bordo destro della border box. |
| [`strikethrough_horizontal`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | Barrato orizzontale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea orizzontale barrata. |
| [`strikethrough_vertical`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | Barrato verticale (predefinito è false) - specifica lo stato nascosto o mostrato di una linea verticale barrata. |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | Barrato dal basso a sinistra al alto a destra (predefinito è false).<br/>            Specificare lo stato nascosto o mostrato di una linea diagonale barrata dall'angolo in basso a sinistra all'angolo in alto a destra della border box. |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | Barrato dal alto a sinistra al basso a destra (predefinito è false).<br/>            Specificare lo stato nascosto o mostrato di una linea diagonale barrata dall'angolo in alto a sinistra all'angolo in basso a destra della border box. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/join/#imathelement) | Unisce un elemento matematico e forma un blocco matematico |
| [`join(self, math_text)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/join/#str) | Unisce un testo matematico e forma un blocco matematico |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/divide/#str) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`enclose(self)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/enclose/#) | Racchiude un elemento matematico tra parentesi |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri di inquadratura |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/function/#imathelement) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/function/#str) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prende la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prende la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | Crea pedice |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | Crea pedice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | Crea apice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | Crea apice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea pedice e apice a sinistra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | Crea pedice e apice a sinistra |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/radical/#str) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | Prende il limite superiore |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | Prende il limite superiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | Prende il limite inferiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | Prende il limite inferiore |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operatore N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | Crea un operatore N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | Prende l'integrale |
| [`integral(self, integral_type)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | Prende l'integrale senza limiti |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | Prende l'integrale |
| [`group(self)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/group/#) | Posiziona questo elemento in un gruppo usando una parentesi graffa inferiore |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Posiziona questo elemento in un gruppo usando un carattere di raggruppamento come la parentesi graffa inferiore o un altro |
| [`to_border_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/to_border_box/#) | Posiziona questo elemento in una border-box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Posiziona questo elemento in una border-box |
| [`to_math_array(self)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/to_math_array/#) | Inserisce in una matrice verticale |
| [`accent(self, accent_character)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/accent/#char) | Imposta un segno diacritico (un carattere sopra questo elemento) |
| [`overbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/overbar/#) | Imposta una barra sopra questo elemento |
| [`underbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/underbar/#) | Imposta una barra sotto questo elemento |
| [`to_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/to_box/#) | Posiziona questo elemento in una scatola non visiva (raggruppamento logico) <br/>            che è usata per raggruppare componenti di un'equazione o altra istanza di testo matematico.<br/>            Un oggetto incapsulato può (ad esempio) fungere da emulatore di operatore con o senza un punto di allineamento, <br/>            servire come punto di interruzione di riga, oppure essere raggruppato in modo da non consentire interruzioni di riga al suo interno. |
| [`get_children(self)`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/get_children/#) | Ottiene gli elementi figli |

### Vedi anche
* classe [`MathBorderBox`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox)
* classe [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)