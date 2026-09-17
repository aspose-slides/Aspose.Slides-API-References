---
title: MathPhantom class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.mathtext/mathphantom/
---
## MathPhantom κλάση

Αναπαριστά ένα φανταστικό μαθηματικό αντικείμενο (<m:phant>) που επηρεάζει τη διάταξη του στοιχείου-παιδίου χωρίς υποχρεωτική εμφάνισή του. Ένα φαντάσμιο μπορεί να κρύβει την βασική του έκφραση διατηρώντας το πλάτος, το ύψος ή το βάθος ώστε να ευθυγραμμίζει τύπους ή να κρατά χώρο. Η ορατότητα και η γεωμετρική συμπεριφορά ελέγχονται από ιδιότητες όπως Show, ZeroWid, ZeroAsc, ZeroDesc και Transp.

**Κληρονομικότητα:**[`MathPhantom`](/slides/python-net/el/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)

Ο τύπος MathPhantom εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`MathPhantom`](/slides/python-net/el/aspose.slides.mathtext/mathphantom) <br/> χρησιμοποιώντας το καθορισμένο βασικό μαθηματικό στοιχείο. |

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/base/) | Βασικό όρισμα |
| [`show`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/show/) | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν το βασικό στοιχείο εμφανίζεται. |
| [`zero_width`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/zero_width/) | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν το πλάτος του βασικού στοιχείου <br/> πρέπει να θεωρηθεί μηδενικό. |
| [`zero_asc`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/zero_asc/) | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν η άνοδος (ύψος πάνω από τη γραμμή βάσης) <br/> του βασικού στοιχείου πρέπει να θεωρηθεί μηδενική. |
| [`zero_desc`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/zero_desc/) | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν η κατάβαση (βάθος κάτω από τη γραμμή βάσης) <br/> του βασικού στοιχείου πρέπει να θεωρηθεί μηδενική. |
| [`transp`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/transp/) | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν το φαντάσμιο είναι διαφανές <br/> για κανόνες απόστασης βασισμένους στην κλάση. |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/join/#imathelement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/join/#str) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/divide/#imathelement) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/divide/#str) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/enclose/#) | Εμφανίζει ένα μαθηματικό στοιχείο μέσα σε παρενθέσεις |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/enclose/#char-char) | Εμφανίζει ένα μαθηματικό στοιχείο μέσα σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/function/#imathelement) | Παίρνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/function/#str) | Παίρνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και επιπλέον καθορισμένο όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και επιπλέον καθορισμένο όρισμα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | Δημιουργεί δέκτη |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/set_subscript/#str) | Δημιουργεί δέκτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | Δημιουργεί εκθέτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/set_superscript/#str) | Δημιουργεί εκθέτη |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | Δημιουργεί δέκτη και εκθέτη δεξιά |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | Δημιουργεί δέκτη και εκθέτη δεξιά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | Δημιουργεί δέκτη και εκθέτη αριστερά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | Δημιουργεί δέκτη και εκθέτη αριστερά |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/radical/#imathelement) | Ορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/radical/#str) | Ορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | Παίρνει ανώτερο όριο |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | Παίρνει ανώτερο όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | Παίρνει κατώτερο όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | Παίρνει κατώτερο όριο |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | Δημιουργεί τελεστή N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | Δημιουργεί τελεστή N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Παίρνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | Παίρνει το ολοκλήρωμα |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | Παίρνει το ολοκλήρωμα χωρίς όρια |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | Παίρνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | Παίρνει το ολοκλήρωμα |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/group/#) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας παρενθετικό αγκύλιο στο κάτω μέρος |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως παρενθετικό αγκύλιο στο κάτω μέρος ή άλλο |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/to_border_box/#) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-πλαίσιο |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-πλαίσιο |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/to_math_array/#) | Τοποθετεί σε κάθετη σειρά |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/accent/#char) | Ορίζει σημάδι τονισμού (χαρακτήρας πάνω από αυτό το στοιχείο) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/overbar/#) | Ορίζει μπάρα στην κορυφή αυτού του στοιχείου |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/underbar/#) | Ορίζει μπάρα στο κάτω μέρος αυτού του στοιχείου |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/to_box/#) | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό πλαίσιο (λογική ομαδοποίηση) <br/> που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλου τμήματος μαθηματικού κειμένου.<br/> Ένα πλαίσιο μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, <br/> να λειτουργήσει ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπει αλλαγές γραμμής εντός. |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/mathphantom/get_children/#) | Λαμβάνει τα στοιχεία-παιδιά |

### Δείτε επίσης
* κλάση [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)
* κλάση [`MathPhantom`](/slides/python-net/el/aspose.slides.mathtext/mathphantom)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)