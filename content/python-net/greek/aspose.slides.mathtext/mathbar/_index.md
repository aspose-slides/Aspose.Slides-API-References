---
title: MathBar class
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides.mathtext/mathbar/
---
## MathBar κλάση

Καθορίζει τη συνάρτηση μπάρας, η οποία αποτελείται από ένα βασικό όρισμα και μια πάνω ή κάτω γραμμή

**Κληρονομικότητα:**[`MathBar`](/slides/python-net/el/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)

Ο τύπος MathBar εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/__init__/#imathelement) | Αρχικοποιεί το MathBar με πάνω μπάρα (Θέση: Κορυφή) |
| [`__init__(self, element, position)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | Αρχικοποιεί το MathBar με καθορισμένη θέση |

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/el/aspose.slides.mathtext/mathbar/base/) | Βασικό όρισμα |
| [`position`](/slides/python-net/el/aspose.slides.mathtext/mathbar/position/) | Θέση της γραμμής μπάρας. <br/>            Προεπιλογή: Κορυφή |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/join/#imathelement) | Ενώζει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/join/#str) | Ενώζει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/divide/#imathelement) | Δημιουργεί κλάσμα με αυτό το αριθμητή και καθορισμένο παρονομαστή |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/divide/#str) | Δημιουργεί κλάσμα με αυτό το αριθμητή και καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτό το αριθμητή και καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτό το αριθμητή και καθορισμένο παρονομαστή |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/enclose/#) | Τοποθετεί ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/enclose/#char-char) | Τοποθετεί ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες ως περιτύλιγμα |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/function/#imathelement) | Δέχεται συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα συνάρτησης |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/function/#str) | Δέχεται συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα συνάρτησης |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | Δέχεται την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | Δέχεται την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | Δέχεται την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Δέχεται την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα και επιπρόσθετο καθορισμένο όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Δέχεται την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα και επιπρόσθετο καθορισμένο όρισμα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | Δημιουργεί δείκτη |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/set_subscript/#str) | Δημιουργεί δείκτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | Δημιουργεί εκθέτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/set_superscript/#str) | Δημιουργεί εκθέτη |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/radical/#imathelement) | Καθορίζει τη μαθηματική ρίζα του δοθέντος βαθμού από το καθορισμένο όρισμα. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/radical/#str) | Καθορίζει τη μαθηματική ρίζα του δοθέντος βαθμού από το καθορισμένο όρισμα. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | Δέχεται άνω όριο |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | Δέχεται άνω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | Δέχεται κατώτερο όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | Δέχεται κατώτερο όριο |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | Δημιουργεί τελεστή N-αριου |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | Δημιουργεί τελεστή N-αριου |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Δέχεται το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | Δέχεται το ολοκλήρωμα |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | Δέχεται το ολοκλήρωμα χωρίς όρια |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | Δέχεται το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | Δέχεται το ολοκλήρωμα |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/group/#) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κατωφύση αγκύλη |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως η κατωφύση αγκύλη ή άλλον |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/to_border_box/#) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/to_math_array/#) | Τοποθετεί σε κατακόρυφη σειρά |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/accent/#char) | Ορίζει σημάδι τόνου (χαρακτήρας πάνω από αυτό το στοιχείο) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/overbar/#) | Ορίζει μπάρα στην κορυφή αυτού του στοιχείου |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/underbar/#) | Ορίζει μπάρα στο κάτω μέρος αυτού του στοιχείου |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/to_box/#) | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) <br/>            που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης μορφής μαθηματικού κειμένου.<br/>            Ένα αντικείμενο σε κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, <br/>            να λειτουργήσει ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπονται αλλαγές γραμμής εντός του. |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbar/get_children/#) | Λαμβάνει τα παιδικά στοιχεία |

### Δείτε επίσης
* κλάση [`MathBar`](/slides/python-net/el/aspose.slides.mathtext/mathbar)
* κλάση [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)