---
title: MathNaryOperator class
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator κλάση

Καθορίζει ένα N-ary μαθηματικό αντικείμενο, όπως Summation και Integral.  
Αποτελείται από έναν τελεστή, μια βάση (ή όρισμα) και προαιρετικά άνω και κάτω όρια.  
Παραδείγματα N-ary τελεστών είναι: Summation, Union, Intersection, Integral

**Inheritance:**[`MathNaryOperator`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)

Ο τύπος MathNaryOperator εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathNaryOperator. |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`base`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/base/) | Βασικό επιχείρημα |
| [`subscript`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/subscript/) | Καθορίζει ένα υπογράφημα επιχείρημα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το κάτω όριο |
| [`superscript`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/superscript/) | Καθορίζει ένα εκγράφημα επιχείρημα που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το άνω όριο |
| [`operator`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/operator/) | Nary Operator Character<br/>            For example: '∑', '∫' |
| [`limit_location`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/limit_location/) | Η θέση των ορίων (υπογράφημα και εκγράφημα) |
| [`grow_to_match_operand_height`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα ώστε να ταιριάζει στο ύψος του τελεστέου |
| [`hide_subscript`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | Απόκρυψη υπογράφηματος |
| [`hide_superscript`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | Απόκρυψη εκγράφηματος |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/join/#str) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/divide/#str) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/enclose/#) | Τοποθετεί ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | Τοποθετεί ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | Αναλαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα συνάρτησης |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/function/#str) | Αναλαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα συνάρτησης |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | Αναλαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | Αναλαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | Αναλαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Αναλαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα και επιπλέον καθορισμένο όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Αναλαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα και επιπλέον καθορισμένο όρισμα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | Δημιουργεί υπογράφημα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | Δημιουργεί υπογράφημα |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | Δημιουργεί εκγράφημα |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | Δημιουργεί εκγράφημα |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | Δημιουργεί υπογράφημα και εκγράφημα στα δεξιά |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | Δημιουργεί υπογράφημα και εκγράφημα στα δεξιά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | Δημιουργεί υπογράφημα και εκγράφημα στα αριστερά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | Δημιουργεί υπογράφημα και εκγράφημα στα αριστερά |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/radical/#str) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | Αναλαμβάνει άνω όριο |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | Αναλαμβάνει άνω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | Αναλαμβάνει κάτω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | Αναλαμβάνει κάτω όριο |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | Δημιουργεί έναν N-ary τελεστή |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | Δημιουργεί έναν N-ary τελεστή |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Αναλαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | Αναλαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | Αναλαμβάνει το ολοκλήρωμα χωρίς όρια |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | Αναλαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | Αναλαμβάνει το ολοκλήρωμα |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/group/#) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας άγκυρα κάτω |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως άγκυρα κάτω ή άλλο |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | Τοποθετεί σε κάθετη σειρά |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/accent/#char) | Ορίζει σημείο τόνου (χαρακτήρας στην κορυφή αυτού του στοιχείου) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/overbar/#) | Ορίζει μπάρα πάνω από αυτό το στοιχείο |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/underbar/#) | Ορίζει μπάρα κάτω από αυτό το στοιχείο |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/to_box/#) | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) <br/>            που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλου μαθηματικού κειμένου.<br/>            Ένα κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, <br/>            να λειτουργήσει ως σημείο διάσπασης γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπει στοίχιση εντός. |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator/get_children/#) | Λαμβάνει τα παιδικά στοιχεία |


### Δείτε επίσης
* κλάση [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)
* κλάση [`MathNaryOperator`](/slides/python-net/el/aspose.slides.mathtext/mathnaryoperator)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)