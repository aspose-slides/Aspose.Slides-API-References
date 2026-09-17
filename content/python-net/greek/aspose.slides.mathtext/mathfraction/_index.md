---
title: MathFraction class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.mathtext/mathfraction/
---
## MathFraction κλάση

Καθορίζει το αντικείμενο κλάσματος, το οποίο αποτελείται από αριθμητή και παρονομαστή διαχωρισμένα με μια μπάρα κλάσματος.
            Η μπάρα κλάσματος μπορεί να είναι οριζόντια ή διαγώνια, ανάλογα με τις ιδιότητες του κλάσματος.
            Το αντικείμενο κλάσματος χρησιμοποιείται επίσης για την αναπαράσταση της συνάρτησης στοίβας, που τοποθετεί ένα στοιχείο πάνω από άλλο, χωρίς μπάρα κλάσματος.

**Κληρονομικότητα:**[`MathFraction`](/slides/python-net/el/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)

Ο τύπος MathFraction αποκαλύπτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | Initializes MathFraction with the specified numerator, denominator and type |
| [`__init__(self, numerator, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | Initializes a MathFraction of type 'Bar' with the specified numerator and denominator |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`fraction_type`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/fraction_type/) | Fraction type<br/>            Default: Bar |
| [`numerator`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/numerator/) | Numerator |
| [`denominator`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/denominator/) | Denominator |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/join/#imathelement) | Joins a mathematical element and forms a mathematical block |
| [`join(self, math_text)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/join/#str) | Joins a mathematical text and forms a mathematical block |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/divide/#imathelement) | Creates a fraction with this numerator and specified denominator |
| [`divide(self, denominator)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/divide/#str) | Creates a fraction with this numerator and specified denominator |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`enclose(self)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/enclose/#) | Encloses a math element in parenthesis |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/enclose/#char-char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/function/#imathelement) | Takes a function of an argument using this instance as the function name |
| [`function(self, function_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/function/#str) | Takes a function of an argument using this instance as the function name |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | Takes specified function using this instance as the argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | Takes specified function using this instance as the argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | Takes specified function using this instance as the argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Takes specified function using this instance as the argument and specified additional argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Takes specified function using this instance as the argument and specified additional argument |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | Creates subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/set_subscript/#str) | Creates subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | Creates superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/set_superscript/#str) | Creates superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | Creates subscript and superscript on the left |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | Creates subscript and superscript on the left |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/radical/#imathelement) | Specifies the mathematical root of the given degree from the specified argument. |
| [`radical(self, degree)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/radical/#str) | Specifies the mathematical root of the given degree from the specified argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | Takes upper limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | Takes upper limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | Takes lower limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | Takes lower limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | Creates a N-ary operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | Creates a N-ary operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Takes the integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | Takes the integral |
| [`integral(self, integral_type)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | Takes the integral without limits |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | Takes the integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | Takes the integral |
| [`group(self)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/group/#) | Places this element in a group using a bottom curly bracket |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [`to_border_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/to_border_box/#) | Places this element in a border-box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Places this element in a border-box |
| [`to_math_array(self)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/to_math_array/#) | Puts in a vertical array |
| [`accent(self, accent_character)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/accent/#char) | Sets an accent mark (a character on the top of this element) |
| [`overbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/overbar/#) | Sets a bar on the top of this element |
| [`underbar(self)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/underbar/#) | Sets a bar on the bottom of this element |
| [`to_box(self)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/to_box/#) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [`get_children(self)`](/slides/python-net/el/aspose.slides.mathtext/mathfraction/get_children/#) | Get children elements |

### Δείτε επίσης
* κλάση [`MathElementBase`](/slides/python-net/el/aspose.slides.mathtext/mathelementbase)
* κλάση [`MathFraction`](/slides/python-net/el/aspose.slides.mathtext/mathfraction)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)