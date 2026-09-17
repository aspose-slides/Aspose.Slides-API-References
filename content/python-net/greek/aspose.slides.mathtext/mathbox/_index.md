---
title: MathBox class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.mathtext/mathbox/
---
## MathBox κλάση

Καθορίζει τη λογική περιττοποίηση (συσκευασία) του μαθηματικού στοιχείου.
            Για παράδειγμα, ένα αντικείμενο σε κουτί μπορεί να λειτουργήσει ως προσομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης,
            να λειτουργήσει ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί έτσι ώστε να μην επιτρέπονται αλλαγές γραμμής εντός του.
            Για παράδειγμα, ο τελεστής "==" πρέπει να τοποθετηθεί σε κουτί για να αποτρέπεται η αλλαγή γραμμής.

**Inheritance:**[`MathBox`](/slides/python-net/el/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)

Ο τύπος MathBox εκθέτει τα ακόλουθη μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Αρχικοποιεί το MathBox με το καθορισμένο στοιχείο ως όρισμα |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`base`](/slides/python-net/el/aspose.slides.mathtext/mathbox/base/) | Βασικό όρισμα |
| [`operator_emulator`](/slides/python-net/el/aspose.slides.mathtext/mathbox/operator_emulator/) | Προσομοιωτής τελεστή.<br/>            Όταν είναι true, το κουτί και τα περιεχόμενα του συμπεριφέρονται ως ένας ενιαίος τελεστής και κληρονομούν τις ιδιότητες ενός τελεστή. <br/>            Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να λειτουργήσει ως σημείο αλλαγής γραμμής και μπορεί να ευθυγραμμιστεί με άλλους τελεστές.<br/>            Οι προσομοιωτές τελεστών χρησιμοποιούνται συχνά όταν ένα ή περισσότερα σύμβολα συνδυάζονται για να σχηματίσουν έναν τελεστή, όπως το '=='.<br/>            Προεπιλεγμένη τιμή: false |
| [`no_break`](/slides/python-net/el/aspose.slides.mathtext/mathbox/no_break/) | Χωρίς διακοπή<br/>            Αυτή η ιδιότητα καθορίζει την ιδιότητα "αδιάσπαστο" στο κουτί αντικειμένου. Όταν είναι true, δεν μπορούν να εμφανιστούν αλλαγές γραμμής εντός του κουτιού.<br/>            Αυτό μπορεί να είναι σημαντικό για προσομοιωτές τελεστών που αποτελούνται από περισσότερους από έναν δυαδικούς τελεστές. <br/>            Όταν αυτό το στοιχείο δεν καθορίζεται, μπορούν να εμφανιστούν διακοπές μέσα στο κουτί.<br/>            Προεπιλογή: true |
| [`differential`](/slides/python-net/el/aspose.slides.mathtext/mathbox/differential/) | Διαφορικό<br/>            Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ., 𝑑𝑥 σε ολοκληρωτέο) και λαμβάνει το κατάλληλο <br/>            οριζόντιο διάστημα για το μαθηματικό διαφορικό.<br/>            Προεπιλογή: false |
| [`alignment_point`](/slides/python-net/el/aspose.slides.mathtext/mathbox/alignment_point/) | Όταν είναι true, αυτός ο προσομοιωτής τελεστή λειτουργεί ως σημείο ευθυγράμμισης· δηλαδή, <br/>            τα ορισμένα σημεία ευθυγράμμισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό.<br/>            Προεπιλογή: false |
| [`explicit_break`](/slides/python-net/el/aspose.slides.mathtext/mathbox/explicit_break/) | Explicit break καθορίζει αν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, <br/>            ώστε η γραμμή να σπάσει στην αρχή του αντικειμένου box.<br/>            Καθορίζει τον αριθμό του τελεστή στην προηγούμενη γραμμή μαθηματικού κειμένου που θα<br/>            χρησιμοποιηθεί ως σημείο ευθυγράμμισης για την τρέχουσα γραμμή μαθηματικού κειμένου<br/>            δυνατές τιμές: 1..255<br/>            Προεπιλογή: 0 (χωρίς ρητή διακοπή) |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/join/#imathelement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/join/#str) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/divide/#imathelement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/divide/#str) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/enclose/#) | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/enclose/#char-char) | Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως κάδρο |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/function/#imathelement) | Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτή την παρουσία ως όνομα συνάρτησης |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/function/#str) | Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτή την παρουσία ως όνομα συνάρτησης |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Δημιουργεί υποδείκτη |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/set_subscript/#str) | Δημιουργεί υποδείκτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Δημιουργεί εκθέτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/set_superscript/#str) | Δημιουργεί εκθέτη |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Δημιουργεί υποδείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Δημιουργεί υποδείκτη και εκθέτη στα δεξιά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Δημιουργεί υποδείκτη και εκθέτη στα αριστερά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Δημιουργεί υποδείκτη και εκθέτη στα αριστερά |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/radical/#imathelement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/radical/#str) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Λαμβάνει άνω όριο |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Λαμβάνει άνω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Λαμβάνει κάτω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Λαμβάνει κάτω όριο |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Δημιουργεί έναν N-οριακό τελεστή |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | Δημιουργεί έναν N-οριακό τελεστή |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Λαμβάνει το ολοκλήρωμα χωρίς όρια |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Λαμβάνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | Λαμβάνει το ολοκλήρωμα |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/group/#) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως η κάτω αγκύλη ή άλλον |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/to_border_box/#) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίβλημα |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίβλημα |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/to_math_array/#) | Τοποθετεί σε κάθετη διάταξη |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/accent/#char) | Ορίζει ένα τονικό σημείο (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/overbar/#) | Ορίζει μια γραμμή στην κορυφή αυτού του στοιχείου |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/underbar/#) | Ορίζει μια γραμμή στο κάτω μέρος αυτού του στοιχείου |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/to_box/#) | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) <br/>            το οποίο χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης παρουσίας μαθηματικού κειμένου.<br/>            Ένα αντικείμενο σε κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως προσομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, <br/>            να λειτουργήσει ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί έτσι ώστε να μην επιτρέπονται αλλαγές γραμμής εντός. |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/mathbox/get_children/#) | Λαμβάνει τα στοιχεία παιδιών |

### Δείτε επίσης
* κλάση [`MathBox`](/slides/python-net/el/aspose.slides.mathtext/mathbox)
* κλάση [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)