---
title: MathDelimiter class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter κλάση

Καθορίζει το αντικείμενο διαχωριστικού, που αποτελείται από χαρακτήρες έναρξης και λήξης (όπως παρενθέσεις, 
            αγκύλες, αγκύλες και κατακόρυφες γραμμές), και ένα ή περισσότερα μαθηματικά στοιχεία μέσα, χωρισμένα με έναν καθορισμένο χαρακτήρα.
            Παραδείγματα: (𝑥2); [𝑥2|𝑦2]

**Κληρονομικότητα:**[`MathDelimiter`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)

Ο τύπος MathDelimiter εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Αρχικοποιεί το MathDelimiter με το καθορισμένο στοιχείο ως μοναδικό βασικό όρισμα |

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/arguments/) | Ένα ή περισσότερα μαθηματικά στοιχεία χωρισμένα από χαρακτήρες διαχωριστικού |
| [`beginning_character`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Ο Χαρακτήρας Αρχής Διαχωριστικού καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα διαχωριστικού. <br/>            Οι μαθηματικοί διαχωριστικοί είναι περικλειστικοί χαρακτήρες όπως παρενθέσεις, αγκύλες και άγκιστρα.<br/>            Η προεπιλογή: '('. |
| [`separator_character`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/separator_character/) | Ο Χαρακτήρας Διαχωριστικού Διαχωριστή καθορίζει τον χαρακτήρα που χωρίζει τα ορίσματα στο αντικείμενο διαχωριστικού. <br/>            Η προεπιλογή: '\|'. |
| [`ending_character`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/ending_character/) | Ο Χαρακτήρας Λήξης Διαχωριστικού καθορίζει τον τελικό, ή κλειστό, χαρακτήρα διαχωριστικού. <br/>            Οι μαθηματικοί διαχωριστικοί είναι περικλειστικοί χαρακτήρες όπως παρενθέσεις, αγκύλες και άγκιστρα.<br/>            Η προεπιλογή: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Καθορίζει την επέκταση των BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Όταν είναι true, οι διαχωριστικοί μεγαλώνουν κατακόρυφα ώστε να ταιριάζουν με το ύψος του τελεστέου.<br/>            Η προεπιλεγμένη τιμή είναι true |
| [`delimiter_shape`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Καθορίζει το σχήμα των διαχωριστικών στο αντικείμενο διαχωριστικού. <br/>            Όταν είναι MathDelimiterShape.Centered, τα διαχωριστικά κεντρώνονται γύρω από τον άξονα των μαθηματικών του κειμένου <br/>            και προσαρμόζονται ώστε να ταιριάζουν με το συνολικό ύψος του περιεχομένου τους.<br/>            Όταν είναι MathDelimiterShape.Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους. |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/join/#str) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Δημιουργεί κλασματικό με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/divide/#str) | Δημιουργεί κλασματικό με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Δημιουργεί κλασματικό του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Δημιουργεί κλασματικό του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαισίωση |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/enclose/#) | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Παίρνει μια συνάρτηση από ένα όρισμα χρησιμοποιώντας αυτήν την περίπτωση ως όνομα λειτουργίας |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/function/#str) | Παίρνει μια συνάρτηση από ένα όρισμα χρησιμοποιώντας αυτήν την περίπτωση ως όνομα λειτουργίας |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την περίπτωση ως όρισμα |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την περίπτωση ως όρισμα |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την περίπτωση ως όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την περίπτωση ως όρισμα και συγκεκριμένο πρόσθετο όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την περίπτωση ως όρισμα και συγκεκριμένο πρόσθετο όρισμα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Δημιουργεί δείκτη |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Δημιουργεί δείκτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Δημιουργεί εκθέτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Δημιουργεί εκθέτη |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Καθορίζει τη μαθηματική ρίζα του δοθέντος βαθμού από το καθορισμένο όρισμα. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/radical/#str) | Καθορίζει τη μαθηματική ρίζα του δοθέντος βαθμού από το καθορισμένο όρισμα. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Παίρνει άνω όριο |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Παίρνει άνω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Παίρνει κάτω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Παίρνει κάτω όριο |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Δημιουργεί έναν N-ary τελεστή |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Δημιουργεί έναν N-ary τελεστή |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Παίρνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Παίρνει το ολοκλήρωμα |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Παίρνει το ολοκλήρωμα χωρίς όρια |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Παίρνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Παίρνει το ολοκλήρωμα |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/group/#) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως η κάτω αγκύλη ή άλλον |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο περιγράμματος |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο περιγράμματος |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Τοποθετεί σε κατακόρυφη σειρά |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/accent/#char) | Ορίζει σημάδι τόνου (χαρακτήρα πάνω από αυτό το στοιχείο) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/overbar/#) | Τοποθετεί μια γραμμή στην κορυφή αυτού του στοιχείου |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/underbar/#) | Τοποθετεί μια γραμμή στο κάτω μέρος αυτού του στοιχείου |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/to_box/#) | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό πλαίσιο (λογική ομαδοποίηση) <br/>            το οποίο χρησιμοποιείται για την ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης εμφάνισης μαθηματικού κειμένου.<br/>            Ένα πλαίσιο αντικείμενο μπορεί (για παράδειγμα) να λειτουργήσει ως προσομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, <br/>            να λειτουργήσει ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπει αλλαγές γραμμής εντός. |
| [`delimit(self, separator_character)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Διαχωρίζει τα ορίσματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα διαχωριστικού |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/get_children/#) | Λαμβάνει τα παιδικά στοιχεία |


### Δείτε επίσης
* κλάση [`MathDelimiter`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter)
* κλάση [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)