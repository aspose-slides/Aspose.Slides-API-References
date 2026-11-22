---
title: MathBlock class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.mathtext/mathblock/
---
## MathBlock κλάση

Καθορίζει μια παρουσία μαθηματικού κειμένου που περιλαμβάνεται σε ένα MathParagraph και ξεκινά σε δική του γραμμή. Όλες οι μαθηματικές ζώνες, συμπεριλαμβανομένων εξισώσεων, εκφράσεων, πινάκων εξισώσεων ή εκφράσεων και τύπων, αντιπροσωπεύονται από μπλοκ μαθηματικού.

**Κληρονομικότητα:**[`MathBlock`](/slides/python-net/el/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)

Ο τύπος MathBlock εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/__init__/#) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathBlock. |
| [`__init__(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Δημιουργεί ένα νέο μαθηματικό μπλοκ και τοποθετεί το καθορισμένο στοιχείο μέσα του |
| [`__init__(self, math_elements)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`count`](/slides/python-net/el/aspose.slides.mathtext/mathblock/count/) | Αποκτά τον αριθμό των παιδικών μαθηματικών στοιχείων που περιέχονται πραγματικά στη συλλογή.<br/>            Μόνο για ανάγνωση **int**. |
| [`is_read_only`](/slides/python-net/el/aspose.slides.mathtext/mathblock/is_read_only/) | Επιστρέφει false επειδή η συλλογή παιδικών στοιχείων μπορεί να τροποποιηθεί. |

Αποκτά ή ορίζει το IMathElement στον καθορισμένο δείκτη.

## Δεικτοδότης

| Όνομα | Περιγραφή |
| :- | :- |
| [`[index]`](/slides/python-net/el/aspose.slides.mathtext/mathblock/__getitem__/) | Ο μηδενικός δείκτης του αντικειμένου |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/join/#imathelement) | Ενώνει ένα μαθηματικό στοιχείο με αυτό το μαθηματικό μπλοκ |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/join/#str) | Ενώνει ένα μαθηματικό κείμενο με αυτό το μαθηματικό μπλοκ |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/divide/#imathelement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/divide/#str) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/enclose/#) | Περικλείει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/enclose/#char-char) | Περικλείει τα παιδικά στοιχεία αυτού του μπλοκ σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως περιθώριο |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Περικλείει τα παιδικά στοιχεία αυτού του μπλοκ σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους ως περιθώριο<br/>            και οριοθετεί με χαρακτήρα διαχωρισμού |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/function/#imathelement) | Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα συνάρτησης |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/function/#str) | Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα συνάρτησης |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα και καθορισμένο επιπλέον όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα και καθορισμένο επιπλέον όρισμα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Δημιουργεί δείκτη |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/set_subscript/#str) | Δημιουργεί δείκτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Δημιουργεί εκθέτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/set_superscript/#str) | Δημιουργεί εκθέτη |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/radical/#imathelement) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/radical/#str) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Λαμβάνει άνω όριο |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Λαμβάνει άνω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Λαμβάνει κάτω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Λαμβάνει κάτω όριο |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Δημιουργεί τελεστή N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Δημιουργεί τελεστή N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Λαμβάνει το ολοκλήρωμα χωρίς όρια |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Λαμβάνει το ολοκλήρωμα |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/group/#) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια άγκυρα κάτω |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως η άγκυρα κάτω ή άλλον |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/to_border_box/#) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/to_math_array/#) | Τοποθετεί τα παιδικά στοιχεία σε κάθετη διάταξη |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/accent/#char) | Ορίζει χαρακτήρα τονισμό (χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/overbar/#) | Ορίζει μπάρα στην κορυφή αυτού του στοιχείου |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/underbar/#) | Ορίζει μπάρα στο κάτω μέρος αυτού του στοιχείου |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/to_box/#) | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό πλαίσιο (λογική ομαδοποίηση) <br/>            που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης παρουσίασης μαθηματικού κειμένου.<br/>            Ένα αντικείμενο σε πλαίσιο μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, <br/>            να λειτουργήσει ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπει αλλαγές γραμμής εντός. |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/get_children/#) | Αποκτά παιδικά στοιχεία |
| [`add(self, item)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/add/#imathelement) | Προσθέτει ένα μαθηματικό στοιχείο στο τέλος της συλλογής. |
| [`clear(self)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/clear/#) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [`contains(self, item)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/contains/#imathelement) | Καθορίζει αν η συλλογή περιέχει μια συγκεκριμένη τιμή. |
| [`copy_to(self, array, array_index)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Αντιγράφει σε καθορισμένο πίνακα. |
| [`remove(self, item)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/remove/#imathelement) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [`index_of(self, item)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Καθορίζει το δείκτη ενός συγκεκριμένου μαθηματικού στοιχείου στη συλλογή. |
| [`insert(self, index, item)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Εισάγει ένα MathElement στη συλλογή στον καθορισμένο δείκτη. |
| [`remove_at(self, index)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/remove_at/#int) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [`join_block(self, other)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Ενώνει ένα άλλο μαθηματικό μπλοκ με αυτό. |
| [`delimit(self, separator_character)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/delimit/#char) | Οριοθετεί τα παιδικά στοιχεία με χαρακτήρα διαχωριστή (χωρίς τις αγκύλες) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/el/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Αποθηκεύει το περιεχόμενο αυτού του [`MathBlock`](/slides/python-net/el/aspose.slides.mathtext/mathblock) ως MathML |

### Δείτε επίσης
* κλάση [`MathBlock`](/slides/python-net/el/aspose.slides.mathtext/mathblock)
* κλάση [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)