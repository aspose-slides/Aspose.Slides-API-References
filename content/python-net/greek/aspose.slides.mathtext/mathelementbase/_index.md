---
title: MathElementBase class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase κλάση

Βασική κλάση για IMathElement με την υλοποίηση ορισμένων μεθόδων που είναι κοινές σε όλες τις κληρονομημένες κλάσεις
For internal use only. Η κληρονομημένη κλάση πρέπει να είναι IMathElement.

Ο τύπος MathElementBase περιλαμβάνει τα παρακάτω μέλη:

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/join/#imathelement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/join/#str) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/divide/#imathelement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/divide/#str) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/divide/#imathelement-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/divide/#str-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/enclose/#) | Τοποθετεί ένα μαθηματικό στοιχείο σε παρένθεση |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/enclose/#char-char) | Τοποθετεί ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες, όπως παρένθεση ή άλλους χαρακτήρες ως πλαίσιο |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/function/#imathelement) | Δημιουργεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα της συνάρτησης |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/function/#str) | Δημιουργεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα της συνάρτησης |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#imathelement) | Δέχεται μια καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#str) | Δέχεται μια καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsofoneargument) | Δέχεται μια καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Δέχεται μια καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Δέχεται μια καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/set_subscript/#imathelement) | Δημιουργεί δείκτη |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/set_subscript/#str) | Δημιουργεί δείκτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/set_superscript/#imathelement) | Δημιουργεί εκθέτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/set_superscript/#str) | Δημιουργεί εκθέτη |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#str-str) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#str-str) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/radical/#imathelement) | Καθορίζει τη μαθηματική ρίζα του συγκεκριμένου βαθμού από το καθορισμένο όρισμα. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/radical/#str) | Καθορίζει τη μαθηματική ρίζα του συγκεκριμένου βαθμού από το καθορισμένο όρισμα. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/set_upper_limit/#imathelement) | Λαμβάνει άνω όριο |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/set_upper_limit/#str) | Λαμβάνει άνω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/set_lower_limit/#imathelement) | Λαμβάνει κάτω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/set_lower_limit/#str) | Λαμβάνει κάτω όριο |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-imathelement-imathelement) | Δημιουργεί έναν τελεστή N-ορίου |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-str-str) | Δημιουργεί έναν τελεστή N-ορίου |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes) | Λαμβάνει το ολοκλήρωμα χωρίς όρια |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str-mathlimitlocations) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str) | Λαμβάνει το ολοκλήρωμα |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/group/#) | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/group/#char-mathtopbotpositions-mathtopbotpositions) | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας ένα χαρακτήρα ομαδοποίησης όπως η κάτω αγκύλη ή άλλον |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/to_border_box/#) | Τοποθετεί αυτό το στοιχείο σε ένα πλαίσιο-περίγραμμα |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Τοποθετεί αυτό το στοιχείο σε ένα πλαίσιο-περίγραμμα |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/to_math_array/#) | Τοποθετεί σε κάθετη διάταξη |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/accent/#char) | Ορίζει ένα τονικό σημάδι (χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/overbar/#) | Τοποθετεί μια μπάρα στην κορυφή αυτού του στοιχείου |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/underbar/#) | Τοποθετεί μια μπάρα στο κάτω μέρος αυτού του στοιχείου |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/to_box/#) | Τοποθετεί αυτό το στοιχείο σε ένα μη οπτικό πλαίσιο (λογική ομαδοποίηση) <br/>            που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης παρουσίασης μαθηματικού κειμένου.<br/>            Ένα πλαίσιο αντικείμενο μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, <br/>            να λειτουργήσει ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπονται αλλαγές γραμμής εντός. |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase/get_children/#) |  |

### Δείτε επίσης
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)