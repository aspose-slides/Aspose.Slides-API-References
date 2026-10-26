---
title: ParagraphFormat class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/paragraphformat/
---
## ParagraphFormat κλάση

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης παραγράφου. Σε αντίθεση με [`IParagraphFormatEffectiveData`](/slides/python-net/el/aspose.slides/iparagraphformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

**Inheritance:**[`ParagraphFormat`](/slides/python-net/el/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/el/aspose.slides/pviobject)

Ο τύπος ParagraphFormat εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides/paragraphformat/__init__/#) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης [`ParagraphFormat`](/slides/python-net/el/aspose.slides/paragraphformat). |

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`alignment`](/slides/python-net/el/aspose.slides/paragraphformat/alignment/) | Returns or sets the text alignment in a paragraph with no inheritance.<br/>            Ανάγνωση/εγγραφή [`TextAlignment`](/slides/python-net/el/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/el/aspose.slides/paragraphformat/space_within/) | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`space_before`](/slides/python-net/el/aspose.slides/paragraphformat/space_before/) | Returns or sets the amount of space before the first line in a paragraph with no inheritance.<br/>            A positive value specifies the percentage of the font size that the white space should be.<br/>            A negative value specifies the size of the white space in point size.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`space_after`](/slides/python-net/el/aspose.slides/paragraphformat/space_after/) | Returns or sets the amount of space after the last line in a paragraph with no inheritance.<br/>            A positive value specifies the percentage of the font size that the white space should be.<br/>            A negative value specifies the size of the white space in point size.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`east_asian_line_break`](/slides/python-net/el/aspose.slides/paragraphformat/east_asian_line_break/) | Determines whether the East Asian line break is used in a paragraph. No inheritance applied.<br/>            Ανάγνωση/εγγραφή [`NullableBool`](/slides/python-net/el/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/el/aspose.slides/paragraphformat/right_to_left/) | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied.<br/>            Ανάγνωση/εγγραφή [`NullableBool`](/slides/python-net/el/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/el/aspose.slides/paragraphformat/latin_line_break/) | Determines whether the Latin line break is used in a paragraph. No inheritance applied.<br/>            Ανάγνωση/εγγραφή [`NullableBool`](/slides/python-net/el/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/el/aspose.slides/paragraphformat/hanging_punctuation/) | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied.<br/>            Ανάγνωση/εγγραφή [`NullableBool`](/slides/python-net/el/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/el/aspose.slides/paragraphformat/margin_left/) | Returns or sets the left margin in a paragraph with no inheritance.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`margin_right`](/slides/python-net/el/aspose.slides/paragraphformat/margin_right/) | Returns or sets the right margin in a paragraph with no inheritance.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`indent`](/slides/python-net/el/aspose.slides/paragraphformat/indent/) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`default_tab_size`](/slides/python-net/el/aspose.slides/paragraphformat/default_tab_size/) | Returns or sets default tabulation size with no inheritance.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`tabs`](/slides/python-net/el/aspose.slides/paragraphformat/tabs/) | Returns tabulations of a paragraph. No inheritance applied.<br/>            Μόνο ανάγνωση [`ITabCollection`](/slides/python-net/el/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/el/aspose.slides/paragraphformat/font_alignment/) | Returns or sets a font alignment in a paragraph with no inheritance.<br/>            Ανάγνωση/εγγραφή [`FontAlignment`](/slides/python-net/el/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/el/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/el/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/el/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/el/aspose.slides/paragraphformat/default_portion_format/) |  |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/el/aspose.slides/paragraphformat/get_effective/#) | Αποκτά τα αποτελεσματικά δεδομένα μορφοποίησης παραγράφου με την κληρονομιά εφαρμοσμένη. |


### Παρατηρήσεις

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης παραγράφου που ορίζονται για τη συγκεκριμένη παράγραφο. Αυτό σημαίνει ότι
            δεν εφαρμόζεται κληρονομιά κατά τη λήψη τιμών, έτσι στην πλειονότητα των περιπτώσεων θα λάβετε τιμές που σημαίνουν "απροσδιόριστο".


Για να λάβετε τις αποτελεσματικές τιμές παραμέτρων μορφοποίησης, συμπεριλαμβανομένων των κληρονομημένων, χρειάζεται να χρησιμοποιήσετε τη μέθοδο [`ParagraphFormat.get_effective`](/slides/python-net/el/aspose.slides/paragraphformat/get_effective)
            η οποία επιστρέφει μια παρουσία [`IParagraphFormatEffectiveData`](/slides/python-net/el/aspose.slides/iparagraphformateffectivedata).

### Δείτε επίσης
* κλάση [`IParagraphFormatEffectiveData`](/slides/python-net/el/aspose.slides/iparagraphformateffectivedata)
* κλάση [`ParagraphFormat`](/slides/python-net/el/aspose.slides/paragraphformat)
* κλάση [`PVIObject`](/slides/python-net/el/aspose.slides/pviobject)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)