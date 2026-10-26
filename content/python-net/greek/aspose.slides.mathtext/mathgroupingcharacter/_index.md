---
title: MathGroupingCharacter class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter κλάση

Καθορίζει ένα σύμβολο ομαδοποίησης πάνω ή κάτω από μια έκφραση, συνήθως για να τονίσει τη σχέση μεταξύ των στοιχείων

**Κληρονομικότητα:**[`MathGroupingCharacter`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)

Ο τύπος MathGroupingCharacter εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathGroupingCharacter <br/>            με το προεπιλεγμένο χαρακτήρα ομαδοποίησης U+23DF (BOTTOM CURLY BRACKET) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathGroupingCharacter. |

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/base/) | Βασικό όρισμα |
| [`character`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/character/) | Χαρακτήρας ομαδοποίησης<br/>            Προεπιλεγμένη τιμή: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/position/) | Θέση του χαρακτήρα ομαδοποίησης.<br/>            Προεπιλογή: Κάτω |
| [`vertical_justification`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | Κατακόρυφη στοίχιση του χαρακτήρα ομαδοποίησης.<br/>            Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη βάση γραμμής.<br/>            Για παράδειγμα, όταν ο χαρακτήρας ομαδοποίησης βρίσκεται πάνω από το αντικείμενο, <br/>            VerticalJustification του Top σημαίνει ότι η κορυφή του αντικειμένου βρίσκεται στη βάση γραμμής;<br/>            όταν VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου βρίσκεται στη βάση γραμμής<br/>            Προεπιλογή: Bottom για Position=Top, και Top για Position=Bottom |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | Δημιουργεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το στιγμιότυπο ως όνομα συνάρτησης |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | Δημιουργεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το στιγμιότυπο ως όνομα συνάρτησης |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | Δημιουργεί την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το στιγμιότυπο ως όρισμα |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | Δημιουργεί την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το στιγμιότυπο ως όρισμα |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | Δημιουργεί την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το στιγμιότυπο ως όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Δημιουργεί την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το στιγμιότυπο ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Δημιουργεί την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το στιγμιότυπο ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | Δημιουργεί δείκτη |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | Δημιουργεί δείκτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | Δημιουργεί εκθέτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | Δημιουργεί εκθέτη |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | Δημιουργεί άνω όριο |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | Δημιουργεί άνω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | Δημιουργεί κάτω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | Δημιουργεί κάτω όριο |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Δημιουργεί έναν N-ary τελεστή |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | Δημιουργεί έναν N-ary τελεστή |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Δημιουργεί το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | Δημιουργεί το ολοκλήρωμα |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | Δημιουργεί το ολοκλήρωμα χωρίς όρια |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Δημιουργεί το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | Δημιουργεί το ολοκλήρωμα |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/group/#) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης όπως η κάτω αγκύλη ή άλλος |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-πλευρά |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-πλευρά |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | Βάζει σε κατακόρυφο σύνολο |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | Ορίζει ένα σημάδι τόνου (χαρακτήρας στην κορυφή αυτού του στοιχείου) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | Ορίζει μπάρα στην κορυφή αυτού του στοιχείου |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | Ορίζει μπάρα στο κάτω μέρος αυτού του στοιχείου |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | Τοποθετεί αυτό το στοιχείο σε μη οπτικό πλαίσιο (λογική ομαδοποίηση) <br/>            που χρησιμοποιείται για να ομαδοποιήσει στοιχεία μιας εξίσωσης ή άλλης παρουσίας μαθηματικού κειμένου.<br/>            Ένα πλαίσιο αντικείμενο μπορεί (για παράδειγμα) να λειτουργήσει ως εξομιλητής τελεστή με ή χωρίς σημείο ευθυγράμμισης, <br/>            να λειτουργήσει ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί έτσι ώστε να μην επιτρέπεται αλλαγή γραμμής εντός. |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | Λαμβάνει τα στοιχεία τέκνα |

### Δείτε επίσης
* κλάση [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)
* κλάση [`MathGroupingCharacter`](/slides/python-net/el/aspose.slides.mathtext/mathgroupingcharacter)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)