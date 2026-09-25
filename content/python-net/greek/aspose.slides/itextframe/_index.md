---
title: ITextFrame class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/itextframe/
---
## ITextFrame κλάση

Αναπαριστά ένα TextFrame.

Ο τύπος ITextFrame αποκαλύπτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`paragraphs`](/slides/python-net/el/aspose.slides/itextframe/paragraphs/) | Επιστρέφει τη λίστα όλων των παραγράφων σε ένα πλαίσιο.<br/>            Μόνο-ανάγνωση [`IParagraphCollection`](/slides/python-net/el/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/el/aspose.slides/itextframe/text/) | Λαμβάνει ή ορίζει το απλό κείμενο για ένα TextFrame.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`text_frame_format`](/slides/python-net/el/aspose.slides/itextframe/text_frame_format/) | Επιστρέφει το αντικείμενο μορφοποίησης για αυτό το αντικείμενο TextFrame.<br/>            Μόνο-ανάγνωση [`ITextFrameFormat`](/slides/python-net/el/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/el/aspose.slides/itextframe/hyperlink_queries/) | Παρέχει εύκολη πρόσβαση σε περιέχουσες υπερσυνδέσεις.<br/>            Μόνο-ανάγνωση [`IHyperlinkQueries`](/slides/python-net/el/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/el/aspose.slides/itextframe/parent_shape/) | Επιστρέφει το γονικό σχήμα ή None εάν το γονικό αντικείμενο δεν υλοποιεί το διεπαφή IShape<br/>            Μόνο-ανάγνωση [`IShape`](/slides/python-net/el/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/el/aspose.slides/itextframe/parent_cell/) | Επιστρέφει το γονικό κελί ή None εάν το γονικό αντικείμενο δεν υλοποιεί το διεπαφή ICell.<br/>            Μόνο-ανάγνωση [`ICell`](/slides/python-net/el/aspose.slides/icell). |
| [`slide`](/slides/python-net/el/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/itextframe/presentation/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/el/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/el/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/el/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Επισημαίνει όλες τις αντιστοιχίες του δείγματος κειμένου με το καθορισμένο χρώμα. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/el/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/el/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/el/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Ενώνει τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους. |
| [`split_text_by_columns(self)`](/slides/python-net/el/aspose.slides/itextframe/split_text_by_columns/#) | Διαχωρίζει το κείμενο του [`ITextFrame`](/slides/python-net/el/aspose.slides/itextframe) σε έναν πίνακα συμβολοσειρών, <br/>            όπου κάθε στοιχείο αντιστοιχεί σε μια ξεχωριστή στήλη κειμένου μέσα στο πλαίσιο. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/el/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/el/aspose.slides/itextframe/replace_regex/#str-str) | Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο συμβολοσειρά. |


### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)