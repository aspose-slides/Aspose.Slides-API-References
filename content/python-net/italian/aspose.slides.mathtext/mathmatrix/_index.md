---
title: MathMatrix class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix classe

Specifica l'oggetto Matrix, costituito da elementi figlio disposti in una o più righe e colonne. 
            È importante notare che le matrici non hanno delimitatori incorporati. 
            Per inserire la matrice tra parentesi è necessario utilizzare l'oggetto delimitatore (IMathDelimiter).
            È possibile utilizzare argomenti null per creare spazi vuoti nelle matrici.

**Eredità:**[`MathMatrix`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)

Il tipo MathMatrix espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Inizializza una nuova istanza della classe MathMatrix. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`row_count`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/row_count/) | Numero di righe nella matrice |
| [`column_count`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/column_count/) | Numero di colonne nella matrice |
| [`hide_placeholders`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Nascondi i segnaposto per gli elementi vuoti della matrice<br/>            Predefinito: false |
| [`base_justification`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/base_justification/) | Specifica l'allineamento verticale rispetto al testo circostante. <br/>            I valori possibili sono top, bottom e center.<br/>            Predefinito: Center |
| [`min_column_width`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/min_column_width/) | Larghezza minima della colonna in twip (1/20 di punto)<br/>            La spaziatura del gap (nota anche come “Column Gap” o “Gap Width”) viene aggiunta a <br/>            MinColumnWidth per determinare la spaziatura totale delle colonne della matrice<br/>            (distanza tra i lati corrispondenti di colonne diverse).<br/>            Predefinito: 0. |
| [`column_gap_rule`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | Il tipo di spaziatura orizzontale tra le colonne di una matrice; <br/>            Le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip).<br/>            Predefinito: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/column_gap/) | Il valore della spaziatura orizzontale tra le colonne di una matrice;<br/>            Se ColumnGapRule è impostato a 3 ("Exactly"), l'unità è interpretata come twip (1/20 di punto)<br/>            Se ColumnGapRule è impostato a 4 ("Multiple"), l'unità è interpretata come numero di incrementi di 0,5 em.<br/>            Negli altri casi viene ignorato.<br/>            Predefinito: 0 |
| [`row_gap_rule`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | Il tipo di spaziatura verticale tra le righe di una matrice; <br/>            Le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip).<br/>            Predefinito: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/row_gap/) | Il valore della spaziatura verticale tra le righe di una matrice;<br/>            Se RowGapRule è impostato a 3 ("Exactly"), l'unità è interpretata come twip (1/20 di punto)<br/>            Se RowGapRule è impostato a 4 ("Multiple"), l'unità è interpretata come mezze righe.<br/>            Predefinito: 0 |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Unisce un elemento matematico e forma un blocco matematico |
| [`join(self, math_text)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/join/#str) | Unisce un testo matematico e forma un blocco matematico |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/divide/#str) | Crea una frazione con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [`enclose(self)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/enclose/#) | Racchiude un elemento matematico tra parentesi |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri come cornice |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/function/#str) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Prende la funzione specificata usando questa istanza come argomento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prende la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prende la funzione specificata usando questa istanza come argomento e un argomento aggiuntivo specificato |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Crea pedice |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Crea pedice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Crea apice |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Crea apice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Crea pedice e apice a destra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea pedice e apice a sinistra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Crea pedice e apice a sinistra |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Specifica la radice matematica del grado dato dal argomento specificato. |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/radical/#str) | Specifica la radice matematica del grado dato dal argomento specificato. |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Prende il limite superiore |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Prende il limite superiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Prende il limite inferiore |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Prende il limite inferiore |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operatore N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | Crea un operatore N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Prende l'integrale |
| [`integral(self, integral_type)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Prende l'integrale senza limiti |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prende l'integrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Prende l'integrale |
| [`group(self)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/group/#) | Posiziona questo elemento in un gruppo usando una graffa inferiore |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Posiziona questo elemento in un gruppo usando un carattere di raggruppamento come una graffa inferiore o altro |
| [`to_border_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Posiziona questo elemento in una casella bordata |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Posiziona questo elemento in una casella bordata |
| [`to_math_array(self)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Inserisce in un array verticale |
| [`accent(self, accent_character)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/accent/#char) | Imposta un segno diacritico (un carattere sopra questo elemento) |
| [`overbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/overbar/#) | Imposta una barra sulla parte superiore di questo elemento |
| [`underbar(self)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/underbar/#) | Imposta una barra nella parte inferiore di questo elemento |
| [`to_box(self)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/to_box/#) | Posiziona questo elemento in una casella non visiva (raggruppamento logico) <br/>            che è usata per raggruppare componenti di un'equazione o di un altro testo matematico.<br/>            Un oggetto incassato può (ad esempio) fungere da emulatore di operatore con o senza punto di allineamento, <br/>            fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire rotture di riga al suo interno. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Ottiene l'allineamento orizzontale della colonna specificata |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Imposta l'allineamento orizzontale della colonna specificata |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Imposta l'allineamento orizzontale delle colonne specificate |
| [`insert_row_before(self, row_index)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Inserisce una nuova riga prima di quella specificata<br/>            Inizialmente tutti gli elementi nella nuova riga sono None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Inserisce una nuova riga dopo quella specificata<br/>            Inizialmente tutti gli elementi nella nuova riga sono None. |
| [`delete_row(self, row_index)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Elimina la riga specificata |
| [`insert_column_before(self, column_index)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Inserisce una nuova colonna prima di quella specificata<br/>            Inizialmente tutti gli elementi nella nuova colonna sono None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Inserisce una nuova colonna dopo quella specificata<br/>            Inizialmente tutti gli elementi nella nuova colonna sono None. |
| [`delete_column(self, column_index)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Elimina la colonna specificata |
| [`get_children(self)`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/get_children/#) | Ottiene gli elementi figli |


### Vedi anche
* classe [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase)
* classe [`MathMatrix`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)