---
title: MathArray class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.mathtext/matharray/
---
## MathArray κλάση

Καθορίζει έναν κάθετο πίνακα εξισώσεων ή οποιωνδήποτε μαθηματικών αντικειμένων

**Κληρονομικότητα:**[`MathArray`](/slides/python-net/el/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)

Ο τύπος MathArray εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/el/aspose.slides.mathtext/matharray/__init__/#imathelement) | Δημιουργεί έναν μαθηματικό πίνακα και τοποθετεί το καθορισμένο στοιχείο σε αυτό |
| [`__init__(self, elements)`](/slides/python-net/el/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`arguments`](/slides/python-net/el/aspose.slides.mathtext/matharray/arguments/) | Το σύνολο των στοιχείων του πίνακα |
| [`base_justification`](/slides/python-net/el/aspose.slides.mathtext/matharray/base_justification/) | Καθορίζει την στοίχιση του πίνακα σε σχέση με το περιβάλλον κείμενο<br/>            Το κείμενο εκτός του πίνακα μπορεί να στοιχίζεται με το κάτω, το πάνω ή το κεντρικό μέρος ενός αντικειμένου πίνακα.<br/>            Προεπιλεγμένη τιμή: Κέντρο |
| [`maximum_distribution`](/slides/python-net/el/aspose.slides.mathtext/matharray/maximum_distribution/) | Μέγιστη κατανομή<br/>            Όταν είναι true, ο πίνακας διανέμεται στην μέγιστη πλάτος του στοιχείου που τον περιέχει (σελίδα, στήλη, κελί κ.λπ.). |
| [`object_distribution`](/slides/python-net/el/aspose.slides.mathtext/matharray/object_distribution/) | Κατανομή αντικειμένου<br/>            Όταν είναι true, τα περιεχόμενα του πίνακα διανέμονται στην μέγιστη πλάτος του αντικειμένου του πίνακα. |
| [`row_spacing_rule`](/slides/python-net/el/aspose.slides.mathtext/matharray/row_spacing_rule/) | Ο τύπος κάθετης απόστασης μεταξύ των στοιχείων του πίνακα<br/>            Προεπιλογή: SingleLineGap |
| [`row_spacing`](/slides/python-net/el/aspose.slides.mathtext/matharray/row_spacing/) | Απόσταση μεταξύ των γραμμών ενός πίνακα<br/>            Χρησιμοποιείται μόνο όταν το RowSpacingRule ορίζεται σε 3 Exactly, οπότε η μονάδα μέτρησης είναι σημεία<br/>            ή Multiple, όπου η μονάδα μέτρησης είναι μισές γραμμές.<br/>            Προεπιλογή: 0 |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/matharray/join/#imathelement) | Σανδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/matharray/join/#str) | Σανδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/matharray/divide/#imathelement) | Δημιουργεί μια κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/matharray/divide/#str) | Δημιουργεί μια κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | Δημιουργεί μια κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | Δημιουργεί μια κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/matharray/enclose/#) | Τοποθετεί ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/matharray/enclose/#char-char) | Τοποθετεί ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαισίωση |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/matharray/function/#imathelement) | Λαμβάνει μια λειτουργία ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα της λειτουργίας |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/matharray/function/#str) | Λαμβάνει μια λειτουργία ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα της λειτουργίας |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | Λαμβάνει τη καθορισμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | Λαμβάνει τη καθορισμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | Λαμβάνει τη καθορισμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Λαμβάνει τη καθορισμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο επιπρόσθετο όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Λαμβάνει τη καθορισμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο επιπρόσθετο όρισμα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | Δημιουργεί δείκτη |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/matharray/set_subscript/#str) | Δημιουργεί δείκτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | Δημιουργεί εκθέτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/matharray/set_superscript/#str) | Δημιουργεί εκθέτη |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/matharray/radical/#imathelement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/matharray/radical/#str) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | Λαμβάνει άνω όριο |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/matharray/set_upper_limit/#str) | Λαμβάνει άνω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | Λαμβάνει κάτω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/matharray/set_lower_limit/#str) | Λαμβάνει κάτω όριο |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | Δημιουργεί έναν N-ary τελεστή |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | Δημιουργεί έναν N-ary τελεστή |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | Λαμβάνει το ολοκλήρωμα χωρίς όρια |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | Λαμβάνει το ολοκλήρωμα |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/matharray/group/#) | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας μια αγκύλη |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης όπως η κάτω καμπυλή αγκύλη ή κάποιον άλλο |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/matharray/to_border_box/#) | Τοποθετεί αυτό το στοιχείο σε ένα πλαίσιο-περίγραμμα |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Τοποθετεί αυτό το στοιχείο σε ένα πλαίσιο-περίγραμμα |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/matharray/to_math_array/#) | Τοποθετεί σε κάθετο πίνακα |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/matharray/accent/#char) | Ορίζει σημείο τόνου (έναν χαρακτήρα πάνω από αυτό το στοιχείο) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/matharray/overbar/#) | Ορίζει μια μπάρα στην κορυφή αυτού του στοιχείου |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/matharray/underbar/#) | Ορίζει μια μπάρα στο κάτω μέρος αυτού του στοιχείου |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/matharray/to_box/#) | Τοποθετεί αυτό το στοιχείο σε ένα μη οπτικό κουτί (λογική ομαδοποίηση) <br/>            το οποίο χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης εμφάνισης μαθηματικού κειμένου.<br/>            Ένα κουτιού αντικείμενο μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, <br/>            να λειτουργήσει ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί έτσι ώστε να μην επιτρέπεται αλλαγή γραμμής μέσα σε αυτό. |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/matharray/get_children/#) | Λαμβάνει τα στοιχεία παιδιών |

### Δείτε επίσης
* κλάση [`MathArray`](/slides/python-net/el/aspose.slides.mathtext/matharray)
* κλάση [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)