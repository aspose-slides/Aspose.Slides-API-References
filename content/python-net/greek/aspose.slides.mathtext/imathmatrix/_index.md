---
title: IMathMatrix class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix κλάση

Καθορίζει το αντικείμενο Matrix, που αποτελείται από θυγατρικά στοιχεία τακτοποιημένα σε μία ή περισσότερες σειρές και στήλες. 
            Είναι σημαντικό να σημειωθεί ότι οι μητρώες δεν έχουν ενσωματωμένους οριοθέτες. 
            Για να τοποθετήσετε τη μητρώα σε αγκύλες, πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη (IMathDelimiter).
            Μπορούν να χρησιμοποιηθούν μηδενικές (Null) παράμετροι για τη δημιουργία κενών στις μητρώες.

Ο τύπος IMathMatrix εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`row_count`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/row_count/) | Αριθμός σειρών στη μητρώα |
| [`column_count`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/column_count/) | Αριθμός στηλών στη μητρώα |
| [`hide_placeholders`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Απόκρυψη των θέσεων για κενά στοιχεία της μητρώας<br/>            Προεπιλογή: false |
| [`base_justification`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/base_justification/) | Καθορίζει την κάθετη στοίχιση σε σχέση με το γύρω κείμενο.<br/>            Πιθανές τιμές είναι top, bottom, και center.<br/>            Προεπιλογή: Center |
| [`min_column_width`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/min_column_width/) | Ελάχιστο πλάτος στήλης σε twips (1/20ο σημείου)<br/>            Το διάκενο (επίσης αναφέρεται ως “Column Gap” ή “Gap Width”) προστίθεται στο <br/>            το MinColumnWidth για να καθορίσει τη συνολική απόσταση στήλης της μητρώας<br/>            (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών).<br/>            Προεπιλογή: 0. |
| [`column_gap_rule`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | Ο τύπος της οριζόντιας απόστασης μεταξύ των στηλών μιας μητρώας;<br/>            Οι μονάδες οριζόντιας απόστασης μπορούν να είναι ems ή points (αποθηκευμένες ως twips).<br/>            Προεπιλογή: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/column_gap/) | Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών μιας μητρώας;<br/>            Εάν το ColumnGapRule είναι ορισμένο σε 3 («Exactly»), τότε η μονάδα ερμηνεύεται ως twips (1/20ο σημείου)<br/>            Εάν το ColumnGapRule είναι ορισμένο σε 4 («Multiple»), τότε η μονάδα ερμηνεύεται ως αριθμός βημάτων 0.5 em.<br/>            Σε άλλες περιπτώσεις αγνοείται.<br/>            Προεπιλογή: 0 |
| [`row_gap_rule`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | Ο τύπος της κάθετης απόστασης μεταξύ των γραμμών μιας μητρώας;<br/>            Οι μονάδες κάθετης απόστασης μπορούν να είναι γραμμές ή points (αποθηκευμένες ως twips).<br/>            Προεπιλογή: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/row_gap/) | Η τιμή της κάθετης απόστασης μεταξύ των γραμμών μιας μητρώας;<br/>            Εάν το RowGapRule είναι ορισμένο σε 3 («Exactly»), τότε η μονάδα ερμηνεύεται ως twips (1/20ο σημείου)<br/>            Εάν το RowGapRule είναι ορισμένο σε 4 («Multiple»), τότε η μονάδα ερμηνεύεται ως μισές γραμμές.<br/>            Προεπιλογή: 0 |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Λαμβάνει την οριζόντια στοίχιση της καθορισμένης στήλης |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Ορίζει την οριζόντια στοίχιση της καθορισμένης στήλης |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Ορίζει την οριζόντια στοίχιση των καθορισμένων στηλών |
| [`insert_row_before(self, row_index)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Εισάγει μια νέα σειρά πριν από την καθορισμένη<br/>            Αρχικά όλα τα στοιχεία στη νέα σειρά είναι None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Εισάγει μια νέα σειρά μετά την καθορισμένη<br/>            Αρχικά όλα τα στοιχεία στη νέα σειρά είναι None. |
| [`delete_row(self, row_index)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Διαγράφει τη καθορισμένη σειρά |
| [`insert_column_before(self, column_index)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Εισάγει μια νέα στήλη πριν από την καθορισμένη<br/>            Αρχικά όλα τα στοιχεία στη νέα στήλη είναι None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Εισάγει μια νέα στήλη μετά την καθορισμένη<br/>            Αρχικά όλα τα στοιχεία στη νέα στήλη είναι None. |
| [`delete_column(self, column_index)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Διαγράφει τη καθορισμένη στήλη |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/imathmatrix/to_box/#) |  |


### Δείτε επίσης
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)