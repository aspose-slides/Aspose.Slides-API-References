---
title: MathDelimiter class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter κλάση

Καθορίζει το αντικείμενο οριοθέτη, που αποτελείται από χαρακτήρες έναρξης και λήξης (όπως παρενθέσεις, αγκύλες, τετράγωνες αγκύλες και κάθετες γραμμές) και ένα ή περισσότερα μαθηματικά στοιχεία μέσα, χωρισμένα με συγκεκριμένο χαρακτήρα. Παραδείγματα: (𝑥2); [𝑥2|𝑦2]

**Κληρονομικότητα:**[`MathDelimiter`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)

Ο τύπος MathDelimiter εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Αρχικοποιεί το MathDelimiter με το καθορισμένο στοιχείο ως μοναδικό βασικό όρισμα |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`arguments`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/arguments/) | Ένα ή περισσότερα μαθηματικά στοιχεία χωρισμένα με χαρακτήρες οριοθέτη |
| [`beginning_character`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Ο χαρακτήρας έναρξης του οριοθέτη καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα του οριοθέτη. <br/>            Τα μαθηματικά οριοθέτες είναι χαρακτήρες που περικλείουν όπως παρενθέσεις, αγκύλες και αγκύλες.<br/>            Προεπιλογή: '('. |
| [`separator_character`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/separator_character/) | Ο χαρακτήρας διαχωριστικού του οριοθέτη καθορίζει τον χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο οριοθέτη. <br/>            Προεπιλογή: '\|'. |
| [`ending_character`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/ending_character/) | Ο χαρακτήρας λήξης του οριοθέτη καθορίζει τον τελικό, ή κλειστό, χαρακτήρα του οριοθέτη. <br/>            Τα μαθηματικά οριοθέτες είναι χαρακτήρες που περικλείουν όπως παρενθέσεις, αγκύλες και αγκύλες.<br/>            Προεπιλογή: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Καθορίζει την επέκταση των χαρακτήρων BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Όταν είναι true, οι οριοθέτες αυξάνονται κάθετα ώστε να ταιριάζουν με το ύψος του τελεστή τους.<br/>            Η προεπιλεγμένη τιμή είναι true |
| [`delimiter_shape`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Καθορίζει το σχήμα των οριοθετών στο αντικείμενο οριοθέτη. <br/>            Όταν είναι MathDelimiterShape.Centered, οι οριοθέτες κεντράρονται γύρω από τον άξονα μαθηματικού κειμένου <br/>            και προσαρμόζονται ώστε να ταιριάζουν με το πλήρες ύψος του περιεχομένου τους.<br/>            Όταν είναι MathDelimiterShape.Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/join/#str) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/divide/#str) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/enclose/#) | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαισίωση |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Δημιουργεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/function/#str) | Δημιουργεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Δημιουργεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Δημιουργεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Δημιουργεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Δημιουργεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και έναν καθορισμένο πρόσθετο όρισμα |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Δημιουργεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και έναν καθορισμένο πρόσθετο όρισμα |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Δημιουργεί δείκτη |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Δημιουργεί δείκτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Δημιουργεί εκθέτη |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Δημιουργεί εκθέτη |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη δεξιά |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Δημιουργεί δείκτη και εκθέτη δεξιά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Δημιουργεί δείκτη και εκθέτη αριστερά |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Δημιουργεί δείκτη και εκθέτη αριστερά |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/radical/#str) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Παίρνει το άνω όριο |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Παίρνει το άνω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Παίρνει το κάτω όριο |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Παίρνει το κάτω όριο |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Δημιουργεί έναν N-αριθμητικό τελεστή |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Δημιουργεί έναν N-αριθμητικό τελεστή |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Παίρνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Παίρνει το ολοκλήρωμα |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Παίρνει το ολοκλήρωμα χωρίς όρια |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Παίρνει το ολοκλήρωμα |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Παίρνει το ολοκλήρωμα |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/group/#) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κάτω καμπύλη αγκύλη |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως η κάτω καμπύλη αγκύλη ή άλλον |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο περιγράμματος |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο περιγράμματος |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Τοποθετεί σε κάθετο σύνολο |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/accent/#char) | Ορίζει έντονη σημείωση (χαρακτήρας στην κορυφή αυτού του στοιχείου) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/overbar/#) | Θέτει μια γραμμή στην κορυφή αυτού του στοιχείου |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/underbar/#) | Θέτει μια γραμμή στο κάτω μέρος αυτού του στοιχείου |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/to_box/#) | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) <br/>            το οποίο χρησιμοποιείται για την ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλου τμήματος μαθηματικού κειμένου.<br/>            Ένα αντικείμενο σε κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, <br/>            να λειτουργεί ως σημείο αλλαγής γραμμής, ή να ομαδοποιείται ώστε να μην επιτρέπονται αλλαγές γραμμής εντός. |
| [`delimit(self, separator_character)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Οριοθετεί τα ορίσματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα οριοθέτη |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter/get_children/#) | Αποκτά τα παιδικά στοιχεία |


### Δείτε επίσης
* κλάση [`MathDelimiter`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter)
* κλάση [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)