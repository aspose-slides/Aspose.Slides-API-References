---
title: MathematicalText class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.mathtext/mathematicaltext/
---
## Κλάση MathematicalText

Μαθηματικό κείμενο

**Inheritance:**[`MathematicalText`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext) → [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)

Ο τύπος MathematicalText εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/__init__/#) | Προεπιλεγμένος κατασκευαστής (δημιουργεί τιμή String.Empty) |
| [`__init__(self, math_symbol)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/__init__/#char) | Δημιουργεί MathText με ένα μόνο σύμβολο |
| [`__init__(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/__init__/#str) | Δημιουργεί MathematicalText από κείμενο |
| [`__init__(self, math_text, portion_format)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/__init__/#str-iportionformat) | Δημιουργεί MathematicalText από κείμενο και ρυθμίσεις μορφοποίησης |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`value`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/value/) | Τιμή κειμένου |
| [`format`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/format/) | Ιδιότητες μορφοποίησης κειμένου |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/join/#imathelement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί έναν μαθηματικό μπλοκ |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/join/#str) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί έναν μαθηματικό μπλοκ |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/divide/#imathelement) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/divide/#str) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/divide/#imathelement-mathfractiontypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/divide/#str-mathfractiontypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/enclose/#) | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/enclose/#char-char) | Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/function/#imathelement) | Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/function/#str) | Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#imathelement) | Λαμβάνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#str) | Λαμβάνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsofoneargument) | Λαμβάνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Λαμβάνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Λαμβάνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/set_subscript/#imathelement) | Δημιουργεί υπό δείκτη |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/set_subscript/#str) | Δημιουργεί υπό δείκτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/set_superscript/#imathelement) | Δημιουργεί υψηλό δείκτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/set_superscript/#str) | Δημιουργεί υψηλό δείκτη |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#imathelement-imathelement) | Δημιουργεί υπό δείκτη και υψηλό δείκτη στα δεξιά |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#str-str) | Δημιουργεί υπό δείκτη και υψηλό δείκτη στα δεξιά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#imathelement-imathelement) | Δημιουργεί υπό δείκτη και υψηλό δείκτη στα αριστερά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#str-str) | Δημιουργεί υπό δείκτη και υψηλό δείκτη στα αριστερά |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/radical/#imathelement) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/radical/#str) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#imathelement) | Λαμβάνει άνω όριο |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#str) | Λαμβάνει άνω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#imathelement) | Λαμβάνει κάτω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#str) | Λαμβάνει κάτω όριο |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-imathelement-imathelement) | Δημιουργεί τελεστή N-αρι |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-str-str) | Δημιουργεί τελεστή N-αρι |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes) | Λαμβάνει το ολοκλήρωμα χωρίς όρια |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str-mathlimitlocations) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str) | Λαμβάνει το ολοκλήρωμα |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/group/#) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας αριστερή αγκύλη |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/group/#char-mathtopbotpositions-mathtopbotpositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης, όπως η αριστερή αγκύλη ή άλλον |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/to_border_box/#) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περιθώριο |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περιθώριο |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/to_math_array/#) | Τοποθετεί σε κατακόρυφο πίνακα |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/accent/#char) | Ορίζει σημείο τόνου (χαρακτήρας πάνω από αυτό το στοιχείο) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/overbar/#) | Ορίζει γραμμή πάνω από αυτό το στοιχείο |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/underbar/#) | Ορίζει γραμμή κάτω από αυτό το στοιχείο |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/to_box/#) | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό πλαίσιο (λογική ομαδοποίηση) <br/>            το οποίο χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης εμφάνισης μαθηματικού κειμένου.<br/>            Ένα αντικείμενο σε πλαίσιο μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, <br/>            να λειτουργήσει ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπει αλλαγές γραμμής εντός. |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext/get_children/#) |  |

### Δείτε επίσης
* κλάση [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)
* κλάση [`MathematicalText`](/slides/python-net/el/aspose.slides.mathtext/mathematicaltext)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)