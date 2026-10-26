---
title: MathAccent class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.mathtext/mathaccent/
---
## MathAccent κλάση

Καθορίζει τη συνάρτηση τονισμού, που αποτελείται από μια βάση και ένα συνδυαστικό διακριτικό σημάδι
            Example: 𝑎́

**Inheritance:**[`MathAccent`](/slides/python-net/el/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)

Ο τύπος MathAccent εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | Δημιουργεί έναν μαθηματικό τονισμό που εφαρμόζεται σε ένα καθορισμένο μαθηματικό στοιχείο με την προεπιλεγμένη τιμή χαρακτήρα τονισμού |
| [`__init__(self, element, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | Δημιουργεί έναν μαθηματικό τονισμό που εφαρμόζεται σε ένα καθορισμένο μαθηματικό στοιχείο |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`base`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/base/) | Το όρισμα στο οποίο εφαρμόστηκε ο τονισμός |
| [`character`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/character/) | Χαρακτήρας Τονισμού<br/>            Η τιμή πρέπει να βρίσκεται εντός του εύρους (U+0300–U+036F) ή (U+20D0–U+20EF)<br/>            Προεπιλεγμένη τιμή: Συνδυαστικός Καμπύλωση Τόνου (U+0302) |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/join/#imathelement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/join/#str) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/divide/#imathelement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/divide/#str) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/enclose/#) | Τοποθετεί ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/enclose/#char-char) | Τοποθετεί ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/function/#imathelement) | Δημιουργεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτή την παρουσία ως όνομα συνάρτησης |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/function/#str) | Δημιουργεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτή την παρουσία ως όνομα συνάρτησης |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | Χρησιμοποιεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | Χρησιμοποιεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | Χρησιμοποιεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Χρησιμοποιεί τη συγκεκριμένη συνάρτηση με αυτή την παρουσία ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Χρησιμοποιεί τη συγκεκριμένη συνάρτηση με αυτή την παρουσία ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | Δημιουργεί δείκτη |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/set_subscript/#str) | Δημιουργεί δείκτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | Δημιουργεί εκθέτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/set_superscript/#str) | Δημιουργεί εκθέτη |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/radical/#imathelement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/radical/#str) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | Παίρνει το άνω όριο |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | Παίρνει το άνω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | Παίρνει το κάτω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | Παίρνει το κάτω όριο |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | Δημιουργεί έναν N-αρικό τελεστή |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | Δημιουργεί έναν N-αρικό τελεστή |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Υπολογίζει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | Υπολογίζει το ολοκλήρωμα |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | Υπολογίζει το ολοκλήρωμα χωρίς όρια |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | Υπολογίζει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | Υπολογίζει το ολοκλήρωμα |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/group/#) | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης όπως η κάτω αγκύλη ή άλλον |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/to_border_box/#) | Τοποθετεί αυτό το στοιχείο σε ένα πλαίσιο-περίγραμμα |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Τοποθετεί αυτό το στοιχείο σε ένα πλαίσιο-περίγραμμα |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/to_math_array/#) | Τοποθετεί σε κατακόρυφη διάταξη |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/accent/#char) | Ορίζει ένα σημάδι τονισμού (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/overbar/#) | Ορίζει μια γραμμή στην κορυφή αυτού του στοιχείου |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/underbar/#) | Ορίζει μια γραμμή στο κάτω μέρος αυτού του στοιχείου |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/to_box/#) | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό πλαίσιο (λογική ομαδοποίηση) <br/>            που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλου κειμένου μαθηματικού τύπου.<br/>            Ένα αντικείμενο σε πλαίσιο μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, <br/>            να λειτουργήσει ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπεται αλλαγή γραμμής εντός. |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/mathaccent/get_children/#) | Λαμβάνει τα στοιχεία-παιδιά |


### Δείτε επίσης
* κλάση [`MathAccent`](/slides/python-net/el/aspose.slides.mathtext/mathaccent)
* κλάση [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)