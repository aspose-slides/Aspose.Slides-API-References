---
title: MathMatrix class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix κλάση

Καθορίζει το αντικείμενο Matrix, που αποτελείται από θυγατρικά στοιχεία τοποθετημένα σε μία ή περισσότερες γραμμές και στήλες.  
Είναι σημαντικό να σημειωθεί ότι οι μήτρες δεν έχουν ενσωματωμένους οριοθέτες.  
Για να τοποθετήσετε τη μήτρα σε αγκύλες, θα πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη (IMathDelimiter).  
Μπορούν να χρησιμοποιηθούν μηδενικά (Null) ορίσματα για τη δημιουργία κενών στη μήτρα.

**Κληρονομικότητα:**[`MathMatrix`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)

Ο τύπος MathMatrix εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Αρχικοποιεί μια νέα παρουσία της κλάσης MathMatrix. |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`row_count`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/row_count/) | Αριθμός γραμμών στη μήτρα |
| [`column_count`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/column_count/) | Αριθμός στηλών στη μήτρα |
| [`hide_placeholders`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Απόκρυψη των θέσεων κράτησης για κενά στοιχεία της μήτρας<br/>            Προεπιλογή: false |
| [`base_justification`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/base_justification/) | Καθορίζει την κατακόρυφη στοίχιση ως προς το γύρω κείμενο.<br/>            Οι δυνατές τιμές είναι top, bottom, και center.<br/>            Προεπιλογή: Center |
| [`min_column_width`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/min_column_width/) | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου)<br/>            Το κενό διάστημα (επίσης αναφέρεται ως “Column Gap” ή “Gap Width”) προστίθεται στο <br/>            MinColumnWidth για να καθορίσει το συνολικό διάστημα στήλης της μήτρας<br/>            (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών).<br/>            Προεπιλογή: 0. |
| [`column_gap_rule`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | Ο τύπος της οριζόντιας απόστασης μεταξύ των στηλών μιας μήτρας;<br/>            Οι μονάδες οριζόντιας απόστασης μπορούν να είναι ems ή points (αποθηκευμένα ως twips).<br/>            Προεπιλογή: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/column_gap/) | Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών μιας μήτρας;<br/>            Εάν το ColumnGapRule ορίζεται σε 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)<br/>            Εάν το ColumnGapRule ορίζεται σε 4 ("Multiple"), η μονάδα ερμηνεύεται ως αριθμός 0.5 em βημάτων.<br/>            Σε άλλες περιπτώσεις αγνοείται.<br/>            Προεπιλογή: 0 |
| [`row_gap_rule`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | Ο τύπος της κατακόρυφης απόστασης μεταξύ των σειρών μιας μήτρας;<br/>            Οι μονάδες κατακόρυφης απόστασης μπορούν να είναι lines ή points (αποθηκευμένα ως twips).<br/>            Προεπιλογή: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/row_gap/) | Η τιμή της κατακόρυφης απόστασης μεταξύ των σειρών μιας μήτρας;<br/>            Εάν το RowGapRule ορίζεται σε 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)<br/>            Εάν το RowGapRule ορίζεται σε 4 ("Multiple"), η μονάδα ερμηνεύεται ως half-lines.<br/>            Προεπιλογή: 0 |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Συνδυάζει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/join/#str) | Συνδυάζει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/divide/#str) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/enclose/#) | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαισίωση |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/function/#str) | Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο επιπλέον όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο επιπλέον όρισμα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Δημιουργεί δείκτη |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Δημιουργεί δείκτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Δημιουργεί εκθέτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Δημιουργεί εκθέτη |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη δεξιά |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Δημιουργεί δείκτη και εκθέτη δεξιά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη αριστερά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Δημιουργεί δείκτη και εκθέτη αριστερά |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/radical/#str) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Λαμβάνει άνω όριο |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Λαμβάνει άνω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Λαμβάνει κατώτερο όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Λαμβάνει κατώτερο όριο |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | Δημιουργεί έναν N-αρο τελεστή |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | Δημιουργεί έναν N-αρο τελεστή |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Λαμβάνει το ολοκλήρωμα χωρίς όρια |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Λαμβάνει το ολοκλήρωμα |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/group/#) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας ένα καμπύλο αγκύλη στο κάτω μέρος |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης όπως η κατωκάτω αγκύλη ή άλλον |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Τοποθετεί σε κάθετη διάταξη |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/accent/#char) | Θέτει ένα σημείο προσήμου (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/overbar/#) | Θέτει μπάρα στην κορυφή αυτού του στοιχείου |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/underbar/#) | Θέτει μπάρα στο κάτω μέρος αυτού του στοιχείου |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/to_box/#) | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) <br/>            που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης μορφής μαθηματικού κειμένου.<br/>            Ένα αντικείμενο σε κουτί μπορεί (π.χ.) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, <br/>            να λειτουργήσει ως σημείο διακοπής γραμμής, ή να ομαδοποιηθεί ώστε να μη επιτρέπει διακοπές γραμμής μέσα σε αυτό. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Λαμβάνει την οριζόντια στοίχιση της καθορισμένης στήλης |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Ορίζει την οριζόντια στοίχιση της καθορισμένης στήλης |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Ορίζει την οριζόντια στοίχιση των καθορισμένων στηλών |
| [`insert_row_before(self, row_index)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Εισάγει μια νέα σειρά πριν από την καθορισμένη<br/>            Αρχικά όλα τα στοιχεία στη νέα σειρά είναι None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Εισάγει μια νέα σειρά μετά από την καθορισμένη<br/>            Αρχικά όλα τα στοιχεία στη νέα σειρά είναι None. |
| [`delete_row(self, row_index)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Διαγράφει την καθορισμένη σειρά |
| [`insert_column_before(self, column_index)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Εισάγει μια νέα στήλη πριν από την καθορισμένη<br/>            Αρχικά όλα τα στοιχεία στη νέα στήλη είναι None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Εισάγει μια νέα στήλη μετά από την καθορισμένη<br/>            Αρχικά όλα τα στοιχεία στη νέα στήλη είναι None. |
| [`delete_column(self, column_index)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Διαγράφει την καθορισμένη στήλη |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix/get_children/#) | Λαμβάνει τα παιδικά στοιχεία |

### Δείτε επίσης
* κλάση [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)
* κλάση [`MathMatrix`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)